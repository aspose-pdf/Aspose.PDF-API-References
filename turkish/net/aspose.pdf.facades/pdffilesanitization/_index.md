---
title: PdfFileSanitization
second_title: Aspose.PDF for .NET API Referansı
description: Temizleme ve kurtarma APIsini temsil eder. Belgeleri başka bir şekilde oluşturamıyor/açamıyorsanız kullanın.
type: docs
weight: 2550
url: /tr/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

Temizleme ve kurtarma API'sini temsil eder. Belgeleri başka bir şekilde oluşturamıyor/açamıyorsanız kullanın.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log) { get; } | Dosya Kaydedildikten sonra dosya ile ne yapıldığını kontrol edebilirsiniz. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom) { get; set; } | pdf data sonrasındaki verilerin kaldırılmasına izin verir |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop) { get; set; } | pdf verilerinden önceki verilerin kaldırılmasına izin verir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf#bindpdf)(Document) | Cepheyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf#bindpdf_1)(Stream) | Sanitize. için bir Pdf akışı bağlar |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf#bindpdf_2)(string) | Sanitize. için bir Pdf dosyası bağlar |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close)() | Cepheyi kapatır. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover)() | Belgeyi kurtarır. Özelleştirmek için özellikleri kullanın. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save#save)(Stream) | Sonuç PDF'sini akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save#save_1)(string) | Sonuç PDF'sini dosyaya kaydeder. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom)() | Son %%EOF. 'den sonraki verileri kaldırır |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop)() | %PDF'den önceki verileri kaldırır. |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->