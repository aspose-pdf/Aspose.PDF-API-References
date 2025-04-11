---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfViewer. Rappresenta una classe per visualizzare o stampare un pdf
type: docs
weight: 4630
url: /it/net/aspose.pdf.facades/pdfviewer/
---
## Classe PdfViewer

Rappresenta una classe per visualizzare o stampare un pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | Inizializza un nuovo oggetto `PdfViewer`. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfViewer`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Ottiene o imposta un valore bool che indica se il file deve essere stampato con dimensioni ottimizzate. Se falso, stampa la pagina senza ridimensionamento. Se vero, stampa la pagina con ridimensionamento per adattarsi all'area stampabile. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Ottiene o imposta un valore bool che indica se il file deve essere stampato con rotazione automatica. |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Ottiene o imposta un valore AutoRotateMode che indica la direzione di rotazione. |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (Media/Crop boxes). Il valore CropBox è utilizzato per impostazione predefinita. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Ottiene o imposta la modalità di presentazione del modulo. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Ottiene o imposta un valore che indica l'allineamento orizzontale. |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Ottiene il conteggio delle pagine del file Pdf corrente. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Ottiene o imposta la password del documento di input. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Ottiene o imposta un valore bool che indica se la pagina viene stampata in scala di grigi. Per impostazione predefinita è falso. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | Imposta o ottiene una modalità per PdfViewer per stampare come immagine. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Ottiene o imposta il nome del documento nella coda della stampante quando il documento viene stampato. Il valore predefinito è il nome del file. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Ottiene o imposta un valore bool che indica se produrre il dialogo del numero di pagina durante la stampa. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Ottiene il risultato del lavoro di stampa. Se ha successo, allora null; altrimenti, oggetto eccezione. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | Ottiene o imposta le opzioni di rendering. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Ottiene o imposta la risoluzione durante la visualizzazione e la stampa. Maggiore è la risoluzione, più lenta è la velocità. Il valore predefinito è 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Ottiene o imposta un valore a virgola mobile che indica il fattore di scala. Il valore predefinito è 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Ottiene/imposta l'uso della conversione della pagina pdf in un file png intermedio durante la stampa in modalità file. Usalo quando la dimensione del file di output è importante. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Ottiene o imposta un valore che indica l'allineamento verticale. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Inizializza la facciata. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Inizializza la facciata. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Inizializza la facciata. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Chiude la facciata. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Ottiene le pagine del file pdf corrente. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Decodifica una pagina di un file Pdf. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Smaltisce le risorse della facciata. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Ottiene le impostazioni di pagina predefinite. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Ottiene le impostazioni della stampante predefinite. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Stampa il documento Pdf utilizzando la stampante predefinita. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Stampa il documento Pdf con le impostazioni della stampante. La dimensione della pagina di output si adatterà alla dimensione della prima pagina del documento. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Stampa il documento Pdf con impostazioni. Se la dimensione del documento non corrisponde alla dimensione della pagina, verrà estesa per adattarsi alla dimensione della pagina. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Stampa il documento Pdf con una finestra di dialogo di configurazione. Scegli una stampante utilizzando la finestra di dialogo. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Apre e stampa un grande flusso Pdf. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere prestazioni migliori. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Apre e stampa un grande file Pdf. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere prestazioni migliori. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Apre e stampa un grande flusso Pdf con impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere prestazioni migliori. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Apre e stampa un grande file Pdf con impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere prestazioni migliori. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Apre e stampa un grande flusso Pdf con impostazioni di pagina e impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere prestazioni migliori. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Apre e stampa un grande file Pdf con impostazioni di pagina e impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere prestazioni migliori. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Salva il documento PDF risultante nello stream. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Salva il documento PDF risultante nel file. |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Si verifica prima dell'inizio della stampa e consente di fornire gestori di stampa personalizzati invece di quello predefinito. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | Si verifica quando la stampa di una pagina termina nel PdfViewer. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Aggiunge/rimuove l'iscrizione all'evento di stampa dell'ultima pagina. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Aggiunge/rimuove l'iscrizione all'evento di stampa dell'ultima pagina. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | Si verifica prima che una pagina inizi a stampare. |

### Vedi anche

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)