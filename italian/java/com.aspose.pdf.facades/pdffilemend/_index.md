---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per aggiungere testi e immagini sulle pagine di un documento PDF esistente."
type: docs
weight: 500
url: /it/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

Rappresenta una classe per aggiungere testi e immagini sulle pagine di un documento PDF esistente.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | Costruttore. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | Costruttore. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Costruttore. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Costruttore. |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Costruttore. |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Costruttore. |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | Costruttore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Aggiunge un'immagine alla pagina specificata del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | Non implementato. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | Non implementato. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Non implementato. |
| [close](#close--) | Chiude l'oggetto PdfFileMend. |
| [dispose](#dispose--) | Chiude l'oggetto PdfFileMend. Questo metodo è obsoleto, usa close() invece. |
| [getDocument](#getDocument--) | Ottiene il documento su cui {@code PdfFileMend} sta lavorando. |
| [getInputFile](#getInputFile--) | Ottiene il file di input. |
| [getInputStream](#getInputStream--) | Ottiene lo stream di input. |
| [getOutputFile](#getOutputFile--) | Ottiene il file di output. |
| [getOutputStream](#getOutputStream--) | Ottiene lo stream di output. |
| [getTextPositioningMode](#getTextPositioningMode--) | Ottiene la strategia di posizionamento del testo. {@code PositioningMode} La modalità predefinita è Legacy. |
| [getWrapMode](#getWrapMode--) | Ottiene l'algoritmo di a capo automatico. |
| [save](#save-java.io.OutputStream-) | Salva il documento PDF nel file specificato. |
| [save](#save-java.lang.String-) | Salva il documento PDF nel file specificato. |
| [setInputFile](#setInputFile-java.lang.String-) | Obsoleto. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Imposta lo stream di input. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Imposta il file di output. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Questo metodo è deprecato. Usa il metodo Save(outputStream) per ottenere i risultati della facciata. |
| [setTextPositioningMode](#setTextPositioningMode-int-) | Imposta la strategia di posizionamento del testo. {@code PositioningMode} La modalità predefinita è Legacy. |
| [setWordWrap](#setWordWrap-boolean-) | Imposta un valore bool che indica l'andare a capo automatico nei metodi AddText. Se il valore è true, il testo in FormattedText verrà mandato a capo. Per impostazione predefinita, il valore è false. |
| [setWrapMode](#setWrapMode-int-) | Imposta l'algoritmo di a capo automatico. |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

Costruttore.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
Costruttore.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Costruttore.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
Costruttore.

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
Costruttore.

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
Costruttore.

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
Costruttore.

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Aggiunge un'immagine alla pagina specificata del documento PDF alle coordinate specificate. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
Non implementato.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
Non implementato.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Non implementato.

### close {#close--}
```
public void close()
```

Chiude l'oggetto PdfFileMend.

### dispose {#dispose--}
```
public void dispose()
```

Chiude l'oggetto PdfFileMend. Questo metodo è obsoleto, usa close() invece.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Ottiene il documento su cui {@code PdfFileMend} sta lavorando.

**Returns:**
Oggetto IDocument

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Ottiene il file di input.

**Returns:**
valore String

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Ottiene lo stream di input.

**Returns:**
stream di input.

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Ottiene il file di output.

**Returns:**
valore String

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Ottiene lo stream di output.

**Returns:**
stream di output.

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

Ottiene la strategia di posizionamento del testo. {@code PositioningMode} La modalità predefinita è Legacy.

**Returns:**
Elemento PositioningMode @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Ottiene l'algoritmo di a capo automatico.

**Returns:**
valore WordWrapMode @see WordWrapMode

### save {#save-java.io.OutputStream-}
Salva il documento PDF nel file specificato.

### save {#save-java.lang.String-}
Salva il documento PDF nel file specificato.

### setInputFile {#setInputFile-java.lang.String-}
Obsoleto.

### setInputStream {#setInputStream-java.io.InputStream-}
Imposta lo stream di input.

### setOutputFile {#setOutputFile-java.lang.String-}
Imposta il file di output.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Questo metodo è deprecato. Usa il metodo Save(outputStream) per ottenere i risultati della facciata.

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

Imposta la strategia di posizionamento del testo. {@code PositioningMode} La modalità predefinita è Legacy.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento PositioningMode @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

Imposta un valore bool che indica l'andare a capo automatico nei metodi AddText. Se il valore è true, il testo in FormattedText verrà mandato a capo. Per impostazione predefinita, il valore è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Imposta l'algoritmo di a capo automatico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento WordWrapMode @see WordWrapMode |
