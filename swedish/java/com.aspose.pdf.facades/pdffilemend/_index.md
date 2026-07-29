---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för att lägga till texter och bilder på sidorna i ett befintligt PDF-dokument."
type: docs
weight: 500
url: /sv/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

Representerar en klass för att lägga till texter och bilder på sidorna i ett befintligt PDF-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | Konstruktor. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | Ej implementerad. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | Ej implementerad. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Ej implementerad. |
| [close](#close--) | Stänger PdfFileMend-objektet. |
| [dispose](#dispose--) | Stänger PdfFileMend-objektet. Denna metod är föråldrad, använd close() istället. |
| [getDocument](#getDocument--) | Hämtar dokumentet som {@code PdfFileMend} arbetar med. |
| [getInputFile](#getInputFile--) | Hämtar indatafilen. |
| [getInputStream](#getInputStream--) | Hämtar indataströmmen. |
| [getOutputFile](#getOutputFile--) | Hämtar utdatafilen. |
| [getOutputStream](#getOutputStream--) | Hämtar utströmmen. |
| [getTextPositioningMode](#getTextPositioningMode--) | Hämtar textplaceringsstrategi. {@code PositioningMode} Standardläge är Legacy. |
| [getWrapMode](#getWrapMode--) | Hämtar radbrytningsalgoritm. |
| [save](#save-java.io.OutputStream-) | Sparar PDF-dokumentet till den angivna filen. |
| [save](#save-java.lang.String-) | Sparar PDF-dokumentet till den angivna filen. |
| [setInputFile](#setInputFile-java.lang.String-) | Föråldrad. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Ställer in inmatningsströmmen. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Ställer in utdatafilen. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Denna metod är föråldrad. Använd Save(outputStream)-metoden för att få facade-resultat. |
| [setTextPositioningMode](#setTextPositioningMode-int-) | Ställer in textplaceringsstrategi. {@code PositioningMode} Standardläge är Legacy. |
| [setWordWrap](#setWordWrap-boolean-) | Ställer in ett booleskt värde som indikerar radbrytning i AddText-metoder. Om värdet är true kommer texten i FormattedText att radbrytas. Som standard är värdet false. |
| [setWrapMode](#setWrapMode-int-) | Ställer in radbrytningsalgoritm. |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

Konstruktor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
Konstruktor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Konstruktor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
Konstruktor.

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
Konstruktor.

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
Konstruktor.

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
Konstruktor.

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
Ej implementerad.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
Ej implementerad.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Ej implementerad.

### close {#close--}
```
public void close()
```

Stänger PdfFileMend-objektet.

### dispose {#dispose--}
```
public void dispose()
```

Stänger PdfFileMend-objektet. Denna metod är föråldrad, använd close() istället.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Hämtar dokumentet som {@code PdfFileMend} arbetar med.

**Returns:**
IDocument-objekt

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Hämtar indatafilen.

**Returns:**
String värde

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Hämtar indataströmmen.

**Returns:**
indataström.

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Hämtar utdatafilen.

**Returns:**
String värde

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Hämtar utströmmen.

**Returns:**
utdataström.

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

Hämtar textplaceringsstrategi. {@code PositioningMode} Standardläge är Legacy.

**Returns:**
PositioningMode-element @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Hämtar radbrytningsalgoritm.

**Returns:**
WordWrapMode värde @see WordWrapMode

### save {#save-java.io.OutputStream-}
Sparar PDF-dokumentet till den angivna filen.

### save {#save-java.lang.String-}
Sparar PDF-dokumentet till den angivna filen.

### setInputFile {#setInputFile-java.lang.String-}
Föråldrad.

### setInputStream {#setInputStream-java.io.InputStream-}
Ställer in inmatningsströmmen.

### setOutputFile {#setOutputFile-java.lang.String-}
Ställer in utdatafilen.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Denna metod är föråldrad. Använd Save(outputStream)-metoden för att få facade-resultat.

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

Ställer in textplaceringsstrategi. {@code PositioningMode} Standardläge är Legacy.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | PositioningMode-element @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

Ställer in ett booleskt värde som indikerar radbrytning i AddText-metoder. Om värdet är true kommer texten i FormattedText att radbrytas. Som standard är värdet false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Ställer in radbrytningsalgoritm.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | WordWrapMode-element @see WordWrapMode |
