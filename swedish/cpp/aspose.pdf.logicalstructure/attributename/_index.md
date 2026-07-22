---
title: "Aspose::Pdf::LogicalStructure::AttributeName klass"
linktitle: "AttributeName"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LogicalStructure::AttributeName klass. Representerar klassen för attributnamnsvärden i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class


Representerar klass för attributnamnsvärden.

```cpp
class AttributeName : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [FromNameAttributeKey](./fromnameattributekey/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::LogicalStructure::AttributeKey\>\&) | Hämtar attributnamn för attributnyckel. |
| [get_AttributeKey](./get_attributekey/)() const | Hämtar attributnyckel. |
| [get_Name](./get_name/)() const | Hämtar namnvärde för attribut. |
| [ToString](./tostring/)() const override | Returnerar en sträng som representerar det aktuella objektet. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [BlockAlign_After](./blockalign_after/) | Attribute BlockAlign: After - Efterkant av det sista barnets allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| static [BlockAlign_Before](./blockalign_before/) | Attribute BlockAlign: Before - Förekant av det första barnets allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| static [BlockAlign_Justify](./blockalign_justify/) | Attribute BlockAlign: Justify - Barnen är justerade med både före- och efterkanten av tabellcellens innehållsrektangel. Det första barnet placeras enligt beskrivningen för Before och det sista barnet enligt beskrivningen för After, med lika avstånd mellan barnen. Om det bara finns ett barn, ska det endast justeras med före kanten, som för Before. |
| static [BlockAlign_Middle](./blockalign_middle/) | Attribute BlockAlign: Middle- Barnen är centrerade i tabellcellen. Avståndet mellan före kanten av det första barnets allokeringsrektangel och den för tabellcellens innehållsrektangel ska vara samma som avståndet mellan efter kanten av det sista barnets allokeringsrektangel och den för tabellcellens innehållsrektangel. |
| static [BorderStyle_Dashed](./borderstyle_dashed/) | Attribute BorderStyle: Dashed - Kantlinjen är en serie korta linjesegment. |
| static [BorderStyle_Dotted](./borderstyle_dotted/) | Attribute BorderStyle: Dotted - Kantlinjen är en serie punkter. |
| static [BorderStyle_Double](./borderstyle_double/) | Attribute BorderStyle: Double - Kantlinjen består av två solida linjer. Summan av de två linjerna och avståndet mellan dem är lika med värdet för BorderThickness. |
| static [BorderStyle_Groove](./borderstyle_groove/) | Attribute BorderStyle: Groove - Kantlinjen ser ut som om den var inristad i duken. |
| static [BorderStyle_Hidden](./borderstyle_hidden/) | Attribute BorderStyle: Hidden - Samma som None, förutom när det gäller kantkonfliktlösning för tabell-element. |
| static [BorderStyle_Inset](./borderstyle_inset/) | Attribute BorderStyle: Inset - Kantlinjen får hela rutan att se ut som om den var inbäddad i duken. |
| static [BorderStyle_None](./borderstyle_none/) | Attribute BorderStyle: None - Ingen kant. Tvingar det beräknade värdet av BorderThicknessto att vara 0. |
| static [BorderStyle_Outset](./borderstyle_outset/) | Attribute BorderStyle: Outset - Kantlinjen får hela rutan att se ut som om den kom ut ur duken (motsatsen till Inset). |
| static [BorderStyle_Ridge](./borderstyle_ridge/) | Attribute BorderStyle: Ridge - Kantlinjen ser ut som om den kom ut ur duken (motsatsen till Groove). |
| static [BorderStyle_Solid](./borderstyle_solid/) | Attribute BorderStyle: Solid - Kantlinjen är ett enda linjesegment. |
| static [Checked_neutral](./checked_neutral/) | Attribute checked: Neutral - Tillståndet för en radioknapp eller kryssrutan. |
| static [Checked_off](./checked_off/) | Attribute checked: Off - Tillståndet för en radioknapp eller kryssrutan. |
| static [Checked_on](./checked_on/) | Attribute checked: On - Tillståndet för en radioknapp eller kryssrutan. |
| static [GlyphOrientationVertical_Auto](./glyphorientationvertical_auto/) | Attribute GlyphOrientationVertical: Auto - Anger en standardorientering för text, beroende på om den är fullbredd (lika bred som hög). |
| static [Height_Auto](./height_auto/) | Attribute Height: Auto - Elementets höjd ska bestämmas av det inneboende höjdet på dess innehåll. |
| static [InlineAlign_Center](./inlinealign_center/) | Attribute InlineAlign: [Center](../../aspose.pdf/center/) - Varje barn centrerat inom tabellcellen. Avståndet mellan startkanterna på barnets allokeringsrektangel och tabellcellens innehållsrektangel ska vara samma som avståndet mellan deras slutkanter. |
| static [InlineAlign_End](./inlinealign_end/) | Attribute InlineAlign: End - Slutkanten på varje barns allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| static [InlineAlign_Start](./inlinealign_start/) | Attribute InlineAlign: Start - Startkanten på varje barns allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| static [LineHeight_Auto](./lineheight_auto/) | Attribute LineHeight: Auto - Ingen justering av värdet för BaselineShift ska göras. |
| static [LineHeight_Normal](./lineheight_normal/) | Attribute LineHeight: Normal - Justera radhöjden för att inkludera eventuellt icke‑nollvärde som anges för BaselineShift. |
| static [ListNumbering_Circle](./listnumbering_circle/) | Attribute ListNumbering: Circle - Öppen cirkulär punkt. |
| static [ListNumbering_Decimal](./listnumbering_decimal/) | Attribute ListNumbering: Decimal - Decimala arabiska siffror (1-9, 10-99, …). |
| static [ListNumbering_Disc](./listnumbering_disc/) | Attribute ListNumbering: Disc - Solid cirkulär punkt. |
| static [ListNumbering_LowerAlpha](./listnumbering_loweralpha/) | Attribute ListNumbering: LowerAlpha - Gemena bokstäver (a, b, c, …). |
| static [ListNumbering_LowerRoman](./listnumbering_lowerroman/) | Attribute ListNumbering: LowerRoman - Gemena romerska siffror (i, ii, iii, iv, …). |
| static [ListNumbering_None](./listnumbering_none/) | Attribute ListNumbering: None - Ingen automatisk numrering; Lbl-element (om de finns) innehåller godtycklig text som inte är föremål för något numreringsschema. |
| static [ListNumbering_Square](./listnumbering_square/) | Attribute ListNumbering: Square - Solid fyrkantig punkt. |
| static [ListNumbering_UpperAlpha](./listnumbering_upperalpha/) | Attribute ListNumbering: UpperAlpha - Versala bokstäver (A, B, C, …). |
| static [ListNumbering_UpperRoman](./listnumbering_upperroman/) | Attribute ListNumbering: UpperRoman - Versala romerska siffror (I, II, III, IV, …). |
| static [Placement_Before](./placement_before/) | Attribute Placement: Before - Placerad så att elementets allokeringsrektangels förekant sammanfaller med den för det närmaste omgivande referensområdet. |
| static [Placement_Block](./placement_block/) | Attribute Placement: Block - Staplad i blockförloppsriktningen inom ett omgivande referensområde eller överordnad BLSE. |
| static [Placement_End](./placement_end/) | Attributplacering: Slut - Placeras så att elementets slutkant av allokeringsrektangeln sammanfaller med den närmaste omslutande referensytan. |
| static [Placement_Inline](./placement_inline/) | Attributplacering: Inline - Packas i inline‑progressionsriktningen inom ett omslutande BLSE. |
| static [Placement_Start](./placement_start/) | Attributplacering: Start - Placeras så att elementets startkant av allokeringsrektangeln sammanfaller med den närmaste omslutande referensytan. |
| static [Role_cb](./role_cb/) | Attributroll: cb - Kryssruta. |
| static [Role_pb](./role_pb/) | Attributroll: pb - Tryckknapp. |
| static [Role_rb](./role_rb/) | Attributroll: rb - Radioknapp. |
| static [Role_tv](./role_tv/) | Attributroll: tv - Textvärdefält. |
| static [RubyAlign_Center](./rubyalign_center/) | Attribut RubyAlign: [Center](../../aspose.pdf/center/) - Innehållet ska centreras i inline‑progressionsriktningen. |
| static [RubyAlign_Distribute](./rubyalign_distribute/) | Attribut RubyAlign: Distribute - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline‑progressionsriktningen. Dock ska också utrymme infogas vid textens startkant och slutkant. Avståndet ska fördelas med förhållandet 1:2:1 (start:infogning:slut). Det ska ändras till 0:1:1-förhållande om ruby visas i början av en textrad eller till 1:1:0-förhållande om ruby visas i slutet av textraden. |
| static [RubyAlign_End](./rubyalign_end/) | Attribut RubyAlign: End - Innehållet ska justeras mot slutkanten i inline‑progressionsriktningen. |
| static [RubyAlign_Justify](./rubyalign_justify/) | Attribut RubyAlign: Justify - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline‑progressionsriktningen. |
| static [RubyAlign_Start](./rubyalign_start/) | Attribut RubyAlign: Start - Innehållet ska justeras mot startkanten i inline‑progressionsriktningen. |
| static [RubyPosition_After](./rubyposition_after/) | Attribut RubyPosition: After - RT‑innehållet ska justeras längs elementets efterkant. |
| static [RubyPosition_Before](./rubyposition_before/) | Attribut RubyPosition: Before - RT‑innehållet ska justeras längs elementets förekant. |
| static [RubyPosition_Inline](./rubyposition_inline/) | Attribut RubyPosition: Inline - RT‑ och tillhörande RP‑element ska formateras som en parenteskommentar, efter RB‑elementet. |
| static [RubyPosition_Warichu](./rubyposition_warichu/) | Attribut RubyPosition: Warichu - RT‑ och tillhörande RP‑element ska formateras som en warichu, efter RB‑elementet. |
| static [Scope_Both](./scope_both/) | Attributomfång: Båda. |
| static [Scope_Column](./scope_column/) | Attributomfång: Kolumn. |
| static [Scope_Row](./scope_row/) | Attributomfång: [Row](../../aspose.pdf/row/). |
| static [TextAlign_Center](./textalign_center/) | Attribut TextAlign: [Center](../../aspose.pdf/center/) - Centrerad mellan start- och slutkanten. |
| static [TextAlign_End](./textalign_end/) | Attribut TextAlign: End - Justerad mot slutkanten. |
| static [TextAlign_Justify](./textalign_justify/) | Attribut TextAlign: Justify - Justerad mot både start- och slutkanten, med internt avstånd inom varje rad expanderat, om nödvändigt, för att uppnå sådan justering. Den sista (eller enda) raden ska bara justeras mot startkanten. |
| static [TextAlign_Start](./textalign_start/) | Attribut TextAlign: Start - Justerad mot startkanten. |
| static [TextDecorationType_LineThrough](./textdecorationtype_linethrough/) | Attribut TextDecorationType: LineThrough - En linje genom mitten av texten. |
| static [TextDecorationType_None](./textdecorationtype_none/) | Attribut TextDecorationType: None - Ingen textdekoration. |
| static [TextDecorationType_Overline](./textdecorationtype_overline/) | Attribut TextDecorationType: Overline - En linje ovanför texten. |
| static [TextDecorationType_Underline](./textdecorationtype_underline/) | Attribut TextDecorationType: Underline - En linje under texten. |
| static [Width_Auto](./width_auto/) | Attribut Width: Auto - elementets bredd ska bestämmas av den inneboende bredden på dess innehåll. |
| static [WritingMode_LrTb](./writingmode_lrtb/) | Attribut WritingMode: LrTb - Inline-förlopp från vänster till höger; blockförlopp från topp till botten. Detta är det typiska skrivläget för västerländska skriftsystem. |
| static [WritingMode_RlTb](./writingmode_rltb/) | Attribut WritingMode: RlTb - Inline-förlopp från höger till vänster; blockförlopp från topp till botten. Detta är det typiska skrivläget för arabiska och hebreiska skriftsystem. |
| static [WritingMode_TbRl](./writingmode_tbrl/) | Attribut WritingMode: TbRl - Inline-förlopp från topp till botten; blockförlopp från höger till vänster. Detta är det typiska skrivläget för kinesiska och japanska skriftsystem. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
