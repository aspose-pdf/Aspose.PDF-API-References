---
title: AutoFiller
second_title: Aspose.PDF for .NET API Referansı
description: Veritabanından veya diğer veri kaynağından veri almak için bir sınıfı temsil eder bunları şablon pdfnin tasarlanmış alanlarına doldurur ve sonunda yeni pdf dosyası veya akışı oluşturur. İki şablon dosyası giriş modu vardır akış veya pdf dosyası olarak giriş . Dört tür çıktı modu vardır bir birleştirilmiş akış bir birleştirilmiş dosya birçok küçük akış birçok küçük dosya. Bir System.Data.DataTableda bulunan değişmez verileri alabilir.
type: docs
weight: 2170
url: /tr/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

Veritabanından veya diğer veri kaynağından veri almak için bir sınıfı temsil eder, bunları şablon pdf'nin tasarlanmış alanlarına doldurur ve sonunda yeni pdf dosyası veya akışı oluşturur. İki şablon dosyası giriş modu vardır: akış veya pdf dosyası olarak giriş . Dört tür çıktı modu vardır: bir birleştirilmiş akış, bir birleştirilmiş dosya, birçok küçük akış, birçok küçük dosya. Bir System.Data.DataTable'da bulunan değişmez verileri alabilir.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [AutoFiller](autofiller)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename) { get; set; } | Çok sayıda küçük dosya oluşturulacaksa temel dosya adını alır veya ayarlar. Oluşturulan dosya "BasicFileName0","BasicFileName1",... gibi olacaktır. Başka bir özellik ile çalışır[`GeneratingPath`](./generatingpath) GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath) { get; set; } | Çok sayıda küçük pdf dosyası oluşturulacaksa, küçük pdf dosyalarının Oluşturma Yolunu alır veya ayarlar. Başka bir mülkle çalışır[`BasicFileName`](./basicfilename)BasicFileName. Dört çıkış modundan biri. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams) { get; set; } | Birçok Çıktı Akışını alır veya ayarlar. Dört çıkış modundan biri. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields) { set; } | Düzleştirilmeyecek alanları ayarlar. Bu özellik ayarlanmazsa tüm alanlar düzleştirilir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf)(Document) | Bir Pdf belgesini bağlar. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_1)(Stream) | Bir Pdf dosyasını bağlar. |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_2)(string) | Bir Pdf dosyasını bağlar. |
| [Close](../../aspose.pdf.facades/autofiller/close)() | Nesneyi ve çıktı akışlarını kapatır. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose)() | Nesneyi ve çıktı akışlarını kapatır. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable)(DataTable) | DataTable türündeki verileri içe aktarır. dataTable'ın her sütununun adı, büyük/küçük harfe duyarlı olması durumunda pdf şablonunun bir alan adıyla ile aynı olmalıdır. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_1)(Stream) | Tüm pdf'leri kaydeder. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_2)(string) | Tüm pdf'leri kaydeder. |

### Örnekler

```csharp
[C#]
//Not: mail.pdf, yedi metin alanına sahip bir şablon pdf'dir. NorthWind.mdb, microsoft erişim veritabanıdır.
////Ortak kısım: NorthWind.mdb veritabanındaki verileri alın ve DataTable'a doldurun.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

//Veri tablosunu oluştur.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


//Veritabanı kaynağına bağlanın ve verileri sorgulayın.
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
////Ortak bölümün sonu.

////birinci durum:
////Giriş şablonu pdf bir pdf dosyasıdır ve çıktı büyük bir birleştirilmiş akıştır.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

////durum iki:
////Giriş şablonu pdf bir pdf dosyasıdır ve çıktı çok sayıda küçük dosyadır.
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'Not: mail.pdf, yedi metin alanına sahip bir şablon pdf'dir. NorthWind.mdb, microsoft erişim veritabanıdır.
'Ortak kısım: NorthWind.mdb veritabanındaki verileri alın ve DataTable'a doldurun. 
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'Veri tablosunu oluşturun.
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'Veri tablosu için sütunlar oluşturun. 
'Every column's  name should be the same as one field's name of the templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'Veritabanı kaynağına bağlanın ve verileri sorgulayın.
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'Verileri sorgulayın ve veri tablosuna ekleyin.
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'Datatable'ın son sütununu oluşturun.
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'Ortak bölümün sonu.

'birinci durum:
'Girdi şablonu pdf bir pdf dosyasıdır ve çıktı büyük bir birleştirilmiş akıştır.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'durum iki:
'Girdi şablonu pdf bir pdf dosyasıdır ve çıktı çok sayıda küçük dosyadır.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### Ayrıca bakınız

* interface [ISaveableFacade](../isaveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
