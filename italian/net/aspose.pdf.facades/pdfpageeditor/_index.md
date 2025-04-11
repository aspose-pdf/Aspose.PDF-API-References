---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfPageEditor. Rappresenta una classe per modificare le pagine dei file PDF, inclusa la rotazione della pagina, lo zoom, il movimento della posizione e la modifica delle dimensioni della pagina
type: docs
weight: 4590
url: /it/net/aspose.pdf.facades/pdfpageeditor/
---
## Classe PdfPageEditor

Rappresenta una classe per modificare la pagina del file PDF, inclusa la rotazione della pagina, lo zoom, il movimento della posizione e la modifica delle dimensioni della pagina.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | Costruttore per la classe PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | Costruttore per la classe PdfPageEditor. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Ottiene o imposta la durata di visualizzazione per le pagine. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del contenuto PDF originale sulla pagina risultante, il valore predefinito è AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Una tabella hash contiene il numero di pagina e il grado di rotazione, la chiave rappresenta il numero di pagina, il valore della chiave rappresenta la rotazione in gradi. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Ottiene o imposta le dimensioni della pagina del file di output. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Ottiene o imposta i numeri di pagina da modificare. Per impostazione predefinita, ogni pagina verrebbe modificata. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Ottiene o imposta la rotazione delle pagine, la rotazione deve essere 0, 90, 180 o 270. Il valore predefinito è 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Ottiene o imposta la durata dell'effetto di transizione. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Ottiene o imposta lo stile di transizione da utilizzare quando si passa a questa pagina da un'altra durante una presentazione. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Ottiene o imposta l'allineamento verticale del contenuto PDF originale sulla pagina risultante, il valore predefinito è VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Ottiene o imposta il coefficiente di zoom. Il valore 1.0 corrisponde al 100%. Il valore predefinito è 1.0.  Il seguente esempio dimostra come cambiare lo zoom delle pagine del documento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Applica le modifiche apportate alle pagine del documento. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza la facciata. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Rilascia Aspose.Pdf.Document associato a una facciata. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Restituisce la dimensione della casella specificata nel documento. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Restituisce la rotazione della pagina specificata. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Restituisce il numero totale di pagine. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Restituisce le dimensioni della pagina della pagina specificata. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Sposta l'origine da (0, 0) al punto designato. L'origine è in basso a sinistra e l'unità è punto (1 pollice = 72 punti). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Salva il documento modificato nello stream. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Salva il documento modificato nel file. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Persiane Verticali |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Persiane Verticali |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Wipe dal Basso in Alto |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Glitter Diagonale |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | La vecchia pagina si dissolve |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Scatola Inversa |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Glitter da Sinistra a Destra |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Wipe da Sinistra a Destra |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Scatola Esterna |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Wipe da Destra a Sinistra |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | Divisione Orizzontale IN |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Divisione Orizzontale Out |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | Divisione Verticale In |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Divisione Verticale Out |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Glitter dall'Alto in Basso |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Wipe dall'Alto in Basso |

### Vedi Anche

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)