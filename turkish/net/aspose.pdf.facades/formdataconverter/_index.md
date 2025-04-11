---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormDataConverter sınıfı. Verileri bir formatta başka bir formata dönüştüren bir sınıfı temsil eder. fdf/xml/pdf/xfdf formatındaki verileri OLEDB/OdbcDB formatına dönüştürebilir. Ayrıca OLEDB/OdbcDB formatındaki verileri fdf/xml/xfdf formatındaki verilere dönüştürebilir. fdf'yi "hard-named" etiket ile xml'ye dönüştürebilir.
type: docs
weight: 4320
url: /tr/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter Sınıfı

Verileri bir formatta başka bir formata dönüştüren bir sınıfı temsil eder. fdf/xml/pdf/xfdf formatındaki verileri OLEDB/OdbcDB formatına dönüştürebilir. Ayrıca OLEDB/OdbcDB formatındaki verileri fdf/xml/xfdf formatındaki verilere dönüştürebilir. fdf'yi "hard-named" etiket ile xml'ye dönüştürebilir.

```csharp
public sealed class FormDataConverter
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData, veri ihracından önce tabloyu temizleyecektir. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable, Tablo'da mevcut değilse gerekli alanı oluşturacaktır. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase, mevcut değilse tablo oluşturacaktır. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase, mevcut tabloyu kaldıracak ve bu özellik true olarak ayarlandığında yeni bir tablo oluşturacaktır. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Orta veri konteynerini alır veya ayarlar, bir DataTable. Verileri bir formatta başka bir formata dönüştürmeden önce tanımlanmalıdır. DataTable'ın Sütunları ve TableName'i tanımlanmalıdır. TableName, veritabanındaki Tablo'nun adıdır. Her sütunun ColumnName'i pdf'nin nitelikli alan adıdır. Her sütunun Caption'ı veritabanındaki tablonun sütun adıdır. Alan adı tablo sütun adıyla aynıysa, Caption belirtilmesine gerek yoktur. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Bu yöntem kullanılmaz. Lütfen bunun yerine ConvertToStreams() kullanın. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Akış dosyalarını tabloya dönüştürür. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Tablo verilerini akışlara dönüştürür. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Veritabanından tabloya veri ihraç eder. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Tablo verilerini veritabanına ithal eder. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | FDF dosyasını XML'ye dönüştürür. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | XML ithalat/ihracat form veri dosyasını FDF formatına dönüştürür. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)