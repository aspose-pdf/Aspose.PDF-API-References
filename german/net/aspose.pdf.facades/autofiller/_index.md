---
title: AutoFiller
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert eine Klasse zum Empfangen von Daten aus einer Datenbank oder einer anderen Datenquelle füllt sie in die entworfenen Felder der PDF-Vorlage aus und generiert schließlich eine neue PDF-Datei oder einen neuen Stream. Es hat zwei Vorlagendatei-Eingabemodi Eingabe als Stream oder als PDF-Datei . Es hat vier Arten von Ausgabemodi einen zusammengeführten Stream eine zusammengeführte Datei viele kleine Streams viele kleine Dateien. Es kann wörtliche Daten empfangen die in einer System.Data.DataTable enthalten sind.
type: docs
weight: 2170
url: /de/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Repräsentiert eine Klasse zum Empfangen von Daten aus einer Datenbank oder einer anderen Datenquelle, füllt sie in die entworfenen Felder der PDF-Vorlage aus und generiert schließlich eine neue PDF-Datei oder einen neuen Stream. Es hat zwei Vorlagendatei-Eingabemodi: Eingabe als Stream oder als PDF-Datei . Es hat vier Arten von Ausgabemodi: einen zusammengeführten Stream, eine zusammengeführte Datei, viele kleine Streams, viele kleine Dateien. Es kann wörtliche Daten empfangen, die in einer System.Data.DataTable enthalten sind.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [AutoFiller](autofiller)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename) { get; set; } | Ermittelt oder setzt den grundlegenden Dateinamen, wenn viele kleine Dateien generiert werden. Die generierte Datei sieht aus wie "BasicFileName0", "BasicFileName1",... Es funktioniert mit einer anderen Eigenschaft[`GeneratingPath`](./generatingpath) GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath) { get; set; } | Ermittelt oder setzt den Generierungspfad der kleinen PDF-Dateien, wenn viele kleine PDF-Dateien generiert werden sollen. Es funktioniert mit einer anderen Eigenschaft[`BasicFileName`](./basicfilename)BasicFileName. Einer der vier Ausgabemodi. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams) { get; set; } | Holt oder setzt die vielen Output Streams. Einer von vier Ausgabemodi. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields) { set; } | Legt die Felder fest, die nicht reduziert werden. Wenn diese Eigenschaft nicht gesetzt ist, werden alle Felder reduziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf)(Document) | Bindet ein PDF-Dokument. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_1)(Stream) | Bindet eine PDF-Datei. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_2)(string) | Bindet eine PDF-Datei. |
| [Close](../../aspose.pdf.facades/autofiller/close)() | Schließt die Objekt- und Ausgabeströme. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose)() | Schließt die Objekt- und Ausgabeströme. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable)(DataTable) | Importiert Daten vom Typ DataTable. Der Name jeder Spalte der dataTable muss derselbe sein wie ein Feldname der PDF-Vorlage, wobei die Groß- und Kleinschreibung beachtet werden muss. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_1)(Stream) | Speichert alle PDFs. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_2)(string) | Speichert alle PDFs. |

### Beispiele

```csharp
[C#]
//Hinweis: mail.pdf ist ein Vorlagen-PDF mit sieben Textfeldern. NorthWind.mdb ist die Microsoft Access-Datenbank.
////Gemeinsamer Teil: Holen Sie sich die Daten aus der Datenbank NorthWind.mdb und füllen Sie sie in die DataTable ein.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Erstelle die Datentabelle.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Mit der Datenbankquelle verbinden und die Daten abfragen.
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
////Ende des gemeinsamen Teils.

////Fall eins:
////Eingabevorlage pdf ist eine PDF-Datei und die Ausgabe ist ein großer zusammengeführter Stream.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////Fall zwei:
////Eingabevorlage pdf ist eine PDF-Datei und die Ausgabe besteht aus vielen kleinen Dateien.
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'Hinweis: mail.pdf ist ein Vorlagen-PDF mit sieben Textfeldern. NorthWind.mdb ist die Microsoft Access-Datenbank.
'Gemeinsamer Teil: Holen Sie sich die Daten aus der Datenbank NorthWind.mdb und füllen Sie sie in die DataTable ein. 
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'Konstruieren Sie die Datentabelle.
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'Erstellen Sie Spalten für die Datentabelle. 
'Every column's  name should be the same as one field's name of the templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'Stellen Sie eine Verbindung zur Datenbankquelle her und fragen Sie die Daten ab.
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'Fragen Sie die Daten ab und fügen Sie sie in die Datentabelle ein.
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'Konstruieren Sie die letzte Spalte der Datentabelle.
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'Ende des gemeinsamen Teils.

'Fall eins:
'Die PDF-Eingabevorlage ist eine PDF-Datei und die Ausgabe ein großer zusammengeführter Stream.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'Fall zwei:
'Die PDF-Eingabevorlage ist eine PDF-Datei und die Ausgabe besteht aus vielen kleinen Dateien.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### Siehe auch

* interface [ISaveableFacade](../isaveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
