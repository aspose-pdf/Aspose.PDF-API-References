---
title: "Form"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Form nesnesini temsil eden sınıf."
type: docs
weight: 110
url: /tr/python-net/aspose.pdf.forms/form/
---

## Form class

Form nesnesini temsil eden sınıf.

Form türü aşağıdaki üyeleri ortaya çıkar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| is_synchronized | Nesne iş parçacığı güvenli ise true döndürür. |
| sync_root | Eşzamanlama nesnesini döndürür. |
| auto_recalculate | Ayarlanırsa, herhangi bir alan değiştirildiğinde tüm form alanları yeniden hesaplanır. Varsayılan değer true'tır. Çok sayıda hesaplanmış alan içeren form doldurulurken performansı artırmak için false olarak ayarlayın. |
| auto_restore_form | Ayarlanırsa, eksik form alanları ek açıklamalarda mevcutsa otomatik olarak oluşturulur. |
| default_resources | Bu forma yerleştirilen varsayılan kaynakları alır. |
| default_appearance | Formun varsayılan görünümünü alır veya ayarlar (form alanları için varsayılan yazı tipi, metin boyutu ve rengi tanımlayan nesne). |
| xfa | Formun XFA verilerini alır (varsa). |
| ignore_needs_rendering | Bu özellik true ise NeedsRendering anahtarının değeri dönüşüm sırasında yok sayılacaktır <br/>            XFA formundan Standart forma. Varsayılan olarak false'tur. |
| remove_permission | Bu özellik true ise "Perms" sözlüğü, pdf belgesi dönüşümden sonra kaldırılacaktır <br/>            dinamik belgelerden standart forma. "Perms" sözlüğü, Adobe Acrobat okuyucusunda zorunlu alanların seçim görüntülenmesini bozabilecek kurallar içerebilir.<br/>            Varsayılan olarak false'tur. |
| emulate_requierd_groups | Bu özellik true ise gerekli Xfa exclGroup öğe kapsayıcıları için ek kırmızı sınır dikdörtgenleri çizilecektir<br/>            Bu özellik, Xfa form temsilinin standart forma dönüşümü sırasında exclGroup için benzerlerin olmaması nedeniyle tanıtıldı.<br/>            Varsayılan olarak false'tur. |
| type | Formun tipini alır. Olası değerler: Standard, Static, Dynamic. |
| fields | Hiyerarşik formun en düşük seviyesindeki tüm alanların listesini alır. |
| signatures_exist | Ayarlanırsa, belge en az bir imza alanı içerir. |
| signatures_append_only | Ayarlanırsa, belge, dosya önceki içeriğini değiştirecek şekilde kaydedildiğinde (yazıldığında) geçersiz olabilecek imzalar içerir, <br/>            artımlı bir güncellemenin aksine. |
| sign_dependent_elements_rendering_mode_when_converted | Formlar imzalama bilgisi içerebilir, yani imzalı ya da imzasız olabilir.<br/>              Ve formun görünümü bazen formun imzalı olup olmamasına bağlı olmalıdır.<br/>              Bu özellik, form dönüştürücüsüne (ör. XFA formunu Standart forma dönüştürürken)<br/>              sonuç formun imzalı mı yoksa imzasız mı render edilmesi gerektiğini bildirir. |
## Indexer
| Ad | Açıklama |
| :- | :- |
| [index] | Formun alanını alan indeksine göre alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| delete(field) | Formdan alanı sil. |
| delete(field_name) | Formdan alanı adını kullanarak siler. |
| add(field, page_number) | Form üzerine alan ekler. |
| add(field) | Form üzerine alan ekler. |
| add(field, partial_name, page_number) | Form'a yeni bir alan ekler; Bu alan zaten başka bir formda veya bu formda yer alıyorsa, alanın bir kopyası oluşturulur. |
| has_field(field) | Formun zaten belirtilen alana sahip olup olmadığını kontrol edin. |
| has_field(field_name) | Belirtilen isimdeki alanın zaten Form'a eklenip eklenmediğini belirler. |
| copy_to(array, index) | Formda yer alan alanları diziye kopyalar. |
| flatten() | Tüm form alanlarını kaldırır ve değerlerini doğrudan sayfaya yerleştirir. |
| add_field_appearance(field, page_number, rect) | Belirtilen konumda, belgenin belirtilen sayfasına alanın ek bir görünümünü ekler. |
| get_fields_in_rect(rect) | Belirtilen dikdörtgen içindeki alanları döndürür. |

### Ayrıca Bakınız

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

