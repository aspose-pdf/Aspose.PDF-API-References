---
title: FormDataConverter
second_title: Aspose.PDF for .NET API Referansı
description: Verileri bir biçimden başka bir biçime dönüştürmek için bir sınıfı temsil eder. fdf/xml/pdf/xfdf içindeki verileri OLEDB/OdbcDBye dönüştürebilir. Ayrıca OLEDB/OdbcDBdeki verileri içindeki verilere dönüştürebilir. fdf/xml/xfdf. hard-named etiketi ile fdfyi xmlye dönüştürebilir.
type: docs
weight: 2330
url: /tr/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

Verileri bir biçimden başka bir biçime dönüştürmek için bir sınıfı temsil eder. fdf/xml/pdf/xfdf içindeki verileri OLEDB/OdbcDB'ye dönüştürebilir. Ayrıca OLEDB/OdbcDB'deki verileri içindeki verilere dönüştürebilir. fdf/xml/xfdf. "hard-named" etiketi ile fdf'yi xml'ye dönüştürebilir.

```csharp
public sealed class FormDataConverter
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [FormDataConverter](formdataconverter)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport) { get; set; } | ExportFromData, verileri dışa aktarmadan önce tabloyu temizleyecektir. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield) { get; set; } | ConvertToDataTable, Tablo'da yoksa gerekli alanı yaratacaktır. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable) { get; set; } | ImportIntoDatabase, mevcut değilse tablo oluşturacaktır. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable) { get; set; } | ImportIntoDatabase, bu özellik true olarak ayarlanırsa mevcut tabloyu bırakacak ve yeni tablo oluşturacaktır. |
| [Table](../../aspose.pdf.facades/formdataconverter/table) { get; set; } | Ortadaki veri kapsayıcısını alır veya ayarlar, bir DataTable. Verileri bir biçimden başka bir biçime dönüştürmeden önce tanımlanmalıdır. DataTable'ın Sütunları ve TabloAdı tanımlanmalıdır. TabloAdı, database. Her sütunun SütunAdı, pdf'nin nitelikli alan adıdır. Her sütunun Caption , veritabanındaki tablonun sütun adıdır. Alan adı, column tablosunun adıyla aynıysa, Altyazının belirtilmesine gerek yoktur. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams)(Stream[], DataType) | Bu yöntem artık kullanılmamaktadır. Lütfen bunun yerine ConvertToStreams() kullanın. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable)(Stream[], DataType) | strem dosyalarını tabloya dönüştürün. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams)(Stream[], DataType) | Tablodaki verileri akışlara dönüştürün. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase)(string, DataType) | Verileri veritabanından tabloya aktarır. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase)(string, DataType) | Tablodan veri tabanına veri aktarır. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml)(Stream, Stream) | FDF dosyasını XML'e dönüştürün. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf)(Stream, Stream) | XML içe/dışa aktarma formu veri dosyasını FDF biçimine dönüştürün. |

### Ayrıca bakınız

* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
