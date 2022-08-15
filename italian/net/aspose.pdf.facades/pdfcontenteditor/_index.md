---
title: PdfContentEditor
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta una classe per modificare il contenuto del file PDF.
type: docs
weight: 2440
url: /it/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

Rappresenta una classe per modificare il contenuto del file PDF.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor#constructor)() | Il costruttore dell'oggetto PdfContentEditor. |
| [PdfContentEditor](pdfcontenteditor#constructor_1)(Document) | Inizializza nuovo[`PdfContentEditor`](../pdfcontenteditor) oggetto sulla base del*document* . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy) { get; set; } | Un insieme di parametri per l'operazione di sostituzione del testo |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions) { get; set; } | Ottiene o imposta le opzioni di modifica del testo. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions) { get; set; } | Ottiene o imposta le opzioni di sostituzione del testo. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions) { get; set; } | Ottiene o imposta le opzioni di ricerca del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction)(string, string) | Aggiunge un'azione aggiuntiva per l'evento del documento. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment_1)(string, string) | Aggiunge un allegato al documento senza annotazioni. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment)(Stream, string, string) | Aggiunge un allegato al documento senza annotazioni. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_1)(Stream) | Associa un flusso PDF per la modifica. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_2)(string) | Associa un file PDF per la modifica. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference)(int) | Modifica la preferenza di visualizzazione. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close)() | Chiude il documento aperto. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink)(Rectangle, string, int) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_1)(Rectangle, string, int, Color) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction)(string, Color, bool, bool, string, string, string) | Crea un segnalibro con l'azione specificata. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret)(int, Rectangle, Rectangle, string, string, Color) | Crea annotazioni con accento circonflesso. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink)(Rectangle, int, Color, Enum[]) | Crea un collegamento ad azioni personalizzate nel documento PDF. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_2)(Rectangle, string, string, int, string) | Crea annotazione file allegato. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment)(Rectangle, string, Stream, string, int, string) | Crea annotazione file allegato. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_3)(Rectangle, string, string, int, string, double) | Crea annotazione file allegato. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | Crea annotazione file allegato. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext)(Rectangle, string, int) | Crea annotazioni di testo libere nel documento PDF |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink)(string, Rectangle, int, Color) | Crea un collegamento a JavaScript nel documento PDF. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | Crea annotazione riga. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink)(Rectangle, int, int) | Crea un collegamento locale nel documento PDF. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_1)(Rectangle, int, int, Color) | Crea un collegamento locale nel documento PDF. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | Crea un collegamento locale nel documento PDF. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup)(Rectangle, string, int, int, Color) | Crea annotazioni di markup nel documento PDF. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie)(Rectangle, string, int) | Crea annotazioni filmato. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink)(Rectangle, string, int, int) | Crea un collegamento a un'altra pagina del documento PDF. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | Crea un collegamento a un'altra pagina del documento PDF. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | Crea un collegamento a un'altra pagina del documento PDF. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon)(LineInfo, int, Rectangle, string) | Crea annotazioni poligonali. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline)(LineInfo, int, Rectangle, string) | Crea annotazione polilinea. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup)(Rectangle, string, bool, int) | Crea annotazioni popup nel documento PDF. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp)(int, Rectangle, string, Color, Stream) | Crea un'annotazione del timbro di gomma. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_1)(int, Rectangle, string, Color, string) | Crea un'annotazione del timbro di gomma. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_2)(int, Rectangle, string, string, Color) | Crea un'annotazione del timbro di gomma. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound)(Rectangle, string, string, int, string) | Crea annotazioni sonore. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle)(Rectangle, string, Color, bool, int, int) | Crea annotazioni a cerchio quadrato. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext)(Rectangle, string, string, bool, string, int) | Crea annotazioni di testo nel documento PDF |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink)(Rectangle, string, int) | Crea un collegamento web nel documento PDF. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_1)(Rectangle, string, int, Color) | Crea un collegamento web nel documento PDF. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_2)(Rectangle, string, int, Color, Enum[]) | Crea un collegamento web nel documento PDF. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments)() | Elimina tutti gli allegati nel documento PDF. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage)() | Elimina tutte le immagini dal documento PDF. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage_1)(int, int[]) | Elimina le immagini specificate nella pagina specificata. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp)(int, int[]) | Elimina più timbri sulla pagina specificata in base agli indici dei timbri. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid)(int) | Elimina timbro per ID da tutte le pagine del documento. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid_1)(int, int) | Elimina il timbro sulla pagina specificata in base all'ID timbro. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids_1)(int[]) | Elimina i timbri con ID specificati da tutte le pagine del documento. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids)(int, int[]) | Elimina i timbri sulla pagina specificata in base a più ID timbro. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve)(LineInfo, int, Rectangle, string) | Crea annotazione curva. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink)() | Estrae la raccolta di istanze Link contenute nel documento PDF. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps)(int) | Restituisce l'array di timbri sulla pagina. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference)() | Restituisce la preferenza di visualizzazione. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid)(int, int) | Nasconde il timbro. Dopo essere stato nascosto, la visibilità del timbro può essere ripristinata con il metodo ShowStampById. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp)(int, int, double, double) | Modifica la posizione del timbro sulla pagina. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid)(int, int, double, double) | Modifica la posizione del timbro sulla pagina. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction)() | Rimuove l'azione aperta dal documento. Questa operazione è utile quando si concatenano più documenti che utilizzano l'azione esplicita "Vai a" all'avvio. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage)(int, int, string) | Sostituisce l'immagine specificata nella pagina specificata del documento PDF con un'altra immagine. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_2)(string, string) | Sostituisce il testo nel file PDF. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext)(string, int, string) | Sostituisce il testo nel file PDF nella pagina specificata. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_4)(string, string, int) | Sostituisce il testo nel file PDF e imposta la dimensione del carattere. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_3)(string, string, TextState) | Sostituisce il testo nel file PDF utilizzando specificato[`TextState`](../../aspose.pdf.text/textstate) oggetto. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_1)(string, int, string, TextState) | Sostituisce il testo nel file PDF nella pagina specificata.[`TextState`](../../aspose.pdf.text/textstate) l'oggetto (famiglia di caratteri, colore) può essere specificato per sostituire il testo. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Salva il documento PDF nel flusso specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Salva il documento PDF nel file specificato. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid)(int, int) | Mostra il timbro che è stato nascosto da HiddenStampById. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose) | Un tipo di evento del documento. Chiude un documento. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen) | Un tipo di evento del documento. Apre un documento. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted) | Un tipo di evento del documento. Esegui un'azione dopo la stampa. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved) | Un tipo di evento del documento. Esegui un'azione dopo il salvataggio. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint) | Un tipo di evento del documento. Esegui un'azione prima di stampare. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave) | Un tipo di evento del documento. Esegui un'azione prima di salvare. |

### Guarda anche

* class [SaveableFacade](../saveablefacade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
