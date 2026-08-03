---
title: "Klassen AutoFiller"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.AutoFiller‑klassen. Representerar en klass för att ta emot data från en databas eller annan datakälla och fylla dem i de designade fälten i mall‑pdf‑filen och slutligen generera en ny pdf‑fil eller ström. Den har två inmatningslägen för mallfilen: som en ström eller en pdf‑fil. Den har fyra typer av utmatningslägen: en sammanslagen ström, en sammanslagen fil, många små strömmar, många små filer. Den kan ta emot bokstavlig data som finns i en System.Data.DataTable."
type: docs
weight: 4270
url: /sv/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Representerar en klass för att ta emot data från databas eller annan datakälla, fylla dem i de designade fälten i mall‑pdf‑filen och slutligen generera en ny pdf‑fil eller ström. Den har två inmatningslägen för mallfil: inmatning som en ström eller en pdf‑fil. Den har fyra typer av utmatningslägen: en sammanslagen ström, en sammanslagen fil, många små strömmar, många små filer. Den kan ta emot bokstavliga data som finns i en System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [AutoFiller](autofiller/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | Hämtar eller anger det grundläggande filnamnet om många små filer ska genereras. Den genererade filen kommer att vara t.ex. "BasicFileName0","BasicFileName1",... Den fungerar tillsammans med en annan egenskap [`GeneratingPath`](./generatingpath/)GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | Hämtar eller anger Generating Path för de små pdf‑filerna om många små pdf‑filer ska genereras. Den fungerar tillsammans med en annan egenskap [`BasicFileName`](./basicfilename/)BasicFileName. Ett av de fyra utmatningslägena. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | Hämtar eller anger de många utdata‑strömmarna. Ett av fyra utdata‑lägen. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | Anger fälten som inte ska plattas ut. Om den här egenskapen inte är angiven, kommer alla fält att plattas ut. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Kopplar ett Pdf-dokument. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Kopplar en Pdf-fil. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Kopplar en Pdf-fil. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | Stänger objektet och utdata‑strömmarna. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | Stänger objektet och utdata‑strömmarna. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | Importerar data av typen DataTable. Varje kolumnnamn i dataTable måste vara exakt samma som ett fältnamn i mall‑pdf:en, skiftlägeskänsligt. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | Sparar alla pdf-filer. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | Sparar alla pdf-filer. |

## Exempel

```csharp
[C#]
//Obs: mail.pdf är en mall‑pdf som har sju textfält. NorthWind.mdb är Microsoft Access‑databasen.
////Common part: Hämta data från databasen NorthWind.mdb och fyll den i DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Skapa datatabellen.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Anslut till databaskällan och hämta data.
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
////Slut på gemensam del.

////fall ett:
////Ingångsmall‑pdf är en pdf‑fil och utdata är en stor sammanslagen ström.\t\t
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////fall två:
////Ingångsmall‑pdf är en pdf‑fil och utdata är många små filer.
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'Note: mail.pdf is a template pdf which has seven text fields. NorthWind.mdb is the microsoft access db.
'Common part: Get the data from the database NorthWind.mdb fill it into the DataTable. 
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'Construct the data table.
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'Create columns for the datatable. 
'Every column's  name should be the same as one field's name of the templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'Connect to the database source and query the data.
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'Query the data and insert into the datatable.
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'Construct the last column  of the Datatable.
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'End of Common part.

'case one:
'Input template pdf is a pdf file and output is a big merged stream.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'case two:
'Input template pdf is a pdf file and output is a lot of small files.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### Se även

* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


