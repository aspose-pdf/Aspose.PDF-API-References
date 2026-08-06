---
title: "ExcelSaveOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Excel formatına dışa aktarma için kaydetme seçenekleri"
type: docs
weight: 330
url: /tr/python-net/aspose.pdf/excelsaveoptions/
---

## ExcelSaveOptions class

Excel formatına dışa aktarma için kaydetme seçenekleri

ExcelSaveOptions türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| ExcelSaveOptions() | ExcelSaveOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| warning_handler | Üretilen herhangi bir uyarıyı işlemek için geri çağırma. <br/>            WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. <br/>            Continue varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı Abort döndürürse Kaydetme işlemi durmalıdır. |
| save_format | Veri kaydetme biçimi. |
| close_response | Belge yanıt içine kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını gösteren boolean değeri alır veya ayarlar. |
| extract_ocr_sublayer_only | Bu özellik, görüntü veya metin çıkarma işlevselliğini etkinleştirir <br/>            OCR alt katmanına sahip PDF belgeleri için. |
| try_merge_adjacent_same_background_images | Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka plan görüntülerini içerir<br/>              birbiri yakınına yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşturulmuş.<br/>              Bu gibi durumlarda hedef formatların renderleyicileri (ör. DOCS formatı için MsWord) bazen oluşturur<br/>              arka plan görüntülerinin parçaları arasında görülebilir sınırlar,<br/>              çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır.<br/>               Eğer dışa aktarılan belgenin böyle görülebilir sınırlar içerdiği görülürse <br/>              aynı arka plan görüntülerinin parçaları arasında, lütfen bu ayarı kullanarak bu istenmeyen etkiden <br/>              kurtulmayı deneyin. <br/>                DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır,<br/>              bu yüzden, lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |
| minimize_the_number_of_worksheets | Sonuç çalışma kitabındaki sayfa sayısını azaltmanız gerekiyorsa true ayarlayın.<br/>            Varsayılan değer false'tur; bu, her PDF sayfasının ayrı bir çalışma sayfası olarak kaydedileceği anlamına gelir. |
| insert_blank_column_at_first | Çalışma sayfasının ilk sütunu olarak boş bir sütun eklemeniz gerekiyorsa true ayarlayın.<br/>            Varsayılan değer false'tur; bu, boş sütunun eklenmeyeceği anlamına gelir. |
| uniform_worksheets | Belge boyunca tutarlı sütun bölümü kullanmak için true ayarlayın. <br/>            Varsayılan değer false'tur; bu, sütun bölümünün her sayfa için bağımsız olacağı anlamına gelir. |
| format | Çıktı biçimi |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

