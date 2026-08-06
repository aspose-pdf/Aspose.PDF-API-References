---
title: "Page"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF belgesinin sayfasını temsil eden sınıf."
type: docs
weight: 1080
url: /tr/python-net/aspose.pdf/page/
---

## Page class

PDF belgesinin sayfasını temsil eden sınıf.

Page türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| is_add_paragraphs_after_last | Sayfanın son paragrafından sonra paragraf eklemeyi alır veya ayarlar |
| background_image | Sayfa için arka plan görüntüsünü alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| toc_info | İçindekiler tablosu bilgisini alır veya ayarlar. |
| header | Sayfa başlığını alır veya ayarlar. |
| katmanlar | Katmanlar koleksiyonunu alır veya ayarlar. |
| alt bilgi | Sayfa alt bilgisini alır veya ayarlar. |
| paragraphs | Paragrafları alır. |
| page_info | Sayfa bilgisini alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| dikdörtgen | Sayfanın dikdörtgenini alır veya ayarlar.<br/>            Alırken: belirtilmişse sayfa kırpma kutusu döndürülür, aksi takdirde sayfa medya kutusu döndürülür.<br/>            Ayarlarken: sayfa medya kutusu her zaman ayarlanır.<br/>            Lütfen bu özelliğin sayfa dönüşünü dikkate almadığını unutmayın. Dönüşü dikkate alan sayfa dikdörtgenini elde etmek için lütfen ActualRect kullanın. |
| color_type | Sayfaların renk türünü SetColor operatörlerinden,<br/>            görüntüler ve formlar aracılığıyla alınan bilgilere göre ayarlar. |
| note_line_style | Notlar için satır stilini alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| tab_order | Sayfanın sekme sırasını alır veya ayarlar. <br/>            Olası değerler: Row, Column. Varsayılan, Manual |
| duration | Sayfa görüntüleme süresini alır veya ayarlar. Bu, sayfanın sunum sırasında saniye cinsinden gösterileceği süredir.<br/>            Süre tanımlı değilse -1 döndürür. |
| contents | Sayfanın içerik akışındaki operatörlerin koleksiyonunu alır.<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| group | Sayfanın sayfa grubunun özelliklerini belirten bir grup öznitelik sınıfını alır veya ayarlar; bu, şeffaf görüntüleme modelinde kullanılır. |
| annotations | Sayfa ek açıklamalarının koleksiyonunu alır.<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | Sayfa kaynaklarını alır. Resources nesnesi görüntüler, formlar ve yazı tiplerinin koleksiyonlarını içerir.<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| döndür | Sayfanın dönüşünü alır veya ayarlar. |
| trim_box | Sayfanın trim kutusunu alır veya ayarlar. |
| art_box | Sayfanın art kutusunu alır veya ayarlar. |
| bleed_box | Sayfanın bleed kutusunu alır veya ayarlar. |
| crop_box | Sayfanın kırpma kutusunu alır veya ayarlar. |
| media_box | Sayfanın medya kutusunu alır veya ayarlar. |
| sayı | Sayfanın numarasını al. |
| rotation_matrix | Sayfa için dönüşüm matrisini alır. |
| background | Sayfanın arka plan rengini alır veya ayarlar. |
| watermark | Sayfanın filigranını alır veya ayarlar. |
| artifacts | Sayfadaki artefaktların koleksiyonunu alır. |
| eylemler | Sayfa özelliklerinin koleksiyonunu alır. |
| fields_in_tab_order | Bu sayfadaki sekme sırasındaki Field nesnelerinin listesini alır. |
| user_unit | UserUnit değerini alır veya ayarlar. Varsayılan kullanıcı alanı birimlerinin boyutunu, 1 ⁄ 72 inç'in katları olarak veren pozitif bir sayıdır.<br/>            Varsayılan değer 1'dir. Bu sayfadaki girişi temizlemek için sıfır veya negatif bir değer ayarlayın. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| send_to(device, output) | Sayfayı verilen sayfa cihazı ile işleme gönderir. |
| send_to(device, output_file_name) | Sayfayı verilen sayfa cihazı ile işleme gönderir. |
| accept(visitor) | Anotasyonlarla çalışmak için işlevsellik sağlayan bir ziyaretçi nesnesi olan [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) kabul eder. |
| accept(visitor) | Metin nesneleriyle çalışmak için işlevsellik sağlayan bir ziyaretçi nesnesi olan [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) kabul eder. |
| accept(visitor) | Görüntü yerleştirme nesneleriyle çalışmak için işlevsellik sağlayan bir ziyaretçi nesnesi olan [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) kabul eder. |
| accept(visitor) | Metin nesneleriyle çalışmak için işlevsellik sağlayan bir ziyaretçi nesnesi olan [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) kabul eder. |
| add_image(image_stream, image_rect) | Görüntüyü sayfaya ekler ve belirtilen dikdörtgenin ortasına, görüntünün oranını koruyarak yerleştirir. |
| add_image(hocr, image_stream, image_rect) | Aranabilir görüntüyü sayfaya ekler ve belirtilen dikdörtgenin ortasına, görüntünün oranını koruyarak yerleştirir. |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | Sayfaya görüntü ekler ve görüntünün dikdörtgen konumuna göre yerleştirir. |
| add_image(image_path, rectangle) | Aranabilir görüntüyü sayfaya ekler ve belirtilen dikdörtgenin ortasına, görüntünün oranını koruyarak yerleştirir. |
| is_blank(fill_threshold_factor) | Sayfanın boş olup olmadığını gösteren bayrağı alır. |
| get_page_rect(consider_rotation) | Sayfanın CropBox'una (veya CropBox null ise MediaBox'a) göre sayfanın dikdörtgenini döndürür. |
| calculate_content_b_box() | Görünür kenar boşlukları olmadan içeriği kapsayan dikdörtgeni (bbox) hesaplar. |
| rotation_to_int(rotation) | Dönüşüm enum üyesini tamsayı değerine çevirir. |
| int_to_rotation(rotation) | Tamsayı değerini karşılık gelen dönüşüm enum üyesine çevirir. |
| add_stamp(stamp) | Sayfaya damga koyar. Damga sayfa numarası, görüntü veya basit metin, ör. bir logo olabilir. |
| flatten() | Sayfada bulunan tüm alanları kaldırır ve yerine değerlerini yerleştirir. |
| set_page_size(width, height) | Sayfanın boyutunu ayarlar. |
| make_grayscale() | Sayfayı gri tonlamaya dönüştürür. |
| free_memory() | Önbelleğe alınmış verileri temizler |
| get_notifications() | Sayfa içeriğiyle ilgili iç işlemler hakkında bildirimleri döndürür. (Şu anda yalnızca metin ekleme senaryolarındaki paragraf olaylarıyla ilgili bildirimler desteklenmektedir.) |
| as_byte_array(resolution) | Mevcut sayfayı bitmap olarak dönüştürür ve ardından bayt dizisini döndürür. |
| as_xml() | Mevcut sayfayı utf8 kodlamasında xml olarak dönüştürür. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

