---
title: "WatermarkAnnotation"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Watermark ek açıklama nesnesini tanımlayan sınıf."
type: docs
weight: 860
url: /tr/python-net/aspose.pdf.annotations/watermarkannotation/
---

## WatermarkAnnotation class

Watermark ek açıklama nesnesini tanımlayan sınıf.

WatermarkAnnotation türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| WatermarkAnnotation(page, rect) | WatermarkAnnotation sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| vertical_alignment | Paragrafın dikey hizalamasını alır veya ayarlar. |
| horizontal_alignment | Ek açıklama için metin hizalamasını alır veya ayarlar. |
| kenar boşluğu | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| is_first_paragraph_in_column | Bu paragrafın bir sonraki sütunda olup olmayacağını gösteren bool değerini alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| is_kept_with_next | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını gösteren bool değerini alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| is_in_new_page | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bool değerini alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| is_in_line_paragraph | Paragrafın satır içi olup olmadığını alır veya ayarlar.<br/>            Varsayılan false'tur. (pdf oluşturma için) |
| köprü | Parçacık hiperlinkini alır veya ayarlar (pdf oluşturucu için). |
| z_index | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex <br/>            bir grafik, daha küçük ZIndex değerine sahip grafiğin üzerine yerleştirilir. ZIndex negatif olabilir. Negatif <br/>            ZIndex bir grafik, sayfadaki metnin arkasına yerleştirilir. |
| donusturme_sirasinda_gorunum_guncelle | Doğru ise, PF belgesi görüntüye dönüştürülmeden önce ek açıklama görünümü güncellenir. Bu, alanların doğru dönüştürülmesini sağlar ancak muhtemelen daha fazla zaman gerektirir. |
| yazı_tipi_altkümesini_kullan | Bu özellik true olarak ayarlanırsa, yazı tipleri belgeye alt küme olarak eklenir. Varsayılan değer true'tur. |
| bayraklar | Ek açıklamanın bayrakları. |
| ek_aciklama_tipi | Annotation tipini alır. |
| genişlik | Ek açıklamanın genişliğini alır veya ayarlar. |
| eylemler | Ek açıklama eylemlerinin listesini alır. |
| yükseklik | Ek açıklamanın yüksekliğini alır veya ayarlar. |
| dikdörtgen | Ek açıklama dikdörtgenini alır veya ayarlar. |
| içerik | Ek açıklama metnini alır veya ayarlar. |
| name | Sayfadaki ek açıklama adını alır veya ayarlar. |
| değiştirildi | Ek açıklamanın son değiştirildiği tarih ve saati alır veya ayarlar. |
| renk | Ek açıklama rengini alır veya ayarlar. |
| border | Ek açıklama kenarlık özelliklerini alır veya ayarlar. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| aktif_durum | Mevcut anotasyon görünüm durumunu alır veya ayarlar. |
| özellikler | Ek açıklama özelliklerini alır. |
| durumlar | Ek açıklamanın görünüm sözlüğünü alır. |
| hizalama | Ek açıklama hizalaması. Bu özellik artık kullanılmıyor. Bunun yerine HorizontalAligment kullanın. |
| metin_yatay_hizalama | Ek açıklama için metin hizalamasını alır veya ayarlar. |
| tam_ad | Ek açıklamanın tam nitelikli adını alır. |
| görünüm | Ek açıklamanın görünüm sözlüğünü alır. |
| sayfa_indeksi | Ek açıklamayı içeren sayfanın indeksini alır. |
| fixed_print | Watermark annotation'ın sabit baskı nesnesi. |
| opaklık | Annotation opaklığını alır veya ayarlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| clone() | Bu örneği kopyalar.<br/>            Sanal yöntem. Her zaman null döndürür. |
| get_rectangle(consider_rotation) | Sayfa dönüşünü dikkate alarak ek açıklamanın dikdörtgenini döndürür. |
| accept(visitor) | Annotation için ziyaretçi uygula. |
| flatten() | Ek açıklama içeriğini doğrudan sayfaya yerleştirir,<br/>            ek açıklama nesnesi kaldırılacaktır. |
| change_after_resize(transform) | Parametreleri ve görünümü, matris dönüşümüne göre günceller. |
| set_text(text) | Annotation metnini ayarla. |
| set_text_and_state(text, text_state) | Annotation metnini ayarla. |

### Ayrıca Bakınız

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

