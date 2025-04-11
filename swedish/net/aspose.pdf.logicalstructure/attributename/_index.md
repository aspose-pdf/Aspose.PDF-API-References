---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.AttributeName klass. Representerar klass för Attributnamn Värden
type: docs
weight: 6220
url: /sv/net/aspose.pdf.logicalstructure/attributename/
---
## Attributnamn klass

Representerar klass för Attributnamn Värden.

```csharp
public sealed class AttributeName
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Attributnyckel](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | Hämtar attributnyckel. |
| [Namn](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | Hämtar namnvärdet för attributet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FrånNamnAttributnyckel](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, Attributnyckel) | Hämtar attributnamn för attributnyckel. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [BlockAlign_Efter](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Attribut BlockAlign: Efter - Efter kanten av den sista barnets allokeringsrektangel justerad med den av tabellcellens innehållsrektangel. |
| static readonly [BlockAlign_Före](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Attribut BlockAlign: Före - Före kanten av den första barnets allokeringsrektangel justerad med den av tabellcellens innehållsrektangel. |
| static readonly [BlockAlign_Rättfärdig](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Attribut BlockAlign: Rättfärdig - Barn justerade med både före och efter kanterna av tabellcellens innehållsrektangel. Det första barnet ska placeras som beskrivs för Före och det sista barnet som beskrivs för Efter, med lika avstånd mellan barnen. Om det bara finns ett barn, ska det justeras med före kanten endast, som för Före. |
| static readonly [BlockAlign_Mitt](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Attribut BlockAlign: Mitt - Barn centrerade inom tabellcellen. Avståndet mellan före kanten av den första barnets allokeringsrektangel och den av tabellcellens innehållsrektangel ska vara detsamma som avståndet mellan efter kanten av den sista barnets allokeringsrektangel och den av tabellcellens innehållsrektangel. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Attribut BorderStyle: Dotted - Gränsen är en serie korta linjesegment. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Attribut BorderStyle: Dotted - Gränsen är en serie prickar. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Attribut BorderStyle: Dubbel - Gränsen är två solida linjer. Summan av de två linjerna och utrymmet mellan dem är lika med värdet av BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Attribut BorderStyle: Groove - Gränsen ser ut som om den var inristad i duken. |
| static readonly [BorderStyle_Gömd](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Attribut BorderStyle: Gömd - Samma som Ingen, förutom när det gäller gränskonfliktlösning för tabellkomponenter. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Attribut BorderStyle: Inset - Gränsen får hela rutan att se ut som om den var inbäddad i duken. |
| static readonly [BorderStyle_Ingen](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Attribut BorderStyle: Ingen - Ingen gräns. Tvingar det beräknade värdet av BorderThickness att vara 0. |
| static readonly [BorderStyle_Utstickande](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Attribut BorderStyle: Utstickande - Gränsen får hela rutan att se ut som om den kom ut ur duken (motsatsen till Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Attribut BorderStyle: Ridge - Gränsen ser ut som om den kom ut ur duken (motsatsen till Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Attribut BorderStyle: Solid - Gränsen är ett enda linjesegment. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Attribut checked: Neutral - Tillståndet för en radioknapp eller kryssruta. |
| static readonly [Checked_avstängd](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Attribut checked: Avstängd - Tillståndet för en radioknapp eller kryssruta. |
| static readonly [Checked_på](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Attribut checked: På - Tillståndet för en radioknapp eller kryssruta. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Attribut GlyphOrientationVertical: Auto - Anger en standardorientering för text, beroende på om den är fullbredd (lika bred som den är hög). |
| static readonly [Höjd_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Attribut Höjd: Auto - Elementets höjd ska bestämmas av den inneboende höjden av dess innehåll. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Attribut InlineAlign: Center - Varje barn centrerat inom tabellcellen. Avståndet mellan startkanterna av barnets allokeringsrektangel och tabellcellens innehållsrektangel ska vara detsamma som avståndet mellan deras slutkanter. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Attribut InlineAlign: End - Slutkanten av varje barns allokeringsrektangel justerad med den av tabellcellens innehållsrektangel. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Attribut InlineAlign: Start - Startkanten av varje barns allokeringsrektangel justerad med den av tabellcellens innehållsrektangel. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Attribut LineHeight: Auto - Justering för värdet av BaselineShift ska inte göras. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Attribut LineHeight: Normal - Justera radens höjd för att inkludera något icke-nollvärde som anges för BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Attribut ListNumbering: Cirkel - Öppen cirkulär punkt. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Attribut ListNumbering: Decimal - Decimala arabiska siffror (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Attribut ListNumbering: Disc - Solid cirkulär punkt. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Attribut ListNumbering: LowerAlpha - Små bokstäver (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Attribut ListNumbering: LowerRoman - Små romerska siffror (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Attribut ListNumbering: Ingen - Ingen automatisk numrering; Lbl-element (om det finns) innehåller godtycklig text som inte omfattas av något numreringsschema. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Attribut ListNumbering: Fyrkant - Solid fyrkantig punkt. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Attribut ListNumbering: UpperAlpha - Versaler (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Attribut ListNumbering: UpperRoman - Versala romerska siffror (I, II, III, IV, ...). |
| static readonly [Placement_Före](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Attribut Placering: Före - Placerad så att före kanten av elementets allokeringsrektangel sammanfaller med den av det närmaste inneslutande referensområdet. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Attribut Placering: Block - Staplad i blockprogressionsriktningen inom ett inneslutande referensområde eller förälder BLSE. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Attribut Placering: Slut - Placerad så att slutkanten av elementets allokeringsrektangel sammanfaller med den av det närmaste inneslutande referensområdet. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Attribut Placering: Inline - Packad i inline-progressionsriktningen inom en inneslutande BLSE. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Attribut Placering: Start - Placerad så att startkanten av elementets allokeringsrektangel sammanfaller med den av det närmaste inneslutande referensområdet. |
| static readonly [Roll_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Attribut Roll: cb - Kryssruta. |
| static readonly [Roll_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Attribut Roll: pb - Tryckknapp. |
| static readonly [Roll_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Attribut Roll: rb - Radioknapp. |
| static readonly [Roll_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Attribut Roll: tv - Text-värde fält. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Attribut RubyAlign: Center - Innehållet ska centreras i inline-progressionsriktningen. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Attribut RubyAlign: Distribute - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline-progressionsriktningen. Utrymme ska också sättas in vid startkanten och slutkanten av texten. Avståndet ska fördelas med ett 1:2:1 (start:infix:slut) förhållande. Det ska ändras till ett 0:1:1 förhållande om rubyn visas i början av en textrad eller till ett 1:1:0 förhållande om rubyn visas i slutet av textraden. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Attribut RubyAlign: End - Innehållet ska justeras på slutkanten i inline-progressionsriktningen. |
| static readonly [RubyAlign_Rättfärdig](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Attribut RubyAlign: Rättfärdig - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline-progressionsriktningen. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Attribut RubyAlign: Start - Innehållet ska justeras på startkanten i inline-progressionsriktningen. |
| static readonly [RubyPosition_Efter](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Attribut RubyPosition: Efter - RT-innehållet ska justeras längs efter kanten av elementet. |
| static readonly [RubyPosition_Före](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Attribut RubyPosition: Före - RT-innehållet ska justeras längs före kanten av elementet. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Attribut RubyPosition: Inline - RT och associerade RP-element ska formateras som en parenteskommentar, efter RB-elementet. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Attribut RubyPosition: Warichu - RT och associerade RP-element ska formateras som en warichu, efter RB-elementet. |
| static readonly [Scope_Båda](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Attribut Scope: Båda. |
| static readonly [Scope_Kolumn](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Attribut Scope: Kolumn. |
| static readonly [Scope_Rad](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Attribut Scope: Rad. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Attribut TextAlign: Center - Centrerad mellan start- och slutkanterna. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Attribut TextAlign: End - Justerad med slutkanten. |
| static readonly [TextAlign_Rättfärdig](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Attribut TextAlign: Rättfärdig - Justerad med både start- och slutkanterna, med internt avstånd inom varje rad utvidgat, om nödvändigt, för att uppnå sådan justering. Den sista (eller enda) raden ska justeras med startkanten endast. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Attribut TextAlign: Start - Justerad med startkanten. |
| static readonly [TextDecorationType_LinjeGenom](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Attribut TextDecorationType: LinjeGenom - En linje genom mitten av texten. |
| static readonly [TextDecorationType_Ingen](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Attribut TextDecorationType: Ingen - Ingen textdekoration. |
| static readonly [TextDecorationType_Överlinje](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Attribut TextDecorationType: Överlinje - En linje ovanför texten. |
| static readonly [TextDecorationType_Underlinje](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Attribut TextDecorationType: Underlinje - En linje under texten. |
| static readonly [Bredd_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Attribut Bredd: Auto - elementets bredd ska bestämmas av den inneboende bredden av dess innehåll. |
| static readonly [Skrivläge_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Attribut WritingMode: LrTb - Inline-progression från vänster till höger; blockprogression från topp till botten. Detta är det typiska skrivläget för västerländska skriftsystem. |
| static readonly [Skrivläge_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Attribut WritingMode: RlTb - Inline-progression från höger till vänster; blockprogression från topp till botten. Detta är det typiska skrivläget för arabiska och hebreiska skriftsystem. |
| static readonly [Skrivläge_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Attribut WritingMode: TbRl - Inline-progression från topp till botten; blockprogression från höger till vänster. Detta är det typiska skrivläget för kinesiska och japanska skriftsystem. |

### Se Även

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)