---
title: "TextFragmentAbsorber"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Metin fragmentlerinin bir emici nesnesini temsil eder.<br/>            Metin araması yapar ve [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar."
type: docs
weight: 400
url: /tr/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

Metin fragmentlerinin bir emici nesnesini temsil eder.<br/>            Metin araması yapar ve [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar.

TextFragmentAbsorber türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| TextFragmentAbsorber() | Belge veya sayfanın tüm metin segmentlerini arayan [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) sınıfının yeni bir örneğini başlatır. |
| TextFragmentAbsorber(text_edit_options) | TextFragmentAbsorber sınıfının yeni bir örneğini başlatır |
| TextFragmentAbsorber(phrase) | TextFragmentAbsorber sınıfının yeni bir örneğini başlatır |
| TextFragmentAbsorber(phrase, text_search_options) | TextFragmentAbsorber sınıfının yeni bir örneğini başlatır |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | TextFragmentAbsorber sınıfının yeni bir örneğini başlatır |
| TextFragmentAbsorber(phrase, text_edit_options) | TextFragmentAbsorber sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| text | PDF belge veya sayfasında [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) tarafından çıkarılan metni alır. |
| has_errors | Değer, metin çıkarımı sırasında hataların bulunup bulunmadığını gösterir.<br/>            Hataların aranması yalnızca TextSearchOptions.LogTextExtractionErrors = true olduğunda gerçekleştirilecektir; ve bu performansı düşürebilir. |
| errors | [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) nesnelerinin listesi. Metin çıkarımı sırasında bulunan hatalar hakkında bilgi içerir.<br/>            Hataların aranması yalnızca TextSearchOptions.LogTextExtractionErrors = true olduğunda gerçekleştirilecektir; ve bu performansı düşürebilir. |
| extraction_options | Metin çıkarma seçeneklerini alır veya ayarlar. |
| text_search_options | Arama seçeneklerini alır veya ayarlar. Seçenekler, düzenli ifadeler kullanarak aramayı etkinleştirir. |
| text_fragments | Arama gerçekleşmelerinin koleksiyonunu alır; bu gerçekleşmeler [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) nesneleriyle sunulur. |
| phrase | [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) tarafından PDF belgesinde veya sayfasında aranan ifadeyi alır veya ayarlar. |
| text_edit_options | Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembolün yazı tipiyle yazılamadığı durumlarda özel davranışı tanımlar. |
| text_replace_options | Metin değiştirme seçeneklerini alır veya ayarlar. Seçenekler, parça metni daha kısa/uzun bir metinle değiştirildiğinde davranışı tanımlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| visit(page) | Belirtilen sayfada arama gerçekleştirir. |
| visit(pdf) | Belirtilen belgede arama gerçekleştirir. |
| visit(x_form) | Belirtilen form nesnesinde arama gerçekleştirir. |
| apply_for_all_fragments(font) | Emilen tüm metin parçalarına yazı tipini uygular. Sayfa(lar) üzerindeki tüm parçalar emildiyse, parçalar arasında döngü yapmaktan daha hızlı çalışır. Aksi takdirde döngüyle benzer şekilde çalışır. |
| apply_for_all_fragments(font_size) | Emilen tüm metin parçalarına yazı tipi boyutunu uygular. Sayfa(lar) üzerindeki tüm parçalar emildiyse, parçalar arasında döngü yapmaktan daha hızlı çalışır. Aksi takdirde döngüyle benzer şekilde çalışır. |
| apply_for_all_fragments(font, font_size) | Emilen tüm metin parçalarına yazı tipini ve boyutunu uygular. Sayfa(lar) üzerindeki tüm parçalar emildiyse, parçalar arasında döngü yapmaktan daha hızlı çalışır. Aksi takdirde döngüyle benzer şekilde çalışır. |
| remove_all_text(page) | Belirtilen sayfadan tüm metni kaldırır. |
| remove_all_text(page, rect) | Belirtilen sayfada, belirtilen dikdörtgen içindeki metni kaldırır. |
| remove_all_text(document) | Belgeden tüm metni kaldırır. |
| reset() | Bu [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) nesnesinin TextFragments koleksiyonunu temizler. |

### Ayrıca Bakınız

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

