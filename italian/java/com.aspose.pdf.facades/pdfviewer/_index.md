---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per visualizzare o stampare un pdf."
type: docs
weight: 610
url: /it/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

Rappresenta una classe per visualizzare o stampare un pdf.

## Campi

| Campo | Descrizione |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | Aggiunge/rimuove l'iscrizione all'evento di stampa dell'ultima pagina. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Aggiunge/rimuove l'iscrizione all'evento di stampa dell'ultima pagina. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfViewer](#PdfViewer--) | Inizializza un nuovo oggetto {@code PdfViewer}. |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | Inizializza un nuovo oggetto {@code PdfViewer}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Inizializza la facciata. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Inizializza la facciata. |
| [bindPdf](#bindPdf-java.lang.String-) | Inizializza la facciata. |
| [close](#close--) | Chiude il file PDF corrente. |
| [closePdfFile](#closePdfFile--) | Chiude il file PDF corrente. |
| [decodeAllPages](#decodeAllPages--) | Ottieni le pagine del file PDF corrente. |
| [decodePage](#decodePage-int-) | Decodifica una pagina di un file PDF. |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Decodifica la pagina in BufferedImage |
| [dispose](#dispose--) | Rilascia le risorse della facciata. Questo metodo è obsoleto, usa close() al suo posto. |
| [getAutoResize](#getAutoResize--) | Imposta un valore booleano che indica se il file deve essere stampato con dimensione ottimizzata. |
| [getAutoRotate](#getAutoRotate--) | Restituisce un valore bool che indica se il file deve essere stampato con rotazione automatica |
| [getAutoRotateMode](#getAutoRotateMode--) | Restituisce un valore AutoRotateMode che indica la direzione della rotazione |
| [getCoordinateType](#getCoordinateType--) | Ottiene il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [getCopiesPrinted](#getCopiesPrinted--) | Restituisce il numero di copie stampate |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Restituisce le impostazioni predefinite della pagina. |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | Restituisce le impostazioni predefinite della stampante. |
| [getFormPresentationMode](#getFormPresentationMode--) | Ottiene la modalità di presentazione del modulo. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Restituisce un valore che indica l'allineamento orizzontale |
| [getPageCount](#getPageCount--) | Restituisce il conteggio delle pagine del file Pdf corrente. |
| [getPassword](#getPassword--) | Restituisce la password del documento di input. |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> Restituisce o imposta un valore bool che indica se la pagina viene stampata in scala di grigi. Per impostazione predefinita è false. </p> <hr> Il valore predefinito è false. |
| [getPrintAsImage](#getPrintAsImage--) | <p> Restituisce una modalità per PdfViewer per stampare come immagine. </p> |
| [getPrinterJobName](#getPrinterJobName--) | Restituisce il nome del documento nella coda di stampa quando il documento è stampato. Il valore predefinito è il nome del file. |
| [getPrintPageDialog](#getPrintPageDialog--) | Restituisce un valore bool che indica se generare la finestra di dialogo del numero di pagina durante la stampa. |
| [getPrintStatus](#getPrintStatus--) | Restituisce il risultato del lavoro di stampa. Se ha avuto successo restituisce null; altrimenti, un oggetto eccezione. |
| [getRenderingOptions](#getRenderingOptions--) | Ottiene le opzioni di rendering. |
| [getResolution](#getResolution--) | Restituisce o imposta la risoluzione durante la visualizzazione e la stampa. Maggiore è la risoluzione, più lenta è la velocità. Il valore predefinito è 150. Questa proprietà modifica la risoluzione dell'immagine nei flussi di conversione da pagina a immagine: quando {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) è impostato su {@code }, o quando viene chiamato il metodo {@link #decodePage(int)} o {@link #decodeAllPages}. Per impostare una risoluzione della stampante per la stampa diretta su una stampante, utilizzare la proprietà {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) nella classe {@code PageSettings}. |
| [getScaleFactor](#getScaleFactor--) | Restituisce un valore a virgola mobile che indica il fattore di scala. Il valore predefinito è 1.0. |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | Restituisce l'utilizzo della conversione della pagina pdf in un file png intermedio durante la stampa in modalità file. Usalo quando la dimensione del file di output è importante. |
| [getVerticalAlignment](#getVerticalAlignment--) | Restituisce un valore che indica l'allineamento verticale |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Questo metodo è deprecato. Restituisce il flag che controlla la visibilità delle aree nascoste nella pagina. |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> Apre un flusso di file Pdf. Ma non decodifica effettivamente le pagine del file Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> Apre un file Pdf, ma non decodifica effettivamente le pagine del file Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> Stampa il documento Pdf utilizzando la stampante predefinita. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Stampa il documento Pdf con le impostazioni della stampante. La dimensione della pagina di output si adatterà alla dimensione della prima pagina del documento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Stampa il documento Pdf con impostazioni. Se le dimensioni del documento non sono compatibili con le dimensioni della pagina, pdf.kit le estenderà per adattarle alla pagina. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //stampa il file con dimensioni regolate viewer.setAutoRotate ( true); //stampa il file con rotazione regolata viewer.setPrintPageDialog ( false);//non mostrare la finestra di dialogo del numero di pagina durante la stampa PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> Apre e stampa un flusso Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //stampa il file con dimensioni regolate viewer.setAutoRotate ( true); //stampa il file con rotazione regolata viewer.printPageDialog=false;//non mostrare la finestra di dialogo del numero di pagina durante la stampa viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente OpenPdfFile(). |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Apre e stampa un flusso Pdf di grandi dimensioni con le impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // stampa il file con dimensioni regolate viewer.setAutoRotate(true); // stampa il file con rotazione regolata viewer.setPrintPageDialog(false); // non mostrare la finestra di dialogo del numero di pagina durante // la stampa PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente OpenPdfFile(). |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Apre e stampa un flusso Pdf di grandi dimensioni con le impostazioni della pagina e della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //stampa il file con dimensioni regolate viewer.setAutoRotate ( true); //stampa il file con rotazione regolata viewer.setPrintPageDialog ( false);//non mostrare la finestra di dialogo del numero di pagina durante la stampa PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente OpenPdfFile(). |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> Apre e stampa un file Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // stampa il file con dimensioni regolate viewer.setAutoRotate(true); // stampa il file con rotazione regolata viewer.setPrintPageDialog(false);// non mostrare la finestra di dialogo del numero di pagina durante // la stampa viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Apre e stampa un file PDF di grandi dimensioni con le impostazioni della stampante specificate. Se il tuo file PDF ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //stampa il file con dimensione regolata viewer.setAutoRotate ( true); //stampa il file con rotazione regolata viewer.setPrintPageDialog ( false);//non mostrare la finestra di dialogo del numero di pagina durante la stampa PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente OpenPdfFile(). |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Apre e stampa un file PDF di grandi dimensioni con le impostazioni della pagina e della stampante specificate. Se il tuo file PDF ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // stampa il file con dimensione regolata viewer.setAutoRotate(true); // stampa il file con rotazione regolata viewer.setPrintPageDialog(false); // non mostrare la finestra di dialogo del numero di pagina durante // la stampa PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente OpenPdfFile(). |
| [save](#save-java.io.InputStream-) | Salva il documento PDF risultante nello stream. |
| [save](#save-java.lang.String-) | Salva il documento PDF risultante su file. |
| [setAutoResize](#setAutoResize-boolean-) | Imposta un valore booleano che indica se il file deve essere stampato con dimensione ottimizzata. |
| [setAutoRotate](#setAutoRotate-boolean-) | Imposta un valore booleano che indica se il file deve essere stampato con rotazione automatica |
| [setAutoRotateMode](#setAutoRotateMode-int-) | Imposta un valore AutoRotateMode che indica la direzione della rotazione |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Imposta il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Imposta la modalità di presentazione del modulo. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Imposta un valore che indica l'allineamento orizzontale |
| [setPassword](#setPassword-java.lang.String-) | Imposta la password del documento di input. |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> Restituisce o imposta un valore bool che indica se la pagina viene stampata in scala di grigi. Per impostazione predefinita è false. </p> <hr> Il valore predefinito è false. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> Imposta una modalità per PdfViewer per stampare come immagine. </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | Imposta il nome del documento nella coda della stampante quando il documento viene stampato. Il valore predefinito è il nome del file. |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | Imposta un valore booleano che indica se produrre la finestra di dialogo del numero di pagina durante la stampa. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Imposta le opzioni di rendering. |
| [setResolution](#setResolution-int-) | Imposta la risoluzione durante la visualizzazione e la stampa. Maggiore è la risoluzione, più lenta è la velocità. Il valore predefinito è 150. Questa proprietà modifica la risoluzione dell'immagine nei flussi di conversione da pagina a immagine: quando {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) è impostato a {@code }, o quando viene chiamato il metodo {@link #decodePage(int)} o {@link #decodeAllPages}. Per impostare una risoluzione della stampante per la stampa diretta su stampante, utilizzare la proprietà {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) nella classe {@code PageSettings}. |
| [setScaleFactor](#setScaleFactor-float-) | Imposta un valore a virgola mobile che indica il fattore di scala. Il valore predefinito è 1.0. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Obsoleto. |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | Imposta l'utilizzo della conversione della pagina PDF in un file PNG intermedio durante la stampa in modalità file. Usalo quando la dimensione del file di output è importante. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Imposta un valore che indica l'allineamento verticale |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

Aggiunge/rimuove l'iscrizione all'evento di stampa dell'ultima pagina.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

Aggiunge/rimuove l'iscrizione all'evento di stampa dell'ultima pagina.

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

Inizializza un nuovo oggetto {@code PdfViewer}.

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
Inizializza un nuovo oggetto {@code PdfViewer}.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Inizializza la facciata.

### bindPdf {#bindPdf-java.io.InputStream-}
Inizializza la facciata.

### bindPdf {#bindPdf-java.lang.String-}
Inizializza la facciata.

### close {#close--}
```
public void close()
```

Chiude il file PDF corrente.

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

Chiude il file PDF corrente.

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

Ottieni le pagine del file PDF corrente.

**Returns:**
restituisce l'array di immagini delle pagine PDF.

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

Decodifica una pagina di un file PDF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Il numero di pagina di un file PDF che deve essere compreso tra 1 e PageCount. |

**Returns:**
restituisce l'immagine della pagina PDF.

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
Decodifica la pagina in BufferedImage

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Rilascia le risorse della facciata. Questo metodo è obsoleto, usa close() al suo posto.

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

Imposta un valore booleano che indica se il file deve essere stampato con dimensione ottimizzata.

**Returns:**
valore booleano: se false stampa la pagina senza scalatura. Se true stampa la pagina con scalatura per adattarla all'area stampabile.

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

Restituisce un valore bool che indica se il file deve essere stampato con rotazione automatica

**Returns:**
valore booleano

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

Restituisce un valore AutoRotateMode che indica la direzione della rotazione

**Returns:**
Elemento AutoRotateMode @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Ottiene il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita.

**Returns:**
Elemento PageCoordinateType @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

Restituisce il numero di copie stampate

**Returns:**
valore int

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Restituisce le impostazioni predefinite della pagina.

**Returns:**
Oggetto delle impostazioni della pagina.

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

Restituisce le impostazioni predefinite della stampante.

**Returns:**
Oggetto delle impostazioni della pagina.

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Ottiene la modalità di presentazione del modulo.

**Returns:**
FormPresentationMode elemento @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Restituisce un valore che indica l'allineamento orizzontale

**Returns:**
Elemento HorizontalAlignment @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Restituisce il conteggio delle pagine del file Pdf corrente.

**Returns:**
restituisce il conteggio delle pagine.

### getPassword {#getPassword--}
```
public String getPassword()
```

Restituisce la password del documento di input.

**Returns:**
valore String

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> Restituisce o imposta un valore bool che indica se la pagina viene stampata in scala di grigi. Per impostazione predefinita è false. </p> <hr> Il valore predefinito è false.

**Returns:**
valore booleano

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> Restituisce una modalità per PdfViewer per stampare come immagine. </p>

**Returns:**
valore booleano <hr> Se true stampa sempre come immagine (genera l'immagine che viene stampata) Se false stampa direttamente sul dispositivo se tutte le funzionalità sono supportate. Nel caso in cui il documento contenga funzionalità non supportate, il sistema può decidere automaticamente di stampare come immagine. Il valore predefinito è false.

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

Restituisce il nome del documento nella coda di stampa quando il documento è stampato. Il valore predefinito è il nome del file.

**Returns:**
valore String

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

Restituisce un valore bool che indica se generare la finestra di dialogo del numero di pagina durante la stampa.

**Returns:**
valore booleano

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

Restituisce il risultato del lavoro di stampa. Se ha avuto successo restituisce null; altrimenti, un oggetto eccezione.

**Returns:**
oggetto eccezione o null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Ottiene le opzioni di rendering.

**Returns:**
oggetto RenderingOptions

### getResolution {#getResolution--}
```
public int getResolution()
```

Restituisce o imposta la risoluzione durante la visualizzazione e la stampa. Maggiore è la risoluzione, più lenta è la velocità. Il valore predefinito è 150. Questa proprietà modifica la risoluzione dell'immagine nei flussi di conversione da pagina a immagine: quando {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) è impostato su {@code }, o quando viene chiamato il metodo {@link #decodePage(int)} o {@link #decodeAllPages}. Per impostare una risoluzione della stampante per la stampa diretta su una stampante, utilizzare la proprietà {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) nella classe {@code PageSettings}.

**Returns:**
valore int

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

Restituisce un valore a virgola mobile che indica il fattore di scala. Il valore predefinito è 1.0.

**Returns:**
valore a virgola mobile.

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

Restituisce l'utilizzo della conversione della pagina pdf in un file png intermedio durante la stampa in modalità file. Usalo quando la dimensione del file di output è importante.

**Returns:**
valore booleano.

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Restituisce un valore che indica l'allineamento verticale

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Questo metodo è deprecato. Restituisce il flag che controlla la visibilità delle aree nascoste nella pagina.

**Returns:**
valore booleano

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> Apre un flusso di file Pdf. Ma non decodifica effettivamente le pagine del file Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\test.pdf"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> Apre un file Pdf, ma non decodifica effettivamente le pagine del file Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> Stampa il documento Pdf usando la stampante predefinita. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Stampa il documento Pdf con le impostazioni della stampante. La dimensione della pagina di output si adatterà alla dimensione della prima pagina del documento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Stampa il documento Pdf con le impostazioni. Se la dimensione del documento non è compatibile con la dimensione della pagina, pdf.kit la estenderà per adattarla alla pagina. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> Apre e stampa un grande flusso Pdf. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Questo metodo ha integrato l'apertura e la stampa del file e non è necessario chiamare esplicitamente OpenPdfFile().

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Apre e stampa un grande flusso Pdf con le impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Questo metodo ha integrato l'apertura e la stampa del file e non è necessario chiamare esplicitamente OpenPdfFile().

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Apre e stampa un grande flusso Pdf con le impostazioni di pagina e di stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente OpenPdfFile().

### printLargePdf {#printLargePdf-java.lang.String-}
<p> Apre e stampa un grande file Pdf. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\test.pdf"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Apre e stampa un grande file Pdf con le impostazioni di stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente OpenPdfFile().

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Apre e stampa un grande file Pdf con le impostazioni di pagina e di stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente OpenPdfFile().

### save {#save-java.io.InputStream-}
Salva il documento PDF risultante nello stream.

### save {#save-java.lang.String-}
Salva il documento PDF risultante su file.

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

Imposta un valore booleano che indica se il file deve essere stampato con dimensione ottimizzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano: se false stampa la pagina senza scalatura. Se true stampa la pagina con scalatura per adattarla all'area stampabile. |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

Imposta un valore booleano che indica se il file deve essere stampato con rotazione automatica

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

Imposta un valore AutoRotateMode che indica la direzione della rotazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento AutoRotateMode @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Imposta il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Imposta la modalità di presentazione del modulo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | FormPresentationMode elemento |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Imposta un valore che indica l'allineamento orizzontale

### setPassword {#setPassword-java.lang.String-}
Imposta la password del documento di input.

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> Restituisce o imposta un valore bool che indica se la pagina viene stampata in scala di grigi. Per impostazione predefinita è false. </p> <hr> Il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> Imposta una modalità per PdfViewer per stampare come immagine. </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano <hr> Se true stampa sempre come immagine (genera l'immagine che viene stampata) Se false stampa direttamente sul dispositivo se tutte le funzionalità sono supportate. Nel caso in cui il documento contenga funzionalità non supportate, il sistema può decidere automaticamente di stampare come immagine. Il valore predefinito è false. |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
Imposta il nome del documento nella coda della stampante quando il documento viene stampato. Il valore predefinito è il nome del file.

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

Imposta un valore booleano che indica se produrre la finestra di dialogo del numero di pagina durante la stampa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Imposta le opzioni di rendering.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Imposta la risoluzione durante la visualizzazione e la stampa. Maggiore è la risoluzione, più lenta è la velocità. Il valore predefinito è 150. Questa proprietà modifica la risoluzione dell'immagine nei flussi di conversione da pagina a immagine: quando {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) è impostato a {@code }, o quando viene chiamato il metodo {@link #decodePage(int)} o {@link #decodeAllPages}. Per impostare una risoluzione della stampante per la stampa diretta su stampante, utilizzare la proprietà {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) nella classe {@code PageSettings}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

Imposta un valore a virgola mobile che indica il fattore di scala. Il valore predefinito è 1.0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore a virgola mobile. |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Obsoleto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

Imposta l'utilizzo della conversione della pagina PDF in un file PNG intermedio durante la stampa in modalità file. Usalo quando la dimensione del file di output è importante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano. |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Imposta un valore che indica l'allineamento verticale
