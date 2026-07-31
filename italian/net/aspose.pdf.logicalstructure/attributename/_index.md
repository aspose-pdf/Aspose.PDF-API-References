---
title: "Classe AttributeName"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.LogicalStructure.AttributeName. Rappresenta la classe per i valori dei nomi degli attributi"
type: docs
weight: 6360
url: /it/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Rappresenta la classe per i valori dei nomi degli attributi.

```csharp
public sealed class AttributeName
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | Restituisce la chiave dell'attributo. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | Ottiene il valore del nome dell'attributo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | Ottiene il nome dell'attributo per la chiave dell'attributo. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Attributo BlockAlign: After - Il bordo posteriore dell'ultimo rettangolo di allocazione del figlio è allineato con quello del rettangolo di contenuto della cella della tabella. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Attributo BlockAlign: Before - Il bordo anteriore del primo rettangolo di allocazione del figlio è allineato con quello del rettangolo di contenuto della cella della tabella. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Attributo BlockAlign: Justify - I figli sono allineati sia con il bordo anteriore sia con quello posteriore del rettangolo di contenuto della cella della tabella. Il primo figlio deve essere posizionato come descritto per Before e l'ultimo figlio come descritto per After, con spaziatura uguale tra i figli. Se c'è un solo figlio, deve essere allineato solo con il bordo anteriore, come per Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Attributo BlockAlign: Middle - I figli sono centrati all'interno della cella della tabella. La distanza tra il bordo anteriore del rettangolo di allocazione del primo figlio e quello del rettangolo di contenuto della cella della tabella deve essere la stessa della distanza tra il bordo posteriore del rettangolo di allocazione dell'ultimo figlio e quello del rettangolo di contenuto della cella della tabella. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Attributo BorderStyle: Dashed - Il bordo è una serie di brevi segmenti di linea. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Attributo BorderStyle: Dotted - Il bordo è una serie di punti. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Attributo BorderStyle: Double - Il bordo è costituito da due linee solide. La somma delle due linee e dello spazio tra di esse è uguale al valore di BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Attributo BorderStyle: Groove - Il bordo sembra essere scolpito nella tela. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Attributo BorderStyle: Hidden - Come None, tranne per la risoluzione dei conflitti di bordo per gli elementi della tabella. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Attributo BorderStyle: Inset - Il bordo fa apparire l'intero riquadro come se fosse incassato nella tela. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Attributo BorderStyle: None - Nessun bordo. Forza il valore calcolato di BorderThicknessto a 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Attributo BorderStyle: Outset - Il bordo fa apparire l'intero riquadro come se emergesse dalla tela (l'opposto di Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Attributo BorderStyle: Ridge - Il bordo sembra emergere dalla tela (l'opposto di Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Attributo BorderStyle: Solid - Il bordo è un unico segmento di linea. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Attributo checked: Neutral - Lo stato di un campo pulsante radio o casella di controllo. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Attributo checked: Off - Lo stato di un campo pulsante radio o casella di controllo. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Attributo checked: On - Lo stato di un campo pulsante radio o casella di controllo. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Attributo GlyphOrientationVertical: Auto - Specifica un orientamento predefinito per il testo, a seconda che sia a larghezza piena (largo quanto alto). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Attributo Height: Auto - L'altezza dell'elemento sarà determinata dall'altezza intrinseca del suo contenuto. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Attributo InlineAlign: Center - Ogni figlio centrato all'interno della cella della tabella. La distanza tra i bordi iniziali del rettangolo di allocazione del figlio e il rettangolo di contenuto della cella della tabella deve essere la stessa della distanza tra i loro bordi finali. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Attributo InlineAlign: End - Il bordo finale del rettangolo di allocazione di ogni figlio è allineato a quello del rettangolo di contenuto della cella della tabella. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Attributo InlineAlign: Start - Il bordo iniziale del rettangolo di allocazione di ogni figlio è allineato a quello del rettangolo di contenuto della cella della tabella. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Attributo LineHeight: Auto - Non verrà effettuata alcuna regolazione per il valore di BaselineShift. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Attributo LineHeight: Normal - Regola l'altezza della linea includendo qualsiasi valore diverso da zero specificato per BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Attributo ListNumbering: Circle - Punto elenco circolare aperto. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Attributo ListNumbering: Decimal - Numeri arabi decimali (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Attributo ListNumbering: Disc - Punto elenco circolare pieno. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Attributo ListNumbering: LowerAlpha - Lettere minuscole (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Attributo ListNumbering: LowerRoman - Numeri romani minuscoli (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Attributo ListNumbering: None - Nessuna numerazione automatica; gli elementi Lbl (se presenti) contengono testo arbitrario non soggetto a nessuno schema di numerazione. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Attributo ListNumbering: Square - Punto elenco quadrato pieno. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Attributo ListNumbering: UpperAlpha - Lettere maiuscole (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Attributo ListNumbering: UpperRoman - Numeri romani maiuscoli (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Attributo Placement: Before - Posizionato in modo che il bordo precedente del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina che lo contiene. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Attributo Placement: Block - Impilato nella direzione di avanzamento del blocco all'interno di un'area di riferimento contenente o del BLSE genitore. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Attributo Placement: End - Posizionato in modo che il bordo finale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina che lo contiene. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Attributo Placement: Inline - Compattato nella direzione di avanzamento in linea all'interno di un BLSE contenitore. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Attributo Placement: Start - Posizionato in modo che il bordo iniziale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina che lo contiene. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Attributo Role: cb - Casella di controllo. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Attributo Role: pb - Pulsante. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Attributo Role: rb - Pulsante radio. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Attributo Role: tv - Campo di valore testuale. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Attributo RubyAlign: Center - Il contenuto deve essere centrato nella direzione di avanzamento in linea. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Attributo RubyAlign: Distribute - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di avanzamento in linea. Tuttavia, lo spazio deve essere inserito anche ai bordi iniziale e finale del testo. La spaziatura deve essere distribuita usando un rapporto 1:2:1 (inizio:inserto:fine). Deve essere modificata a un rapporto 0:1:1 se il ruby appare all'inizio di una riga di testo o a un rapporto 1:1:0 se il ruby appare alla fine della riga di testo. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Attributo RubyAlign: End - Il contenuto deve essere allineato al bordo finale nella direzione di avanzamento in linea. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Attributo RubyAlign: Justify - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di avanzamento in linea. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Attributo RubyAlign: Start - Il contenuto deve essere allineato al bordo iniziale nella direzione di avanzamento in linea. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Attributo RubyPosition: After - Il contenuto RT deve essere allineato lungo il bordo successivo dell'elemento. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Attributo RubyPosition: Before - Il contenuto RT deve essere allineato lungo il bordo precedente dell'elemento. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Attributo RubyPosition: Inline - Gli elementi RT e RP associati devono essere formattati come un commento tra parentesi, seguendo l'elemento RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Attributo RubyPosition: Warichu - Gli elementi RT e RP associati devono essere formattati come un warichu, seguendo l'elemento RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Attributo Scope: Both. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Attributo Scope: Column. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Attributo Scope: Row. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Attributo TextAlign: Center - Centrato tra i bordi iniziale e finale. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Attributo TextAlign: End - Allineato al bordo finale. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Attributo TextAlign: Justify - Allineato sia al margine iniziale che a quello finale, con spaziatura interna all'interno di ogni riga espansa, se necessario, per ottenere tale allineamento. L'ultima (o unica) riga deve essere allineata solo al margine iniziale. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Attributo TextAlign: Start - Allineato al margine iniziale. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Attributo TextDecorationType: LineThrough - Una linea che attraversa il centro del testo. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Attributo TextDecorationType: None - Nessuna decorazione del testo. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Attributo TextDecorationType: Overline - Una linea sopra il testo. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Attributo TextDecorationType: Underline - Una linea sotto il testo. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Attributo Width: Auto - la larghezza dell'elemento sarà determinata dalla larghezza intrinseca del suo contenuto. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Attributo WritingMode: LrTb - Progressione in linea da sinistra a destra; progressione di blocco dall'alto verso il basso. Questa è la modalità di scrittura tipica per i sistemi di scrittura occidentali. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Attributo WritingMode: RlTb - Progressione in linea da destra a sinistra; progressione di blocco dall'alto verso il basso. Questa è la modalità di scrittura tipica per i sistemi di scrittura arabi ed ebraici. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Attributo WritingMode: TbRl - Progressione in linea dall'alto verso il basso; progressione di blocco da destra a sinistra. Questa è la modalità di scrittura tipica per i sistemi di scrittura cinese e giapponese. |

### Vedi anche

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


