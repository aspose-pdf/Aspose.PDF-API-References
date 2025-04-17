---
title: Class AutoFiller
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.AutoFiller klass. Representerar en klass för att ta emot data från databas eller annan datakälla, fyller dem i de utformade fälten i den mallade pdfen och genererar till sist en ny pdf-fil eller ström. Den har två inmatningslägen för mallfil inmatning som en ström eller en pdf-fil. Den har fyra typer av utmatningslägen en sammanslagen ström, en sammanslagen fil, många små strömmar, många små filer. Den kan ta emot bokstavlig data som finns i en System.Data.DataTable
type: docs
weight: 4150
url: /sv/net/aspose.pdf.facades/autofiller/
---
## AutoFiller klass

Representerar en klass för att ta emot data från databas eller annan datakälla, fyller dem i de utformade fälten i den mallade pdf:en och genererar till sist en ny pdf-fil eller ström. Den har två inmatningslägen för mallfil: inmatning som en ström eller en pdf-fil. Den har fyra typer av utmatningslägen: en sammanslagen ström, en sammanslagen fil, många små strömmar, många små filer. Den kan ta emot bokstavlig data som finns i en System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [AutoFiller](autofiller/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | Hämtar eller ställer in det grundläggande filnamnet om många små filer ska genereras. Den genererade filen kommer att vara som "BasicFileName0","BasicFileName1",... Det fungerar med en annan egenskap [`GeneratingPath`](./generatingpath/)GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | Hämtar eller ställer in Generating Path för de små pdf-filerna om många små pdf-filer ska genereras. Det fungerar med en annan egenskap [`BasicFileName`](./basicfilename/)BasicFileName. En av de fyra utmatningslägena. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | Hämtar eller ställer in de många utmatningsströmmarna. En av fyra utmatningslägen. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | Ställer in de fält som inte kommer att plattas ut. Om denna egenskap inte är inställd kommer alla fält att plattas ut. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Binder ett Pdf-dokument. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Binder en Pdf-fil. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Binder en Pdf-fil. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | Stänger objektet och utmatningsströmmarna. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | Stänger objektet och utmatningsströmmarna. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | Importerar data av typen DataTable. Varje kolumnnamn i dataTable måste vara detsamma som ett fältnamn i den mallade pdf:en med avseende på versaler. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | Sparar alla pdf:er. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | Sparar alla pdf:er. |

## Exempel

```csharp
[C#]
//Note: mail.pdf is a template pdf which has seven text fields. NorthWind.mdb is the microsoft access db.
////Common part: Get the data from the database NorthWind.mdb fill it into the DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Construct the data table.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Connect to the database source and query the data.
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
////End of Common part.

////case one:
////Input template pdf is a pdf file and output is a big merged stream.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////case two:
////Input template pdf is a pdf file and output is a lot of small files.
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

### Se Även

* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)