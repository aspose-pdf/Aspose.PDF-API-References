---
title: "AttributeName"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar klass för attributnamnsvärden."
type: docs
weight: 50
url: /sv/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

Representerar klass för attributnamnsvärden.

Typen AttributeName exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| name | Hämtar namnvärdet för attributet. |
| attribute_key | Hämtar attributnyckel. |
| PLACEMENT_BLOCK | Attributplacering: Block - Staplad i block‑förloppsriktningen inom ett omslutande referensområde eller föräldra‑BLSE. |
| PLACEMENT_INLINE | Attributplacering: Inline - Packad i inline‑förloppsriktningen inom ett omslutande BLSE. |
| PLACEMENT_BEFORE | Attributplacering: Before - Placerad så att elementets förekant på allokeringsrektangeln sammanfaller med den för det närmaste omslutande referensområdet. |
| PLACEMENT_START | Attributplacering: Start - Placerad så att startkanten på elementets allokeringsrektangel sammanfaller med den för det närmaste omslutande referensområdet. |
| PLACEMENT_END | Attributplacering: End - Placerad så att slutkanten på elementets allokeringsrektangel sammanfaller med den för det närmaste omslutande referensområdet. |
| WRITING_MODE_LR_TB | Attribut WritingMode: LrTb - Inlinjeförlopp från vänster till höger; blockförlopp från topp till botten. Detta är det typiska skrivläget för västerländska skriftsystem. |
| WRITING_MODE_RL_TB | Attribut WritingMode: RlTb - Inlinjeförlopp från höger till vänster; blockförlopp från topp till botten. Detta är det typiska skrivläget för arabiska och hebreiska skriftsystem. |
| WRITING_MODE_TB_RL | Attribut WritingMode: TbRl - Inlinjeförlopp från topp till botten; blockförlopp från höger till vänster. Detta är det typiska skrivläget för kinesiska och japanska skriftsystem. |
| BORDER_STYLE_NONE | Attribut BorderStyle: None - Ingen kant. Tvingar det beräknade värdet av BorderThicknessto att vara 0. |
| BORDER_STYLE_HIDDEN | Attribut BorderStyle: Hidden - Samma som None, förutom när det gäller kantkonfliktlösning för tabell-element. |
| BORDER_STYLE_DOTTED | Attribut BorderStyle: Dotted - Kanten är en serie av prickar. |
| BORDER_STYLE_DASHED | Attribut BorderStyle: Dashed - Kanten är en serie av korta linjesegment. |
| BORDER_STYLE_SOLID | Attribut BorderStyle: Solid - Kanten är ett enda linjesegment. |
| BORDER_STYLE_DOUBLE | Attribut BorderStyle: Double - Kanten är två solida linjer. Summan av de två linjerna och utrymmet mellan dem är lika med värdet av BorderThickness. |
| BORDER_STYLE_GROOVE | Attribut BorderStyle: Groove - Kanten ser ut som om den var inristad i duken. |
| BORDER_STYLE_RIDGE | Attribut BorderStyle: Ridge - Kanten ser ut som om den kom upp ur duken (motsatsen till Groove). |
| BORDER_STYLE_INSET | Attribut BorderStyle: Inset - Kanten får hela rutan att se ut som om den var inbäddad i duken. |
| BORDER_STYLE_OUTSET | Attribut BorderStyle: Outset - Kanten får hela rutan att se ut som om den kom upp ur duken (motsatsen till Inset). |
| TEXT_ALIGN_START | Attribut TextAlign: Start - Justerad med startkanten. |
| TEXT_ALIGN_CENTER | Attribut TextAlign: Center - Centrerad mellan start- och slutkanterna. |
| TEXT_ALIGN_END | Attribut TextAlign: End - Justerad mot slutkanten. |
| TEXT_ALIGN_JUSTIFY | Attribut TextAlign: Justify - Justerad mot både start- och slutkanterna, med internt avstånd inom varje rad utökat, om nödvändigt, för att uppnå sådan justering. Den sista (eller enda) raden ska bara justeras mot startkanten. |
| WIDTH_AUTO | Attribut Width: Auto - elementets bredd ska bestämmas av innehållets inneboende bredd. |
| HEIGHT_AUTO | Attribut Height: Auto - elementets höjd ska bestämmas av innehållets inneboende höjd. |
| BLOCK_ALIGN_BEFORE | Attribut BlockAlign: Before - Före-kanten på det första barnets allokeringsrektangel är inriktad med den för tabellcellens innehållsrektangel. |
| BLOCK_ALIGN_MIDDLE | Attribut BlockAlign: Middle- Barn centrerade inom tabellcellen. Avståndet mellan före-kanten på det första barnets allokeringsrektangel och den för tabellcellens innehållsrektangel ska vara samma som avståndet mellan efter-kanten på det sista barnets allokeringsrektangel och den för tabellcellens innehållsrektangel. |
| BLOCK_ALIGN_AFTER | Attribut BlockAlign: After - Efter-kanten på det sista barnets allokeringsrektangel är inriktad med den för tabellcellens innehållsrektangel. |
| BLOCK_ALIGN_JUSTIFY | Attribut BlockAlign: Justify - Barnen är inriktade mot både före- och efter-kanten på tabellcellens innehållsrektangel. Det första barnet placeras enligt beskrivningen för Before och det sista barnet enligt beskrivningen för After, med lika stort avstånd mellan barnen. Om det bara finns ett barn, ska det bara justeras mot före-kanten, enligt Before. |
| INLINE_ALIGN_START | Attribut InlineAlign: Start - Startkanten på varje barns allokeringsrektangel är inriktad med den för tabellcellens innehållsrektangel. |
| INLINE_ALIGN_CENTER | Attribut InlineAlign: Center - Varje barn centrerat inom tabellcellen. Avståndet mellan startkanterna på barnets allokeringsrektangel och tabellcellens innehållsrektangel ska vara samma som avståndet mellan deras slutkanter. |
| INLINE_ALIGN_END | Attribut InlineAlign: End - Slutkanten på varje barns allokeringsrektangel är inriktad med den för tabellcellens innehållsrektangel. |
| LINE_HEIGHT_NORMAL | Attribut LineHeight: Normal - Justera radhöjden för att inkludera eventuellt icke‑nollvärde som anges för BaselineShift. |
| LINE_HEIGHT_AUTO | Attribut LineHeight: Auto - Justering för värdet av BaselineShift får inte göras. |
| TEXT_DECORATION_TYPE_NONE | Attribut TextDecorationType: None - Ingen textdekoration. |
| TEXT_DECORATION_TYPE_UNDERLINE | Attribut TextDecorationType: Underline - En linje under texten. |
| TEXT_DECORATION_TYPE_OVERLINE | Attribut TextDecorationType: Overline - En linje ovanför texten. |
| TEXT_DECORATION_TYPE_LINE_THROUGH | Attribut TextDecorationType: LineThrough - En linje genom mitten av texten. |
| RUBY_ALIGN_START | Attribut RubyAlign: Start - Innehållet ska justeras på startkanten i inline‑progressionsriktningen. |
| RUBY_ALIGN_CENTER | Attribut RubyAlign: Center - Innehållet ska centreras i inline‑progressionsriktningen. |
| RUBY_ALIGN_END | Attribut RubyAlign: End - Innehållet ska justeras på slutkanten i inline‑progressionsriktningen. |
| RUBY_ALIGN_JUSTIFY | Attribut RubyAlign: Justify - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline‑progressionsriktningen. |
| RUBY_ALIGN_DISTRIBUTE | Attribut RubyAlign: Distribute - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline‑progressionsriktningen. Dock ska också utrymme infogas vid startkanten och slutkanten av texten. Avståndet ska fördelas med ett förhållande på 1:2:1 (start:infix:slut). Det ska ändras till ett förhållande 0:1:1 om ruby visas i början av en textrad eller till 1:1:0 om ruby visas i slutet av en textrad. |
| RUBY_POSITION_BEFORE | Attribut RubyPosition: Before - RT‑innehållet ska justeras längs elementets before‑kant. |
| RUBY_POSITION_AFTER | Attribut RubyPosition: After - RT‑innehållet ska justeras längs elementets after‑kant. |
| RUBY_POSITION_WARICHU | Attribute RubyPosition: Warichu - RT- och associerade RP-element ska formateras som en warichu, efter RB-elementet. |
| RUBY_POSITION_INLINE | Attribute RubyPosition: Inline - RT- och associerade RP-element ska formateras som en parenteskommentar, efter RB-elementet. |
| GLYPH_ORIENTATION_VERTICAL_AUTO | Attribute GlyphOrientationVertical: Auto - Anger en standardorientering för text, beroende på om den är fullbredd (lika bred som hög). |
| LIST_NUMBERING_NONE | Attribute ListNumbering: None - Ingen automatisk numrering; Lbl-element (om de finns) innehåller godtycklig text som inte omfattas av något numreringsschema. |
| LIST_NUMBERING_DISC | Attribute ListNumbering: Disc - Solid cirkulär punkt. |
| LIST_NUMBERING_CIRCLE | Attribute ListNumbering: Circle - Öppen cirkulär punkt. |
| LIST_NUMBERING_SQUARE | Attribute ListNumbering: Square - Solid fyrkantig punkt. |
| LIST_NUMBERING_DECIMAL | Attribute ListNumbering: Decimal - Decimala arabiska siffror (1-9, 10-99, ...). |
| LIST_NUMBERING_UPPER_ROMAN | Attribute ListNumbering: UpperRoman - Stora romerska siffror (I, II, III, IV, ...). |
| LIST_NUMBERING_LOWER_ROMAN | Attribute ListNumbering: LowerRoman - Små romerska siffror (i, ii, iii, iv, ...). |
| LIST_NUMBERING_UPPER_ALPHA | Attribute ListNumbering: UpperAlpha - Stora bokstäver (A, B, C, ...). |
| LIST_NUMBERING_LOWER_ALPHA | Attribute ListNumbering: LowerAlpha - Små bokstäver (a, b, c, ...). |
| ROLE_RB | Attribute Role: rb - Radioknapp. |
| ROLE_CB | Attributroll: cb - kryssruta. |
| ROLE_PB | Attributroll: pb - tryckknapp. |
| ROLE_TV | Attributroll: tv - textvärdefält. |
| CHECKED_ON | Attribut markerad: På - Tillståndet för en radioknapp eller kryssruta. |
| CHECKED_OFF | Attribut markerad: Av - Tillståndet för en radioknapp eller kryssruta. |
| CHECKED_NEUTRAL | Attribut markerad: Neutral - Tillståndet för en radioknapp eller kryssruta. |
| SCOPE_ROW | Attributomfång: Rad. |
| SCOPE_COLUMN | Attributomfång: Kolumn. |
| SCOPE_BOTH | Attributomfång: Båda. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | Hämtar attributnamn för attributnyckel. |

### Se även

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

