---
title: "RedactionAnnotation"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Redact ek açıklamasını temsil eder."
type: docs
weight: 680
url: /tr/python-net/aspose.pdf.annotations/redactionannotation/
---

## RedactionAnnotation class

Redact ek açıklamasını temsil eder.

RedactionAnnotation türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| RedactionAnnotation(document) | RedactionAnnotation sınıfının yeni bir örneğini başlatır. |
| RedactionAnnotation(page, rect) | RedactionAnnotation sınıfının yeni bir örneğini başlatır. |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| vertical_alignment | Yok |
| horizontal_alignment | Ek açıklama için metin hizalamasını alır veya ayarlar. |
| kenar boşluğu | Yok |
| is_first_paragraph_in_column | Yok |
| is_kept_with_next | Yok |
| is_in_new_page | Yok |
| is_in_line_paragraph | Yok |
| köprü | Yok |
| z_index | Yok |
| donusturme_sirasinda_gorunum_guncelle | Doğru ise, PF belgesi görüntüye dönüştürülmeden önce ek açıklama görünümü güncellenir. Bu, alanların doğru dönüştürülmesini sağlar ancak muhtemelen daha fazla zaman gerektirir. |
| yazı_tipi_altkümesini_kullan | Bu özellik true olarak ayarlanırsa, yazı tipleri belgeye alt küme olarak eklenir. Varsayılan değer true'tur. |
| bayraklar | Ek açıklamanın bayrakları. |
| ek_aciklama_tipi | Ek açıklamanın türünü alır. |
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
| title | Ek açıklamanın başlık çubuğunda gösterilecek metni alır veya ayarlar. |
| rich_text | Ek açıklama açıldığında pop-up penceresinde görüntülenecek zengin metin dizesini alır veya ayarlar. |
| creation_date | Ek açıklamanın oluşturulduğu tarih ve saati alır. |
| subject | Nesnenin açıklamasını temsil eden metni alır. |
| popup | Bu ek açıklamayla ilişkili metni girmek veya düzenlemek için pop-up ek açıklaması. |
| opaklık | Ek açıklamayı çizerken kullanılacak sabit opaklık değerini alır veya ayarlar. |
| in_reply_to | Bu ek açıklamanın "yanıtı" olduğu ek açıklamaya bir referans.<br/>            Her iki ek açıklama da belgenin aynı sayfasında olmalıdır. |
| reply_type | Bu ek açıklama ile InReplyTo tarafından belirtilen ek açıklama arasındaki ilişkiyi ("yanıt türü") belirten bir dize.<br/>             |
| quad_point | Kaldırılması amaçlanan içerik bölgesinin koordinatlarını belirten 8xN sayı dizisi. |
| default_appearance | Varsayılan görünüm dizesini alır veya ayarlar. |
| fill_color | Ek açıklamayı doldurmak için rengi alır veya ayarlar. |
| border_color | Redaksiyon aktif olmadığında çizilen kenarın rengini alır veya ayarlar. |
| overlay_text | Redaksiyon ek açıklamasına yazdırılacak metin. |
| repeat | Doğru ise overlay text ek açıklama üzerinde tekrarlanacaktır. |
| text_alignment | Alır veya ayarlar. Overlay Text hizalaması. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| clone() | Yok |
| get_rectangle(consider_rotation) | Sayfa dönüşünü dikkate alarak ek açıklamanın dikdörtgenini döndürür. |
| accept(visitor) | Ek açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| flatten() | Ek açıklamayı düzleştirir, yani ek açıklamayı kaldırır ve onun eklenmesini sağlar. |
| change_after_resize(transform) | Parametreleri ve görünümü, matris dönüşümüne göre günceller. |
| redact() | Ek açıklamayı düzleştirir ve sayfa içeriklerini redakte eder (yani redakte edilen ek açıklamanın altındaki metin ve görüntüyü kaldırır). |

### Ayrıca Bakınız

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

