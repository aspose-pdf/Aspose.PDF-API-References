---
title: "Classe PdfFileStamp"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Facades.PdfFileStamp. Classe per aggiungere timbri, filigrane o sfondi ai file PDF"
type: docs
weight: 4690
url: /it/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

Classe per aggiungere timbri (filigrana o sfondo) ai file PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfFileStamp` basato sul *document*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | Imposta il formato del file PDF. Il file risultante verrà salvato nel formato specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facade del documento su cui sta lavorando. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Mantiene la sicurezza se vero. (Questa funzionalità sarà implementata nelle versioni successive). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Ottiene o imposta lo stile di numerazione delle pagine. Valori possibili: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Ottiene o imposta il flag di ottimizzazione. I flussi di risorse uguali nel file risultante vengono uniti in un unico oggetto PDF se questo flag è impostato. Ciò consente di ridurre la dimensione del file risultante ma può causare un'esecuzione più lenta e requisiti di memoria maggiori. Valore predefinito: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Ottiene l'altezza della prima page nel file di origine. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Ottiene o imposta la rotazione del numero di page. La rotazione è in gradi. Il valore predefinito è 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Ottiene la larghezza della prima page nel file di input. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | ID del timbro del prossimo timbro aggiunto (includendo page headers/hooters/page numbers). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Ottiene o imposta il numero iniziale per la prima page nel file di input. Le pagine successive saranno numerate a partire da questo valore. Ad esempio, se StartingNumber è impostato a 100, le pagine del document avranno i numeri 100, 101, 102... |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Aggiunge un piè di pagina alle pages del document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Aggiunge un'immagine come piè di pagina della page. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Aggiunge un'immagine come piè di pagina alle pages del document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Aggiunge un piè di pagina alle pages del document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Aggiunge un'immagine come piè di pagina della page. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Aggiunge un'immagine come piè di pagina delle pages. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Aggiunge un'intestazione alla page. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Aggiunge un'immagine come intestazione sulle pages. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Aggiunge un'immagine come intestazione alle pages del file. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Aggiunge un'intestazione alle pages del file. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Aggiunge un'immagine nella parte superiore della page. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Aggiunge un'immagine come intestazione sulle pages. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Aggiunge il numero di pagina alla pagina. Il numero di pagina può contenere il segno # che verrà sostituito con il numero di pagina. Il numero di pagina è posizionato nella parte inferiore della pagina, centrato orizzontalmente. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Aggiunge il numero di pagina al file. Il testo del numero di pagina può contenere il segno # che verrà sostituito con il numero della pagina. Il numero di pagina è posizionato nella parte inferiore della pagina, centrato orizzontalmente. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Aggiunge il numero di pagina alle pagine. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Aggiunge il numero di pagina alle pagine. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Aggiunge il numero di pagina nella posizione specificata sulla pagina. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Aggiunge il numero di pagina nella posizione specificata sulla pagina. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Aggiunge il numero di pagina alle pagine del documento. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Aggiunge il numero di pagina alle pagine del documento. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Aggiunge il timbro al file. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza il facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza il facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza il facade. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Chiude i file aperti e salva le modifiche. Attenzione. Se i flussi di input o output sono specificati, non vengono chiusi dal metodo Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | Salva il documento nello stream specificato. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | Salva il risultato nel file specificato. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | Posizione in basso a sinistra. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | Posizione in basso al centro. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | Posizione in basso a destra. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | Posizione a sinistra. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | Posizione a destra. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | Posizione in alto a sinistra. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | Posizione in alto al centro. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | Posizione in alto a destra. |

### Vedi anche

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


