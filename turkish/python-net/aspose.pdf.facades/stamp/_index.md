---
title: "Stamp"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Damga temsil eden sınıf."
type: docs
weight: 410
url: /tr/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

Damga temsil eden sınıf.

Stamp türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| Stamp() | Stamp sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| stamp_id | Damganın tanımlayıcısını alır veya ayarlar. |
| kalite | Damga görüntüsünün kalitesini yüzde olarak alır veya ayarlar. Geçerli değerler 0..100%. |
| opaklık | Damganın opaklığını alır veya ayarlar. |
| page_number | Sayfa numarasını alır veya ayarlar. |
| sayfalar | Damga tarafından etkilenecek sayfa numaralarını içeren diziyi alır veya ayarlar. <br/>            Eğer Pages = null ise belgenin tüm sayfaları etkilenir. |
| rotation | Damganın döndürülmesini derece cinsinden alır veya ayarlar. |
| is_background | Arkaplan durumunu alır veya ayarlar. true ise damga, damgalanan sayfanın arkaplanı olarak yerleştirilir.<br/>            Varsayılan olarak false olarak ayarlanır. |
| blending_space | BlendingColorSpace değerini alır veya ayarlar. Bu değer, sayfada şeffaflık ve karıştırma işlemlerini gerçekleştirmek için kullanılan bir renk uzayını tanımlar. <br/>             |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(pdf_file, page_number) | Damga olarak kullanılacak PDF dosyasını ve sayfa numarasını ayarlar. |
| bind_pdf(pdf_stream, page_number) | Damga olarak kullanılacak PDF dosyasını ve sayfa numarasını ayarlar. |
| bind_image(image_file) | Görüntüyü damga olarak ayarlar. |
| bind_image(image) | Damga olarak kullanılacak görüntüyü ayarlar. |
| bind_logo(formatted_text) | Metni damga olarak ayarlar. |
| bind_text_state(text_state) | Damga metninin metin durumunu ayarlar. |
| set_origin(origin_x, origin_y) | Damganın yerleştirileceği sayfadaki konumu ayarlar. |
| set_image_size(width, height) | Görüntü damgasının boyutunu ayarlar. Görüntü, belirtilen değerlere göre ölçeklendirilecektir. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

