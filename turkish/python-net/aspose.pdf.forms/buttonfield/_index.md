---
title: "ButtonField"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Sınıf, itme düğmesi alanını temsil eder."
type: docs
weight: 20
url: /tr/python-net/aspose.pdf.forms/buttonfield/
---

## ButtonField class

Sınıf, itme düğmesi alanını temsil eder.

ButtonField türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| ButtonField() | Generator için Button alanı yapıcı. |
| ButtonField(page, rect) | ButtonField sınıfının yeni bir örneğini başlatır |
| ButtonField(doc, rect) | ButtonField sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| vertical_alignment | Yok |
| horizontal_alignment | Yok |
| kenar boşluğu | Yok |
| is_first_paragraph_in_column | Yok |
| is_kept_with_next | Yok |
| is_in_new_page | Yok |
| is_in_line_paragraph | Yok |
| köprü | Yok |
| z_index | Yok |
| donusturme_sirasinda_gorunum_guncelle | Yok |
| yazı_tipi_altkümesini_kullan | Yok |
| bayraklar | Yok |
| ek_aciklama_tipi | Ek açıklamanın türünü alır. |
| genişlik | Yok |
| eylemler | Ek açıklama eylemlerini alır. |
| yükseklik | Yok |
| dikdörtgen | Alan dikdörtgenini alır veya ayarlar. |
| içerik | Yok |
| name | Yok |
| değiştirildi | Yok |
| renk | Yok |
| kenar | Yok |
| aktif_durum | Yok |
| özellikler | Yok |
| durumlar | Yok |
| hizalama | Yok |
| metin_yatay_hizalama | Yok |
| tam_ad | Yok |
| görünüm | Yok |
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
| normal_caption | Normal başlığı alır veya ayarlar. |
| rollover_caption | Düğmenin, kullanıcı fare imlecini <br/>            aktif alanına basmadan kaydırdığında gösterilecek rollover başlığını alır veya ayarlar. |
| alternate_caption | Düğmenin, <br/>            aktif alanı içinde fare düğmesine basıldığında gösterilecek alternatif başlığını alır veya ayarlar. |
| normal_icon | Düğmenin, kullanıcıyla etkileşime girmediğinde gösterilecek normal simgesini alır veya ayarlar. |
| rollover_icon | Düğmenin, kullanıcı <br/>            fare imlecini aktif alanına basmadan kaydırdığında gösterilecek rollover simgesini alır veya ayarlar. |
| alternate_icon | Aktif alan içinde fare düğmesine basıldığında gösterilecek alternatif simgeyi alır veya ayarlar. |
| icon_fit | Widget açıklamasının simgesinin açıklama dikdörtgeni içinde nasıl görüntüleneceğini belirten ikon uyum nesnesini alır. |
| ic_position | İkon başlığı konumunu alır veya ayarlar. |
## Indexer
| Ad | Açıklama |
| :- | :- |
| [index] | Bu alanda indeks ile bulunan alt alanı alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| clone() | Yok |
| get_rectangle(consider_rotation) | Yok |
| accept(visitor) | Ziyaretçiyi kabul eder. |
| flatten() | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| change_after_resize(transform) | Yok |
| recalculate() | Formdaki tüm hesaplanmış alanları yeniden hesaplar. |
| copy_to(array, index) | Bu alanın alt alanlarını belirtilen indeksden başlayarak diziye kopyalar. |
| set_position(point) | Alanının konumunu ayarlar. |
| add_image(image) | Görüntüyü alan kaynaklarına ekler ve çizer. |

### Ayrıca Bakınız

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

