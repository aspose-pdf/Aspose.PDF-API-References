---
title: Class AutoFiller
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.AutoFiller sınıfı. Veritabanından veya diğer veri kaynaklarından veri almayı, bunları şablon pdf'nin tasarlanmış alanlarına doldurmayı ve en sonunda yeni bir pdf dosyası veya akışı oluşturmayı temsil eden bir sınıftır. İki şablon dosyası girdi modu vardır bir akış olarak veya bir pdf dosyası olarak. Dört tür çıktı modu vardır birleştirilmiş bir akış, birleştirilmiş bir dosya, birçok küçük akış, birçok küçük dosya. System.Data.DataTable içinde bulunan literal verileri alabilir.
type: docs
weight: 4150
url: /tr/net/aspose.pdf.facades/autofiller/
---
## AutoFiller Sınıfı

Veritabanından veya diğer veri kaynaklarından veri almayı, bunları şablon pdf'nin tasarlanmış alanlarına doldurmayı ve en sonunda yeni bir pdf dosyası veya akışı oluşturmayı temsil eden bir sınıftır. İki şablon dosyası girdi modu vardır: bir akış olarak veya bir pdf dosyası olarak. Dört tür çıktı modu vardır: birleştirilmiş bir akış, birleştirilmiş bir dosya, birçok küçük akış, birçok küçük dosya. System.Data.DataTable içinde bulunan literal verileri alabilir.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [AutoFiller](autofiller/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename/) { get; set; } | Birçok küçük dosya oluşturulacaksa temel dosya adını alır veya ayarlar. Oluşturulan dosya "BasicFileName0","BasicFileName1",... gibi olacaktır. [`GeneratingPath`](./generatingpath/) özelliği ile çalışır. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath/) { get; set; } | Birçok küçük pdf dosyası oluşturulacaksa küçük pdf dosyalarının Üretim Yolunu alır veya ayarlar. [`BasicFileName`](./basicfilename/) özelliği ile çalışır. Dört çıktı modundan biri. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams/) { get; set; } | Birçok Çıktı Akışını alır veya ayarlar. Dört çıktı modundan biri. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields/) { set; } | Düzleştirilmeyecek alanları ayarlar. Bu özellik ayarlanmazsa, tüm alanlar düzleştirilecektir. |

## Metodlar

| İsim | Açıklama |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf)(Document) | Bir Pdf belgesini bağlar. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_1)(Stream) | Bir Pdf dosyasını bağlar. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf/#bindpdf_2)(string) | Bir Pdf dosyasını bağlar. |
| [Close](../../aspose.pdf.facades/autofiller/close/)() | Nesneyi ve çıktı akışlarını kapatır. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose/)() | Nesneyi ve çıktı akışlarını kapatır. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable/)(DataTable) | DataTable türündeki verileri içe aktarır. DataTable'ın her sütun adı, şablon pdf'nin bir alan adıyla büyük/küçük harf duyarlı olarak aynı olmalıdır. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_1)(Stream) | Tüm pdf'leri kaydeder. |
| [Save](../../aspose.pdf.facades/autofiller/save/#save_2)(string) | Tüm pdf'leri kaydeder. |

## Örnekler

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

### Ayrıca Bakınız

* arayüz [ISaveableFacade](../isaveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)