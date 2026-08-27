---
title: "Kelas FormDataConverter"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Facades.FormDataConverter. Mewakili kelas untuk mengonversi data dari satu format ke format lain. Itu dapat mengonversi data dalam fdf/xml/pdf/xfdf ke OLEDB/OdbcDB. Itu juga dapat mengonversi data dalam OLEDB/OdbcDB ke data dalam fdf/xml/xfdf. Itu dapat mengonversi fdf ke xml dengan tag hardnamed."
type: docs
weight: 4440
url: /id/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

Mewakili kelas untuk mengonversi data dari satu format ke format lain. Dapat mengonversi data dalam fdf/xml/pdf/xfdf ke OLEDB/OdbcDB. Juga dapat mengonversi data dalam OLEDB/OdbcDB ke data dalam fdf/xml/xfdf. Dapat mengonversi fdf ke xml dengan tag "hard-named".

```csharp
public sealed class FormDataConverter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData akan mengosongkan tabel sebelum ekspor data. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable akan membuat field yang diperlukan jika tidak ada dalam Tabel. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase akan membuat tabel jika tidak ada. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase akan menghapus tabel yang ada dan membuat tabel baru jika properti ini diatur ke true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Mendapatkan atau mengatur kontainer data menengah, satu DataTable. Harus didefinisikan sebelum mengonversi data dari satu format ke format lain. Columns dan TableName dari DataTable harus didefinisikan. TableName adalah nama Table dalam basis data. Setiap ColumnName kolom adalah nama field yang memenuhi syarat dari pdf. Setiap Caption kolom adalah nama kolom tabel dalam basis data. Jika nama field sama dengan nama kolom tabel, Caption tidak perlu ditentukan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Metode ini sudah usang. Silakan gunakan ConvertToStreams() sebagai gantinya. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Konversi file aliran menjadi tabel. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Konversi data dalam tabel menjadi aliran. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Ekspor data dari basis data ke tabel. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Impor data dari tabel ke basis data. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Konversi file FDF ke XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Konversi file data formulir impor/ekspor XML ke format FDF. |

### Lihat Juga

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


