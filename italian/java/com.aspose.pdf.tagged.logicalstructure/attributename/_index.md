---
title: "AttributeName"
linktitle: "AttributeName"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe per i valori dei nomi degli attributi."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.AttributeName

```
public final class AttributeName extends Object
```

Rappresenta la classe per i valori dei nomi degli attributi.

## Campi

| Campo | Descrizione |
| --- | --- |
| [BlockAlign_After](#BlockAlign_After) | Attributo BlockAlign: After - L'estremità posteriore del rettangolo di allocazione dell'ultimo figlio allineata con quella del rettangolo di contenuto della cella della tabella. |
| [BlockAlign_Before](#BlockAlign_Before) | Attributo BlockAlign: Before - L'estremità anteriore del rettangolo di allocazione del primo figlio allineata con quella del rettangolo di contenuto della cella della tabella. |
| [BlockAlign_Justify](#BlockAlign_Justify) | Attributo BlockAlign: Justify - I figli sono allineati sia con l'estremità anteriore sia con quella posteriore del rettangolo di contenuto della cella della tabella. Il primo figlio deve essere posizionato come descritto per Before e l'ultimo figlio come descritto per After, con spaziatura uguale tra i figli. Se c'è un solo figlio, deve essere allineato solo con l'estremità anteriore, come per Before. |
| [BlockAlign_Middle](#BlockAlign_Middle) | Attributo BlockAlign: Middle- I figli sono centrati all'interno della cella della tabella. La distanza tra l'estremità anteriore del rettangolo di allocazione del primo figlio e quella del rettangolo di contenuto della cella della tabella deve essere la stessa della distanza tra l'estremità posteriore del rettangolo di allocazione dell'ultimo figlio e quella del rettangolo di contenuto della cella della tabella. |
| [BorderStyle_Dashed](#BorderStyle_Dashed) | Attributo BorderStyle: Dashed - Il bordo è una serie di brevi segmenti di linea. |
| [BorderStyle_Dotted](#BorderStyle_Dotted) | Attributo BorderStyle: Dotted - Il bordo è una serie di punti. |
| [BorderStyle_Double](#BorderStyle_Double) | Attributo BorderStyle: Double - Il bordo è costituito da due linee solide. La somma delle due linee e dello spazio tra di esse è pari al valore di BorderThickness. |
| [BorderStyle_Groove](#BorderStyle_Groove) | Attributo BorderStyle: Groove - Il bordo sembra essere scolpito nella tela. |
| [BorderStyle_Hidden](#BorderStyle_Hidden) | Attributo BorderStyle: Hidden - Come None, tranne per la risoluzione dei conflitti di bordo per gli elementi della tabella. |
| [BorderStyle_Inset](#BorderStyle_Inset) | Attributo BorderStyle: Inset - Il bordo fa apparire l'intera casella come se fosse incassata nella tela. |
| [BorderStyle_None](#BorderStyle_None) | Attributo BorderStyle: None - Nessun bordo. Forza il valore calcolato di BorderThicknessto a 0. |
| [BorderStyle_Outset](#BorderStyle_Outset) | Attributo BorderStyle: Outset - Il bordo fa apparire l'intera casella come se emergesse dalla tela (l'opposto di Inset). |
| [BorderStyle_Ridge](#BorderStyle_Ridge) | Attributo BorderStyle: Ridge - Il bordo sembra emergere dalla tela (l'opposto di Groove). |
| [BorderStyle_Solid](#BorderStyle_Solid) | Attributo BorderStyle: Solid - Il bordo è un singolo segmento di linea. |
| [Checked_neutral](#Checked_neutral) | Attributo checked: Neutral - Lo stato di un campo pulsante radio o casella di controllo. |
| [Checked_off](#Checked_off) | Attributo checked: Off - Lo stato di un pulsante radio o di una casella di controllo. |
| [Checked_on](#Checked_on) | Attributo checked: On - Lo stato di un pulsante radio o di una casella di controllo. |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical_Auto) | Attributo GlyphOrientationVertical: Auto - Specifica un orientamento predefinito per il testo, a seconda che sia a larghezza piena (largo quanto alto). |
| [Height_Auto](#Height_Auto) | Attributo Height: Auto - L'altezza dell'elemento deve essere determinata dall'altezza intrinseca del suo contenuto. |
| [InlineAlign_Center](#InlineAlign_Center) | Attributo InlineAlign: Center - Ogni figlio è centrato all'interno della cella della tabella. La distanza tra i bordi iniziali del rettangolo di allocazione del figlio e il rettangolo di contenuto della cella della tabella deve essere la stessa della distanza tra i loro bordi finali. |
| [InlineAlign_End](#InlineAlign_End) | Attributo InlineAlign: End - Il bordo finale del rettangolo di allocazione di ogni figlio è allineato a quello del rettangolo di contenuto della cella della tabella. |
| [InlineAlign_Start](#InlineAlign_Start) | Attributo InlineAlign: Start - Il bordo iniziale del rettangolo di allocazione di ogni figlio è allineato a quello del rettangolo di contenuto della cella della tabella. |
| [LineHeight_Auto](#LineHeight_Auto) | Attributo LineHeight: Auto - Non verrà effettuata alcuna regolazione del valore di BaselineShift. |
| [LineHeight_Normal](#LineHeight_Normal) | Attributo LineHeight: Normal - Regola l'altezza della linea per includere qualsiasi valore diverso da zero specificato per BaselineShift. |
| [ListNumbering_Circle](#ListNumbering_Circle) | Attributo ListNumbering: Circle - Punto elenco circolare aperto. |
| [ListNumbering_Decimal](#ListNumbering_Decimal) | Attributo ListNumbering: Decimal - Numeri arabi decimali (1-9, 10-99, ...). |
| [ListNumbering_Disc](#ListNumbering_Disc) | Attributo ListNumbering: Disc - Punto elenco circolare pieno. |
| [ListNumbering_LowerAlpha](#ListNumbering_LowerAlpha) | Attributo ListNumbering: LowerAlpha - Lettere minuscole (a, b, c, ...). |
| [ListNumbering_LowerRoman](#ListNumbering_LowerRoman) | Attributo ListNumbering: LowerRoman - Numeri romani minuscoli (i, ii, iii, iv, ...). |
| [ListNumbering_None](#ListNumbering_None) | Attributo ListNumbering: None - Nessuna numerazione automatica; gli elementi Lbl (se presenti) contengono testo arbitrario non soggetto a nessuno schema di numerazione. |
| [ListNumbering_Square](#ListNumbering_Square) | Attributo ListNumbering: Square - Punto elenco quadrato pieno. |
| [ListNumbering_UpperAlpha](#ListNumbering_UpperAlpha) | Attributo ListNumbering: UpperAlpha - Lettere maiuscole (A, B, C, ...). |
| [ListNumbering_UpperRoman](#ListNumbering_UpperRoman) | Attributo ListNumbering: UpperRoman - Numeri romani maiuscoli (I, II, III, IV, ...). |
| [Placement_Before](#Placement_Before) | Attributo Placement: Before - Posizionato in modo che il bordo iniziale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina che lo contiene. |
| [Placement_Block](#Placement_Block) | Attributo Placement: Block - Impilato nella direzione di avanzamento del blocco all'interno di un'area di riferimento contenente o del BLSE genitore. |
| [Placement_End](#Placement_End) | Attributo Placement: End - Posizionato in modo che il bordo finale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina che lo contiene. |
| [Placement_Inline](#Placement_Inline) | Attributo Placement: Inline - Compattato nella direzione di avanzamento in linea all'interno di un BLSE contenitore. |
| [Placement_Start](#Placement_Start) | Attributo Placement: Start - Posizionato in modo che il bordo iniziale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina che lo contiene. |
| [Role_cb](#Role_cb) | Attributo Role: cb - Casella di controllo. |
| [Role_pb](#Role_pb) | Attributo Role: pb - Pulsante push. |
| [Role_rb](#Role_rb) | Attributo Role: rb - Pulsante radio. |
| [Role_tv](#Role_tv) | Attributo Role: tv - Campo valore di testo. |
| [RubyAlign_Center](#RubyAlign_Center) | Attributo RubyAlign: Center - Il contenuto deve essere centrato nella direzione di avanzamento inline. |
| [RubyAlign_Distribute](#RubyAlign_Distribute) | Attributo RubyAlign: Distribute - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di avanzamento inline. Tuttavia, lo spazio deve essere inserito anche ai bordi iniziale e finale del testo. La spaziatura deve essere distribuita usando un rapporto 1:2:1 (inizio:infix:fine). Deve essere modificato a un rapporto 0:1:1 se il ruby appare all'inizio di una riga di testo o a un rapporto 1:1:0 se il ruby appare alla fine della riga di testo. |
| [RubyAlign_End](#RubyAlign_End) | Attributo RubyAlign: End - Il contenuto deve essere allineato al bordo finale nella direzione di avanzamento inline. |
| [RubyAlign_Justify](#RubyAlign_Justify) | Attributo RubyAlign: Justify - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di avanzamento inline. |
| [RubyAlign_Start](#RubyAlign_Start) | Attributo RubyAlign: Start - Il contenuto deve essere allineato al bordo iniziale nella direzione di avanzamento inline. |
| [RubyPosition_After](#RubyPosition_After) | Attributo RubyPosition: After - Il contenuto RT deve essere allineato lungo il bordo after dell'elemento. |
| [RubyPosition_Before](#RubyPosition_Before) | Attributo RubyPosition: Before - Il contenuto RT deve essere allineato lungo il bordo before dell'elemento. |
| [RubyPosition_Inline](#RubyPosition_Inline) | Attributo RubyPosition: Inline - Gli elementi RT e gli RP associati devono essere formattati come un commento tra parentesi, seguendo l'elemento RB. |
| [RubyPosition_Warichu](#RubyPosition_Warichu) | Attributo RubyPosition: Warichu - Gli elementi RT e gli RP associati devono essere formattati come un warichu, seguendo l'elemento RB. |
| [Scope_Both](#Scope_Both) | Attributo Scope: Both. |
| [Scope_Column](#Scope_Column) | Attributo Scope: Column. |
| [Scope_Row](#Scope_Row) | Attributo Scope: Row. |
| [TextAlign_Center](#TextAlign_Center) | Attributo TextAlign: Center - Centrato tra i bordi iniziale e finale. |
| [TextAlign_End](#TextAlign_End) | Attributo TextAlign: End - Allineato al bordo finale. |
| [TextAlign_Justify](#TextAlign_Justify) | Attributo TextAlign: Justify - Allineato sia al bordo iniziale che a quello finale, con la spaziatura interna di ogni riga espansa, se necessario, per ottenere tale allineamento. L'ultima (o unica) riga deve essere allineata solo al bordo iniziale. |
| [TextAlign_Start](#TextAlign_Start) | Attributo TextAlign: Start - Allineato al bordo iniziale. |
| [TextDecorationType_LineThrough](#TextDecorationType_LineThrough) | Attributo TextDecorationType: LineThrough - Una linea attraversa il centro del testo. |
| [TextDecorationType_None](#TextDecorationType_None) | Attributo TextDecorationType: None - Nessuna decorazione del testo. |
| [TextDecorationType_Overline](#TextDecorationType_Overline) | Attributo TextDecorationType: Overline - Una linea sopra il testo. |
| [TextDecorationType_Underline](#TextDecorationType_Underline) | Attributo TextDecorationType: Underline - Una linea sotto il testo. |
| [Width_Auto](#Width_Auto) | Attributo Width: Auto - la larghezza dell'elemento deve essere determinata dalla larghezza intrinseca del suo contenuto. |
| [WritingMode_LrTb](#WritingMode_LrTb) | Attributo WritingMode: LrTb - Progressione inline da sinistra a destra; progressione di blocco dall'alto verso il basso. Questa è la modalità di scrittura tipica per i sistemi di scrittura occidentali. |
| [WritingMode_RlTb](#WritingMode_RlTb) | Attributo WritingMode: RlTb - Progressione inline da destra a sinistra; progressione di blocco dall'alto verso il basso. Questa è la modalità di scrittura tipica per i sistemi di scrittura arabi ed ebraici. |
| [WritingMode_TbRl](#WritingMode_TbRl) | Attributo WritingMode: TbRl - Progressione in linea dall'alto verso il basso; progressione a blocchi da destra a sinistra. Questa è la modalità di scrittura tipica per i sistemi di scrittura cinese e giapponese. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [fromNameAttributeKey](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Ottiene il nome dell'attributo per la chiave dell'attributo. |
| [getAttributeKey](#getAttributeKey--) | Ottiene la chiave dell'attributo. |
| [getName](#getName--) | Ottiene il valore del nome dell'attributo. |
| [toString](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |

### BlockAlign_After {#BlockAlign_After}
```
public static final AttributeName BlockAlign_After
```

Attributo BlockAlign: After - L'estremità posteriore del rettangolo di allocazione dell'ultimo figlio allineata con quella del rettangolo di contenuto della cella della tabella.

### BlockAlign_Before {#BlockAlign_Before}
```
public static final AttributeName BlockAlign_Before
```

Attributo BlockAlign: Before - L'estremità anteriore del rettangolo di allocazione del primo figlio allineata con quella del rettangolo di contenuto della cella della tabella.

### BlockAlign_Justify {#BlockAlign_Justify}
```
public static final AttributeName BlockAlign_Justify
```

Attributo BlockAlign: Justify - I figli sono allineati sia con l'estremità anteriore sia con quella posteriore del rettangolo di contenuto della cella della tabella. Il primo figlio deve essere posizionato come descritto per Before e l'ultimo figlio come descritto per After, con spaziatura uguale tra i figli. Se c'è un solo figlio, deve essere allineato solo con l'estremità anteriore, come per Before.

### BlockAlign_Middle {#BlockAlign_Middle}
```
public static final AttributeName BlockAlign_Middle
```

Attributo BlockAlign: Middle- I figli sono centrati all'interno della cella della tabella. La distanza tra l'estremità anteriore del rettangolo di allocazione del primo figlio e quella del rettangolo di contenuto della cella della tabella deve essere la stessa della distanza tra l'estremità posteriore del rettangolo di allocazione dell'ultimo figlio e quella del rettangolo di contenuto della cella della tabella.

### BorderStyle_Dashed {#BorderStyle_Dashed}
```
public static final AttributeName BorderStyle_Dashed
```

Attributo BorderStyle: Dashed - Il bordo è una serie di brevi segmenti di linea.

### BorderStyle_Dotted {#BorderStyle_Dotted}
```
public static final AttributeName BorderStyle_Dotted
```

Attributo BorderStyle: Dotted - Il bordo è una serie di punti.

### BorderStyle_Double {#BorderStyle_Double}
```
public static final AttributeName BorderStyle_Double
```

Attributo BorderStyle: Double - Il bordo è costituito da due linee solide. La somma delle due linee e dello spazio tra di esse è pari al valore di BorderThickness.

### BorderStyle_Groove {#BorderStyle_Groove}
```
public static final AttributeName BorderStyle_Groove
```

Attributo BorderStyle: Groove - Il bordo sembra essere scolpito nella tela.

### BorderStyle_Hidden {#BorderStyle_Hidden}
```
public static final AttributeName BorderStyle_Hidden
```

Attributo BorderStyle: Hidden - Come None, tranne per la risoluzione dei conflitti di bordo per gli elementi della tabella.

### BorderStyle_Inset {#BorderStyle_Inset}
```
public static final AttributeName BorderStyle_Inset
```

Attributo BorderStyle: Inset - Il bordo fa apparire l'intera casella come se fosse incassata nella tela.

### BorderStyle_None {#BorderStyle_None}
```
public static final AttributeName BorderStyle_None
```

Attributo BorderStyle: None - Nessun bordo. Forza il valore calcolato di BorderThicknessto a 0.

### BorderStyle_Outset {#BorderStyle_Outset}
```
public static final AttributeName BorderStyle_Outset
```

Attributo BorderStyle: Outset - Il bordo fa apparire l'intera casella come se emergesse dalla tela (l'opposto di Inset).

### BorderStyle_Ridge {#BorderStyle_Ridge}
```
public static final AttributeName BorderStyle_Ridge
```

Attributo BorderStyle: Ridge - Il bordo sembra emergere dalla tela (l'opposto di Groove).

### BorderStyle_Solid {#BorderStyle_Solid}
```
public static final AttributeName BorderStyle_Solid
```

Attributo BorderStyle: Solid - Il bordo è un singolo segmento di linea.

### Checked_neutral {#Checked_neutral}
```
public static final AttributeName Checked_neutral
```

Attributo checked: Neutral - Lo stato di un campo pulsante radio o casella di controllo.

### Checked_off {#Checked_off}
```
public static final AttributeName Checked_off
```

Attributo checked: Off - Lo stato di un pulsante radio o di una casella di controllo.

### Checked_on {#Checked_on}
```
public static final AttributeName Checked_on
```

Attributo checked: On - Lo stato di un pulsante radio o di una casella di controllo.

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical_Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```

Attributo GlyphOrientationVertical: Auto - Specifica un orientamento predefinito per il testo, a seconda che sia a larghezza piena (largo quanto alto).

### Height_Auto {#Height_Auto}
```
public static final AttributeName Height_Auto
```

Attributo Height: Auto - L'altezza dell'elemento deve essere determinata dall'altezza intrinseca del suo contenuto.

### InlineAlign_Center {#InlineAlign_Center}
```
public static final AttributeName InlineAlign_Center
```

Attributo InlineAlign: Center - Ogni figlio è centrato all'interno della cella della tabella. La distanza tra i bordi iniziali del rettangolo di allocazione del figlio e il rettangolo di contenuto della cella della tabella deve essere la stessa della distanza tra i loro bordi finali.

### InlineAlign_End {#InlineAlign_End}
```
public static final AttributeName InlineAlign_End
```

Attributo InlineAlign: End - Il bordo finale del rettangolo di allocazione di ogni figlio è allineato a quello del rettangolo di contenuto della cella della tabella.

### InlineAlign_Start {#InlineAlign_Start}
```
public static final AttributeName InlineAlign_Start
```

Attributo InlineAlign: Start - Il bordo iniziale del rettangolo di allocazione di ogni figlio è allineato a quello del rettangolo di contenuto della cella della tabella.

### LineHeight_Auto {#LineHeight_Auto}
```
public static final AttributeName LineHeight_Auto
```

Attributo LineHeight: Auto - Non verrà effettuata alcuna regolazione del valore di BaselineShift.

### LineHeight_Normal {#LineHeight_Normal}
```
public static final AttributeName LineHeight_Normal
```

Attributo LineHeight: Normal - Regola l'altezza della linea per includere qualsiasi valore diverso da zero specificato per BaselineShift.

### ListNumbering_Circle {#ListNumbering_Circle}
```
public static final AttributeName ListNumbering_Circle
```

Attributo ListNumbering: Circle - Punto elenco circolare aperto.

### ListNumbering_Decimal {#ListNumbering_Decimal}
```
public static final AttributeName ListNumbering_Decimal
```

Attributo ListNumbering: Decimal - Numeri arabi decimali (1-9, 10-99, ...).

### ListNumbering_Disc {#ListNumbering_Disc}
```
public static final AttributeName ListNumbering_Disc
```

Attributo ListNumbering: Disc - Punto elenco circolare pieno.

### ListNumbering_LowerAlpha {#ListNumbering_LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```

Attributo ListNumbering: LowerAlpha - Lettere minuscole (a, b, c, ...).

### ListNumbering_LowerRoman {#ListNumbering_LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```

Attributo ListNumbering: LowerRoman - Numeri romani minuscoli (i, ii, iii, iv, ...).

### ListNumbering_None {#ListNumbering_None}
```
public static final AttributeName ListNumbering_None
```

Attributo ListNumbering: None - Nessuna numerazione automatica; gli elementi Lbl (se presenti) contengono testo arbitrario non soggetto a nessuno schema di numerazione.

### ListNumbering_Square {#ListNumbering_Square}
```
public static final AttributeName ListNumbering_Square
```

Attributo ListNumbering: Square - Punto elenco quadrato pieno.

### ListNumbering_UpperAlpha {#ListNumbering_UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```

Attributo ListNumbering: UpperAlpha - Lettere maiuscole (A, B, C, ...).

### ListNumbering_UpperRoman {#ListNumbering_UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```

Attributo ListNumbering: UpperRoman - Numeri romani maiuscoli (I, II, III, IV, ...).

### Placement_Before {#Placement_Before}
```
public static final AttributeName Placement_Before
```

Attributo Placement: Before - Posizionato in modo che il bordo iniziale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina che lo contiene.

### Placement_Block {#Placement_Block}
```
public static final AttributeName Placement_Block
```

Attributo Placement: Block - Impilato nella direzione di avanzamento del blocco all'interno di un'area di riferimento contenente o del BLSE genitore.

### Placement_End {#Placement_End}
```
public static final AttributeName Placement_End
```

Attributo Placement: End - Posizionato in modo che il bordo finale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina che lo contiene.

### Placement_Inline {#Placement_Inline}
```
public static final AttributeName Placement_Inline
```

Attributo Placement: Inline - Compattato nella direzione di avanzamento in linea all'interno di un BLSE contenitore.

### Placement_Start {#Placement_Start}
```
public static final AttributeName Placement_Start
```

Attributo Placement: Start - Posizionato in modo che il bordo iniziale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina che lo contiene.

### Role_cb {#Role_cb}
```
public static final AttributeName Role_cb
```

Attributo Role: cb - Casella di controllo.

### Role_pb {#Role_pb}
```
public static final AttributeName Role_pb
```

Attributo Role: pb - Pulsante push.

### Role_rb {#Role_rb}
```
public static final AttributeName Role_rb
```

Attributo Role: rb - Pulsante radio.

### Role_tv {#Role_tv}
```
public static final AttributeName Role_tv
```

Attributo Role: tv - Campo valore di testo.

### RubyAlign_Center {#RubyAlign_Center}
```
public static final AttributeName RubyAlign_Center
```

Attributo RubyAlign: Center - Il contenuto deve essere centrato nella direzione di avanzamento inline.

### RubyAlign_Distribute {#RubyAlign_Distribute}
```
public static final AttributeName RubyAlign_Distribute
```

Attributo RubyAlign: Distribute - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di avanzamento inline. Tuttavia, lo spazio deve essere inserito anche ai bordi iniziale e finale del testo. La spaziatura deve essere distribuita usando un rapporto 1:2:1 (inizio:infix:fine). Deve essere modificato a un rapporto 0:1:1 se il ruby appare all'inizio di una riga di testo o a un rapporto 1:1:0 se il ruby appare alla fine della riga di testo.

### RubyAlign_End {#RubyAlign_End}
```
public static final AttributeName RubyAlign_End
```

Attributo RubyAlign: End - Il contenuto deve essere allineato al bordo finale nella direzione di avanzamento inline.

### RubyAlign_Justify {#RubyAlign_Justify}
```
public static final AttributeName RubyAlign_Justify
```

Attributo RubyAlign: Justify - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di avanzamento inline.

### RubyAlign_Start {#RubyAlign_Start}
```
public static final AttributeName RubyAlign_Start
```

Attributo RubyAlign: Start - Il contenuto deve essere allineato al bordo iniziale nella direzione di avanzamento inline.

### RubyPosition_After {#RubyPosition_After}
```
public static final AttributeName RubyPosition_After
```

Attributo RubyPosition: After - Il contenuto RT deve essere allineato lungo il bordo after dell'elemento.

### RubyPosition_Before {#RubyPosition_Before}
```
public static final AttributeName RubyPosition_Before
```

Attributo RubyPosition: Before - Il contenuto RT deve essere allineato lungo il bordo before dell'elemento.

### RubyPosition_Inline {#RubyPosition_Inline}
```
public static final AttributeName RubyPosition_Inline
```

Attributo RubyPosition: Inline - Gli elementi RT e gli RP associati devono essere formattati come un commento tra parentesi, seguendo l'elemento RB.

### RubyPosition_Warichu {#RubyPosition_Warichu}
```
public static final AttributeName RubyPosition_Warichu
```

Attributo RubyPosition: Warichu - Gli elementi RT e gli RP associati devono essere formattati come un warichu, seguendo l'elemento RB.

### Scope_Both {#Scope_Both}
```
public static final AttributeName Scope_Both
```

Attributo Scope: Both.

### Scope_Column {#Scope_Column}
```
public static final AttributeName Scope_Column
```

Attributo Scope: Column.

### Scope_Row {#Scope_Row}
```
public static final AttributeName Scope_Row
```

Attributo Scope: Row.

### TextAlign_Center {#TextAlign_Center}
```
public static final AttributeName TextAlign_Center
```

Attributo TextAlign: Center - Centrato tra i bordi iniziale e finale.

### TextAlign_End {#TextAlign_End}
```
public static final AttributeName TextAlign_End
```

Attributo TextAlign: End - Allineato al bordo finale.

### TextAlign_Justify {#TextAlign_Justify}
```
public static final AttributeName TextAlign_Justify
```

Attributo TextAlign: Justify - Allineato sia al bordo iniziale che a quello finale, con la spaziatura interna di ogni riga espansa, se necessario, per ottenere tale allineamento. L'ultima (o unica) riga deve essere allineata solo al bordo iniziale.

### TextAlign_Start {#TextAlign_Start}
```
public static final AttributeName TextAlign_Start
```

Attributo TextAlign: Start - Allineato al bordo iniziale.

### TextDecorationType_LineThrough {#TextDecorationType_LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```

Attributo TextDecorationType: LineThrough - Una linea attraversa il centro del testo.

### TextDecorationType_None {#TextDecorationType_None}
```
public static final AttributeName TextDecorationType_None
```

Attributo TextDecorationType: None - Nessuna decorazione del testo.

### TextDecorationType_Overline {#TextDecorationType_Overline}
```
public static final AttributeName TextDecorationType_Overline
```

Attributo TextDecorationType: Overline - Una linea sopra il testo.

### TextDecorationType_Underline {#TextDecorationType_Underline}
```
public static final AttributeName TextDecorationType_Underline
```

Attributo TextDecorationType: Underline - Una linea sotto il testo.

### Width_Auto {#Width_Auto}
```
public static final AttributeName Width_Auto
```

Attributo Width: Auto - la larghezza dell'elemento deve essere determinata dalla larghezza intrinseca del suo contenuto.

### WritingMode_LrTb {#WritingMode_LrTb}
```
public static final AttributeName WritingMode_LrTb
```

Attributo WritingMode: LrTb - Progressione inline da sinistra a destra; progressione di blocco dall'alto verso il basso. Questa è la modalità di scrittura tipica per i sistemi di scrittura occidentali.

### WritingMode_RlTb {#WritingMode_RlTb}
```
public static final AttributeName WritingMode_RlTb
```

Attributo WritingMode: RlTb - Progressione inline da destra a sinistra; progressione di blocco dall'alto verso il basso. Questa è la modalità di scrittura tipica per i sistemi di scrittura arabi ed ebraici.

### WritingMode_TbRl {#WritingMode_TbRl}
```
public static final AttributeName WritingMode_TbRl
```

Attributo WritingMode: TbRl - Progressione in linea dall'alto verso il basso; progressione a blocchi da destra a sinistra. Questa è la modalità di scrittura tipica per i sistemi di scrittura cinese e giapponese.

### fromNameAttributeKey {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
Ottiene il nome dell'attributo per la chiave dell'attributo.

### getAttributeKey {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```

Ottiene la chiave dell'attributo.

**Returns:**
Istanza di AttributeKey

### getName {#getName--}
```
public final String getName()
```

Ottiene il valore del nome dell'attributo.

**Returns:**
valore String

### toString {#toString--}
```
public String toString()
```

Restituisce una stringa che rappresenta l'oggetto corrente.

**Returns:**
Stringa che rappresenta l'oggetto corrente.
