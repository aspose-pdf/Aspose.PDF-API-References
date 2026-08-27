---
title: "FormEditor"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Formları düzenlemek için sınıf (alan ekleme/silme vb.)"
type: docs
weight: 110
url: /tr/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

Formları düzenlemek için sınıf (alan ekleme/silme vb.)

FormEditor türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| FormEditor(src_stream, dest_stream) | FormEditor sınıfının yeni bir örneğini başlatır |
| FormEditor(src_file_name, dest_file_name) | FormEditor sınıfının yeni bir örneğini başlatır |
| FormEditor() | FormEditor için yapıcı. |
| FormEditor(document) | FormEditor sınıfının yeni bir örneğini başlatır |
| FormEditor(document, dest_file_name) | FormEditor sınıfının yeni bir örneğini başlatır |
| FormEditor(document, dest_stream) | FormEditor sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| src_file_name | Kaynak dosyanın adını alır veya ayarlar. |
| dest_file_name | Hedef dosya adını alır veya ayarlar. |
| src_stream | Kaynak akışı alır veya ayarlar. |
| dest_stream | Hedef akışı alır veya ayarlar. |
| items | Yeni oluşturulan liste kutusuna veya combo kutusuna eklenecek öğeleri ayarlar. |
| export_items | Dışa aktarım değerlerine sahip combo kutusu için seçenekleri ayarlar. |
| facade | Alanının görsel özniteliklerini ayarlar. |
| radio_gap | İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydeden üye, varsayılan değer 50'dir. |
| radio_horiz | Radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini gösteren bayrak, varsayılan değer doğrudur. |
| radio_button_item_size | Yeni radyo düğmesi alanı eklendiğinde radyo düğmesi öğesi boyutunu alır veya ayarlar. |
| submit_flag | Gönder düğmesinin gönderim bayraklarını ayarla. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(src_file) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_stream) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save() | Değişiklikleri hedef dosyaya kaydeder. |
| save(dest_file) | Değişiklikleri hedef dosyaya kaydeder. |
| save(dest_stream) | Değişiklikleri hedef dosyaya kaydeder. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | Belirtilen türde alanı forma ekler. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | Belirtilen türde alanı forma ekler. |
| copy_inner_field(field_name, new_field_name, page_num) | Mevcut bir alanı belirtilen sayfa numarasındaki aynı konuma kopyalar.<br/>            Yeni bir belge oluşturulur; bu belge, kaynak belgenin tüm içeriğini, yeni kopyalanan alan dışındaki kısmı ile birlikte içerir. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | Mevcut bir alanı sayfa numarası ve koordinatlar tarafından belirtilen yeni konuma kopyalar.<br/>            Yeni bir belge oluşturulur; bu belge, kaynak belgenin tüm içeriğini, yeni kopyalanan alan dışındaki kısmı ile birlikte içerir. |
| copy_outer_field(src_file_name, field_name) | Mevcut bir alanı bir PDF belgesinden, orijinal sayfa numarası ve koordinatlarıyla başka bir belgeye kopyalar.<br/>            Not: Yalnızca AcroForm alanları için (radyo kutusu hariç). |
| copy_outer_field(src_file_name, field_name, page_num) | Mevcut bir alanı bir PDF belgesinden, belirtilen sayfa numarası ve orijinal koordinatlarla başka bir belgeye kopyalar.<br/>             Not: Yalnızca AcroForm alanları için (radyo kutusu hariç). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | Mevcut bir alanı bir PDF belgesinden, belirtilen sayfa numarası ve koordinatlarla başka bir belgeye kopyalar.<br/>            Not: Yalnızca AcroForm alanları için (radyo kutusu hariç). |
| decorate_field(field_name) | Belirtilen alanın görsel özelliklerini değiştirir. |
| decorate_field(field_type) | Belirtilen alan türüne sahip tüm alanların görsel özelliklerini değiştirir. |
| decorate_field() | Belirtilen alanın görsel özelliklerini değiştirir. |
| add_list_item(field_name, item_name) | Liste kutusuna yeni öğe ekler. |
| add_list_item(field_name, export_name) | Mevcut liste kutusu alanına Export değeriyle yeni bir öğe ekler, yalnızca AcroForm combo kutusu alanı için. |
| close() | Facade'i kapatır. |
| set_field_attribute(field_name, flag) | Alan özelliklerini ayarlar. |
| set_field_appearance(field_name, flags) | Alan bayraklarını ayarla |
| get_field_appearance(field_name) | Alan bayraklarını al. |
| set_submit_flag(field_name, submit_form_flag) | Gönder düğmesinin gönderim bayrağını ayarla. |
| set_submit_url(field_name, url) | Düğmenin URL'sini ayarlar. |
| set_field_limit(field_name, field_limit) | Metin alanının azami karakter sayısını ayarlar. |
| set_field_comb_number(field_name, comb_number) | Düzenli tek satırlık metin alanı için tarama sayısını ayarlar (alan, <br/>            combNumber parametresinin değeri kadar eşit aralıklı konuma, yani taramalara, <br/>            otomatik olarak bölünür). |
| move_field(field_name, llx, lly, urx, ury) | Alan'ın yeni konumunu ayarla. |
| remove_field(field_name) | Alanı formdan kaldır. |
| reset_facade() | Tüm görsel öznitelikleri boş değere sıfırla. |
| reset_inner_facade() | İç cepheye ait tüm görsel öznitelikleri boş değere sıfırla. |
| rename_field(field_name, new_field_name) | Alan adını değiştir. |
| remove_field_action(field_name) | Alan için gönderme eylemini kaldır. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | Form üzerine gönderme düğmesi ekle. |
| del_list_item(field_name, item_name) | Liste alanından öğeyi sil. |
| set_field_script(field_name, script) | PushButton alanı için JavaScript ayarla. Eski JavaScript mevcutsa, yeniyle değiştirilecektir. |
| add_field_script(field_name, script) | PushButton alanı için JavaScript ekle. Eski bir olay varsa, yeni olay ona eklenir. |
| single_2_multiple(field_name) | Tek satırlı metin alanını çok satırlı bir alana dönüştür. |
| set_field_alignment(field_name, alignment) | Metin alanının hizalama stilini ayarla. |
| set_field_alignment_v(field_name, alignment) | Metin alanının dikey hizalama stilini ayarla. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

