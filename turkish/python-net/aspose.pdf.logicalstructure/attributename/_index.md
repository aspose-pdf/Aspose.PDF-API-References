---
title: "AttributeName"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Öznitelik Adı Değerleri için sınıfı temsil eder."
type: docs
weight: 50
url: /tr/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

Öznitelik Adı Değerleri için sınıfı temsil eder.

AttributeName türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| name | Özelliğin ad değerini alır. |
| attribute_key | Özellik anahtarını alır. |
| PLACEMENT_BLOCK | Özellik Yerleşimi: Block - Kapsayan bir referans alanı veya üst BLSE içinde blok-ilerleme yönünde istiflenir. |
| PLACEMENT_INLINE | Özellik Yerleşimi: Inline - Kapsayan bir BLSE içinde satır-ilerleme yönünde paketlenir. |
| PLACEMENT_BEFORE | Özellik Yerleşimi: Before - Elemanın tahsis dikdörtgeninin önceki kenarı, en yakın kapsayan referans alanının kenarıyla örtüşecek şekilde yerleştirilir. |
| PLACEMENT_START | Özellik Yerleşimi: Start - Elemanın tahsis dikdörtgeninin başlangıç kenarı, en yakın kapsayan referans alanının kenarıyla örtüşecek şekilde yerleştirilir. |
| PLACEMENT_END | Özellik Yerleşimi: End - Elemanın tahsis dikdörtgeninin bitiş kenarı, en yakın kapsayan referans alanının kenarıyla örtüşecek şekilde yerleştirilir. |
| WRITING_MODE_LR_TB | Özellik YazmaModu: LrTb - Satır ilerlemesi soldan sağa; blok ilerlemesi üstten alta. Bu, Batı yazı sistemleri için tipik yazma modudur. |
| WRITING_MODE_RL_TB | Özellik YazmaModu: RlTb - Satır ilerlemesi sağdan sola; blok ilerlemesi üstten alta. Bu, Arapça ve İbranice yazı sistemleri için tipik yazma modudur. |
| WRITING_MODE_TB_RL | Özellik YazmaModu: TbRl - Satır ilerlemesi üstten alta; blok ilerlemesi sağdan sola. Bu, Çince ve Japonca yazı sistemleri için tipik yazma modudur. |
| BORDER_STYLE_NONE | Özellik KenarlıkStili: None - Kenarlık yok. BorderThicknessto'nun hesaplanan değerini 0 yapmaya zorlar. |
| BORDER_STYLE_HIDDEN | Özellik KenarlıkStili: Hidden - None ile aynı, ancak tablo öğeleri için kenarlık çakışma çözümlemesi açısından farklıdır. |
| BORDER_STYLE_DOTTED | Özellik KenarlıkStili: Dotted - Kenarlık bir dizi nokta şeklindedir. |
| BORDER_STYLE_DASHED | Özellik BorderStyle: Dashed - Kenar, kısa çizgi segmentlerinden oluşan bir seridir. |
| BORDER_STYLE_SOLID | Özellik BorderStyle: Solid - Kenar tek bir çizgi segmentidir. |
| BORDER_STYLE_DOUBLE | Özellik BorderStyle: Double - Kenar iki katı çizgiden oluşur. İki çizginin ve aralarındaki boşluğun toplamı BorderThickness değerine eşittir. |
| BORDER_STYLE_GROOVE | Özellik BorderStyle: Groove - Kenar, sanki tuvale oyulmuş gibi görünür. |
| BORDER_STYLE_RIDGE | Özellik BorderStyle: Ridge - Kenar, sanki tuvalden çıkıyormuş gibi görünür (Groove'un tersidir). |
| BORDER_STYLE_INSET | Özellik BorderStyle: Inset - Kenar, tüm kutuyu tuvalin içine gömülmüş gibi gösterir. |
| BORDER_STYLE_OUTSET | Özellik BorderStyle: Outset - Kenar, tüm kutuyu tuvalden çıkıyormuş gibi gösterir (Inset'in tersidir). |
| TEXT_ALIGN_START | Özellik TextAlign: Start - Başlangıç kenarıyla hizalanır. |
| TEXT_ALIGN_CENTER | Özellik TextAlign: Center - Başlangıç ve bitiş kenarları arasında ortalanır. |
| TEXT_ALIGN_END | Özellik TextAlign: End - Bitiş kenarıyla hizalanır. |
| TEXT_ALIGN_JUSTIFY | Özellik TextAlign: Justify - Hem başlangıç hem de bitiş kenarlarıyla hizalanır, gerekli olduğunda her satır içindeki boşluklar genişletilerek bu hizalama sağlanır. Son (veya tek) satır yalnızca başlangıç kenarıyla hizalanır. |
| WIDTH_AUTO | Özellik Width: Auto - öğenin genişliği içeriğinin özsel genişliği tarafından belirlenir. |
| HEIGHT_AUTO | Özellik Height: Auto - öğenin yüksekliği içeriğinin özsel yüksekliği tarafından belirlenir. |
| BLOCK_ALIGN_BEFORE | Özellik BlockAlign: Before - İlk çocuğun tahsis dikdörtgeninin ön kenarı, tablo hücresinin içerik dikdörtgeninin ön kenarıyla hizalanır. |
| BLOCK_ALIGN_MIDDLE | Özellik BlockAlign: Orta- Çocuklar tablo hücresinin içinde ortalanır. İlk çocuğun tahsis dikdörtgeninin önceki kenarı ile tablo hücresinin içerik dikdörtgeninin arasındaki mesafe, son çocuğun tahsis dikdörtgeninin sonraki kenarı ile tablo hücresinin içerik dikdörtgeninin arasındaki mesafe ile aynı olmalıdır. |
| BLOCK_ALIGN_AFTER | Özellik BlockAlign: Son - Son çocuğun tahsis dikdörtgeninin kenarı, tablo hücresinin içerik dikdörtgeninin kenarıyla hizalanır. |
| BLOCK_ALIGN_JUSTIFY | Özellik BlockAlign: İki yana hizala - Çocuklar, tablo hücresinin içerik dikdörtgeninin hem önceki hem de sonraki kenarlarıyla hizalanır. İlk çocuk, Ön için açıklandığı gibi yerleştirilecek ve son çocuk, Son için açıklandığı gibi yerleştirilecektir; çocuklar arasında eşit boşluk bulunur. Eğer yalnız bir çocuk varsa, sadece Ön kenara hizalanır, Ön gibi. |
| INLINE_ALIGN_START | Özellik InlineAlign: Başlangıç - Her çocuğun tahsis dikdörtgeninin başlangıç kenarı, tablo hücresinin içerik dikdörtgeninin kenarıyla hizalanır. |
| INLINE_ALIGN_CENTER | Özellik InlineAlign: Ortala - Her çocuk tablo hücresi içinde ortalanır. Çocuğun tahsis dikdörtgeninin başlangıç kenarı ile tablo hücresinin içerik dikdörtgeninin başlangıç kenarı arasındaki mesafe, bitiş kenarları arasındaki mesafe ile aynı olmalıdır. |
| INLINE_ALIGN_END | Özellik InlineAlign: Son - Her çocuğun tahsis dikdörtgeninin son kenarı, tablo hücresinin içerik dikdörtgeninin kenarıyla hizalanır. |
| LINE_HEIGHT_NORMAL | Özellik LineHeight: Normal - Satır yüksekliğini, BaselineShift için belirtilen sıfır olmayan değeri içerecek şekilde ayarlayın. |
| LINE_HEIGHT_AUTO | Özellik LineHeight: Otomatik - BaselineShift değerine herhangi bir ayarlama yapılmayacaktır. |
| TEXT_DECORATION_TYPE_NONE | Özellik TextDecorationType: Yok - Metin süslemesi yok. |
| TEXT_DECORATION_TYPE_UNDERLINE | Özellik TextDecorationType: Altı çizili - Metnin altında bir çizgi. |
| TEXT_DECORATION_TYPE_OVERLINE | Özellik TextDecorationType: Üstü çizgi - Metnin üstünde bir çizgi. |
| TEXT_DECORATION_TYPE_LINE_THROUGH | Özellik TextDecorationType: Üstü çizgili - Metnin ortasından geçen bir çizgi. |
| RUBY_ALIGN_START | Özellik RubyAlign: Başlangıç - İçerik, satır içi ilerleme yönünde başlangıç kenarında hizalanmalıdır. |
| RUBY_ALIGN_CENTER | Özellik RubyAlign: Orta - İçerik, satır içi ilerleme yönünde ortalanmalıdır. |
| RUBY_ALIGN_END | Özellik RubyAlign: Son - İçerik, satır içi ilerleme yönünde son kenarda hizalanmalıdır. |
| RUBY_ALIGN_JUSTIFY | Özellik RubyAlign: İki Kenara Yasla - İçerik, satır içi ilerleme yönünde mevcut genişliği dolduracak şekilde genişletilmelidir. |
| RUBY_ALIGN_DISTRIBUTE | Özellik RubyAlign: Dağıt - İçerik, satır içi ilerleme yönünde mevcut genişliği dolduracak şekilde genişletilmelidir. Ancak, metnin başlangıç ve bitiş kenarlarına da boşluk eklenmelidir. Boşluk, 1:2:1 (başlangıç:ara:bitiş) oranı kullanılarak dağıtılacaktır. Ruby, bir metin satırının başında görünürse oran 0:1:1 olarak, satırın sonunda görünürse 1:1:0 olarak değiştirilecektir. |
| RUBY_POSITION_BEFORE | Özellik RubyPosition: Önce - RT içeriği, öğenin önce kenarı boyunca hizalanmalıdır. |
| RUBY_POSITION_AFTER | Özellik RubyPosition: Sonra - RT içeriği, öğenin sonra kenarı boyunca hizalanmalıdır. |
| RUBY_POSITION_WARICHU | Özellik RubyPosition: Warichu - RT ve ilişkili RP öğeleri, RB öğesinin ardından bir warichu olarak biçimlendirilmelidir. |
| RUBY_POSITION_INLINE | Özellik RubyPosition: Satır İçi - RT ve ilişkili RP öğeleri, RB öğesinin ardından parantez içinde bir yorum olarak biçimlendirilmelidir. |
| GLYPH_ORIENTATION_VERTICAL_AUTO | Özellik GlyphOrientationVertical: Otomatik - Metnin tam genişlikte (genişliği yüksekliği kadar) olup olmamasına bağlı olarak varsayılan bir yön belirler. |
| LIST_NUMBERING_NONE | Özellik ListNumbering: Yok - Otomatik numaralandırma yok; Lbl öğeleri (varsa) herhangi bir numaralandırma şemasına tabi olmayan rastgele metin içerir. |
| LIST_NUMBERING_DISC | Özellik ListNumbering: Daire - Katı dairesel madde işareti. |
| LIST_NUMBERING_CIRCLE | Özellik ListNumbering: Çember - Açık dairesel madde işareti. |
| LIST_NUMBERING_SQUARE | Özellik ListNumbering: Square - Katı kare madde işareti. |
| LIST_NUMBERING_DECIMAL | Özellik ListNumbering: Decimal - Ondalık Arap rakamları (1-9, 10-99, ...). |
| LIST_NUMBERING_UPPER_ROMAN | Özellik ListNumbering: UpperRoman - Büyük harfli Roma rakamları (I, II, III, IV, ...). |
| LIST_NUMBERING_LOWER_ROMAN | Özellik ListNumbering: LowerRoman - Küçük harfli Roma rakamları (i, ii, iii, iv, ...). |
| LIST_NUMBERING_UPPER_ALPHA | Özellik ListNumbering: UpperAlpha - Büyük harfli harfler (A, B, C, ...). |
| LIST_NUMBERING_LOWER_ALPHA | Özellik ListNumbering: LowerAlpha - Küçük harfli harfler (a, b, c, ...). |
| ROLE_RB | Özellik Role: rb - Radyo düğmesi. |
| ROLE_CB | Özellik Role: cb - Onay kutusu. |
| ROLE_PB | Özellik Role: pb - İtme düğmesi. |
| ROLE_TV | Özellik Role: tv - Metin-değer alanı. |
| CHECKED_ON | Özellik checked: On - Bir radyo düğmesi veya onay kutusu alanının durumu. |
| CHECKED_OFF | Özellik checked: Off - Bir radyo düğmesi veya onay kutusu alanının durumu. |
| CHECKED_NEUTRAL | Özellik kontrol edildi: Nötr - Bir radyo düğmesi veya onay kutusu alanının durumu. |
| SCOPE_ROW | Özellik Kapsamı: Satır. |
| SCOPE_COLUMN | Özellik Kapsamı: Sütun. |
| SCOPE_BOTH | Özellik Kapsamı: Her ikisi. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | Özellik anahtarı için özellik adını alır. |

### Ayrıca Bakınız

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

