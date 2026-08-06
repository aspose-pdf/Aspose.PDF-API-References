---
title: "ListBoxField"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "ListBox alanını temsil eden sınıf."
type: docs
weight: 140
url: /tr/python-net/aspose.pdf.forms/listboxfield/
---

## ListBoxField class

ListBox alanını temsil eden sınıf.

ListBoxField türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| ListBoxField() | Generator içinde kullanılmak üzere ListBoxField için yapıcı. |
| ListBoxField(page, rect) | ListBoxField sınıfının yeni bir örneğini başlatır |
| ListBoxField(doc, rect) | ListBoxField sınıfının yeni bir örneğini başlatır |
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
| ek_aciklama_tipi | Yok |
| genişlik | Yok |
| eylemler | Yok |
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
| etkinleştirildiğinde | Yok |
| vurgulama | Yok |
| üst | Yok |
| default_appearance | Yok |
| read_only | Yok |
| required | Yok |
| exportable | Yok |
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
| commit_immediately | Seçim değişikliği sırasında commit bayrağını alır veya ayarlar. |
| multi_select | Çoklu seçim bayrağını alır veya ayarlar. |
| selected | Seçili öğenin indeksini alır veya ayarlar. Öğeler 1'den başlar. |
| selected_items | Çoklu seçim listesinde seçilen öğelerin dizisini alır veya ayarlar. Tek seçim listesi için tek öğeli bir dizi döndürür. |
| seçenekler | Seçim seçeneklerinin koleksiyonunu alır. |
| top_index | Listenin en üstte görünen öğesinin indeksini alır veya ayarlar. |
## Indexer
| Ad | Açıklama |
| :- | :- |
| [index] | Bu alanda indeks ile bulunan alt alanı alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| add_option(option_name) | Belirtilen adla yeni bir seçenek ekler. |
| add_option(export, name) | Belirtilen adla yeni bir seçenek ekler. |
| clone() | Yok |
| get_rectangle(consider_rotation) | Yok |
| accept(visitor) | Yok |
| flatten() | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| change_after_resize(transform) | Yok |
| recalculate() | Formdaki tüm hesaplanmış alanları yeniden hesaplar. |
| copy_to(array, index) | Bu alanın alt alanlarını belirtilen indeksden başlayarak diziye kopyalar. |
| set_position(point) | Alanının konumunu ayarlar. |
| delete_option(option_name) | Seçeneği adıyla siler. |

### Ayrıca Bakınız

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

