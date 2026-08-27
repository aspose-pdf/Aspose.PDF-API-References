---
title: "PdfFileStamp"
linktitle: "PdfFileStamp"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe per aggiungere timbri (filigrana o sfondo) ai file PDF."
type: docs
weight: 540
url: /it/java/com.aspose.pdf.facades/pdffilestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStamp, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStamp, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStamp

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStamp extends SaveableFacade implements IPdfFileStamp
```

Classe per aggiungere timbri (filigrana o sfondo) ai file PDF.

## Campi

| Campo | Descrizione |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Posizione in basso a sinistra. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Posizione in basso al centro. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Posizione in basso a destra. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Posizione a sinistra. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Posizione a destra. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Posizione in alto a sinistra. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Posizione al centro superiore. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Posizione in alto a destra. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFileStamp](#PdfFileStamp--) | <p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-) | <p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-) | <p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-) | <p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-) | <p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.lang.String-java.lang.String-) | <p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.lang.String-java.lang.String-boolean-) | <p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> Aggiunge un piè di pagina alle pagine del documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Aggiunge un piè di pagina alle pagine del documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> Aggiunge un'immagine come piè di pagina della pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> Aggiunge un'immagine come piè di pagina della pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> Aggiunge un'immagine come piè di pagina alle pagine del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Aggiunge l'immagine come piè di pagina delle pagine. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> Aggiunge un'intestazione alla pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Aggiunge un'intestazione alle pagine del file. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> Aggiunge un'immagine come intestazione sulle pagine. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> Aggiunge un'immagine nella parte superiore della pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); IjnputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> Aggiunge un'immagine come intestazione alle pagine del file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InpetuStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> Aggiunge un'immagine come intestazione sulle pagine. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> Aggiunge il numero di pagina alla pagina. Il numero di pagina può contenere il segno # che verrà sostituito con il numero di pagina. Il numero di pagina è posizionato nella parte inferiore della pagina, centrato orizzontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> Aggiunge il numero di pagina nella posizione specificata sulla pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> Aggiunge il numero di pagina alle pagine. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> Aggiunge il numero di pagina alle pagine del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> Aggiunge il numero di pagina al file. Il testo del numero di pagina può contenere il segno # che verrà sostituito con il numero della pagina. Il numero di pagina è posizionato nella parte inferiore della pagina, centrato orizzontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> Aggiunge il numero di pagina nella posizione specificata sulla pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> Aggiunge il numero di pagina alle pagine. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> Aggiunge il numero di pagina alle pagine del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> Aggiunge il timbro al file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity(0.8f); stamp.isBackground(true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> Chiude i file aperti e salva le modifiche. Attenzione. Se i flussi di input o output sono specificati non vengono chiusi dal metodo Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | Obsoleto. |
| [getAttachmentName](#getAttachmentName--) | Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [getContentDisposition](#getContentDisposition--) | Ottiene come il contenuto verrà memorizzato quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline. |
| [getInputFile](#getInputFile--) | Ottiene il nome e il percorso del file di input. |
| [getInputStream](#getInputStream--) | Ottiene lo stream di input. Obsolete("Use bindPdf(inputFile) method for facade initialization.") |
| [getKeepSecurity](#getKeepSecurity--) | Mantiene la sicurezza se vero. (Questa funzionalità sarà implementata nelle prossime versioni). |
| [getNumberingStyle](#getNumberingStyle--) | Ottiene o imposta lo stile di numerazione delle pagine. Valori possibili: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [getOptimizeSize](#getOptimizeSize--) | Ottiene o imposta il flag di ottimizzazione. |
| [getOutputFile](#getOutputFile--) | Ottiene il nome e il percorso del file di output. Obsolete("Use Save(outputFile) method for getting facade results.") |
| [getOutputStream](#getOutputStream--) | Ottiene lo stream di output. |
| [getPageHeight](#getPageHeight--) | <p> Ottiene l'altezza della prima pagina nel file di origine. </p> |
| [getPageNumberRotation](#getPageNumberRotation--) | Ottiene la rotazione del numero di pagina. La rotazione è in gradi. Il valore predefinito è 0. |
| [getPageWidth](#getPageWidth--) | <p> Ottiene la larghezza della prima pagina nel file di input. </p> |
| [getSaveOptions](#getSaveOptions--) | Ottiene le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions. |
| [getStampId](#getStampId--) | ID del timbro del prossimo timbro aggiunto (inclusi intestazioni/piedi di pagina/numeri di pagina). |
| [getStartingNumber](#getStartingNumber--) | Ottiene o imposta il numero iniziale per la prima pagina nel file di input. Le pagine successive saranno numerate a partire da questo valore. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Imposta il formato del file PDF. Il file risultante verrà salvato nel formato specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione. |
| [setInputFile](#setInputFile-java.lang.String-) | Imposta il nome e il percorso del file di input. Obsolete("Use bindPdf(inputFile) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Imposta lo stream di input. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Mantiene la sicurezza se vero. (Questa funzionalità sarà implementata nelle prossime versioni). |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Ottiene o imposta lo stile di numerazione delle pagine. Valori possibili: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Ottiene o imposta il flag di ottimizzazione. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Imposta il nome e il percorso del file di output. Obsolete("Use Save(outputFile) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Imposta o imposta lo stream di output. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Imposta la rotazione del numero di pagina. La rotazione è in gradi. Il valore predefinito è 0. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions. |
| [setStampId](#setStampId-int-) | ID del timbro del prossimo timbro aggiunto (inclusi intestazioni/piedi di pagina/numeri di pagina). |
| [setStartingNumber](#setStartingNumber-int-) | <p> Imposta il numero iniziale per la prima pagina nel file di input. Le pagine successive saranno numerate a partire da questo valore. Per esempio, se StartingNumber è impostato a 100, le pagine del documento avranno i numeri 100, 101, 102... </p> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

Posizione in basso a sinistra.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

Posizione in basso al centro.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

Posizione in basso a destra.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

Posizione a sinistra.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

Posizione a destra.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

Posizione in alto a sinistra.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

Posizione al centro superiore.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

Posizione in alto a destra.

### PdfFileStamp {#PdfFileStamp--}
```
public PdfFileStamp()
```

<p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-}
<p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-}
<p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-}
<p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-}
<p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.lang.String-java.lang.String-}
<p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.lang.String-java.lang.String-boolean-}
<p> Costruttore di PdfFileStamp. Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> Aggiunge un piè di pagina alle pagine del documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Aggiunge un piè di pagina alle pagine del documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> Aggiunge un'immagine come piè di pagina della pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> Aggiunge un'immagine come piè di pagina della pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> Aggiunge un'immagine come piè di pagina alle pagine del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
Aggiunge l'immagine come piè di pagina delle pagine.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> Aggiunge un'intestazione alla pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Aggiunge un'intestazione alle pagine del file. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> Aggiunge un'immagine come intestazione sulle pagine. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> Aggiunge un'immagine nella parte superiore della pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); IjnputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> Aggiunge un'immagine come intestazione alle pagine del file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InpetuStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> Aggiunge un'immagine come intestazione sulle pagine. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> Aggiunge il numero di pagina alla pagina. Il numero di pagina può contenere il segno # che verrà sostituito con il numero di pagina. Il numero di pagina è posizionato nella parte inferiore della pagina, centrato orizzontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> Aggiunge il numero di pagina nella posizione specificata sulla pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> Aggiunge il numero di pagina alle pagine. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> Aggiunge il numero di pagina alle pagine del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> Aggiunge il numero di pagina al file. Il testo del numero di pagina può contenere il segno # che verrà sostituito con il numero della pagina. Il numero di pagina è posizionato nella parte inferiore della pagina, centrato orizzontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> Aggiunge il numero di pagina nella posizione specificata sulla pagina. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> Aggiunge il numero di pagina alle pagine. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> Aggiunge il numero di pagina alle pagine del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> Aggiunge il timbro al file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity(0.8f); stamp.isBackground(true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> Chiude i file aperti e salva le modifiche. Attenzione. Se i flussi di input o output sono specificati non vengono chiusi dal metodo Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsoleto.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

**Returns:**
valore String

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Ottiene come il contenuto verrà memorizzato quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline.

**Returns:**
Elemento ContentDisposition @see com.aspose.pdf.ContentDisposition

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

Ottiene il nome e il percorso del file di input.

**Returns:**
valore String

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Ottiene lo stream di input. Obsolete("Use bindPdf(inputFile) method for facade initialization.")

**Returns:**
Oggetto InputStream

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

Mantiene la sicurezza se vero. (Questa funzionalità sarà implementata nelle prossime versioni).

**Returns:**
valore booleano

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Ottiene o imposta lo stile di numerazione delle pagine. Valori possibili: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase

**Returns:**
Elemento NumberingStyle @see NumberingStyle

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Ottiene o imposta il flag di ottimizzazione.

**Returns:**
valore booleano

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Ottiene il nome e il percorso del file di output. Obsolete("Use Save(outputFile) method for getting facade results.")

**Returns:**
valore String

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Ottiene lo stream di output.

**Returns:**
oggetto OutputStream

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> Ottiene l'altezza della prima pagina nel file di origine. </p>

**Returns:**
valore float <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre>

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

Ottiene la rotazione del numero di pagina. La rotazione è in gradi. Il valore predefinito è 0.

**Returns:**
valore float

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> Ottiene la larghezza della prima pagina nel file di input. </p>

**Returns:**
valore float <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Ottiene le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions.

**Returns:**
oggetto SaveOptions

### getStampId {#getStampId--}
```
public int getStampId()
```

ID del timbro del prossimo timbro aggiunto (inclusi intestazioni/piedi di pagina/numeri di pagina).

**Returns:**
valore int

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Ottiene o imposta il numero iniziale per la prima pagina nel file di input. Le pagine successive saranno numerate a partire da questo valore.

**Returns:**
valore int

### setAttachmentName {#setAttachmentName-java.lang.String-}
Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Imposta il formato del file PDF. Il file risultante verrà salvato nel formato specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione.

### setInputFile {#setInputFile-java.lang.String-}
Imposta il nome e il percorso del file di input. Obsolete("Use bindPdf(inputFile) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Imposta lo stream di input.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

Mantiene la sicurezza se vero. (Questa funzionalità sarà implementata nelle prossime versioni).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Ottiene o imposta lo stile di numerazione delle pagine. Valori possibili: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Ottiene o imposta il flag di ottimizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOutputFile {#setOutputFile-java.lang.String-}
Imposta il nome e il percorso del file di output. Obsolete("Use Save(outputFile) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Imposta o imposta lo stream di output.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```

Imposta la rotazione del numero di pagina. La rotazione è in gradi. Il valore predefinito è 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions.

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

ID del timbro del prossimo timbro aggiunto (inclusi intestazioni/piedi di pagina/numeri di pagina).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> Imposta il numero iniziale per la prima pagina nel file di input. Le pagine successive saranno numerate a partire da questo valore. Per esempio, se StartingNumber è impostato a 100, le pagine del documento avranno i numeri 100, 101, 102... </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber(100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
