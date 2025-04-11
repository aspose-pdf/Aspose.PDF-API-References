---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSanitization sınıfı. Sanitizasyon ve kurtarma API'sini temsil eder. Başka bir şekilde belge oluşturamıyorsanız veya açamıyorsanız bunu kullanın.
type: docs
weight: 4540
url: /tr/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization sınıfı

Sanitizasyon ve kurtarma API'sini temsil eder. Başka bir şekilde belge oluşturamıyorsanız veya açamıyorsanız bunu kullanın.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Dosya kaydedildikten sonra dosya ile ne yapıldığını kontrol edebilirsiniz. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Belge için yeni xref ve trailer oluşturulmasına izin verir. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | PDF verisinden sonra verilerin kaldırılmasına izin verir. |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | PDF verisinden önce verilerin kaldırılmasına izin verir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Yüzeyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Sanitizasyon için bir Pdf akışını bağlar. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Sanitizasyon için bir Pdf dosyasını bağlar. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Yüzeyi kapatır. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Eski xref ve trailer'ı kaldırır ve yeni bir xref ile trailer oluşturur. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Belgeyi kurtarır. Özelleştirmek için özellikleri kullanın. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Sonuç PDF'sini akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Sonuç PDF'sini dosyaya kaydeder. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Son %%EOF'dan sonraki verileri kaldırır. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | %PDF'den önceki verileri kaldırır. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)