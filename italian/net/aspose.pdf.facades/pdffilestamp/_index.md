---
title: PdfFileStamp
second_title: Aspose.PDF per .NET API Reference
description: Classe per laggiunta di timbri filigrana o sfondo ai file PDF.
type: docs
weight: 2580
url: /it/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

Classe per l'aggiunta di timbri (filigrana o sfondo) ai file PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileStamp](pdffilestamp#constructor)() | Costruttore del PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. |
| [PdfFileStamp](pdffilestamp#constructor_1)(Document) | Inizializza nuovo[`PdfFileStamp`](../pdffilestamp) oggetto sulla base del*document* . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffilestamp/attachmentname) { get; set; } | Ottiene o imposta il nome dell'allegato quando il risultato dell'operazione viene archiviato negli oggetti HttpResponse come allegato. |
| [ContentDisposition](../../aspose.pdf.facades/pdffilestamp/contentdisposition) { get; set; } | Ottiene o imposta la modalità di archiviazione del contenuto quando il risultato dell'operazione viene archiviato nell'oggetto HttpResponse. Valore possibile: inline/allegato. Predefinito: inline. |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto) { set; } | Imposta il formato del file PDF. Il file dei risultati verrà salvato nel formato file specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity) { get; set; } | Mantiene la sicurezza se true. (Questa funzione sarà implementata nelle prossime versioni). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle) { get; set; } | Ottiene o imposta lo stile di numerazione delle pagine. Valori possibili: NumeralsArabo, NumeralsRomanMaiuscolo, NumeralsRoman Minuscolo, LettersMaiuscole, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize) { get; set; } | Ottiene o imposta il flag di ottimizzazione. Flussi di risorse uguali nel file risultante vengono uniti in un oggetto PDF se questo flag è impostato. Ciò consente di ridurre la dimensione del file risultante ma può causare un'esecuzione più lenta e maggiori requisiti di memoria. Valore predefinito: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight) { get; } | Ottiene l'altezza della prima pagina nel file sorgente. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation) { get; set; } | Ottiene o imposta la rotazione del numero di pagina. La rotazione è in gradi. Il valore predefinito è 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth) { get; } | Ottiene la larghezza della prima pagina nel file di input. |
| [Response](../../aspose.pdf.facades/pdffilestamp/response) { get; set; } | Ottiene o imposta l'oggetto Response in cui verrà archiviato il risultato dell'operazione. |
| [SaveOptions](../../aspose.pdf.facades/pdffilestamp/saveoptions) { get; set; } | Ottiene o imposta le opzioni di salvataggio quando il risultato viene archiviato come HttpResponse. Valore predefinito: PdfSaveOptions. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid) { get; set; } | ID timbro del successivo timbro aggiunto (incluse intestazioni di pagina/sirena/numeri di pagina). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber) { get; set; } | Ottiene o imposta il numero iniziale per la prima pagina nel file di input. Le pagine successive verranno numerate a partire da questo valore. Ad esempio, se StartingNumber è impostato su 100, le pagine del documento avranno i numeri 100, 101, 102... |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter)(FormattedText, float) | Aggiunge piè di pagina alle pagine del documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_2)(Stream, float) | Aggiunge un'immagine come piè di pagina della pagina. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_4)(string, float) | Aggiunge un'immagine come piè di pagina alle pagine del documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_1)(FormattedText, float, float, float) | Aggiunge piè di pagina alle pagine del documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_3)(Stream, float, float, float) | Aggiunge un'immagine come piè di pagina della pagina. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_5)(string, float, float, float) | Aggiunge immagine come piè di pagina delle pagine. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader)(FormattedText, float) | Aggiunge l'intestazione alla pagina. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_2)(Stream, float) | Aggiunge l'immagine come intestazione alle pagine. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_4)(string, float) | Aggiunge l'immagine come intestazione alle pagine del file. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_1)(FormattedText, float, float, float) | Aggiunge intestazione alle pagine del file. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_3)(Stream, float, float, float) | Aggiunge un'immagine nella parte superiore della pagina. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_5)(string, float, float, float) | Aggiunge l'immagine come intestazione alle pagine. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber)(FormattedText) | Aggiunge il numero di pagina alla pagina. Il numero di pagina può contenere il simbolo # che verrà sostituito con il numero di pagina. Il numero di pagina è posizionato nella parte inferiore della pagina centrato orizzontalmente. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_4)(string) | Aggiungi il numero di pagina al file. Il testo del numero di pagina può contenere il segno # che verrà sostituito con il numero della pagina. Il numero di pagina è posizionato nella parte inferiore della pagina centrato orizzontalmente. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_1)(FormattedText, int) | Aggiunge il numero di pagina alle pagine. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_5)(string, int) | Aggiunge il numero di pagina alle pagine. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_3)(FormattedText, float, float) | Aggiunge il numero di pagina nella posizione specificata nella pagina. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_7)(string, float, float) | Aggiunge il numero di pagina nella posizione specificata nella pagina. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_2)(FormattedText, int, float, float, float, float) | Aggiunge il numero di pagina alle pagine del documento. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_6)(string, int, float, float, float, float) | Aggiunge il numero di pagina alle pagine del documento. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp)(Stamp) | Aggiunge il timbro al file. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inizializza la facciata. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close)() | Chiude i file aperti e salva le modifiche. Avviso. Se vengono specificati flussi di input o output, non vengono chiusi dal metodo Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save)(Stream) | Salva il documento nel flusso specificato. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save_1)(string) | Salva il risultato nel file specificato. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft) | Posizione in basso a sinistra. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle) | Posizione centrale inferiore. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright) | Posizione in basso a destra. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft) | Posizione sinistra. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright) | Posizione corretta. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft) | Posizione superiore sinistra. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle) | Posizione centrale superiore. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright) | Posizione in alto a destra. |

### Guarda anche

* class [SaveableFacade](../saveablefacade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
