---
title: Class AutoFiller
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.AutoFiller-Klasse. Stellt eine Klasse dar, die Daten aus einer Datenbank oder einer anderen Datenquelle empfängt, diese in die vorgesehenen Felder der Vorlage-PDF einfüllt und schließlich eine neue PDF-Datei oder einen Stream generiert. Es gibt zwei Eingabemodi für die Vorlagendatei Eingabe als Stream oder als PDF-Datei. Es gibt vier Arten von Ausgabemodi ein zusammengeführter Stream, eine zusammengeführte Datei, viele kleine Streams, viele kleine Dateien. Es kann literale Daten enthalten, die in einer System.Data.DataTable enthalten sind.
type: docs
weight: 4150
url: /de/net/aspose.pdf.facades/autofiller/
---
## AutoFiller-Klasse

Stellt eine Klasse dar, die Daten aus einer Datenbank oder einer anderen Datenquelle empfängt, diese in die vorgesehenen Felder der Vorlage-PDF einfüllt und schließlich eine neue PDF-Datei oder einen Stream generiert. Es gibt zwei Eingabemodi für die Vorlagendatei: Eingabe als Stream oder als PDF-Datei. Es gibt vier Arten von Ausgabemodi: ein zusammengeführter Stream, eine zusammengeführte Datei, viele kleine Streams, viele kleine Dateien. Es kann literale Daten enthalten, die in einer System.Data.DataTable enthalten sind.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [AutoFiller](autofiller/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | Ruft den Basisdateinamen ab oder legt ihn fest, wenn viele kleine Dateien generiert werden. Die generierte Datei wird wie "BasicFileName0", "BasicFileName1", ... sein. Es funktioniert mit einer anderen Eigenschaft [`GeneratingPath`](./generatingpath/)GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | Ruft den Generierungs-Pfad der kleinen PDF-Dateien ab oder legt ihn fest, wenn viele kleine PDF-Dateien generiert werden sollen. Es funktioniert mit einer anderen Eigenschaft [`BasicFileName`](./basicfilename/)BasicFileName. Einer der vier Ausgabemodi. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | Ruft die vielen Ausgabeströme ab oder legt sie fest. Einer der vier Ausgabemodi. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | Legt die Felder fest, die nicht abgeflacht werden sollen. Wenn diese Eigenschaft nicht gesetzt ist, werden alle Felder abgeflacht. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Bindet ein PDF-Dokument. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Bindet eine PDF-Datei. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Bindet eine PDF-Datei. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | Schließt das Objekt und die Ausgabeströme. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | Schließt das Objekt und die Ausgabeströme. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | Importiert Daten vom Typ DataTable. Jeder Spaltenname der DataTable muss mit einem Feldnamen der Vorlage-PDF übereinstimmen, wobei die Groß- und Kleinschreibung beachtet wird. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | Speichert alle PDFs. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | Speichert alle PDFs. |

## Beispiele

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

### Siehe auch

* Schnittstelle [ISaveableFacade](../isaveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)