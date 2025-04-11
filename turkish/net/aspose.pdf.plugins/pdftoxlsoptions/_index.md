---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToXlsOptions sınıfı. XlsConverter eklentisi için PDF'den XLSX'e dönüştürücü seçeneklerini temsil eder.
type: docs
weight: 9150
url: /tr/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions Sınıfı

[`XlsConverter`](../xlsconverter/) eklentisi için PDF'den XLSX'e dönüştürücü seçeneklerini temsil eder.

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Çıktı formatı. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | PdfConverterOptions eklentisi veri koleksiyonunu döndürür. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Eğer çalışma sayfasının ilk sütunu olarak boş sütun eklemek istiyorsanız true olarak ayarlayın. Varsayılan değer false'tur; bu, boş sütunun eklenmeyeceği anlamına gelir. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Eğer sonuçta oluşan çalışma kitabındaki çalışma sayısı sayısını en aza indirmek istiyorsanız true olarak ayarlayın. Varsayılan değer false'tur; bu, her PDF sayfasının ayrı bir çalışma sayfası olarak kaydedileceği anlamına gelir. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | İşlemin adını alır. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Kaydetme işlemi sonuçları için eklenen hedeflerin koleksiyonunu alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | PdfConverter eklentisi veri koleksiyonuna yeni bir veri kaynağı ekler. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | PdfToXLSXConverterOptions eklentisi veri koleksiyonuna yeni bir veri kaynağı ekler. |

## Diğer Üyeler

| İsim | Açıklama |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | .xlsx, .xls/xml veya csv dosya formatını belirtmeye olanak tanır. Varsayılan değer XLSX'tir. |

### Ayrıca Bakınız

* sınıf [PdfConverterOptions](../pdfconverteroptions/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)