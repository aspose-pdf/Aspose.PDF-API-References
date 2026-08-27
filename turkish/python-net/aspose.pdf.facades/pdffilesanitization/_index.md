---
title: "PdfFileSanitization"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Temizleme ve kurtarma API'sini temsil eder.<br/>            Başka bir şekilde belge oluşturamıyorsanız/açamıyorsanız kullanın."
type: docs
weight: 290
url: /tr/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

Temizleme ve kurtarma API'sini temsil eder.<br/>            Başka bir şekilde belge oluşturamıyorsanız/açamıyorsanız kullanın.

PdfFileSanitization türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfFileSanitization() | PdfFileSanitization sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| log | Dosya kaydedildikten sonra dosyayla ne yapıldığını kontrol edebilirsiniz. |
| use_trim_top | pdf verisinden önceki verileri kaldırmaya izin verir. |
| use_trim_bottom | pdf verisinden sonraki verileri kaldırmaya izin verir. |
| use_rebuild_xref_and_trailer | Belge için yeni xref ve trailer oluşturmayı sağlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(input_file) | Sanitize için bir Pdf dosyasını bağlar. |
| bind_pdf(input_stream) | Sanitize için bir Pdf akışını bağlar. |
| bind_pdf(src_doc) | Facade'i başlatır. |
| save(output_file) | Sonuç PDF'i dosyaya kaydeder. |
| save(output_stream) | Sonuç PDF'i akışa kaydeder. |
| close() | Facade'i kapatır. |
| recover() | Belgeyi kurtarır.<br/>            Özelleştirmek için özellikleri kullanın. |
| trim_top() | %PDF öncesindeki verileri kaldırır. |
| trim_bottom() | Son %%EOF sonrasındaki verileri kaldırır. |
| rebuild_xref_and_trailer() | Eski xref'i trailer ile kaldırır ve yeni bir xref'i trailer ile oluşturur. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

