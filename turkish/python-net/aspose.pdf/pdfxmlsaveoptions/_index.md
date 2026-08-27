---
title: "PdfXmlSaveOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PdfXml formatı için kaydetme seçenekleri."
type: docs
weight: 1260
url: /tr/python-net/aspose.pdf/pdfxmlsaveoptions/
---

## PdfXmlSaveOptions class

PdfXml formatı için kaydetme seçenekleri.

PdfXmlSaveOptions türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfXmlSaveOptions() | PdfXmlSaveOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| warning_handler | Üretilen herhangi bir uyarıyı işlemek için geri çağırma. <br/>            WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. <br/>            Continue varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı Abort döndürürse Kaydetme işlemi durmalıdır. |
| save_format | Veri kaydetme biçimi. |
| close_response | Belge yanıt içine kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını gösteren boolean değeri alır veya ayarlar. |
| extract_ocr_sublayer_only | Bu özellik, görüntü veya metin çıkarma işlevselliğini etkinleştirir <br/>            OCR alt katmanına sahip PDF belgeleri için. |
| try_merge_adjacent_same_background_images | Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka plan görüntülerini içerir<br/>              birbiri yakınına yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşturulmuş.<br/>              Bu gibi durumlarda hedef formatların renderleyicileri (ör. DOCS formatı için MsWord) bazen oluşturur<br/>              arka plan görüntülerinin parçaları arasında görülebilir sınırlar,<br/>              çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır.<br/>               Eğer dışa aktarılan belgenin böyle görülebilir sınırlar içerdiği görülürse <br/>              aynı arka plan görüntülerinin parçaları arasında, lütfen bu ayarı kullanarak bu istenmeyen etkiden <br/>              kurtulmayı deneyin. <br/>                DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır,<br/>              bu yüzden, lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

