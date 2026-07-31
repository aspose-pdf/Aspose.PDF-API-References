---
title: "Classe PdfContentEditor"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Facades.PdfContentEditor. Rappresenta una classe per modificare il contenuto dei file PDF."
type: docs
weight: 4550
url: /it/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

Rappresenta una classe per modificare il contenuto di un file PDF.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor/#constructor)() | Il costruttore dell'oggetto PdfContentEditor. |
| [PdfContentEditor](pdfcontenteditor/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfContentEditor` sulla base del *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facade del documento su cui sta lavorando. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy/) { get; set; } | Un insieme di parametri per l'operazione di sostituzione del testo. |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions/) { get; set; } | Ottiene o imposta le opzioni di modifica del testo. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions/) { get; set; } | Ottiene o imposta le opzioni di sostituzione del testo. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions/) { get; set; } | Ottiene o imposta le opzioni di ricerca del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/)(string, string) | Aggiunge un'azione aggiuntiva per l'evento del documento. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment_1)(string, string) | Aggiunge un allegato al documento senza annotazione. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment)(Stream, string, string) | Aggiunge un allegato al documento senza annotazione. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza il facade. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_1)(Stream) | Associa un flusso PDF per la modifica. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_2)(string) | Associa un file PDF per la modifica. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/)(int) | Modifica le preferenze di visualizzazione. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close/)() | Chiude il documento aperto. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink)(Rectangle, string, int) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_1)(Rectangle, string, int, Color) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/)(string, Color, bool, bool, string, string, string) | Crea un segnalibro con l'azione specificata. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret/)(int, Rectangle, Rectangle, string, string, Color) | Crea un'annotazione cursore. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/)(Rectangle, int, Color, Enum[]) | Crea un collegamento a azioni personalizzate nel documento PDF. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_2)(Rectangle, string, string, int, string) | Crea un'annotazione di allegato file. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment)(Rectangle, string, Stream, string, int, string) | Crea un'annotazione di allegato file. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_3)(Rectangle, string, string, int, string, double) | Crea un'annotazione di allegato file. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | Crea un'annotazione di allegato file. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext/)(Rectangle, string, int) | Crea un'annotazione di testo libero nel documento PDF |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/)(string, Rectangle, int, Color) | Crea un collegamento a JavaScript nel documento PDF. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline/)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | Crea un'annotazione linea. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink)(Rectangle, int, int) | Crea un collegamento locale nel documento PDF. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_1)(Rectangle, int, int, Color) | Crea un collegamento locale nel documento PDF. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | Crea un collegamento locale nel documento PDF. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup/)(Rectangle, string, int, int, Color) | Crea un'annotazione di markup nel documento PDF. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie/)(Rectangle, string, int) | Crea annotazioni video. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink)(Rectangle, string, int, int) | Crea un collegamento a una pagina di un altro documento PDF. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | Crea un collegamento a una pagina di un altro documento PDF. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | Crea un collegamento a una pagina di un altro documento PDF. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon/)(LineInfo, int, Rectangle, string) | Crea un'annotazione poligono. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline/)(LineInfo, int, Rectangle, string) | Crea un'annotazione polilinea. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup/)(Rectangle, string, bool, int) | Crea un'annotazione popup nel documento PDF. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp)(int, Rectangle, string, Color, Stream) | Crea un'annotazione timbro di gomma. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_1)(int, Rectangle, string, Color, string) | Crea un'annotazione timbro di gomma. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_2)(int, Rectangle, string, string, Color) | Crea un'annotazione timbro di gomma. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound/)(Rectangle, string, string, int, string) | Crea annotazioni audio. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle/)(Rectangle, string, Color, bool, int, int) | Crea un'annotazione quadrato-circolo. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext/)(Rectangle, string, string, bool, string, int) | Crea un'annotazione di testo nel documento PDF |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink)(Rectangle, string, int) | Crea un collegamento web nel documento PDF. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_1)(Rectangle, string, int, Color) | Crea un collegamento web nel documento PDF. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_2)(Rectangle, string, int, Color, Enum[]) | Crea un collegamento web nel documento PDF. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments/)() | Elimina tutti gli allegati nel documento PDF. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage)() | Elimina tutte le immagini dal documento PDF. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage_1)(int, int[]) | Elimina le immagini specificate nella pagina specificata. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp/)(int, int[]) | Elimina più timbri nella pagina specificata per indici dei timbri. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid)(int) | Elimina il timbro per ID da tutte le pagine del documento. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid_1)(int, int) | Elimina il timbro nella pagina specificata per ID timbro. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids_1)(int[]) | Elimina i timbri con gli ID specificati da tutte le pagine del documento. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids)(int, int[]) | Elimina i timbri nella pagina specificata per più ID timbro. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve/)(LineInfo, int, Rectangle, string) | Crea un'annotazione curva. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink/)() | Estrae la raccolta di istanze Link contenute nel documento PDF. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps/)(int) | Restituisce l'array di timbri nella pagina. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference/)() | Restituisce la preferenza di visualizzazione. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid/)(int, int) | Nasconde il timbro. Dopo la nasconditura, la visibilità del timbro può essere ripristinata con il metodo ShowStampById. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp/)(int, int, double, double) | Cambia la posizione del timbro nella pagina. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid/)(int, int, double, double) | Cambia la posizione del timbro nella pagina. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/)() | Rimuove l'azione di apertura dal documento. Questa operazione è utile quando si concatenano più documenti che utilizzano un'azione 'GoTo' esplicita all'avvio. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage/)(int, int, string) | Sostituisce l'immagine specificata nella pagina specificata del documento PDF con un'altra immagine. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_2)(string, string) | Sostituisce il testo nel file PDF. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext)(string, int, string) | Sostituisce il testo nel file PDF nella pagina specificata. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_4)(string, string, int) | Sostituisce il testo nel file PDF e imposta la dimensione del carattere. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_3)(string, string, TextState) | Sostituisce il testo nel file PDF usando l'oggetto [`TextState`](../../aspose.pdf.text/textstate/) specificato. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_1)(string, int, string, TextState) | Sostituisce il testo nel file PDF nella pagina specificata. È possibile specificare l'oggetto [`TextState`](../../aspose.pdf.text/textstate/) (famiglia di caratteri, colore) per il testo sostituito. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva il documento PDF nello stream specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva il documento PDF nel file specificato. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid/)(int, int) | Mostra il timbro che è stato nascosto da HiddenStampById. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose/) | Un tipo di evento documento. Chiude un documento. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen/) | Un tipo di evento documento. Apre un documento. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted/) | Un tipo di evento documento. Esegue un'azione dopo la stampa. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved/) | Un tipo di evento documento. Esegue un'azione dopo il salvataggio. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint/) | Un tipo di evento documento. Esegue un'azione prima della stampa. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave/) | Un tipo di evento del documento. Esegue un'azione prima del salvataggio. |

### Vedi anche

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


