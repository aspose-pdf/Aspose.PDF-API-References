---
title: "AttributeName"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per i valori dei nomi degli attributi."
type: docs
weight: 50
url: /it/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

Rappresenta una classe per i valori dei nomi degli attributi.

Il tipo AttributeName espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| name | Ottiene il valore del nome dell'attributo. |
| attribute_key | Ottiene la chiave dell'attributo. |
| PLACEMENT_BLOCK | Posizionamento attributo: Block - Impilato nella direzione di progressione del blocco all'interno di un'area di riferimento contenente o BLSE genitore. |
| PLACEMENT_INLINE | Posizionamento attributo: Inline - Compattato nella direzione di progressione inline all'interno di un BLSE contenitore. |
| PLACEMENT_BEFORE | Posizionamento attributo: Before - Posizionato in modo che il bordo precedente del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina. |
| PLACEMENT_START | Posizionamento attributo: Start - Posizionato in modo che il bordo iniziale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina. |
| PLACEMENT_END | Posizionamento attributo: End - Posizionato in modo che il bordo finale del rettangolo di allocazione dell'elemento coincida con quello dell'area di riferimento più vicina. |
| WRITING_MODE_LR_TB | Modalità di scrittura attributo: LrTb - Progressione inline da sinistra a destra; progressione del blocco dall'alto verso il basso. Questa è la modalità di scrittura tipica per i sistemi di scrittura occidentali. |
| WRITING_MODE_RL_TB | Modalità di scrittura attributo: RlTb - Progressione inline da destra a sinistra; progressione del blocco dall'alto verso il basso. Questa è la modalità di scrittura tipica per i sistemi di scrittura arabi ed ebraici. |
| WRITING_MODE_TB_RL | Modalità di scrittura attributo: TbRl - Progressione inline dall'alto verso il basso; progressione del blocco da destra a sinistra. Questa è la modalità di scrittura tipica per i sistemi di scrittura cinese e giapponese. |
| BORDER_STYLE_NONE | Stile bordo attributo: None - Nessun bordo. Forza il valore calcolato di BorderThicknessto a 0. |
| BORDER_STYLE_HIDDEN | Stile bordo attributo: Hidden - Stesso di None, tranne per la risoluzione dei conflitti di bordo per gli elementi tabella. |
| BORDER_STYLE_DOTTED | Stile bordo attributo: Dotted - Il bordo è una serie di punti. |
| BORDER_STYLE_DASHED | Attributo BorderStyle: Dashed - Il bordo è una serie di brevi segmenti di linea. |
| BORDER_STYLE_SOLID | Attributo BorderStyle: Solid - Il bordo è un unico segmento di linea. |
| BORDER_STYLE_DOUBLE | Attributo BorderStyle: Double - Il bordo è composto da due linee solide. La somma delle due linee e dello spazio tra di esse è uguale al valore di BorderThickness. |
| BORDER_STYLE_GROOVE | Attributo BorderStyle: Groove - Il bordo sembra essere stato intagliato nella tela. |
| BORDER_STYLE_RIDGE | Attributo BorderStyle: Ridge - Il bordo sembra emergere dalla tela (l'opposto di Groove). |
| BORDER_STYLE_INSET | Attributo BorderStyle: Inset - Il bordo fa sembrare l'intera casella incastonata nella tela. |
| BORDER_STYLE_OUTSET | Attributo BorderStyle: Outset - Il bordo fa sembrare l'intera casella emergere dalla tela (l'opposto di Inset). |
| TEXT_ALIGN_START | Attributo TextAlign: Start - Allineato al bordo iniziale. |
| TEXT_ALIGN_CENTER | Attributo TextAlign: Center - Centrado tra i bordi iniziale e finale. |
| TEXT_ALIGN_END | Attributo TextAlign: End - Allineato al bordo finale. |
| TEXT_ALIGN_JUSTIFY | Attributo TextAlign: Justify - Allineato sia al bordo iniziale che a quello finale, con spaziatura interna all'interno di ogni riga espansa, se necessario, per ottenere tale allineamento. L'ultima (o unica) riga deve essere allineata solo al bordo iniziale. |
| WIDTH_AUTO | Attributo Width: Auto - la larghezza dell'elemento sarà determinata dalla larghezza intrinseca del suo contenuto. |
| HEIGHT_AUTO | Attributo Height: Auto - L'altezza dell'elemento sarà determinata dall'altezza intrinseca del suo contenuto. |
| BLOCK_ALIGN_BEFORE | Attributo BlockAlign: Before - Il bordo iniziale del rettangolo di allocazione del primo figlio è allineato a quello del rettangolo di contenuto della cella della tabella. |
| BLOCK_ALIGN_MIDDLE | Attributo BlockAlign: Middle- Figli centrati all'interno della cella della tabella. La distanza tra il bordo precedente del rettangolo di allocazione del primo figlio e quello del rettangolo di contenuto della cella della tabella deve essere la stessa della distanza tra il bordo successivo del rettangolo di allocazione dell'ultimo figlio e quello del rettangolo di contenuto della cella della tabella. |
| BLOCK_ALIGN_AFTER | Attributo BlockAlign: After - Il bordo successivo del rettangolo di allocazione dell'ultimo figlio è allineato con quello del rettangolo di contenuto della cella della tabella. |
| BLOCK_ALIGN_JUSTIFY | Attributo BlockAlign: Justify - Figli allineati sia con il bordo precedente sia con il bordo successivo del rettangolo di contenuto della cella della tabella. Il primo figlio deve essere posizionato come descritto per Before e l'ultimo figlio come descritto per After, con spaziatura uguale tra i figli. Se è presente un solo figlio, deve essere allineato solo al bordo precedente, come per Before. |
| INLINE_ALIGN_START | Attributo InlineAlign: Start - Il bordo iniziale di ciascun rettangolo di allocazione del figlio è allineato con quello del rettangolo di contenuto della cella della tabella. |
| INLINE_ALIGN_CENTER | Attributo InlineAlign: Center - Ogni figlio è centrato all'interno della cella della tabella. La distanza tra i bordi iniziali del rettangolo di allocazione del figlio e del rettangolo di contenuto della cella della tabella deve essere la stessa della distanza tra i loro bordi finali. |
| INLINE_ALIGN_END | Attributo InlineAlign: End - Il bordo finale di ciascun rettangolo di allocazione del figlio è allineato con quello del rettangolo di contenuto della cella della tabella. |
| LINE_HEIGHT_NORMAL | Attributo LineHeight: Normal - Regola l'altezza della linea per includere qualsiasi valore diverso da zero specificato per BaselineShift. |
| LINE_HEIGHT_AUTO | Attributo LineHeight: Auto - Non verrà effettuata alcuna regolazione del valore di BaselineShift. |
| TEXT_DECORATION_TYPE_NONE | Attributo TextDecorationType: None - Nessuna decorazione del testo. |
| TEXT_DECORATION_TYPE_UNDERLINE | Attributo TextDecorationType: Underline - Una linea sotto il testo. |
| TEXT_DECORATION_TYPE_OVERLINE | Attributo TextDecorationType: Overline - Una linea sopra il testo. |
| TEXT_DECORATION_TYPE_LINE_THROUGH | Attributo TextDecorationType: LineThrough - Una linea che attraversa il centro del testo. |
| RUBY_ALIGN_START | Attributo RubyAlign: Start - Il contenuto deve essere allineato al bordo iniziale nella direzione di avanzamento in linea. |
| RUBY_ALIGN_CENTER | Attributo RubyAlign: Center - Il contenuto deve essere centrato nella direzione di avanzamento in linea. |
| RUBY_ALIGN_END | Attributo RubyAlign: End - Il contenuto deve essere allineato al bordo finale nella direzione di avanzamento in linea. |
| RUBY_ALIGN_JUSTIFY | Attributo RubyAlign: Justify - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di avanzamento in linea. |
| RUBY_ALIGN_DISTRIBUTE | Attributo RubyAlign: Distribute - Il contenuto deve essere espanso per riempire la larghezza disponibile nella direzione di avanzamento in linea. Tuttavia, lo spazio deve essere inserito anche al bordo iniziale e al bordo finale del testo. La spaziatura deve essere distribuita usando un rapporto 1:2:1 (inizio:infix:fine). Viene modificato in un rapporto 0:1:1 se il ruby appare all'inizio di una riga di testo o in un rapporto 1:1:0 se il ruby appare alla fine della riga di testo. |
| RUBY_POSITION_BEFORE | Attributo RubyPosition: Before - Il contenuto RT deve essere allineato lungo il bordo precedente dell'elemento. |
| RUBY_POSITION_AFTER | Attributo RubyPosition: After - Il contenuto RT deve essere allineato lungo il bordo successivo dell'elemento. |
| RUBY_POSITION_WARICHU | Attributo RubyPosition: Warichu - Gli elementi RT e RP associati devono essere formattati come un warichu, seguendo l'elemento RB. |
| RUBY_POSITION_INLINE | Attributo RubyPosition: Inline - Gli elementi RT e RP associati devono essere formattati come un commento tra parentesi, seguendo l'elemento RB. |
| GLYPH_ORIENTATION_VERTICAL_AUTO | Attributo GlyphOrientationVertical: Auto - Specifica un'orientazione predefinita per il testo, a seconda che sia a larghezza piena (lungo quanto è alto). |
| LIST_NUMBERING_NONE | Attributo ListNumbering: None - Nessuna numerazione automatica; gli elementi Lbl (se presenti) contengono testo arbitrario non soggetto a nessuno schema di numerazione. |
| LIST_NUMBERING_DISC | Attributo ListNumbering: Disc - Pallino circolare pieno. |
| LIST_NUMBERING_CIRCLE | Attributo ListNumbering: Circle - Pallino circolare vuoto. |
| LIST_NUMBERING_SQUARE | Attributo ListNumbering: Square - Pallino quadrato pieno. |
| LIST_NUMBERING_DECIMAL | Attributo ListNumbering: Decimal - Numeri arabi decimali (1-9, 10-99, ...). |
| LIST_NUMBERING_UPPER_ROMAN | Attributo ListNumbering: UpperRoman - Numeri romani maiuscoli (I, II, III, IV, ...). |
| LIST_NUMBERING_LOWER_ROMAN | Attributo ListNumbering: LowerRoman - Numeri romani minuscoli (i, ii, iii, iv, ...). |
| LIST_NUMBERING_UPPER_ALPHA | Attributo ListNumbering: UpperAlpha - Lettere maiuscole (A, B, C, ...). |
| LIST_NUMBERING_LOWER_ALPHA | Attributo ListNumbering: LowerAlpha - Lettere minuscole (a, b, c, ...). |
| ROLE_RB | Attributo Role: rb - Pulsante di opzione. |
| ROLE_CB | Attributo Role: cb - Casella di controllo. |
| ROLE_PB | Attributo Role: pb - Pulsante. |
| ROLE_TV | Attributo Role: tv - Campo valore di testo. |
| CHECKED_ON | Attributo checked: On - Lo stato di un campo pulsante di opzione o casella di controllo. |
| CHECKED_OFF | Attributo checked: Off - Lo stato di un campo pulsante di opzione o casella di controllo. |
| CHECKED_NEUTRAL | Attributo controllato: Neutro - Lo stato di un campo radio o di una casella di controllo. |
| SCOPE_ROW | Ambito dell'attributo: Riga. |
| SCOPE_COLUMN | Ambito dell'attributo: Colonna. |
| SCOPE_BOTH | Ambito dell'attributo: Entrambi. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | Ottiene il nome dell'attributo per la chiave dell'attributo. |

### Vedi anche

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

