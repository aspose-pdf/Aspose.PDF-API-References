---
title: Class AutoFiller
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.AutoFiller. Mewakili kelas untuk menerima data dari database atau sumber data lain, mengisinya ke dalam bidang yang dirancang dari template pdf dan akhirnya menghasilkan file atau stream pdf baru. Ini memiliki dua mode input file template input sebagai stream atau file pdf. Ini memiliki empat jenis mode output satu stream yang digabungkan, satu file yang digabungkan, banyak stream kecil, banyak file kecil. Ini dapat menerima data literal yang terkandung dalam System.Data.DataTable
type: docs
weight: 4150
url: /id/net/aspose.pdf.facades/autofiller/
---
## Kelas AutoFiller

Mewakili kelas untuk menerima data dari database atau sumber data lain, mengisinya ke dalam bidang yang dirancang dari template pdf dan akhirnya menghasilkan file atau stream pdf baru. Ini memiliki dua mode input file template: input sebagai stream atau file pdf. Ini memiliki empat jenis mode output: satu stream yang digabungkan, satu file yang digabungkan, banyak stream kecil, banyak file kecil. Ini dapat menerima data literal yang terkandung dalam System.Data.DataTable.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [AutoFiller](autofiller/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | Mendapatkan atau mengatur nama file dasar jika banyak file kecil akan dihasilkan. File yang dihasilkan akan seperti "BasicFileName0","BasicFileName1",... Ini bekerja dengan properti lain [`GeneratingPath`](./generatingpath/)GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | Mendapatkan atau mengatur Jalur Generasi dari file pdf kecil jika banyak file pdf kecil akan dihasilkan. Ini bekerja dengan properti lain [`BasicFileName`](./basicfilename/)BasicFileName. Salah satu dari empat mode output. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | Mendapatkan atau mengatur banyak Output Streams. Salah satu dari empat mode output. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | Mengatur bidang yang tidak akan diratakan. Jika properti ini tidak diatur, semua bidang akan diratakan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Mengikat dokumen Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Mengikat file Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Mengikat file Pdf. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | Menutup objek dan output streams. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | Menutup objek dan output streams. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | Mengimpor data tipe DataTable. Setiap nama kolom dari dataTable harus sama dengan satu nama bidang dari template pdf dengan memperhatikan huruf besar kecil. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | Menyimpan semua pdf. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | Menyimpan semua pdf. |

## Contoh

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

### Lihat Juga

* antarmuka [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)