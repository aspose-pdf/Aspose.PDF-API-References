---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.SignOptions sınıfı. İmza eklentisi için İmza Seçeneklerini temsil eder
type: docs
weight: 9250
url: /tr/net/aspose.pdf.plugins/signoptions/
---
## SignOptions sınıfı

[`Signature`](../signature/) eklentisi için İmza Seçeneklerini temsil eder.

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | Varsayılan seçeneklerle `SignOptions` nesnesinin yeni bir örneğini başlatır. |
| [SignOptions](signoptions/#constructor_1)(string, string) | Varsayılan seçeneklerle `SignOptions` nesnesinin yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | İşlem tamamlandıktan sonra giriş akışlarını kapatır. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | İşlem tamamlandıktan sonra çıkış akışlarını kapatır. |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | İmzanın iletişimi. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | OrganizerOptions eklentisi veri koleksiyonunu döndürür. |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | İmzanın konumu. |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | Mevcut imza alanının adı. Yeni bir alan oluşturmak için Null. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Kaydetme işlemi sonuçları için eklenen hedeflerin koleksiyonunu alır. |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | İmzanın yapıldığı sayfa numarası. |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | İmzanın nedeni. |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | İmzanın dikdörtgeni. |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | İmzanın görünürlüğü. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | PdfOrganizer eklentisi veri koleksiyonuna yeni bir veri kaynağı ekler. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | PdfOrganizer eklentisi veri koleksiyonuna yeni bir veri kaynağı ekler. |

### Ayrıca Bakınız

* sınıf [OrganizerBaseOptions](../organizerbaseoptions/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)