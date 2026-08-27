---
title: "Klass AttributeName"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.LogicalStructure.AttributeName-klass. Representerar klass för attributnamnsvärden"
type: docs
weight: 6360
url: /sv/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Representerar klass för attributnamnsvärden.

```csharp
public sealed class AttributeName
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | Hämtar attributnyckel. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | Hämtar namnvärde för attribut. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | Hämtar attributnamn för attributnyckel. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Attribute BlockAlign: After - Efterkant av det sista barnets allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Attribute BlockAlign: Before - Före kant av det första barnets allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Attribut BlockAlign: Justify - Barnen är justerade med både den före- och efterkanten av tabellcellens innehållsrektangel. Det första barnet placeras enligt beskrivningen för Before och det sista barnet enligt beskrivningen för After, med lika avstånd mellan barnen. Om det bara finns ett barn, ska det bara justeras med den före kanten, som för Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Attribut BlockAlign: Middle- Barnen centreras inom tabellcellen. Avståndet mellan den föregående kanten av det första barnets allokeringsrektangel och den för tabellcellens innehållsrektangel ska vara detsamma som avståndet mellan den efterföljande kanten av det sista barnets allokeringsrektangel och den för tabellcellens innehållsrektangel. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Attribut BorderStyle: Dashed - Kantlinjen är en serie av korta linjesegment. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Attribut BorderStyle: Dotted - Kantlinjen är en serie av prickar. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Attribut BorderStyle: Double - Kantlinjen består av två solida linjer. Summan av de två linjerna och avståndet mellan dem är lika med värdet för BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Attribut BorderStyle: Groove - Kantlinjen ser ut som om den var inristad i duken. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Attribut BorderStyle: Hidden - Samma som None, förutom när det gäller konfliktlösning för kanter i tabell-element. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Attribut BorderStyle: Inset - Kantlinjen får hela rutan att se ut som om den var inbäddad i duken. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Attribut BorderStyle: None - Ingen kant. Tvingar det beräknade värdet för BorderThickness att bli 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Attribut BorderStyle: Outset - Kantlinjen får hela rutan att se ut som om den kom ut ur duken (motsatsen till Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Attribut BorderStyle: Ridge - Kantlinjen ser ut som om den kom ut ur duken (motsatsen till Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Attribut BorderStyle: Solid - Kantlinjen är ett enda linjesegment. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Attribut checked: Neutral - Tillståndet för ett radioknapp- eller kryssrutfält. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Attribut checked: Off - Tillståndet för ett radioknapp- eller kryssrutfält. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Attribut checked: On - Tillståndet för ett radioknapp- eller kryssrutfält. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Attribut GlyphOrientationVertical: Auto - Anger en standardorientering för text, beroende på om den är fullbredd (lika bred som hög). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Attribut Height: Auto - Elementets höjd ska bestämmas av det inneboende innehållets höjd. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Attribut InlineAlign: Center - Varje barn centreras inom tabellcellen. Avståndet mellan startkanterna på barnets allokeringsrektangel och tabellcellens innehållsrektangel ska vara detsamma som avståndet mellan deras slutkanter. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Attribut InlineAlign: End - Slutkanten på varje barns allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Attribut InlineAlign: Start - Startkanten på varje barns allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Attribut LineHeight: Auto - Ingen justering av värdet för BaselineShift ska göras. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Attribut LineHeight: Normal - Justera radhöjden för att inkludera eventuellt icke‑nollvärde som angetts för BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Attribut ListNumbering: Circle - Öppen cirkulär punkt. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Attribut ListNumbering: Decimal - Decimala arabiska siffror (1‑9, 10‑99, …). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Attribut ListNumbering: Disc - Solid cirkulär punkt. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Attribut ListNumbering: LowerAlpha - Gemena bokstäver (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Attribut ListNumbering: LowerRoman - Gemena romerska siffror (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Attribut ListNumbering: None - Ingen automatisk numrering; Lbl-element (om de finns) innehåller godtycklig text som inte omfattas av något numreringsschema. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Attribut ListNumbering: Square - Fylld fyrkantig punkt. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Attribut ListNumbering: UpperAlpha - Versala bokstäver (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Attribut ListNumbering: UpperRoman - Versala romerska siffror (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Attribut Placement: Before - Placeras så att elementets före-kant i allokeringsrektangeln sammanfaller med den närmaste omslutande referensytan. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Attribut Placement: Block - Staplas i blockförloppsriktningen inom ett omslutande referensområde eller överordnad BLSE. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Attribut Placement: End - Placeras så att elementets slutkant i allokeringsrektangeln sammanfaller med den närmaste omslutande referensytan. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Attribut Placement: Inline - Packas i inline-förloppsriktningen inom ett omslutande BLSE. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Attribut Placement: Start - Placeras så att elementets startkant i allokeringsrektangeln sammanfaller med den närmaste omslutande referensytan. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Attribut Role: cb - Kryssruta. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Attribut Role: pb - Tryckknapp. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Attribut Role: rb - Radioknapp. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Attribut Role: tv - Textvärdefält. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Attribut RubyAlign: Center - Innehållet ska centreras i inline-förloppsriktningen. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Attribut RubyAlign: Distribute - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline-förloppsriktningen. Dock ska utrymme också infogas vid textens startkant och slutkant. Avståndet ska fördelas med förhållandet 1:2:1 (start:infogning:slut). Det ska ändras till 0:1:1-förhållande om ruby visas i början av en textrad eller till 1:1:0-förhållande om ruby visas i slutet av textraden. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Attribut RubyAlign: End - Innehållet ska justeras mot slutkanten i inline-förloppsriktningen. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Attribut RubyAlign: Justify - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline-förloppsriktningen. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Attribut RubyAlign: Start - Innehållet ska justeras mot startkanten i inline-förloppsriktningen. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Attribut RubyPosition: After - RT-innehållet ska justeras längs elementets efterkant. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Attribut RubyPosition: Before - RT-innehållet ska justeras längs elementets före-kant. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Attribut RubyPosition: Inline - RT- och tillhörande RP-element ska formateras som en parenteskommentar, efter RB-elementet. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Attribut RubyPosition: Warichu - RT- och tillhörande RP-element ska formateras som en warichu, efter RB-elementet. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Attribut Scope: Båda. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Attributomfång: Kolumn. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Attributomfång: Rad. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Attribut TextAlign: Center - Centrerad mellan start- och slutkanterna. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Attribut TextAlign: End - Justerad mot slutkanten. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Attribut TextAlign: Justify - Justerad mot både start- och slutkanterna, med internt avstånd inom varje rad utökat, om nödvändigt, för att uppnå sådan justering. Den sista (eller enda) raden ska bara justeras mot startkanten. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Attribut TextAlign: Start - Justerad mot startkanten. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Attribut TextDecorationType: LineThrough - En linje genom mitten av texten. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Attribut TextDecorationType: None - Ingen textdekoration. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Attribut TextDecorationType: Overline - En linje ovanför texten. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Attribut TextDecorationType: Underline - En linje under texten. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Attribut Width: Auto - elementets bredd ska bestämmas av det inneboende bredden på dess innehåll. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Attribut WritingMode: LrTb - Inline-förlopp från vänster till höger; blockförlopp från topp till botten. Detta är det typiska skrivläget för västerländska skriftsystem. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Attribut WritingMode: RlTb - Inline-förlopp från höger till vänster; blockförlopp från topp till botten. Detta är det typiska skrivläget för arabiska och hebreiska skriftsystem. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Attribut WritingMode: TbRl - Inline-förlopp från topp till botten; blockförlopp från höger till vänster. Detta är det typiska skrivläget för kinesiska och japanska skriftsystem. |

### Se även

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


