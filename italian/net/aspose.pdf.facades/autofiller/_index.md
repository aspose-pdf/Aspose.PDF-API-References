---
title: AutoFiller
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta una classe per ricevere dati dal database o da unaltra fonte di dati li riempie nei campi progettati del modello pdf e infine genera un nuovo file pdf o flusso. Ha due modalità di input del file modello input come flusso o file pdf . Ha quattro tipi di modalità di output un flusso unito un file unito molti piccoli flussi molti piccoli file. Può ricevere dati letterali contenuti in un System.Data.DataTable.
type: docs
weight: 2170
url: /it/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Rappresenta una classe per ricevere dati dal database o da un'altra fonte di dati, li riempie nei campi progettati del modello pdf e infine genera un nuovo file pdf o flusso. Ha due modalità di input del file modello: input come flusso o file pdf . Ha quattro tipi di modalità di output: un flusso unito, un file unito, molti piccoli flussi, molti piccoli file. Può ricevere dati letterali contenuti in un System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [AutoFiller](autofiller)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename) { get; set; } | Ottiene o imposta il nome del file di base se verranno generati molti file di piccole dimensioni. Il file generato sarà come "BasicFileName0","BasicFileName1",... Funziona con un'altra proprietà[`GeneratingPath`](./generatingpath) GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath) { get; set; } | Ottiene o imposta il percorso di generazione dei piccoli file pdf se devono essere generati molti piccoli file pdf. Funziona con un'altra proprietà[`BasicFileName`](./basicfilename)BasicFileName. Una delle quattro modalità di output. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams) { get; set; } | Ottiene o imposta i numerosi flussi di output. Una delle quattro modalità di uscita. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields) { set; } | Imposta i campi che non verranno appiattiti. Se questa proprietà non è impostata, tutti i campi verranno appiattiti. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf)(Document) | Associa un documento Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_1)(Stream) | Associa un file Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_2)(string) | Associa un file Pdf. |
| [Close](../../aspose.pdf.facades/autofiller/close)() | Chiude l'oggetto e i flussi di output. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose)() | Chiude l'oggetto e i flussi di output. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable)(DataTable) | Importa dati di tipo DataTable. Il nome di ogni colonna della tabella dati deve essere uguale a il nome di un campo del modello pdf con distinzione tra maiuscole e minuscole. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_1)(Stream) | Salva tutti i pdf. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_2)(string) | Salva tutti i pdf. |

### Esempi

```csharp
[C#]
//Nota: mail.pdf è un modello pdf con sette campi di testo. NorthWind.mdb è il database di accesso di Microsoft.
////Parte comune: prendi i dati dal database NorthWind.mdb e inseriscili nel DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Costruisci la tabella dati.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Connettersi all'origine del database e interrogare i dati.
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
////Fine parte comune.

////caso uno:
////Il modello di input pdf è un file pdf e l'output è un grande flusso unito.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////caso due:
////Il modello di input pdf è un file pdf e l'output è costituito da molti file di piccole dimensioni.
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'Nota: mail.pdf è un modello pdf che ha sette campi di testo. NorthWind.mdb è il database di accesso di Microsoft.
'Parte comune: ottenere i dati dal database NorthWind.mdb compilarlo nel DataTable. 
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'Costruisci la tabella dei dati.
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'Crea colonne per il datatable. 
'Every column's  name should be the same as one field's name of the templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'Collegarsi all'origine del database e interrogare i dati.
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'Collegarsi all'origine del database e interrogare i dati.
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'Costruisci l'ultima colonna del Datatable.
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'Interroga i dati e inseriscili nel datatable.

'Costruisci l'ultima colonna del Datatable.
'Il modello di input pdf è un file pdf e l'output è un grande flusso unito.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'Fine della parte comune.
'Il modello di input pdf è un file pdf e l'output è un sacco di piccoli file.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### Guarda anche

* interface [ISaveableFacade](../isaveablefacade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
