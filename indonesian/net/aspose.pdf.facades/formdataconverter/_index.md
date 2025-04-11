---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.FormDataConverter. Mewakili kelas untuk mengonversi data dari satu format ke format lain. Ini dapat mengonversi data dalam fdf/xml/pdf/xfdf ke OLEDB/OdbcDB. Ini juga dapat mengonversi data dalam OLEDB/OdbcDB ke data dalam fdf/xml/xfdf. Ini dapat mengonversi fdf ke xml dengan tag "hard-named".
type: docs
weight: 4320
url: /id/net/aspose.pdf.facades/formdataconverter/
---
## Kelas FormDataConverter

Mewakili kelas untuk mengonversi data dari satu format ke format lain. Ini dapat mengonversi data dalam fdf/xml/pdf/xfdf ke OLEDB/OdbcDB. Ini juga dapat mengonversi data dalam OLEDB/OdbcDB ke data dalam fdf/xml/xfdf. Ini dapat mengonversi fdf ke xml dengan tag "hard-named".

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
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData akan menghapus tabel sebelum ekspor data. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable akan membuat field yang diperlukan jika tidak ada dalam Tabel. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase akan membuat tabel jika tidak ada. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase akan menghapus tabel yang ada dan membuat tabel baru jika properti ini disetel ke true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Mendapatkan atau menetapkan wadah data tengah, satu DataTable. Ini harus didefinisikan sebelum mengonversi data dari satu format ke format lain. Kolom dan TableName dari DataTable harus didefinisikan. TableName adalah nama Tabel dalam database. Setiap ColumnName kolom adalah nama field yang memenuhi syarat dari pdf. Setiap Caption kolom adalah nama kolom tabel dalam database. Jika nama field sama dengan nama kolom tabel, Caption tidak perlu ditentukan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Metode ini sudah usang. Silakan gunakan ConvertToStreams() sebagai gantinya. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Mengonversi file dari stream menjadi tabel. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Mengonversi data dalam tabel menjadi stream. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Mengekspor data dari database ke tabel. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Mengimpor data dari tabel ke database. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Mengonversi file FDF menjadi XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Mengonversi file data formulir XML import/export menjadi format FDF. |

### Lihat Juga

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)