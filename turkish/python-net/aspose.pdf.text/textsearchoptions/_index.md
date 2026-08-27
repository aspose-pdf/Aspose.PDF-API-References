---
title: "TextSearchOptions"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Metin arama seçeneklerini temsil eder"
type: docs
weight: 460
url: /tr/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

Metin arama seçeneklerini temsil eder

TextSearchOptions türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | TextSearchOptions sınıfının yeni bir örneğini başlatır |
| TextSearchOptions(rectangle) | TextSearchOptions sınıfının yeni bir örneğini başlatır |
| TextSearchOptions(rectangle, is_regular_expression_used) | TextSearchOptions sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| is_regular_expression_used | Düzenli ifadenin kullanıldığını gösteren değeri alır veya ayarlar. |
| limit_to_page_bounds | Metnin sayfa sınırları içinde aranacağını gösteren değeri alır veya ayarlar. |
| rectangle | Aranan metni sınırlayan dikdörtgeni alır veya ayarlar. |
| use_font_engine_encoding | Metnin font motoru kodlaması kullanılarak aranacağını gösteren değeri alır veya ayarlar.<br/>            true - font motoru kodlamasının kullanılacağını belirtir (belgedeki eksik kodlamadan dolayı metin araması başarısız olursa bunu deneyin)<br/>            false - belge font kodlamasının kullanılacağını belirtir (varsayılan değer) |
| ignore_shadow_text | Normal metnin gölgesini temsil eden metin parçacıklarının arama sırasında yoksayılacağını gösteren değeri alır veya ayarlar.<br/>            true - gölge metnin bulunmayacağını belirtir (metin araması yakın konumlardaki yinelenen parçacıklar döndürürse bunu deneyin)<br/>            false - gölge metnin normal metinle birlikte bulunacağını belirtir (varsayılan değer) |
| log_text_extraction_errors | Metin (parçacık) emicinde metin çıkarma (kod çözme) hatalarının kaydedileceğini gösteren değeri alır veya ayarlar.<br/>            true - metin çıkarma (kod çözme) hatalarının kaydedileceğini belirtir. Performansı düşürebilir.<br/>            false (varsayılan) - hata kaydı yapılmaz. |
| ignore_resource_font_errors | Metin (parça) emicisi tarafından yazı tipi eksikliğiyle ilgili hataların göz ardı edilmesini belirten değeri alır veya ayarlar.<br/>            true - yazı tipi eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara başvuran metin bölümleri işleme sırasında atlanacaktır.<br/>            false (default) - yazı tipi eksikliği hatası, bir istisna fırlatarak işlemi sonlandırır. |
| search_for_text_related_graphics | Metin araması sırasında metinle ilgili grafiklerin (alt çizgi, arka plan vb.) aranmasına izin veren değeri alır veya ayarlar.<br/>            true - metinle ilgili grafiklerin aranması gerçekleştirilecektir (varsayılan değer).<br/>            false - kaynak belgede bulunabilecek grafik öğeleri göz ardı edilecektir. Performans sorunları olduğunda veya alt çizgi, arka plan ya da kırpma işlemlerine ihtiyaç duyulmadığında bunu ayarlayın. |
| stored_graphic_elements_max_count | Bir sayfada metinle ilgili grafiklerin (alt çizgi, arka plan vb.) aranmasını belirtilen öğe sayısı ile sınırlayan değeri alır veya ayarlar.<br/>            Varsayılan değer 250'dir. Performans sorunları durumunda daha düşük bir değer ayarlayın, bazı grafik öğeler bulunamadığında daha yüksek bir değer deneyin. |
| search_in_annotations | Ek açıklamalarda (Annotations) metin aranmasına izin veren değeri alır veya ayarlar.<br/>            true - metin Ek açıklamalarda aranacaktır.<br/>            false - Ek açıklamalardaki metin, TextFragmentAbsorber tarafından ayrıştırılmayacaktır. |

### Ayrıca Bakınız

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

