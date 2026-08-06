---
title: "Field"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Acro form alanları için temel sınıf."
type: docs
weight: 90
url: /tr/python-net/aspose.pdf.forms/field/
---

## Field class

Acro form alanları için temel sınıf.

Field türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| Field(doc) | Field sınıfının yeni bir örneğini başlatır |
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
| eylemler | Ek açıklama eylemlerini alır. |
| yükseklik | Ek açıklamanın yüksekliğini alır veya ayarlar. |
| dikdörtgen | Alan dikdörtgenini alır veya ayarlar. |
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
| sayfa_indeksi | Bu alanı içeren sayfanın indeksini alır. |
| etkinleştirildiğinde | Ek açıklama etkinleştirildiğinde gerçekleştirilecek bir eylem. |
| vurgulama | Ek açıklama vurgulama modu. |
| üst | Ek açıklama üst öğesini alır. |
| default_appearance | Alanının varsayılan görünümünü alır veya ayarlar. |
| read_only | Alanının yalnızca okuma durumunu alır veya ayarlar. |
| required | Alanının gerekli durumunu alır veya ayarlar. |
| exportable | Alanının dışa aktarılabilir bayrağını alır veya ayarlar. |
| partial_name | Alanının kısmi adını alır veya ayarlar. |
| alternate_name | Alanının alternatif adını alır veya ayarlar (Alternatif bir alan <br/>            adı, gerçek alan adının yerine kullanılacak <br/>            ve alanın kullanıcı arayüzünde tanımlandığı her yerde).<br/>            Alternatif ad, Adobe Acrobat'ta alan ipucu olarak kullanılır. |
| mapping_name | Belgeden etkileşimli form alanı verileri dışa aktarılırken kullanılacak alanın eşleme adını alır veya ayarlar. |
| value | Alanının değerini alır veya ayarlar. |
| is_synchronized | Sözlük senkronize edilmişse true döndürür. |
| sync_root | Senkronizasyon nesnesi. |
| is_group | Bu alanın son olmayan alan (yani alan grubu) olup olmadığını gösteren boolean değerini alır veya ayarlar. |
| annotation_index | Bu anotation'ın sayfadaki indeksini alır veya ayarlar. |
| is_shared_field | Generator desteği için özellik. Alan başlık ya da alt bilgiye eklendiğinde kullanılır. true ise, bu alan bir kez oluşturulur ve görünümü belgenin tüm sayfalarında görünür. false ise, her belge sayfası için ayrı bir alan oluşturulur. |
| fit_into_rectangle | true ise, yazı tipi boyutu belirtilen dikdörtgene sığacak şekilde küçültülür. |
| max_font_size | Maksimum yazı tipi boyutu, alan içeriği için kullanılabilir. Boyutu kontrol etmemek için -1. |
| min_font_size | Minimum yazı tipi boyutu, alan içeriği için kullanılabilir. Boyutu kontrol etmemek için -1. |
| tab_order | Alanının sekme sırasını alır veya ayarlar. |
## Indexer
| Ad | Açıklama |
| :- | :- |
| [index] | Bu alanda indeks ile bulunan alt alanı alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| clone() | Yok |
| get_rectangle(consider_rotation) | Sayfa dönüşünü dikkate alarak ek açıklamanın dikdörtgenini döndürür. |
| accept(visitor) | Ziyaretçiyi kabul eder. |
| flatten() | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| change_after_resize(transform) | Parametreleri ve görünümü, matris dönüşümüne göre günceller. |
| recalculate() | Formdaki tüm hesaplanmış alanları yeniden hesaplar. |
| copy_to(array, index) | Bu alanın alt alanlarını belirtilen indeksden başlayarak diziye kopyalar. |
| set_position(point) | Alanının konumunu ayarlar. |

### Ayrıca Bakınız

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

