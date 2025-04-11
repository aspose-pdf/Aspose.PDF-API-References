---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.AttributeName class. Represents class for Attribute Name Values
type: docs
weight: 6220
url: /it/net/aspose.pdf.logicalstructure/attributename/
---
## Classe AttributeName

Rappresenta la classe per i valori del nome dell'attributo.

```csharp
public sealed class AttributeName
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | Ottiene la chiave dell'attributo. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | Ottiene il valore del nome dell'attributo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | Ottiene il nome dell'attributo per la chiave dell'attributo. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Attributo BlockAlign: After - Il bordo dopo dell'allocazione dell'ultimo figlio allineato con quello del rettangolo di contenuto della cella della tabella. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Attributo BlockAlign: Before - Il bordo prima dell'allocazione del primo figlio allineato con quello del rettangolo di contenuto della cella della tabella. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Attributo BlockAlign: Justify - I figli allineati con i bordi prima e dopo del rettangolo di contenuto della cella della tabella. Il primo figlio sarà posizionato come descritto per Before e l'ultimo figlio come descritto per After, con spaziatura uguale tra i figli. Se c'è solo un figlio, sarà allineato solo con il bordo prima, come per Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Attributo BlockAlign: Middle - I figli centrati all'interno della cella della tabella. La distanza tra il bordo prima dell'allocazione del primo figlio e quello del rettangolo di contenuto della cella della tabella sarà la stessa della distanza tra il bordo dopo dell'allocazione dell'ultimo figlio e quello del rettangolo di contenuto della cella della tabella. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Attributo BorderStyle: Dashed - Il bordo è una serie di segmenti di linea corti. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Attributo BorderStyle: Dotted - Il bordo è una serie di punti. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Attributo BorderStyle: Double - Il bordo è due linee solide. La somma delle due linee e lo spazio tra di esse è uguale al valore di BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Attributo BorderStyle: Groove - Il bordo sembra essere scolpito nella tela. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Attributo BorderStyle: Hidden - Stesso di None, tranne che in termini di risoluzione dei conflitti di bordo per gli elementi della tabella. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Attributo BorderStyle: Inset - Il bordo fa sembrare l'intera casella come se fosse incorporata nella tela. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Attributo BorderStyle: None - Nessun bordo. Costringe il valore calcolato di BorderThickness a essere 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Attributo BorderStyle: Outset - Il bordo fa sembrare l'intera casella come se stesse uscendo dalla tela (l'opposto di Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Attributo BorderStyle: Ridge - Il bordo sembra uscire dalla tela (l'opposto di Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Attributo BorderStyle: Solid - Il bordo è un singolo segmento di linea. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Attributo checked: Neutral - Lo stato di un campo radio button o check box. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Attributo checked: Off - Lo stato di un campo radio button o check box. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Attributo checked: On - Lo stato di un campo radio button o check box. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Attributo GlyphOrientationVertical: Auto - Specifica un'orientazione predefinita per il testo, a seconda che sia a larghezza piena (largo quanto alto). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Attributo Height: Auto - L'altezza dell'elemento sarà determinata dall'altezza intrinseca del suo contenuto. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Attributo InlineAlign: Center - Ogni figlio centrato all'interno della cella della tabella. La distanza tra i bordi di inizio del rettangolo di allocazione del figlio e il rettangolo di contenuto della cella della tabella sarà la stessa della distanza tra i loro bordi finali. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Attributo InlineAlign: End - Il bordo finale di ogni rettangolo di allocazione del figlio allineato con quello del rettangolo di contenuto della cella della tabella. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Attributo InlineAlign: Start - Il bordo di inizio di ogni rettangolo di allocazione del figlio allineato con quello del rettangolo di contenuto della cella della tabella. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Attributo LineHeight: Auto - Non verrà effettuata alcuna regolazione per il valore di BaselineShift. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Attributo LineHeight: Normal - Regola l'altezza della linea per includere qualsiasi valore diverso da zero specificato per BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Attributo ListNumbering: Circle - Proiettile circolare aperto. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Attributo ListNumbering: Decimal - Numeri arabi decimali (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Attributo ListNumbering: Disc - Proiettile circolare solido. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Attributo ListNumbering: LowerAlpha - Lettere minuscole (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Attributo ListNumbering: LowerRoman - Numeri romani minuscoli (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Attributo ListNumbering: None - Nessuna numerazione automatica; gli elementi Lbl (se presenti) contengono testo arbitrario non soggetto a nessuno schema di numerazione. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Attributo ListNumbering: Square - Proiettile quadrato solido. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Attributo ListNumbering: UpperAlpha - Lettere maiuscole (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Attributo ListNumbering: UpperRoman - Numeri romani maiuscoli (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Attributo Placement: Before - Posizionato in modo che il bordo prima del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Attributo Placement: Block - Impilato nella direzione di progressione del blocco all'interno di un'area di riferimento o BLSE genitore. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Attributo Placement: End - Posizionato in modo che il bordo finale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Attributo Placement: Inline - Impacchettato nella direzione di progressione in linea all'interno di un BLSE racchiudente. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Attributo Placement: Start - Posizionato in modo che il bordo di inizio del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Attributo Role: cb - Casella di controllo. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Attributo Role: pb - Pulsante di pressione. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Attributo Role: rb - Pulsante radio. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Attributo Role: tv - Campo testo-valore. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Attributo RubyAlign: Center - Il contenuto deve essere centrato nella direzione di progressione in linea. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Attributo RubyAlign: Distribute - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di progressione in linea. Tuttavia, deve essere inserito anche uno spazio all'inizio e alla fine del testo. La spaziatura deve essere distribuita utilizzando un rapporto di 1:2:1 (inizio:infix:fine). Deve essere cambiato in un rapporto di 0:1:1 se il ruby appare all'inizio di una riga di testo o in un rapporto di 1:1:0 se il ruby appare alla fine della riga di testo. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Attributo RubyAlign: End - Il contenuto deve essere allineato sul bordo finale nella direzione di progressione in linea. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Attributo RubyAlign: Justify - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di progressione in linea. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Attributo RubyAlign: Start - Il contenuto deve essere allineato sul bordo di inizio nella direzione di progressione in linea. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Attributo RubyPosition: After - Il contenuto RT deve essere allineato lungo il bordo dopo dell'elemento. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Attributo RubyPosition: Before - Il contenuto RT deve essere allineato lungo il bordo prima dell'elemento. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Attributo RubyPosition: Inline - Gli elementi RT e RP associati devono essere formattati come un commento tra parentesi, seguendo l'elemento RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Attributo RubyPosition: Warichu - Gli elementi RT e RP associati devono essere formattati come un warichu, seguendo l'elemento RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Attributo Scope: Both. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Attributo Scope: Column. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Attributo Scope: Row. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Attributo TextAlign: Center - Centrato tra i bordi di inizio e fine. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Attributo TextAlign: End - Allineato con il bordo finale. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Attributo TextAlign: Justify - Allineato con entrambi i bordi di inizio e fine, con spaziatura interna all'interno di ogni riga espansa, se necessario, per raggiungere tale allineamento. L'ultima (o unica) riga deve essere allineata solo con il bordo di inizio. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Attributo TextAlign: Start - Allineato con il bordo di inizio. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Attributo TextDecorationType: LineThrough - Una linea attraverso il mezzo del testo. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Attributo TextDecorationType: None - Nessuna decorazione del testo. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Attributo TextDecorationType: Overline - Una linea sopra il testo. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Attributo TextDecorationType: Underline - Una linea sotto il testo. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Attributo Width: Auto - la larghezza dell'elemento sarà determinata dalla larghezza intrinseca del suo contenuto. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Attributo WritingMode: LrTb - Progressione in linea da sinistra a destra; progressione del blocco dall'alto verso il basso. Questo è il modo di scrittura tipico per i sistemi di scrittura occidentali. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Attributo WritingMode: RlTb - Progressione in linea da destra a sinistra; progressione del blocco dall'alto verso il basso. Questo è il modo di scrittura tipico per i sistemi di scrittura arabi ed ebraici. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Attributo WritingMode: TbRl - Progressione in linea dall'alto verso il basso; progressione del blocco da destra a sinistra. Questo è il modo di scrittura tipico per i sistemi di scrittura cinesi e giapponesi. |

### Vedi anche

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)