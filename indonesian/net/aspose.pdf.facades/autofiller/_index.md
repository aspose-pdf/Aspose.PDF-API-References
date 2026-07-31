---
title: "Kelas AutoFiller"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Facades.AutoFiller. Mewakili kelas untuk menerima data dari basis data atau sumber data lain, mengisi data tersebut ke dalam bidang yang dirancang pada template pdf dan pada akhirnya menghasilkan file pdf atau stream baru. Memiliki dua mode input file template: sebagai stream atau file pdf. Memiliki empat jenis mode output: satu stream gabungan, satu file gabungan, banyak stream kecil, banyak file kecil. Dapat menerima data literal yang terdapat dalam System.Data.DataTable."
type: docs
weight: 4270
url: /id/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Mewakili kelas untuk menerima data dari basis data atau sumber data lain, mengisi data tersebut ke dalam bidang yang dirancang pada templat pdf dan pada akhirnya menghasilkan file atau aliran pdf baru. Kelas ini memiliki dua mode masukan file templat: masukan sebagai aliran atau file pdf. Ia memiliki empat tipe mode keluaran: satu aliran gabungan, satu file gabungan, banyak aliran kecil, banyak file kecil. Ia dapat menerima data literal yang terdapat dalam System.Data.DataTable.

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
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | Mengambil atau mengatur nama file dasar jika banyak file kecil akan dihasilkan. File yang dihasilkan akan berupa \"BasicFileName0\",\"BasicFileName1\",... Ini bekerja dengan properti lain [`GeneratingPath`](./generatingpath/)GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | Mengambil atau mengatur Jalur Generasi file pdf kecil jika banyak file pdf kecil akan dihasilkan. Ini bekerja dengan properti lain [`BasicFileName`](./basicfilename/)BasicFileName. Salah satu dari empat mode output. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | Mengambil atau mengatur banyak Output Streams. Salah satu dari empat mode output. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | Mengatur bidang yang tidak akan diratakan. Jika properti ini tidak diatur, semua bidang akan diratakan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Mengikat sebuah dokumen Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Mengikat sebuah file Pdf. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Mengikat sebuah file Pdf. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | Menutup objek dan stream output. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | Menutup objek dan stream output. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | Mengimpor data tipe DataTable. Setiap nama kolom dari dataTable harus sama dengan nama satu bidang pada template pdf dengan memperhatikan huruf besar/kecil. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | Menyimpan semua pdf. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | Menyimpan semua pdf. |

## Contoh

```csharp
[C#]
//Catatan: mail.pdf adalah file pdf templat yang memiliki tujuh bidang teks. NorthWind.mdb adalah basis data Microsoft Access.
////Bagian umum: Dapatkan data dari basis data NorthWind.mdb dan isi ke dalam DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Bangun tabel data.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Hubungkan ke sumber basis data dan kueri data.
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
////Akhir Bagian umum.

////kasus satu:
////Template pdf masukan adalah file pdf dan keluaran adalah aliran gabungan besar.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////kasus dua:
////Template pdf masukan adalah file pdf dan keluaran adalah banyak file kecil.
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

* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


