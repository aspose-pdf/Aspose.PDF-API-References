---
title: AttributeName
second_title: Aspose.PDF för .NET API Referens
description: Representerar klass för attributnamnsvärden.
type: docs
weight: 4050
url: /sv/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Representerar klass för attributnamnsvärden.

```csharp
public sealed class AttributeName
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey) { get; } | Hämtar attributnyckel. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name) { get; } | Hämtar namnvärdet för attributet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey)(string, AttributeKey) | Hämtar attributnamn för attributnyckel. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after) | Attribut BlockAlign: After - Efter kanten av det sista barnets allokeringsrektangel justerat med tabellcellens innehållsrektangel. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before) | Attribut BlockAlign: Before - Before edge av det första barnets allokeringsrektangel justerat med tabellcellens innehållsrektangel. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify) | Attribute BlockAlign: Justify – Underordnade justerade med både före- och efterkanterna på tabellcellens innehållsrektangel. Det första barnet ska placeras enligt beskrivningen för Före och det sista barnet som beskrivs för Efter, med lika avstånd mellan barnen. Om det bara finns ett underordnat, ska det justeras med endast före kanten, som för Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle) | Attribut BlockAlign: Middle- Children centrerad i tabellcellen. Avståndet mellan framkanten av det första barnets allokeringsrektangel och tabellcellens innehållsrektangel ska vara detsamma som avståndet mellan efterkanten av det sista barnets allokeringsrektangel och tabellcellens innehållsrektangel. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed) | Attribut BorderStyle: Streckad – Ramen är en serie korta linjesegment. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted) | Attribut BorderStyle: Dotted - Ramen är en serie punkter. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double) | Attribut BorderStyle: Dubbel - Ramen är två heldragna linjer. Summan av de två linjerna och avståndet mellan dem är lika med värdet på BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove) | Attribut BorderStyle: Groove - Bården ser ut som om den var ristad in i duken. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden) | Attribut BorderStyle: Hidden - Samma som Ingen, förutom när det gäller gränskonfliktlösning för tabellelement. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset) | Attribut BorderStyle: Infälld - Ramen får hela rutan att se ut som om den var inbäddad i duken. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none) | Attribut BorderStyle: Ingen - Ingen kantlinje. Tvingar det beräknade värdet för BorderThickness att vara 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset) | Attribut BorderStyle: Outset - Ramen får hela rutan att se ut som om den skulle komma ut ur duken (motsatsen till Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge) | Attribute BorderStyle: Ridge - Bården ser ut som om den skulle komma ut ur duken (motsatsen till Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid) | Attribut BorderStyle: Solid - Ramen är ett enda linjesegment. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral) | Attribut markerat: Neutral - Statusen för en alternativknapp eller kryssruta. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off) | Attribut markerat: Av - Statusen för en alternativknapp eller kryssruta. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on) | Attribut markerat: På - Statusen för en alternativknapp eller kryssruta. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto) | Attribut GlyphOrientationVertical: Auto - Anger en standardorientering för text, beroende på om den är fullbredd (lika bred som hög). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto) | Attribut Height: Auto - Elementets höjd ska bestämmas av den inneboende höjden av dess innehåll. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center) | Attribut InlineAlign: Centrera - Varje underordnat centrerat i tabellcellen. Avståndet mellan startkanterna på barnets allokeringsrektangel och tabellcellens innehållsrektangel ska vara detsamma som avståndet mellan deras ändkanter. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end) | Attribut InlineAlign: End - Slutkanten på varje barns allokeringsrektangel justerad med den för tabellcellens innehållsrektangel. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start) | Attribut InlineAlign: Start - Startkanten av varje barns allokeringsrektangel i linje med den för tabellcellens innehållsrektangel. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto) | Attribut LineHeight: Auto - Justering för värdet på BaselineShift ska inte göras. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal) | Attribut LineHeight: Normal – Justera linjehöjden för att inkludera alla värden som inte är noll specificerade för BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle) | Attribut ListNumbering: Circle - Open circular bullet. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal) | Attribut ListNumbering: Decimal - Decimala arabiska siffror (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc) | Attribut ListNumbering: Disc - Solid cirkulär kula. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha) | Attribut ListNumbering: LowerAlpha - Små bokstäver (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman) | Attribut ListNumbering: LowerRoman - Gemener romerska siffror (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none) | Attribut ListNumbering: Ingen - Ingen autonumrering; Lbl-element (om sådana finns) innehåller godtycklig text som inte omfattas av något numreringsschema. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square) | Attribut ListNumbering: Square - Solid square bullet. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha) | Attribut ListNumbering: UpperAlpha - Versaler (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman) | Attribut ListNumbering: UpperRoman - Versaler romerska siffror (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before) | Attributplacering: Före - Placeras så att förekanten på elementets allokeringsrektangel sammanfaller med den för närmaste omslutande referensarea. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block) | Attributplacering: Block - staplat i blockets framstegsriktning inom ett omslutande referensområde eller överordnad BLSE. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end) | Attributplacering: Slut - Placeras så att ändkanten på elementets allokeringsrektangel sammanfaller med den på närmaste omslutande referensarea. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline) | Attributplacering: Inline - Packad i inline-progressionsriktningen inom en omslutande BLSE. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start) | Attributplacering: Start - Placeras så att startkanten på elementets allokeringsrektangel sammanfaller med den för närmaste omslutande referensarea. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb) | Attributroll: cb - Kryssruta. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb) | Attributroll: pb - Tryckknapp. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb) | Attributroll: rb - alternativknapp. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv) | Attributroll: tv - Text-värdefält. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center) | Attribut RubyAlign: Center - Innehållet ska centreras i inline-progressionsriktningen. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute) | Attribut RubyAlign: Distribute - Innehållet ska utökas för att fylla den tillgängliga bredden i inline-progressionsriktningen. Mellanslag ska dock även infogas vid textens startkant och slutkant. Avståndet ska fördelas med ett förhållande på 1:2:1 (start:infix:slut). Det ska ändras till förhållandet 0:1:1 om rubinen visas i början av en textrad eller till förhållandet 1:1:0 om rubinen visas i slutet av textraden. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end) | Attribut RubyAlign: End - Innehållet ska justeras på ändkanten i inline-progressionsriktningen. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify) | Attribut RubyAlign: Justify - Innehållet ska utökas för att fylla den tillgängliga bredden i inline-progressionsriktningen. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start) | Attribut RubyAlign: Start - Innehållet ska justeras på startkanten i inline-progressionsriktningen. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after) | Attribut RubyPosition: After - RT-innehållet ska justeras längs efterkanten av elementet. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before) | Attribut RubyPosition: Before - RT-innehållet ska justeras längs elementets förekant. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline) | Attribut RubyPosition: Inline - RT och tillhörande RP-element ska formateras som en parenteskommentar, efter RB-elementet. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu) | Attribut RubyPosition: Warichu - RT och tillhörande RP-element ska formateras som en warichu, efter RB-elementet. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both) | Attribut Omfattning: Båda. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column) | Attribut Omfattning: Kolumn. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row) | Attribut Omfattning: Rad. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center) | Attribut TextAlign: Center - Centrerad mellan start- och slutkanterna. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end) | Attribut TextAlign: End - Justerad med ändkanten. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify) | Attribute TextAlign: Justify - Justeras med både start- och slutkanterna, med interna avstånd inom varje rad utökat, om nödvändigt, för att uppnå sådan justering. Den sista (eller enda) raden ska endast riktas mot startkanten. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start) | Attribut TextAlign: Start - Justerad med startkanten. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough) | Attribut TextDecorationType: LineThrough - En linje genom mitten av texten. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none) | Attribut TextDecorationType: Ingen - Ingen textdekoration. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline) | Attribut TextDecorationType: Överlinje - En rad ovanför texten. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline) | Attribut TextDecorationType: Understrykning - En rad under texten. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto) | Attribut Width: Auto - elementets bredd ska bestämmas av den inneboende bredden av dess innehåll. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb) | Attribut WritingMode: LrTb - Inline progression från vänster till höger; blockera progression från topp till botten. Detta är det typiska skrivläget för västerländska skrivsystem. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb) | Attribut WritingMode: RlTb - Inline progression från höger till vänster; blockera progression från topp till botten. Detta är det typiska skrivläget för arabiska och hebreiska skriftsystem. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl) | Attribut WritingMode: TbRl - Inline progression från topp till botten; blockera progression från höger till vänster. Detta är det typiska skrivläget för kinesiska och japanska skrivsystem. |

### Se även

* namnutrymme [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
