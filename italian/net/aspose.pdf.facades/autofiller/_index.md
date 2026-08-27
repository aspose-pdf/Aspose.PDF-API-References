---
title: "Classe AutoFiller"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Facades.AutoFiller class. Rappresenta una classe per ricevere dati da un database o da altre origini dati e inserirli nei campi progettati del PDF modello, generando infine un nuovo file PDF o uno stream. Dispone di due modalità di input del file modello: come stream o come file PDF. Ha quattro tipologie di modalità di output: uno stream unificato, un file unificato, molti piccoli stream, molti piccoli file. Può ricevere dati letterali contenuti in un System.Data.DataTable."
type: docs
weight: 4270
url: /it/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Rappresenta una classe per ricevere dati da un database o da altre origini dati, inserirli nei campi progettati del modello PDF e infine generare un nuovo file PDF o stream. Dispone di due modalità di input per il file modello: input come stream o come file PDF. Ha quattro tipi di modalità di output: un stream unificato, un file unificato, molti piccoli stream, molti piccoli file. Può ricevere dati letterali contenuti in un System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [AutoFiller](autofiller/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | Ottiene o imposta il nome base del file se verranno generati molti piccoli file. Il file generato sarà del tipo "BasicFileName0","BasicFileName1",... Funziona con un'altra proprietà [`GeneratingPath`](./generatingpath/)GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | Ottiene o imposta il Percorso di Generazione dei piccoli file PDF se devono essere generati molti piccoli file PDF. Funziona con un'altra proprietà [`BasicFileName`](./basicfilename/)BasicFileName. Una delle quattro modalità di output. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | Ottiene o imposta i numerosi Output Streams. Una delle quattro modalità di output. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | Imposta i campi che non saranno appiattiti. Se questa proprietà non è impostata, tutti i campi saranno appiattiti. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Associa un documento Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Associa un file Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Associa un file Pdf. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | Chiude l'oggetto e gli stream di output. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | Chiude l'oggetto e gli stream di output. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | Importa dati di tipo DataTable. Il nome di ogni colonna del dataTable deve corrispondere esattamente a quello di un campo del PDF modello, rispettando il case. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | Salva tutti i pdf. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | Salva tutti i pdf. |

## Esempi

```csharp
[C#]
//Nota: mail.pdf è un pdf modello che contiene sette campi di testo. NorthWind.mdb è il database Microsoft Access.
////Common part: Ottieni i dati dal database NorthWind.mdb e inseriscili nel DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Costruisci la DataTable.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Connettiti alla sorgente del database e interroga i dati.
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
////Fine della parte comune.

////caso uno:
////Il pdf modello di input è un file pdf e l'output è un grande flusso unito.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////caso due:
////Il pdf modello di input è un file pdf e l'output è un gran numero di file piccoli.
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

### Vedi anche

* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


