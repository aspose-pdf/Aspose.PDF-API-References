---
title: "DocSaveOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Doc formatına dışa aktarma için kaydetme seçenekleri"
type: docs
weight: 220
url: /tr/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Doc formatına dışa aktarma için kaydetme seçenekleri

DocSaveOptions türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| DocSaveOptions() | DocSaveOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| warning_handler | Üretilen herhangi bir uyarıyı işlemek için geri çağırma. <br/>            WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. <br/>            Continue varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı Abort döndürürse Kaydetme işlemi durmalıdır. |
| save_format | Veri kaydetme biçimi. |
| close_response | Belge yanıt içine kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını gösteren boolean değeri alır veya ayarlar. |
| extract_ocr_sublayer_only | Bu özellik, görüntü veya metin çıkarma işlevselliğini etkinleştirir <br/>            OCR alt katmanına sahip PDF belgeleri için. |
| try_merge_adjacent_same_background_images | Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka plan görüntülerini içerir<br/>              birbiri yakınına yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşturulmuş.<br/>              Bu gibi durumlarda hedef formatların renderleyicileri (ör. DOCS formatı için MsWord) bazen oluşturur<br/>              arka plan görüntülerinin parçaları arasında görülebilir sınırlar,<br/>              çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır.<br/>               Eğer dışa aktarılan belgenin böyle görülebilir sınırlar içerdiği görülürse <br/>              aynı arka plan görüntülerinin parçaları arasında, lütfen bu ayarı kullanarak bu istenmeyen etkiden <br/>              kurtulmayı deneyin. <br/>                DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır,<br/>              bu yüzden, lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |
| mod | Tanıma modu. |
| relative_horizontal_proximity | Pdf'de kelimeler, kelimeleri harflerini veya hecelerini bağımsız olarak yazdıran operatörlerle içsel olarak temsil edilebilir.<br/>              Kelimeleri tespit etmek için bazen gerçek kelimeler olan bağımsız karakter gruplarını tespit etmemiz gerekir.<br/>                Bu ayar, metin öğeleri (harfler, heceler) arasındaki boşluk genişliğini tanımlar<br/>              ve kaynak PDF'de kelimelerin tanınması sırasında kelimeler arasındaki mesafe olarak kabul edilmelidir.<br/>              (harfler arasında en az bu genişlikte boşluk bulunması, metin öğelerinin farklı kelimelere ait olduğu anlamına gelir).<br/>              Bu değer yazı tipi boyutuna göre normlanmıştır - 1.0, varsayılan kelime yazı tipi boyutunun %100'ü anlamına gelir.<br/>             DİKKAT! Bu yalnızca kaynak PDF, optimal değerinin yazı tipinden hesaplanamadığı nadir kullanılan belirli yazı tiplerini içerdiğinde kullanılır.<br/>             Bu nedenle, çoğu durumda bu parametre sonuç belgesinde hiçbir değişiklik yapmaz. |
| max_distance_between_text_lines | Bu parametre, metin satırlarını paragraflara gruplamak için kullanılır.<br/>            İki göreceli metin satırının ne kadar uzakta olabileceğini belirler. Metin satırının yüksekliğinin yüzde yüzlerce cinsinden belirtilir. |
| recognize_bullets | Madde işaretlerinin tanınmasını etkinleştir |
| add_return_to_line_end | Paragraf veya satır sonlarını kullan |
| image_resolution_x | Dönüştürülen görüntülerin X çözünürlüğü. |
| image_resolution_y | Dönüştürülen görüntülerin Y çözünürlüğü. |
| format | Çıktı biçimi |
| batch_size | Toplu dönüşüm uygulanabilir olduğunda toplu boyutunu tanımlar<br/>            kaynak ve hedef format çiftine. |
| memory_save_mode_path | Bellek tasarruf modunda dönüştürme sırasında geçici verileri tutacak yolu (dosya adı veya dizin adı) tanımlar.<br/>             |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

