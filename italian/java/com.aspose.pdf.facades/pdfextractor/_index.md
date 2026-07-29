---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe per estrarre immagini e testo da un documento PDF."
type: docs
weight: 400
url: /it/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

Classe per estrarre immagini e testo da un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * Associa un documento Pdf per la modifica. / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * Associa un documento Pdf per la modifica. / * / * / * |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> Associa il documento PDF dallo stream. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream(\"sample.pdf\"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> Associa il file PDF di input. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf(\"sample.pdf\"); </pre> |
| [extractAttachment](#extractAttachment--) | Estrae gli allegati da un documento Pdf. |
| [extractAttachment](#extractAttachment-java.lang.String-) | Estrae gli allegati da un documento Pdf. |
| [extractImage](#extractImage--) | <p> Estrai le immagini dal file PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> Ottiene tutti i contenitori Marked Content come immagini separate. </p> <p> Ogni Marked Content verrà salvato come immagine in formato png con nome {@code MCID_<ID number of block for the page>.png}</p> |
| [extractText](#extractText--) | <p> Estrae il testo da un documento Pdf. </p> <hr> <pre> Il primo esempio dimostra come estrarre tutto il testo dal file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\\\Text\\\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\\\Text\\\\text.txt\"); </pre> <p> Il secondo esempio dimostra come estrarre il testo di ogni pagina in un unico file txt. </p> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> Estrae il testo da un documento Pdf. </p> <hr> <pre> Il primo esempio dimostra come estrarre tutto il testo dal file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\\\Text\\\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\\\Text\\\\text.txt\"); </pre> <p> Il secondo esempio dimostra come estrarre il testo di ogni pagina in un unico file txt. </p> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | Solo per uso interno |
| [getAttachment](#getAttachment--) | <p> Salva tutti i file di allegato negli stream. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> Salva tutti i file di allegato negli stream. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | Ottiene l'elenco degli allegati. |
| [getAttachNames](#getAttachNames--) | <p> Restituisce l'elenco degli allegati nel file PDF. Nota: ExtractAttachments deve essere chiamato prima di utilizzare questo metodo. </p> <hr> <pre> L'esempio dimostra come estrarre i nomi degli allegati dal file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile(\"sample.pdf\")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> Ottiene la pagina finale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> Imposta la modalità per il processo di estrazione delle immagini. </p> <hr> Il valore predefinito è ExtractImageMode.DefinedInResources che estrae tutte le immagini definite nelle risorse. Per estrarre le immagini effettivamente visualizzate deve essere usata la modalità ExtractImageMode.ActuallyUsed. |
| [getExtractTextMode](#getExtractTextMode--) | <p> Ottiene la modalità per il risultato dell'estrazione del testo. </p> <hr> <pre> L'esempio dimostra l'uso della proprietà {@code ExtractTextMode} nello scenario di estrazione del testo. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\\\Text\\\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\\\Text\\\\text.txt\"); </pre> <p> Valore: 0 è la modalità testo puro e 1 è la modalità ordine grezzo. Il valore predefinito è 0.</p> |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Recupera l'immagine successiva dal file PDF e la memorizza nello stream. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Recupera l'immagine successiva dal file PDF e la memorizza nello stream con il formato immagine specificato. |
| [getNextImage](#getNextImage-java.lang.String-) | <p> Recupera l'immagine successiva dal documento PDF. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Recupera l'immagine successiva dal documento PDF con il formato immagine specificato. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo. |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> Salva il testo di una pagina nello stream. </p> <hr> <pre> L'esempio dimostra l'uso del metodo {@code GetNextPageText} nello scenario di estrazione del testo. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> Salva il testo di una pagina su file. </p> <hr> <pre> L'esempio dimostra l'uso del metodo GetNextPageText nello scenario di estrazione del testo. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | Ottiene la password del file di input. |
| [getResolution](#getResolution--) | Ottiene la risoluzione per le immagini estratte. Il valore predefinito è 150. Le immagini con una risoluzione maggiore sono più nitide. Tuttavia, aumentare il valore della risoluzione comporta un aumento del tempo e della memoria necessari per estrarre le immagini. Di solito, per ottenere un'immagine nitida è sufficiente impostare la risoluzione a 150 o 300. |
| [getStartPage](#getStartPage--) | Oggetto Pdf.Engine che rappresenta il documento PDF. |
| [getText](#getText-java.io.OutputStream-) | Salva il testo nello stream. vedi anche:{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | Salva il testo nello stream. vedi anche:{@code ExtractText} |
| [getText](#getText-java.lang.String-) | Salva il testo su file. vedi anche:{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | Ottiene le opzioni di ricerca del testo. |
| [hasNextImage](#hasNextImage--) | <p> Verifica se sono disponibili altre immagini nel documento PDF. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> Indica se è possibile ottenere più testi o meno. </p> <hr> <pre> L'esempio dimostra l'uso della proprietà {@code HasNextPageText} nello scenario di estrazione del testo. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | È vero quando il testo contiene simboli ebraici o arabi. Questo caso deve essere considerato particolarmente perché le funzioni stringa cambiano comportamento e avviano l'elaborazione del testo da destra a sinistra (eccetto numeri e altri caratteri non testuali). |
| [setEndPage](#setEndPage-int-) | <p> Imposta la pagina finale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> Imposta la modalità per il processo di estrazione delle immagini. </p> <hr> Il valore predefinito è ExtractImageMode.DefinedInResources che estrae tutte le immagini definite nelle risorse. Per estrarre le immagini effettivamente visualizzate deve essere usata la modalità ExtractImageMode.ActuallyUsed. |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> Imposta la modalità per il risultato dell'estrazione del testo. </p> <hr> <pre> L'esempio dimostra l'uso della proprietà {@code ExtractTextMode} nello scenario di estrazione del testo. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> Valore: 0 è la modalità testo puro e 1 è la modalità ordine grezzo. Il valore predefinito è 0. |
| [setPassword](#setPassword-java.lang.String-) | Imposta la password del file di input. |
| [setResolution](#setResolution-int-) | Imposta la risoluzione per le immagini estratte. Il valore predefinito è 150. Le immagini con una risoluzione più alta sono più nitide. Tuttavia aumentare il valore della risoluzione comporta un aumento del tempo e della memoria necessari per estrarre le immagini. Di solito, per ottenere un'immagine nitida è sufficiente impostare la risoluzione a 150 o 300. |
| [setStartPage](#setStartPage-int-) | <p> Imposta la pagina iniziale nell'intervallo di pagine dove verrà eseguita l'operazione di estrazione. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Imposta le opzioni di ricerca del testo. |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * Associa un documento Pdf per la modifica. / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * Associa un documento Pdf per la modifica. / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> Associa il documento PDF dallo stream. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream(\"sample.pdf\"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> Associa il file PDF di input. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf(\"sample.pdf\"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

Estrae gli allegati da un documento Pdf.

### extractAttachment {#extractAttachment-java.lang.String-}
Estrae gli allegati da un documento Pdf.

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> Estrai le immagini dal file PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> Ottiene tutti i contenitori Marked Content come immagini separate. </p> <p> Ogni Marked Content verrà salvato come immagine in formato png con nome {@code MCID_<ID number of block for the page>.png}</p>

### extractText {#extractText--}
```
public void extractText()
```

<p> Estrae il testo da un documento Pdf. </p> <hr> <pre> Il primo esempio dimostra come estrarre tutto il testo da un file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\Text\text.pdf"); extractor.extractText(); extractor.getText("D:\Text\text.txt"); </pre> <p> Il secondo esempio dimostra come estrarre il testo di ogni pagina in un unico file txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> Estrae il testo da un documento Pdf. </p> <hr> <pre> Il primo esempio dimostra come estrarre tutto il testo da un file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\Text\text.pdf"); extractor.extractText(); extractor.getText("D:\Text\text.txt"); </pre> <p> Il secondo esempio dimostra come estrarre il testo di ogni pagina in un unico file txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
Solo per uso interno

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> Salva tutti i file di allegato negli stream. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
L'array di stream del file allegato nel documento pdf.

### getAttachment {#getAttachment-java.lang.String-}
<p> Salva tutti i file di allegato negli stream. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
L'array di stream del file allegato nel documento pdf.

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

Ottiene l'elenco degli allegati.

**Returns:**
Restituisce una List<FileSpecificatio>.

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> Restituisce l'elenco degli allegati nel file PDF. Nota: ExtractAttachments deve essere chiamato prima di utilizzare questo metodo. </p> <hr> <pre> L'esempio dimostra come estrarre i nomi degli allegati dal file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile(\"sample.pdf\")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
Elenco degli allegati

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> Ottiene la pagina finale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
pagina finale.

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> Imposta la modalità per il processo di estrazione delle immagini. </p> <hr> Il valore predefinito è ExtractImageMode.DefinedInResources che estrae tutte le immagini definite nelle risorse. Per estrarre le immagini effettivamente visualizzate deve essere usata la modalità ExtractImageMode.ActuallyUsed.

**Returns:**
Valore ExtractImageMode @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> Ottiene la modalità per il risultato dell'estrazione del testo. </p> <hr> <pre> L'esempio dimostra l'uso della proprietà {@code ExtractTextMode} nello scenario di estrazione del testo. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\Text\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\Text\text.txt"); </pre> <p> Valore: 0 è modalità testo puro e 1 è modalità ordinamento grezzo. Il valore predefinito è 0.

**Returns:**
risultato dell'estrazione del testo.

### getNextImage {#getNextImage-java.io.OutputStream-}
Recupera l'immagine successiva dal file PDF e la memorizza nello stream.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Recupera l'immagine successiva dal file PDF e la memorizza nello stream con il formato immagine specificato.

### getNextImage {#getNextImage-java.lang.String-}
<p> Recupera l'immagine successiva dal documento PDF. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
Recupera l'immagine successiva dal documento PDF con il formato immagine specificato. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo.

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> Salva il testo di una pagina nello stream. </p> <hr> <pre> L'esempio dimostra l'uso del metodo {@code GetNextPageText} nello scenario di estrazione del testo. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> Salva il testo di una pagina su file. </p> <hr> <pre> L'esempio dimostra l'uso del metodo GetNextPageText nello scenario di estrazione del testo. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

Ottiene la password del file di input.

**Returns:**
valore String

### getResolution {#getResolution--}
```
public int getResolution()
```

Ottiene la risoluzione per le immagini estratte. Il valore predefinito è 150. Le immagini con una risoluzione maggiore sono più nitide. Tuttavia, aumentare il valore della risoluzione comporta un aumento del tempo e della memoria necessari per estrarre le immagini. Di solito, per ottenere un'immagine nitida è sufficiente impostare la risoluzione a 150 o 300.

**Returns:**
valore int

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Oggetto Pdf.Engine che rappresenta il documento PDF.

**Returns:**
pagina iniziale nell'intervallo di pagine.

### getText {#getText-java.io.OutputStream-}
Salva il testo nello stream. vedi anche:{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
Salva il testo nello stream. vedi anche:{@code ExtractText}

### getText {#getText-java.lang.String-}
Salva il testo su file. vedi anche:{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Ottiene le opzioni di ricerca del testo.

**Returns:**
opzioni di ricerca del testo.

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> Verifica se sono disponibili altre immagini nel documento PDF. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

**Returns:**
Vero se sono disponibili più immagini.

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> Indica se è possibile ottenere più testi o meno. </p> <hr> <pre> L'esempio dimostra l'uso della proprietà {@code HasNextPageText} nello scenario di estrazione del testo. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
Indica se è possibile ottenere più testi; true significa sì, false no.

### isBidi {#isBidi--}
```
public boolean isBidi()
```

È vero quando il testo contiene simboli ebraici o arabi. Questo caso deve essere considerato particolarmente perché le funzioni stringa cambiano comportamento e avviano l'elaborazione del testo da destra a sinistra (eccetto numeri e altri caratteri non testuali).

**Returns:**
valore booleano

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> Imposta la pagina finale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | pagina finale. |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> Imposta la modalità per il processo di estrazione delle immagini. </p> <hr> Il valore predefinito è ExtractImageMode.DefinedInResources che estrae tutte le immagini definite nelle risorse. Per estrarre le immagini effettivamente visualizzate deve essere usata la modalità ExtractImageMode.ActuallyUsed.

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> Imposta la modalità per il risultato dell'estrazione del testo. </p> <hr> <pre> L'esempio dimostra l'uso della proprietà {@code ExtractTextMode} nello scenario di estrazione del testo. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\Text\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\Text\text.txt"); </pre> Valore: 0 è modalità testo puro e 1 è modalità ordinamento grezzo. Il valore predefinito è 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | risultato dell'estrazione del testo. |

### setPassword {#setPassword-java.lang.String-}
Imposta la password del file di input.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Imposta la risoluzione per le immagini estratte. Il valore predefinito è 150. Le immagini con una risoluzione più alta sono più nitide. Tuttavia aumentare il valore della risoluzione comporta un aumento del tempo e della memoria necessari per estrarre le immagini. Di solito, per ottenere un'immagine nitida è sufficiente impostare la risoluzione a 150 o 300.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> Imposta la pagina iniziale nell'intervallo di pagine dove verrà eseguita l'operazione di estrazione. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | pagina iniziale nell'intervallo di pagine. |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Imposta le opzioni di ricerca del testo.
