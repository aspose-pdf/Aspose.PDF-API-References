---
title: "SignatureField"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "İmza form alanını temsil eder."
type: docs
weight: 270
url: /tr/python-net/aspose.pdf.forms/signaturefield/
---

## SignatureField class

İmza form alanını temsil eder.

SignatureField türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| SignatureField(page, rect) | SignatureField sınıfının yeni bir örneğini başlatır. |
| SignatureField(doc, rect) | SignatureField sınıfının yeni bir örneğini başlatır. |
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
| signature | İmza nesnesini alır.<br/>            Bu nesne, açık anahtar kriptografik standartlarıyla ilgili imza verilerini içerir.<br/>            [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/), [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/) ve [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/) sınıfları <br/>            desteklenen tüm imza nesnesi türlerini temsil eder. |
## Indexer
| Ad | Açıklama |
| :- | :- |
| [index] | Bu alanda indeks ile bulunan alt alanı alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| sign(signature, pfx, pass) | Bu imza alanını kullanarak belgeyi imzalar. |
| sign(signature) | Bu imza alanını kullanarak belgeyi imzalar. |
| extract_image() | İmzanın görüntüsünü jpeg kodlu akış olarak çıkarır. |
| extract_image(format) | İmzanın görüntüsünü kodlanmış akış olarak çıkarır. |
| clone() | Yok |
| get_rectangle(consider_rotation) | Yok |
| accept(visitor) | Ziyaretçiyi kabul eder. |
| flatten() | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| change_after_resize(transform) | Yok |
| recalculate() | Formdaki tüm hesaplanmış alanları yeniden hesaplar. |
| copy_to(array, index) | Bu alanın alt alanlarını belirtilen indeksden başlayarak diziye kopyalar. |
| set_position(point) | Alanının konumunu ayarlar. |
| extract_certificate() | Tek X.509 sertifikasını DER formatında bir akış olarak çıkarır. |

### Ayrıca Bakınız

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

