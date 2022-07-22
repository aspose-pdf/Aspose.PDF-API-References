---
title: AttributeName
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta la classe per i valori del nome attributo.
type: docs
weight: 4050
url: /it/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Rappresenta la classe per i valori del nome attributo.

```csharp
public sealed class AttributeName
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey) { get; } | Ottiene la chiave dell'attributo. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name) { get; } | Ottiene il valore del nome dell'attributo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey)(string, AttributeKey) | Ottiene il nome dell'attributo per la chiave dell'attributo. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after) | Attributo BlockAlign: After - Dopo il bordo del rettangolo di assegnazione dell'ultimo figlio allineato a quello del rettangolo del contenuto della cella della tabella. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before) | Attributo BlockAlign: Before - Prima del bordo del rettangolo di assegnazione del primo figlio allineato a quello del rettangolo del contenuto della cella della tabella. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify) | Attributo BlockAlign: Justify - I figli sono allineati con entrambi i bordi prima e dopo del rettangolo del contenuto della cella della tabella. Il primo bambino deve essere posizionato come descritto per Prima e l'ultimo bambino come descritto per Dopo, con uguale distanza tra i bambini. Se c'è un solo bambino, deve essere allineato solo con il bordo anteriore, come per Prima. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle) | Attributo BlockAlign: Middle- Figli centrati all'interno della cella della tabella. La distanza tra il bordo anteriore del rettangolo di assegnazione del primo figlio e quello del rettangolo del contenuto della cella della tabella deve essere uguale alla distanza tra il bordo successivo del rettangolo di assegnazione dell'ultimo figlio e quello del rettangolo del contenuto della cella della tabella. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed) | Attributo BorderStyle: Tratteggiata - Il bordo è una serie di segmenti di linea corta. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted) | Attributo BorderStyle: Punteggiato - Il bordo è una serie di punti. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double) | Attributo BorderStyle: Double - Il bordo è costituito da due linee continue. La somma delle due linee e dello spazio tra di esse è uguale al valore di BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove) | Attribute BorderStyle: Groove - Il bordo sembra scolpito nella tela. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden) | Attributo BorderStyle: Nascosto - Uguale a Nessuno, tranne in termini di risoluzione dei conflitti di confine per gli elementi della tabella. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset) | Attribute BorderStyle: Inset - Il bordo fa sembrare l'intera casella come se fosse incorporata nella tela. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none) | Attributo BorderStyle: Nessuno - Nessun bordo. Forza il valore calcolato di BorderThickness su 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset) | Attribute BorderStyle: Outset - Il bordo fa sembrare l'intera casella come se stesse uscendo dalla tela (l'opposto di Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge) | Attribute BorderStyle: Ridge - Il bordo sembra uscire dalla tela (l'opposto di Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid) | Attributo BorderStyle: Solid - Il bordo è un singolo segmento di linea. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral) | Attributo selezionato: Neutro - Lo stato di un pulsante di opzione o di un campo di casella di controllo. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off) | Attributo selezionato: Off - Lo stato di un pulsante di opzione o campo della casella di controllo. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on) | Attributo selezionato: On - Lo stato di un pulsante di opzione o di un campo di casella di controllo. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto) | Attributo GlyphOrientationVertical: Auto - Specifica un orientamento predefinito per il testo, a seconda che sia a larghezza intera (tanto larga quanto alta). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto) | Altezza attributo: Auto - L'altezza dell'elemento deve essere determinata dall'altezza intrinseca del suo contenuto. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center) | Attributo InlineAlign: Center - Ogni figlio centrato all'interno della cella della tabella. La distanza tra i bordi iniziali del rettangolo di assegnazione del bambino e il rettangolo del contenuto della cella della tabella deve essere uguale alla distanza tra i loro bordi finali. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end) | Attributo InlineAlign: End - Bordo finale del rettangolo di assegnazione di ciascun figlio allineato a quello del rettangolo del contenuto della cella della tabella. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start) | Attributo InlineAlign: Start - Bordo iniziale del rettangolo di assegnazione di ciascun figlio allineato a quello del rettangolo del contenuto della cella della tabella. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto) | Attributo LineHeight: Auto - La regolazione per il valore di BaselineShift non deve essere effettuata. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal) | Attributo LineHeight: Normal - Regola l'altezza della linea per includere qualsiasi valore diverso da zero specificato per BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle) | Numerazione elenco attributi: Cerchio - Apri punto elenco circolare. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal) | Attribute ListNumbering: Decimal - Numeri arabi decimali (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc) | Numerazione elenco attributi: Disco - Punto elenco circolare solido. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha) | Attribute ListNumbering: LowerAlpha - Lettere minuscole (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman) | Attribute ListNumbering: LowerRoman - Numeri romani minuscoli (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none) | Attributi ListNumbering: Nessuno - Nessuna numerazione automatica; Gli elementi Lbl (se presenti) contengono testo arbitrario non soggetto ad alcuno schema di numerazione. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square) | Elenco attributi Numerazione: Quadrato - Punto elenco quadrato solido. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha) | Attribute ListNumbering: UpperAlpha - Lettere maiuscole (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman) | Attribute ListNumbering: UpperRoman - Numeri romani maiuscoli (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before) | Posizionamento attributo: Prima - Posizionato in modo che il bordo anteriore del rettangolo di assegnazione dell'elemento coincida con quello dell'area di riferimento di chiusura più vicina. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block) | Posizionamento attributo: Blocco - Impilato nella direzione di avanzamento del blocco all'interno di un'area di riferimento racchiusa o BLSE principale. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end) | Posizionamento attributo: Fine - Posizionato in modo che il bordo finale del rettangolo di assegnazione dell'elemento coincida con quello dell'area di riferimento di chiusura più vicina. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline) | Posizionamento attributo: Inline - Imballato nella direzione di progressione inline all'interno di un BLSE che lo racchiude. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start) | Posizionamento attributo: Inizio - Posizionato in modo che il bordo iniziale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento di chiusura più vicina. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb) | Ruolo attributo: cb - Casella di controllo. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb) | Ruolo attributo: pb - Pulsante. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb) | Ruolo attributo: rb - Pulsante di opzione. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv) | Ruolo attributo: tv - Campo valore testo. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center) | Attributo RubyAlign: Center - Il contenuto deve essere centrato nella direzione di avanzamento in linea. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute) | Attributo RubyAlign: Distribute - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di avanzamento inline. Tuttavia, lo spazio deve essere inserito anche sul bordo iniziale e sul bordo finale del testo. La spaziatura deve essere distribuita utilizzando un rapporto 1:2:1 (inizio:infisso:fine). Deve essere modificato in un rapporto 0:1:1 se il rubino appare all'inizio di una riga di testo o in un rapporto 1:1:0 se il rubino appare alla fine della riga di testo. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end) | Attributo RubyAlign: End - Il contenuto deve essere allineato sul bordo finale nella direzione di avanzamento in linea. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify) | Attributo RubyAlign: Justify - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di avanzamento inline. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start) | Attributo RubyAlign: Start - Il contenuto deve essere allineato sul bordo iniziale nella direzione di progressione inline. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after) | Attributo RubyPosition: After - Il contenuto RT deve essere allineato lungo il bordo posteriore dell'elemento. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before) | Attributo RubyPosition: Before - Il contenuto RT deve essere allineato lungo il bordo anteriore dell'elemento. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline) | Attributo RubyPosition: Inline - L'RT e gli elementi RP associati devono essere formattati come commento tra parentesi, dopo l'elemento RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu) | Attributo RubyPosition: Warichu - L'RT e gli elementi RP associati devono essere formattati come warichu, seguendo l'elemento RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both) | Ambito attributo: entrambi. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column) | Ambito attributo: Colonna. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row) | Ambito attributo: Riga. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center) | Attributo TextAlign: Center - Centrato tra i bordi iniziale e finale. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end) | Attributo TextAlign: End - Allineato con il bordo finale. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify) | Attributo TextAlign: Justify - Allineato con entrambi i bordi iniziale e finale, con spaziatura interna all'interno di ciascuna riga espansa, se necessario, per ottenere tale allineamento. L'ultima (o l'unica) riga deve essere allineata solo con il bordo iniziale. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start) | Attributo TextAlign: Start - Allineato con il bordo iniziale. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough) | Attributo TextDecorationType: LineThrough - Una linea nel mezzo del testo. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none) | Attributo TextDecorationType: Nessuno - Nessuna decorazione del testo. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline) | Attributo TextDecorationType: Overline - Una riga sopra il testo. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline) | Attributo TextDecorationType: Underline - Una riga sotto il testo. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto) | Larghezza attributo: Auto - la larghezza dell'elemento deve essere determinata dalla larghezza intrinseca del suo contenuto. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb) | Attribute WritingMode: LrTb - Progressione in linea da sinistra a destra; bloccare la progressione dall'alto verso il basso. Questa è la modalità di scrittura tipica per i sistemi di scrittura occidentali. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb) | Attribute WritingMode: RlTb - Progressione in linea da destra a sinistra; bloccare la progressione dall'alto verso il basso. Questa è la modalità di scrittura tipica per i sistemi di scrittura in arabo ed ebraico. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl) | Attribute WritingMode: TbRl - Progressione in linea dall'alto verso il basso; bloccare la progressione da destra a sinistra. Questa è la modalità di scrittura tipica per i sistemi di scrittura cinesi e giapponesi. |

### Guarda anche

* spazio dei nomi [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
