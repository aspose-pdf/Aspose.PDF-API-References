---
title: "StampAnnotation"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Kauçuk damga ek açıklamasını temsil eder. <br/>             Bu tür ek açıklama, sayfaya bir kauçuk damga ile basılmış gibi görünen metin veya grafik gösterir."
type: docs
weight: 790
url: /tr/python-net/aspose.pdf.annotations/stampannotation/
---

## StampAnnotation class

Kauçuk damga ek açıklamasını temsil eder. <br/>             Bu tür ek açıklama, sayfaya bir kauçuk damga ile basılmış gibi görünen metin veya grafik gösterir.

StampAnnotation türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| StampAnnotation(document) | StampAnnotation sınıfının yeni bir örneğini başlatır |
| StampAnnotation(page, rect) | StampAnnotation sınıfının yeni bir örneğini başlatır |
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
| icon | Kauçuk damga için simgeyi alır veya ayarlar. |
| image | Ek açıklamanın görüntüsünü alır veya ayarlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| clone() | Yok |
| get_rectangle(consider_rotation) | Sayfa dönüşünü dikkate alarak ek açıklamanın dikdörtgenini döndürür. |
| accept(visitor) | [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) ziyaretçisini kabul ederken ek açıklama koleksiyonunu inceler. |
| flatten() | Ek açıklama içeriğini doğrudan sayfaya yerleştirir,<br/>            ek açıklama nesnesi kaldırılacaktır. |
| change_after_resize(transform) | Parametreleri ve görünümü, matris dönüşümüne göre günceller. |

### Ayrıca Bakınız

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

