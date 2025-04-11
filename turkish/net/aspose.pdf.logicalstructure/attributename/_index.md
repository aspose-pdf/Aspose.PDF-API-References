---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.AttributeName sınıfı. Attribute Name Values için kullanılan sınıfı temsil eder.
type: docs
weight: 6220
url: /tr/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName sınıfı

Attribute Name Values için kullanılan sınıfı temsil eder.

```csharp
public sealed class AttributeName
```

## Özellikler

| Name | Description |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | Attribute key değerini alır. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | Özniteliğin name değerini alır. |

## Yöntemler

| Name | Description |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | Attribute key için attribute name değerini alır. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Şu anki nesneyi temsil eden bir string döndürür. |

## Alanlar

| Name | Description |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Attribute BlockAlign: After - Son çocuğun tahsis dikdörtgeninin bitiş kenarı, tablo hücresinin içerik dikdörtgeniyle hizalanır. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Attribute BlockAlign: Before - İlk çocuğun tahsis dikdörtgeninin başlangıç kenarı, tablo hücresinin içerik dikdörtgeniyle hizalanır. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Attribute BlockAlign: Justify - Çocuklar, tablo hücresinin içerik dikdörtgeninin başlangıç ve bitiş kenarlarıyla hizalanır. İlk çocuk, Before için tanımlandığı şekilde yerleştirilir; son çocuk, After için tanımlandığı şekilde yerleştirilir ve çocuklar arasında eşit boşluk bırakılır. Eğer yalnızca bir çocuk varsa, yalnızca başlangıç kenarıyla hizalanır. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Attribute BlockAlign: Middle - Çocuklar, tablo hücresi içinde ortalanır. İlk çocuğun tahsis dikdörtgeninin başlangıç kenarı ile tablo hücresinin içerik dikdörtgeninin başlangıç kenarı arasındaki mesafe, son çocuğun tahsis dikdörtgeninin bitiş kenarı ile tablo hücresinin içerik dikdörtgeninin bitiş kenarı arasındaki mesafeyle aynıdır. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Attribute BorderStyle: Dashed - Kenarlık, kısa çizgi segmentlerinden oluşur. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Attribute BorderStyle: Dotted - Kenarlık, nokta serisidir. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Attribute BorderStyle: Double - Kenarlık, iki dolu çizgiden oluşur. Bu iki çizgi ve aralarındaki boşluğun toplamı, BorderThickness değerine eşittir. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Attribute BorderStyle: Groove - Kenarlık, sanki tuvale oyulmuş gibi görünür. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Attribute BorderStyle: Hidden - Kenarlık stili, None ile aynı olup tablo öğeleri için kenarlık çakışması çözümlemesinde farklılık gösterir. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Attribute BorderStyle: Inset - Kenarlık, tüm kutunun sanki tuval içine gömülmüş gibi görünmesini sağlar. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Attribute BorderStyle: None - Kenarlık yoktur. BorderThickness hesaplanmış değerinin 0 olmasını zorunlu kılar. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Attribute BorderStyle: Outset - Kenarlık, tüm kutunun sanki tuvalden çıkıyormuş gibi görünmesini sağlar (Inset'in tersi). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Attribute BorderStyle: Ridge - Kenarlık, sanki tuvalden çıkıyormuş gibi görünür (Groove'un tersi). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Attribute BorderStyle: Solid - Kenarlık, tek bir çizgi segmentidir. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Attribute checked: Neutral - Bir radyo düğmesi veya onay kutusu alanının durumunu belirtir. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Attribute checked: Off - Bir radyo düğmesi veya onay kutusu alanının durumunu belirtir. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Attribute checked: On - Bir radyo düğmesi veya onay kutusu alanının durumunu belirtir. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Attribute GlyphOrientationVertical: Auto - Metin için, tam genişlikte (yükseği kadar geniş) olup olmadığına bağlı olarak varsayılan bir yön belirtir. |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Attribute Height: Auto - Öğenin yüksekliği, içeriğinin öz yüksekliği tarafından belirlenir. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Attribute InlineAlign: Center - Her çocuk, tablo hücresi içinde ortalanır. Çocuğun tahsis dikdörtgeninin başlangıç kenarı ile tablo hücresinin içerik dikdörtgeninin başlangıç kenarı arasındaki mesafe, bitiş kenarları arasındaki mesafeyle aynıdır. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Attribute InlineAlign: End - Her çocuğun tahsis dikdörtgeninin bitiş kenarı, tablo hücresinin içerik dikdörtgeniyle hizalanır. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Attribute InlineAlign: Start - Her çocuğun tahsis dikdörtgeninin başlangıç kenarı, tablo hücresinin içerik dikdörtgeniyle hizalanır. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Attribute LineHeight: Auto - BaselineShift değeri için herhangi bir ayarlama yapılmaz. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Attribute LineHeight: Normal - BaselineShift için belirtilen sıfır olmayan değeri içerecek şekilde satır yüksekliği ayarlanır. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Attribute ListNumbering: Circle - Açık dairesel madde işareti. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Attribute ListNumbering: Decimal - Ondalık Arap rakamları (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Attribute ListNumbering: Disc - Dolu dairesel madde işareti. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Attribute ListNumbering: LowerAlpha - Küçük harfler (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Attribute ListNumbering: LowerRoman - Küçük Roma rakamları (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Attribute ListNumbering: None - Otomatik numaralandırma yok; Lbl öğeleri (varsa) herhangi bir numaralandırma şemasına tabi olmayan rastgele metin içerir. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Attribute ListNumbering: Square - Dolu kare madde işareti. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Attribute ListNumbering: UpperAlpha - Büyük harfler (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Attribute ListNumbering: UpperRoman - Büyük Roma rakamları (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Attribute Placement: Before - Öğenin tahsis dikdörtgeninin başlangıç kenarı, en yakın çevreleyen referans alanının başlangıç kenarıyla çakışacak şekilde yerleştirilir. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Attribute Placement: Block - Bir çevreleyen referans alanı veya üst BLSE içinde, blok ilerleme yönünde yığılır. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Attribute Placement: End - Öğenin tahsis dikdörtgeninin bitiş kenarı, en yakın çevreleyen referans alanının bitiş kenarıyla çakışacak şekilde yerleştirilir. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Attribute Placement: Inline - Bir çevreleyen BLSE içinde, satır içi ilerleme yönünde sıkıştırılır. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Attribute Placement: Start - Öğenin tahsis dikdörtgeninin başlangıç kenarı, en yakın çevreleyen referans alanının başlangıç kenarıyla çakışacak şekilde yerleştirilir. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Attribute Role: cb - Onay kutusu. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Attribute Role: pb - Push button. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Attribute Role: rb - Radio button. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Attribute Role: tv - Text-value field. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Attribute RubyAlign: Center - İçerik, satır içi ilerleme yönünde ortalanır. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Attribute RubyAlign: Distribute - İçerik, satır içi ilerleme yönündeki mevcut genişliği dolduracak şekilde genişletilir. Ancak, metnin başlangıç ve bitiş kenarlarına da boşluk eklenir. Boşluk, 1:2:1 (başlangıç:orta:son) oranında dağıtılır. Eğer ruby bir metin satırının başlangıcıdaysa oran 0:1:1'e, sonundaysa 1:1:0'a dönüştürülür. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Attribute RubyAlign: End - İçerik, satır içi ilerleme yönündeki bitiş kenarıyla hizalanır. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Attribute RubyAlign: Justify - İçerik, satır içi ilerleme yönündeki mevcut genişliği dolduracak şekilde genişletilir. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Attribute RubyAlign: Start - İçerik, satır içi ilerleme yönündeki başlangıç kenarıyla hizalanır. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Attribute RubyPosition: After - RT içeriği, öğenin bitiş kenarı boyunca hizalanır. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Attribute RubyPosition: Before - RT içeriği, öğenin başlangıç kenarı boyunca hizalanır. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Attribute RubyPosition: Inline - RT ve ilişkili RP öğeleri, RB öğesini takip eden parantez içi yorum olarak biçimlendirilir. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Attribute RubyPosition: Warichu - RT ve ilişkili RP öğeleri, RB öğesini takip eden bir warichu olarak biçimlendirilir. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Attribute Scope: Both - Her ikisi. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Attribute Scope: Column - Sütun. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Attribute Scope: Row - Satır. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Attribute TextAlign: Center - Başlangıç ve bitiş kenarları arasında ortalanır. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Attribute TextAlign: End - Bitiş kenarıyla hizalanır. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Attribute TextAlign: Justify - Hem başlangıç hem de bitiş kenarlarıyla hizalanır; gerekirse, her satırdaki iç boşluk bu hizalamayı sağlamak için genişletilir. Son (veya tek) satır yalnızca başlangıç kenarıyla hizalanır. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Attribute TextAlign: Start - Başlangıç kenarıyla hizalanır. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Attribute TextDecorationType: LineThrough - Metnin ortasından çizgi çekilir. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Attribute TextDecorationType: None - Metin süslemesi yoktur. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Attribute TextDecorationType: Overline - Metnin üzerinde çizgi çekilir. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Attribute TextDecorationType: Underline - Metnin altında çizgi çekilir. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Attribute Width: Auto - Öğenin genişliği, içeriğinin öz genişliği tarafından belirlenir. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Attribute WritingMode: LrTb - Soldan sağa satır içi ilerleme; yukarıdan aşağıya blok ilerleme. Bu, Batı yazı sistemleri için tipik yazım modudur. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Attribute WritingMode: RlTb - Sağdan sola satır içi ilerleme; yukarıdan aşağıya blok ilerleme. Bu, Arap ve İbranice yazı sistemleri için tipiktir. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Attribute WritingMode: TbRl - Yukarıdan aşağıya satır içi ilerleme; sağdan sola blok ilerleme. Bu, Çince ve Japonca yazı sistemleri için tipiktir. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)