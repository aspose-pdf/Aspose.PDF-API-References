---
title: "TeXSaveOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "TeX formatına dışa aktarma için kaydetme seçenekleri"
type: docs
weight: 1540
url: /tr/python-net/aspose.pdf/texsaveoptions/
---

## TeXSaveOptions class

TeX formatına dışa aktarma için kaydetme seçenekleri

TeXSaveOptions türü aşağıdaki üyeleri içerir:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| TeXSaveOptions() | TeXSaveOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| warning_handler | Üretilen herhangi bir uyarıyı işlemek için geri çağırma. <br/>            WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. <br/>            Continue varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı Abort döndürürse Kaydetme işlemi durmalıdır. |
| save_format | Veri kaydetme biçimi. |
| close_response | Belge yanıt içine kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını gösteren boolean değeri alır veya ayarlar. |
| extract_ocr_sublayer_only | Bu özellik, görüntü veya metin çıkarma işlevselliğini etkinleştirir <br/>            OCR alt katmanına sahip PDF belgeleri için. |
| try_merge_adjacent_same_background_images | Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka plan görüntülerini içerir<br/>              birbiri yakınına yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşturulmuş.<br/>              Bu gibi durumlarda hedef formatların renderleyicileri (ör. DOCS formatı için MsWord) bazen oluşturur<br/>              arka plan görüntülerinin parçaları arasında görülebilir sınırlar,<br/>              çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır.<br/>               Eğer dışa aktarılan belgenin böyle görülebilir sınırlar içerdiği görülürse <br/>              aynı arka plan görüntülerinin parçaları arasında, lütfen bu ayarı kullanarak bu istenmeyen etkiden <br/>              kurtulmayı deneyin. <br/>                DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır,<br/>              bu yüzden, lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |
| out_directory_path | Özellik |
| pages_count | Dönüştürmeden sonra sayfa sayısını döndürür. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| add_font_encs(font_encs) | Bir font kodlamasını font kodlama listesine ekler. |
| clear_font_encs() | Yazı tipi kodlama listesini temizler |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

