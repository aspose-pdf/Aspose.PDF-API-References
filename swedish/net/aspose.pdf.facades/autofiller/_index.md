---
title: AutoFiller
second_title: Aspose.PDF för .NET API Referens
description: Representerar en klass för att ta emot data från databas eller annan datakälla fyller dem i de designade fälten i mallen pdf och genererar till sist en ny pdf-fil eller ström. Den har två inmatningslägen för mallfil inmatning som en ström eller en pdf-fil . Den har fyra typer av utdatalägen en sammanslagen ström en sammanslagen fil många små strömmar många små filer. Den kan ta emot bokstavlig data som finns i en System.Data.DataTable.
type: docs
weight: 2170
url: /sv/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Representerar en klass för att ta emot data från databas eller annan datakälla, fyller dem i de designade fälten i mallen pdf och genererar till sist en ny pdf-fil eller ström. Den har två inmatningslägen för mallfil: inmatning som en ström eller en pdf-fil . Den har fyra typer av utdatalägen: en sammanslagen ström, en sammanslagen fil, många små strömmar, många små filer. Den kan ta emot bokstavlig data som finns i en System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [AutoFiller](autofiller)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename) { get; set; } | Hämtar eller ställer in det grundläggande filnamnet om många små filer kommer att genereras. Den genererade filen kommer att vara som "BasicFileName0","BasicFileName1",... Den fungerar med en annan egenskap[`GeneratingPath`](./generatingpath) GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath) { get; set; } | Hämtar eller ställer in genereringsvägen för de små pdf-filerna om många små pdf-filer ska genereras. Det fungerar med en annan fastighet[`BasicFileName`](./basicfilename)BasicFileName. Ett av de fyra utdatalägena. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams) { get; set; } | Hämtar eller ställer in många utdataströmmar. Ett av fyra utgångslägen. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields) { set; } | Ställer in fälten som inte kommer att tillplattas. Om den här egenskapen inte är inställd kommer alla fält att förenklas. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf)(Document) | Binder ett pdf-dokument. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_1)(Stream) | Binder en pdf-fil. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_2)(string) | Binder en pdf-fil. |
| [Close](../../aspose.pdf.facades/autofiller/close)() | Stänger objektet och strömmar ut. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose)() | Stänger objektet och strömmar ut. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable)(DataTable) | Importerar data av typen DataTable. Namnet på varje kolumn på datatabellen måste vara detsamma som ett fältnamn på mallen pdf i skiftlägeskänslighet. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_1)(Stream) | Sparar alla pdf-filer. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_2)(string) | Sparar alla pdf-filer. |

### Exempel

```csharp
[C#]
//Obs: mail.pdf är en pdf-mall som har sju textfält. NorthWind.mdb är Microsoft Access db.
////Gemensam del: Hämta data från databasen NorthWind.mdb fyll den i DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Konstruera datatabellen.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Anslut till databaskällan och fråga efter data.
mDbConnection = new OleDbConnection();
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + 
DbPath + "NorthWind.mdb";
mQueryCommand = new OleDbCommand();
mQueryCommand.Connection = mDbConnection;
mDbConnection.Open();


mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;";
mDbDataAdapter = new OleDbDataAdapter(mQueryCommand);
		
mDbDataAdapter.Fill(mDataTable);

for (int i = 0; i<mDataTable.Rows.Count;i++)
{
	mDataTable.Rows[i][mDataTable.Columns.Count - 1] = "Dear " + mDataTable.Rows[i][0].ToString() + ",";
	System.Console.WriteLine("postalCode:" + mDataTable.Rows[i][3].ToString());
	System.Console.WriteLine("Heading:" + mDataTable.Rows[i][mDataTable.Columns.Count - 1].ToString());
}

mDbDataAdapter.Dispose();
mDbConnection.Close();
////Slutet av den gemensamma delen.

////fall ett:
////Inmatningsmall pdf är en pdf-fil och utdata är en stor sammanslagen ström.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////fall två:
////Inmatningsmall pdf är en pdf-fil och utdata är många små filer.
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'Obs: mail.pdf är en pdf-mall som har sju textfält. NorthWind.mdb är Microsoft Access db.
'Gemensam del: Hämta data från databasen NorthWind.mdb fyll den i DataTable. 
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'Konstruera datatabellen.
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'Skapa kolumner för datatabellen. 
'Every column's  name should be the same as one field's name of the templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'Anslut till databaskällan och fråga efter data.
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'Fråga efter data och infoga i datatabellen.
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'Konstruera den sista kolumnen i datatabellen.
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'Slut på den gemensamma delen.

'fall ett:
'Inmatningsmall pdf är en pdf-fil och utdata är en stor sammanslagen ström.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'fall två:
'Inmatningsmall pdf är en pdf-fil och utdata är många små filer.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### Se även

* interface [ISaveableFacade](../isaveablefacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
