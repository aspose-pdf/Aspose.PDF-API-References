---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: Classe per l'aggiungere timbri o background a file PDF.
type: docs
weight: 4570
url: /it/net/aspose.pdf.facades/pdffilestamp/
---
## Classe PdfFileStamp

Classe per aggiungere timbri (filigrana o sfondo) ai file PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | Costruttore della classe PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfFileStamp` sulla base del *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | Imposta il formato del file PDF. Il file risultante sarà salvato nel formato di file specificato. Se questa proprietà non è specificata, il file sarà salvato nel formato PDF predefinito senza conversione. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Mantiene la sicurezza se vero. (Questa funzionalità sarà implementata nelle prossime versioni). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Ottiene o imposta lo stile di numerazione delle pagine. Valori possibili: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Ottiene o imposta il flag di ottimizzazione. I flussi di risorse uguali nel file risultante vengono uniti in un oggetto PDF se questo flag è impostato. Questo consente di ridurre la dimensione del file risultante, ma può causare un'esecuzione più lenta e maggiori requisiti di memoria. Valore predefinito: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Ottiene l'altezza della prima pagina nel file sorgente. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Ottiene o imposta la rotazione del numero di pagina. La rotazione è in gradi. Il valore predefinito è 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Ottiene la larghezza della prima pagina nel file di input. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | ID del timbro del prossimo timbro aggiunto (inclusi intestazioni/piedi di pagina/numeri di pagina). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Ottiene o imposta il numero iniziale per la prima pagina nel file di input. Le pagine successive saranno numerate a partire da questo valore. Ad esempio, se StartingNumber è impostato su 100, le pagine del documento avranno i numeri 100, 101, 102... |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Aggiunge un piè di pagina alle pagine del documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Aggiunge un'immagine come piè di pagina della pagina. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Aggiunge un'immagine come piè di pagina alle pagine del documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Aggiunge un piè di pagina alle pagine del documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Aggiunge un'immagine come piè di pagina della pagina. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Aggiunge un'immagine come piè di pagina delle pagine. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Aggiunge un'intestazione alla pagina. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Aggiunge un'immagine come intestazione sulle pagine. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Aggiunge un'immagine come intestazione alle pagine del file. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Aggiunge un'intestazione alle pagine del file. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Aggiunge un'immagine in cima alla pagina. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Aggiunge un'immagine come intestazione sulle pagine. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Aggiunge il numero di pagina alla pagina. Il numero di pagina può contenere il segno # che sarà sostituito con il numero di pagina. Il numero di pagina è posizionato in fondo alla pagina centrato orizzontalmente. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Aggiunge il numero di pagina al file. Il testo del numero di pagina può contenere il segno # che sarà sostituito con il numero della pagina. Il numero di pagina è posizionato in fondo alla pagina centrato orizzontalmente. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Aggiunge il numero di pagina alle pagine. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Aggiunge il numero di pagina alle pagine. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Aggiunge il numero di pagina nella posizione specificata sulla pagina. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Aggiunge il numero di pagina nella posizione specificata sulla pagina. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Aggiunge il numero di pagina alle pagine del documento. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Aggiunge il numero di pagina alle pagine del documento. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Aggiunge un timbro al file. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza la facciata. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Chiude i file aperti e salva le modifiche. Attenzione. Se i flussi di input o output sono specificati, non vengono chiusi dal metodo Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
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

### Vedi Anche

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)