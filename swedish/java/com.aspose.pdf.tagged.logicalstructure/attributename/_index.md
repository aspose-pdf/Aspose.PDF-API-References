---
title: "Attributnamn"
linktitle: "Attributnamn"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar klass för attributnamnsvärden."
type: docs
weight: 20
url: /sv/java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.AttributeName

```
public final class AttributeName extends Object
```

Representerar klass för attributnamnsvärden.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [BlockAlign_After](#BlockAlign_After) | Attribut BlockAlign: After - Efterkant av det sista barnets allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| [BlockAlign_Before](#BlockAlign_Before) | Attribut BlockAlign: Before - Förekant av det första barnets allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| [BlockAlign_Justify](#BlockAlign_Justify) | Attribut BlockAlign: Justify - Barnen är justerade med både före- och efterkanten av tabellcellens innehållsrektangel. Det första barnet placeras enligt beskrivningen för Before och det sista barnet enligt beskrivningen för After, med lika avstånd mellan barnen. Om det bara finns ett barn, ska det bara justeras med före-kanten, som för Before. |
| [BlockAlign_Middle](#BlockAlign_Middle) | Attribut BlockAlign: Middle- Barnen är centrerade inom tabellcellen. Avståndet mellan före-kanten av det första barnets allokeringsrektangel och den för tabellcellens innehållsrektangel ska vara samma som avståndet mellan efter-kanten av det sista barnets allokeringsrektangel och den för tabellcellens innehållsrektangel. |
| [BorderStyle_Dashed](#BorderStyle_Dashed) | Attribut BorderStyle: Dashed - Kantlinjen är en serie korta linjesegment. |
| [BorderStyle_Dotted](#BorderStyle_Dotted) | Attribut BorderStyle: Dotted - Kantlinjen är en serie punkter. |
| [BorderStyle_Double](#BorderStyle_Double) | Attribut BorderStyle: Double - Kantlinjen består av två solida linjer. Summan av de två linjerna och avståndet mellan dem är lika med värdet för BorderThickness. |
| [BorderStyle_Groove](#BorderStyle_Groove) | Attribut BorderStyle: Groove - Kantlinjen ser ut som om den var inristad i duken. |
| [BorderStyle_Hidden](#BorderStyle_Hidden) | Attribut BorderStyle: Hidden - Samma som None, förutom när det gäller kantkonfliktlösning för tabellelement. |
| [BorderStyle_Inset](#BorderStyle_Inset) | Attribut BorderStyle: Inset - Kantlinjen får hela rutan att se ut som om den var inbäddad i duken. |
| [BorderStyle_None](#BorderStyle_None) | Attribut BorderStyle: None - Ingen kant. Tvingar det beräknade värdet av BorderThickness att vara 0. |
| [BorderStyle_Outset](#BorderStyle_Outset) | Attribut BorderStyle: Outset - Kantlinjen får hela rutan att se ut som om den kom ut ur duken (motsatsen till Inset). |
| [BorderStyle_Ridge](#BorderStyle_Ridge) | Attribut BorderStyle: Ridge - Kantlinjen ser ut som om den kom ut ur duken (motsatsen till Groove). |
| [BorderStyle_Solid](#BorderStyle_Solid) | Attribut BorderStyle: Solid - Kantlinjen är ett enda linjesegment. |
| [Checked_neutral](#Checked_neutral) | Attribut checked: Neutral - Tillståndet för en radioknapp eller kryssrutfält. |
| [Checked_off](#Checked_off) | Attribut checked: Off - Tillståndet för en radioknapp eller kryssrutfält. |
| [Checked_on](#Checked_on) | Attribut checked: On - Tillståndet för en radioknapp eller kryssrutfält. |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical_Auto) | Attribut GlyphOrientationVertical: Auto - Anger en standardorientering för text, beroende på om den är fullbredd (lika bred som hög). |
| [Height_Auto](#Height_Auto) | Attribut Height: Auto - Elementets höjd ska bestämmas av det inneboende höjden på dess innehåll. |
| [InlineAlign_Center](#InlineAlign_Center) | Attribut InlineAlign: Center - Varje barn är centrerat inom tabellcellen. Avståndet mellan startkanten av barnets allokeringsrektangel och tabellcellens innehållsrektangel ska vara samma som avståndet mellan deras slutkanten. |
| [InlineAlign_End](#InlineAlign_End) | Attribut InlineAlign: End - Slutkanten av varje barns allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| [InlineAlign_Start](#InlineAlign_Start) | Attribut InlineAlign: Start - Startkanten av varje barns allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel. |
| [LineHeight_Auto](#LineHeight_Auto) | Attribut LineHeight: Auto - Justering för värdet av BaselineShift ska inte göras. |
| [LineHeight_Normal](#LineHeight_Normal) | Attribute LineHeight: Normal - Justera radavståndet så att det inkluderar alla icke‑nollvärden som anges för BaselineShift. |
| [ListNumbering_Circle](#ListNumbering_Circle) | Attribute ListNumbering: Circle - Öppna cirkulär punkt. |
| [ListNumbering_Decimal](#ListNumbering_Decimal) | Attribute ListNumbering: Decimal - Decimala arabiska siffror (1-9, 10-99, ...). |
| [ListNumbering_Disc](#ListNumbering_Disc) | Attribute ListNumbering: Disc - Solid cirkulär punkt. |
| [ListNumbering_LowerAlpha](#ListNumbering_LowerAlpha) | Attribute ListNumbering: LowerAlpha - Gemena bokstäver (a, b, c, ...). |
| [ListNumbering_LowerRoman](#ListNumbering_LowerRoman) | Attribute ListNumbering: LowerRoman - Gemena romerska siffror (i, ii, iii, iv, ...). |
| [ListNumbering_None](#ListNumbering_None) | Attribute ListNumbering: None - Ingen automatisk numrering; Lbl-element (om de finns) innehåller godtycklig text som inte är föremål för något numreringsschema. |
| [ListNumbering_Square](#ListNumbering_Square) | Attribute ListNumbering: Square - Solid fyrkantig punkt. |
| [ListNumbering_UpperAlpha](#ListNumbering_UpperAlpha) | Attribute ListNumbering: UpperAlpha - Stora bokstäver (A, B, C, ...). |
| [ListNumbering_UpperRoman](#ListNumbering_UpperRoman) | Attribute ListNumbering: UpperRoman - Stora romerska siffror (I, II, III, IV, ...). |
| [Placement_Before](#Placement_Before) | Attribute Placement: Before - Placerad så att den föregående kanten av elementets allokeringsrektangel sammanfaller med den för det närmaste omgivande referensområdet. |
| [Placement_Block](#Placement_Block) | Attribute Placement: Block - Staplad i blockförloppsriktningen inom ett omgivande referensområde eller överordnad BLSE. |
| [Placement_End](#Placement_End) | Attribute Placement: End - Placerad så att den avslutande kanten av elementets allokeringsrektangel sammanfaller med den för det närmaste omgivande referensområdet. |
| [Placement_Inline](#Placement_Inline) | Attribute Placement: Inline - Packad i inline‑förloppsriktningen inom ett omgivande BLSE. |
| [Placement_Start](#Placement_Start) | Attribute Placement: Start - Placerad så att startkanten av elementets allokeringsrektangel sammanfaller med den för det närmaste omgivande referensområdet. |
| [Role_cb](#Role_cb) | Attribute Role: cb - Kryssruta. |
| [Role_pb](#Role_pb) | Attribute Role: pb - Tryckknapp. |
| [Role_rb](#Role_rb) | Attribute Role: rb - Radioknapp. |
| [Role_tv](#Role_tv) | Attribute Role: tv - Text‑värdefält. |
| [RubyAlign_Center](#RubyAlign_Center) | Attribute RubyAlign: Center - Innehållet ska centreras i inline‑förloppsriktningen. |
| [RubyAlign_Distribute](#RubyAlign_Distribute) | Attribute RubyAlign: Distribute - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline‑förloppsriktningen. Dock ska utrymme även infogas vid startkanten och slutkanten av texten. Avståndet ska fördelas med ett förhållande 1:2:1 (start:infogning:slut). Det ska ändras till 0:1:1 om ruby visas i början av en textrad eller till 1:1:0 om ruby visas i slutet av textraden. |
| [RubyAlign_End](#RubyAlign_End) | Attribute RubyAlign: End - Innehållet ska justeras mot slutkanten i inline‑förloppsriktningen. |
| [RubyAlign_Justify](#RubyAlign_Justify) | Attribute RubyAlign: Justify - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline‑förloppsriktningen. |
| [RubyAlign_Start](#RubyAlign_Start) | Attribute RubyAlign: Start - Innehållet ska justeras mot startkanten i inline‑förloppsriktningen. |
| [RubyPosition_After](#RubyPosition_After) | Attribute RubyPosition: After - RT‑innehållet ska justeras längs efterkanten av elementet. |
| [RubyPosition_Before](#RubyPosition_Before) | Attribute RubyPosition: Before - RT-innehållet ska justeras längs elementets förkant. |
| [RubyPosition_Inline](#RubyPosition_Inline) | Attribute RubyPosition: Inline - RT- och associerade RP-element ska formateras som en parenteskommentar, efter RB-elementet. |
| [RubyPosition_Warichu](#RubyPosition_Warichu) | Attribute RubyPosition: Warichu - RT- och associerade RP-element ska formateras som en warichu, efter RB-elementet. |
| [Scope_Both](#Scope_Both) | Attribute Scope: Båda. |
| [Scope_Column](#Scope_Column) | Attribute Scope: Kolumn. |
| [Scope_Row](#Scope_Row) | Attribute Scope: Rad. |
| [TextAlign_Center](#TextAlign_Center) | Attribute TextAlign: Center - Centrerad mellan start- och slutkanten. |
| [TextAlign_End](#TextAlign_End) | Attribute TextAlign: End - Justerad mot slutkanten. |
| [TextAlign_Justify](#TextAlign_Justify) | Attribute TextAlign: Justify - Justerad mot både start- och slutkanten, med internt avstånd inom varje rad utökat vid behov för att uppnå sådan justering. Den sista (eller enda) raden ska bara justeras mot startkanten. |
| [TextAlign_Start](#TextAlign_Start) | Attribute TextAlign: Start - Justerad mot startkanten. |
| [TextDecorationType_LineThrough](#TextDecorationType_LineThrough) | Attribute TextDecorationType: LineThrough - En linje genom mitten av texten. |
| [TextDecorationType_None](#TextDecorationType_None) | Attribute TextDecorationType: None - Ingen textdekoration. |
| [TextDecorationType_Overline](#TextDecorationType_Overline) | Attribute TextDecorationType: Overline - En linje ovanför texten. |
| [TextDecorationType_Underline](#TextDecorationType_Underline) | Attribute TextDecorationType: Underline - En linje under texten. |
| [Width_Auto](#Width_Auto) | Attribute Width: Auto - elementets bredd ska bestämmas av innehållets inneboende bredd. |
| [WritingMode_LrTb](#WritingMode_LrTb) | Attribute WritingMode: LrTb - Inline-förlopp från vänster till höger; block-förlopp från topp till botten. Detta är det typiska skrivläget för västerländska skriftsystem. |
| [WritingMode_RlTb](#WritingMode_RlTb) | Attribute WritingMode: RlTb - Inline-förlopp från höger till vänster; block-förlopp från topp till botten. Detta är det typiska skrivläget för arabiska och hebreiska skriftsystem. |
| [WritingMode_TbRl](#WritingMode_TbRl) | Attribute WritingMode: TbRl - Inline-förlopp från topp till botten; block-förlopp från höger till vänster. Detta är det typiska skrivläget för kinesiska och japanska skriftsystem. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [fromNameAttributeKey](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Hämtar attributnamn för attributnyckel. |
| [getAttributeKey](#getAttributeKey--) | Hämtar attributnyckel. |
| [getName](#getName--) | Hämtar namnvärde för attribut. |
| [toString](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |

### BlockAlign_After {#BlockAlign_After}
```
public static final AttributeName BlockAlign_After
```

Attribut BlockAlign: After - Efterkant av det sista barnets allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel.

### BlockAlign_Before {#BlockAlign_Before}
```
public static final AttributeName BlockAlign_Before
```

Attribut BlockAlign: Before - Förekant av det första barnets allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel.

### BlockAlign_Justify {#BlockAlign_Justify}
```
public static final AttributeName BlockAlign_Justify
```

Attribut BlockAlign: Justify - Barnen är justerade med både före- och efterkanten av tabellcellens innehållsrektangel. Det första barnet placeras enligt beskrivningen för Before och det sista barnet enligt beskrivningen för After, med lika avstånd mellan barnen. Om det bara finns ett barn, ska det bara justeras med före-kanten, som för Before.

### BlockAlign_Middle {#BlockAlign_Middle}
```
public static final AttributeName BlockAlign_Middle
```

Attribut BlockAlign: Middle- Barnen är centrerade inom tabellcellen. Avståndet mellan före-kanten av det första barnets allokeringsrektangel och den för tabellcellens innehållsrektangel ska vara samma som avståndet mellan efter-kanten av det sista barnets allokeringsrektangel och den för tabellcellens innehållsrektangel.

### BorderStyle_Dashed {#BorderStyle_Dashed}
```
public static final AttributeName BorderStyle_Dashed
```

Attribut BorderStyle: Dashed - Kantlinjen är en serie korta linjesegment.

### BorderStyle_Dotted {#BorderStyle_Dotted}
```
public static final AttributeName BorderStyle_Dotted
```

Attribut BorderStyle: Dotted - Kantlinjen är en serie punkter.

### BorderStyle_Double {#BorderStyle_Double}
```
public static final AttributeName BorderStyle_Double
```

Attribut BorderStyle: Double - Kantlinjen består av två solida linjer. Summan av de två linjerna och avståndet mellan dem är lika med värdet för BorderThickness.

### BorderStyle_Groove {#BorderStyle_Groove}
```
public static final AttributeName BorderStyle_Groove
```

Attribut BorderStyle: Groove - Kantlinjen ser ut som om den var inristad i duken.

### BorderStyle_Hidden {#BorderStyle_Hidden}
```
public static final AttributeName BorderStyle_Hidden
```

Attribut BorderStyle: Hidden - Samma som None, förutom när det gäller kantkonfliktlösning för tabellelement.

### BorderStyle_Inset {#BorderStyle_Inset}
```
public static final AttributeName BorderStyle_Inset
```

Attribut BorderStyle: Inset - Kantlinjen får hela rutan att se ut som om den var inbäddad i duken.

### BorderStyle_None {#BorderStyle_None}
```
public static final AttributeName BorderStyle_None
```

Attribut BorderStyle: None - Ingen kant. Tvingar det beräknade värdet av BorderThickness att vara 0.

### BorderStyle_Outset {#BorderStyle_Outset}
```
public static final AttributeName BorderStyle_Outset
```

Attribut BorderStyle: Outset - Kantlinjen får hela rutan att se ut som om den kom ut ur duken (motsatsen till Inset).

### BorderStyle_Ridge {#BorderStyle_Ridge}
```
public static final AttributeName BorderStyle_Ridge
```

Attribut BorderStyle: Ridge - Kantlinjen ser ut som om den kom ut ur duken (motsatsen till Groove).

### BorderStyle_Solid {#BorderStyle_Solid}
```
public static final AttributeName BorderStyle_Solid
```

Attribut BorderStyle: Solid - Kantlinjen är ett enda linjesegment.

### Checked_neutral {#Checked_neutral}
```
public static final AttributeName Checked_neutral
```

Attribut checked: Neutral - Tillståndet för en radioknapp eller kryssrutfält.

### Checked_off {#Checked_off}
```
public static final AttributeName Checked_off
```

Attribut checked: Off - Tillståndet för en radioknapp eller kryssrutfält.

### Checked_on {#Checked_on}
```
public static final AttributeName Checked_on
```

Attribut checked: On - Tillståndet för en radioknapp eller kryssrutfält.

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical_Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```

Attribut GlyphOrientationVertical: Auto - Anger en standardorientering för text, beroende på om den är fullbredd (lika bred som hög).

### Height_Auto {#Height_Auto}
```
public static final AttributeName Height_Auto
```

Attribut Height: Auto - Elementets höjd ska bestämmas av det inneboende höjden på dess innehåll.

### InlineAlign_Center {#InlineAlign_Center}
```
public static final AttributeName InlineAlign_Center
```

Attribut InlineAlign: Center - Varje barn är centrerat inom tabellcellen. Avståndet mellan startkanten av barnets allokeringsrektangel och tabellcellens innehållsrektangel ska vara samma som avståndet mellan deras slutkanten.

### InlineAlign_End {#InlineAlign_End}
```
public static final AttributeName InlineAlign_End
```

Attribut InlineAlign: End - Slutkanten av varje barns allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel.

### InlineAlign_Start {#InlineAlign_Start}
```
public static final AttributeName InlineAlign_Start
```

Attribut InlineAlign: Start - Startkanten av varje barns allokeringsrektangel är justerad med den för tabellcellens innehållsrektangel.

### LineHeight_Auto {#LineHeight_Auto}
```
public static final AttributeName LineHeight_Auto
```

Attribut LineHeight: Auto - Justering för värdet av BaselineShift ska inte göras.

### LineHeight_Normal {#LineHeight_Normal}
```
public static final AttributeName LineHeight_Normal
```

Attribute LineHeight: Normal - Justera radavståndet så att det inkluderar alla icke‑nollvärden som anges för BaselineShift.

### ListNumbering_Circle {#ListNumbering_Circle}
```
public static final AttributeName ListNumbering_Circle
```

Attribute ListNumbering: Circle - Öppna cirkulär punkt.

### ListNumbering_Decimal {#ListNumbering_Decimal}
```
public static final AttributeName ListNumbering_Decimal
```

Attribute ListNumbering: Decimal - Decimala arabiska siffror (1-9, 10-99, ...).

### ListNumbering_Disc {#ListNumbering_Disc}
```
public static final AttributeName ListNumbering_Disc
```

Attribute ListNumbering: Disc - Solid cirkulär punkt.

### ListNumbering_LowerAlpha {#ListNumbering_LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```

Attribute ListNumbering: LowerAlpha - Gemena bokstäver (a, b, c, ...).

### ListNumbering_LowerRoman {#ListNumbering_LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```

Attribute ListNumbering: LowerRoman - Gemena romerska siffror (i, ii, iii, iv, ...).

### ListNumbering_None {#ListNumbering_None}
```
public static final AttributeName ListNumbering_None
```

Attribute ListNumbering: None - Ingen automatisk numrering; Lbl-element (om de finns) innehåller godtycklig text som inte är föremål för något numreringsschema.

### ListNumbering_Square {#ListNumbering_Square}
```
public static final AttributeName ListNumbering_Square
```

Attribute ListNumbering: Square - Solid fyrkantig punkt.

### ListNumbering_UpperAlpha {#ListNumbering_UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```

Attribute ListNumbering: UpperAlpha - Stora bokstäver (A, B, C, ...).

### ListNumbering_UpperRoman {#ListNumbering_UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```

Attribute ListNumbering: UpperRoman - Stora romerska siffror (I, II, III, IV, ...).

### Placement_Before {#Placement_Before}
```
public static final AttributeName Placement_Before
```

Attribute Placement: Before - Placerad så att den föregående kanten av elementets allokeringsrektangel sammanfaller med den för det närmaste omgivande referensområdet.

### Placement_Block {#Placement_Block}
```
public static final AttributeName Placement_Block
```

Attribute Placement: Block - Staplad i blockförloppsriktningen inom ett omgivande referensområde eller överordnad BLSE.

### Placement_End {#Placement_End}
```
public static final AttributeName Placement_End
```

Attribute Placement: End - Placerad så att den avslutande kanten av elementets allokeringsrektangel sammanfaller med den för det närmaste omgivande referensområdet.

### Placement_Inline {#Placement_Inline}
```
public static final AttributeName Placement_Inline
```

Attribute Placement: Inline - Packad i inline‑förloppsriktningen inom ett omgivande BLSE.

### Placement_Start {#Placement_Start}
```
public static final AttributeName Placement_Start
```

Attribute Placement: Start - Placerad så att startkanten av elementets allokeringsrektangel sammanfaller med den för det närmaste omgivande referensområdet.

### Role_cb {#Role_cb}
```
public static final AttributeName Role_cb
```

Attribute Role: cb - Kryssruta.

### Role_pb {#Role_pb}
```
public static final AttributeName Role_pb
```

Attribute Role: pb - Tryckknapp.

### Role_rb {#Role_rb}
```
public static final AttributeName Role_rb
```

Attribute Role: rb - Radioknapp.

### Role_tv {#Role_tv}
```
public static final AttributeName Role_tv
```

Attribute Role: tv - Text‑värdefält.

### RubyAlign_Center {#RubyAlign_Center}
```
public static final AttributeName RubyAlign_Center
```

Attribute RubyAlign: Center - Innehållet ska centreras i inline‑förloppsriktningen.

### RubyAlign_Distribute {#RubyAlign_Distribute}
```
public static final AttributeName RubyAlign_Distribute
```

Attribute RubyAlign: Distribute - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline‑förloppsriktningen. Dock ska utrymme även infogas vid startkanten och slutkanten av texten. Avståndet ska fördelas med ett förhållande 1:2:1 (start:infogning:slut). Det ska ändras till 0:1:1 om ruby visas i början av en textrad eller till 1:1:0 om ruby visas i slutet av textraden.

### RubyAlign_End {#RubyAlign_End}
```
public static final AttributeName RubyAlign_End
```

Attribute RubyAlign: End - Innehållet ska justeras mot slutkanten i inline‑förloppsriktningen.

### RubyAlign_Justify {#RubyAlign_Justify}
```
public static final AttributeName RubyAlign_Justify
```

Attribute RubyAlign: Justify - Innehållet ska expanderas för att fylla den tillgängliga bredden i inline‑förloppsriktningen.

### RubyAlign_Start {#RubyAlign_Start}
```
public static final AttributeName RubyAlign_Start
```

Attribute RubyAlign: Start - Innehållet ska justeras mot startkanten i inline‑förloppsriktningen.

### RubyPosition_After {#RubyPosition_After}
```
public static final AttributeName RubyPosition_After
```

Attribute RubyPosition: After - RT‑innehållet ska justeras längs efterkanten av elementet.

### RubyPosition_Before {#RubyPosition_Before}
```
public static final AttributeName RubyPosition_Before
```

Attribute RubyPosition: Before - RT-innehållet ska justeras längs elementets förkant.

### RubyPosition_Inline {#RubyPosition_Inline}
```
public static final AttributeName RubyPosition_Inline
```

Attribute RubyPosition: Inline - RT- och associerade RP-element ska formateras som en parenteskommentar, efter RB-elementet.

### RubyPosition_Warichu {#RubyPosition_Warichu}
```
public static final AttributeName RubyPosition_Warichu
```

Attribute RubyPosition: Warichu - RT- och associerade RP-element ska formateras som en warichu, efter RB-elementet.

### Scope_Both {#Scope_Both}
```
public static final AttributeName Scope_Both
```

Attribute Scope: Båda.

### Scope_Column {#Scope_Column}
```
public static final AttributeName Scope_Column
```

Attribute Scope: Kolumn.

### Scope_Row {#Scope_Row}
```
public static final AttributeName Scope_Row
```

Attribute Scope: Rad.

### TextAlign_Center {#TextAlign_Center}
```
public static final AttributeName TextAlign_Center
```

Attribute TextAlign: Center - Centrerad mellan start- och slutkanten.

### TextAlign_End {#TextAlign_End}
```
public static final AttributeName TextAlign_End
```

Attribute TextAlign: End - Justerad mot slutkanten.

### TextAlign_Justify {#TextAlign_Justify}
```
public static final AttributeName TextAlign_Justify
```

Attribute TextAlign: Justify - Justerad mot både start- och slutkanten, med internt avstånd inom varje rad utökat vid behov för att uppnå sådan justering. Den sista (eller enda) raden ska bara justeras mot startkanten.

### TextAlign_Start {#TextAlign_Start}
```
public static final AttributeName TextAlign_Start
```

Attribute TextAlign: Start - Justerad mot startkanten.

### TextDecorationType_LineThrough {#TextDecorationType_LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```

Attribute TextDecorationType: LineThrough - En linje genom mitten av texten.

### TextDecorationType_None {#TextDecorationType_None}
```
public static final AttributeName TextDecorationType_None
```

Attribute TextDecorationType: None - Ingen textdekoration.

### TextDecorationType_Overline {#TextDecorationType_Overline}
```
public static final AttributeName TextDecorationType_Overline
```

Attribute TextDecorationType: Overline - En linje ovanför texten.

### TextDecorationType_Underline {#TextDecorationType_Underline}
```
public static final AttributeName TextDecorationType_Underline
```

Attribute TextDecorationType: Underline - En linje under texten.

### Width_Auto {#Width_Auto}
```
public static final AttributeName Width_Auto
```

Attribute Width: Auto - elementets bredd ska bestämmas av innehållets inneboende bredd.

### WritingMode_LrTb {#WritingMode_LrTb}
```
public static final AttributeName WritingMode_LrTb
```

Attribute WritingMode: LrTb - Inline-förlopp från vänster till höger; block-förlopp från topp till botten. Detta är det typiska skrivläget för västerländska skriftsystem.

### WritingMode_RlTb {#WritingMode_RlTb}
```
public static final AttributeName WritingMode_RlTb
```

Attribute WritingMode: RlTb - Inline-förlopp från höger till vänster; block-förlopp från topp till botten. Detta är det typiska skrivläget för arabiska och hebreiska skriftsystem.

### WritingMode_TbRl {#WritingMode_TbRl}
```
public static final AttributeName WritingMode_TbRl
```

Attribute WritingMode: TbRl - Inline-förlopp från topp till botten; block-förlopp från höger till vänster. Detta är det typiska skrivläget för kinesiska och japanska skriftsystem.

### fromNameAttributeKey {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
Hämtar attributnamn för attributnyckel.

### getAttributeKey {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```

Hämtar attributnyckel.

**Returns:**
AttributeKey-instans

### getName {#getName--}
```
public final String getName()
```

Hämtar namnvärde för attribut.

**Returns:**
String värde

### toString {#toString--}
```
public String toString()
```

Returnerar en sträng som representerar det aktuella objektet.

**Returns:**
Sträng som representerar det aktuella objektet.
