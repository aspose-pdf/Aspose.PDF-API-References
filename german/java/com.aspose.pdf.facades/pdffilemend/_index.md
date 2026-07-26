---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse zum Hinzufügen von Texten und Bildern auf den Seiten eines bestehenden PDF‑Dokuments dar."
type: docs
weight: 500
url: /de/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

Stellt eine Klasse zum Hinzufügen von Texten und Bildern auf den Seiten eines bestehenden PDF‑Dokuments dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | Konstruktor. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> Fügt ein Bild zu der angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Fügt ein Bild zu der angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | Nicht implementiert. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | Nicht implementiert. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Nicht implementiert. |
| [close](#close--) | Schließt das PdfFileMend-Objekt. |
| [dispose](#dispose--) | Schließt das PdfFileMend-Objekt. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [getDocument](#getDocument--) | Gibt das Dokument zurück, an dem {@code PdfFileMend} arbeitet. |
| [getInputFile](#getInputFile--) | Liefert die Eingabedatei. |
| [getInputStream](#getInputStream--) | Liefert den Eingabestream. |
| [getOutputFile](#getOutputFile--) | Gibt die Ausgabedatei zurück. |
| [getOutputStream](#getOutputStream--) | Gibt den Ausgabestream zurück. |
| [getTextPositioningMode](#getTextPositioningMode--) | Gibt die Textpositionierungsstrategie zurück. {@code PositioningMode} Standardmodus ist Legacy. |
| [getWrapMode](#getWrapMode--) | Gibt den Zeilenumbruch-Algorithmus zurück. |
| [save](#save-java.io.OutputStream-) | Speichert das PDF‑Dokument in die angegebene Datei. |
| [save](#save-java.lang.String-) | Speichert das PDF‑Dokument in die angegebene Datei. |
| [setInputFile](#setInputFile-java.lang.String-) | Veraltet. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Setzt den Eingabestream. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Setzt die Ausgabedatei. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Diese Methode ist veraltet. Verwenden Sie die Save(outputStream)-Methode, um Facade-Ergebnisse zu erhalten. |
| [setTextPositioningMode](#setTextPositioningMode-int-) | Setzt die Textpositionierungsstrategie. {@code PositioningMode} Standardmodus ist Legacy. |
| [setWordWrap](#setWordWrap-boolean-) | Setzt einen booleschen Wert, der den Zeilenumbruch in AddText-Methoden angibt. Wenn der Wert true ist, wird der Text in FormattedText umgebrochen. Standardmäßig ist der Wert false. |
| [setWrapMode](#setWrapMode-int-) | Setzt den Zeilenumbruch-Algorithmus. |

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
<p> Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> Fügt ein Bild zu der angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Fügt ein Bild zu der angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
Nicht implementiert.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
Nicht implementiert.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Nicht implementiert.

### close {#close--}
```
public void close()
```

Schließt das PdfFileMend-Objekt.

### dispose {#dispose--}
```
public void dispose()
```

Schließt das PdfFileMend-Objekt. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Gibt das Dokument zurück, an dem {@code PdfFileMend} arbeitet.

**Returns:**
IDocument‑Objekt

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Liefert die Eingabedatei.

**Returns:**
String Wert

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Liefert den Eingabestream.

**Returns:**
Eingabestream.

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Gibt die Ausgabedatei zurück.

**Returns:**
String Wert

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Gibt den Ausgabestream zurück.

**Returns:**
Ausgabestream.

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

Gibt die Textpositionierungsstrategie zurück. {@code PositioningMode} Standardmodus ist Legacy.

**Returns:**
PositioningMode-Element @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Gibt den Zeilenumbruch-Algorithmus zurück.

**Returns:**
WordWrapMode-Wert @see WordWrapMode

### save {#save-java.io.OutputStream-}
Speichert das PDF‑Dokument in die angegebene Datei.

### save {#save-java.lang.String-}
Speichert das PDF‑Dokument in die angegebene Datei.

### setInputFile {#setInputFile-java.lang.String-}
Veraltet.

### setInputStream {#setInputStream-java.io.InputStream-}
Setzt den Eingabestream.

### setOutputFile {#setOutputFile-java.lang.String-}
Setzt die Ausgabedatei.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Diese Methode ist veraltet. Verwenden Sie die Save(outputStream)-Methode, um Facade-Ergebnisse zu erhalten.

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

Setzt die Textpositionierungsstrategie. {@code PositioningMode} Standardmodus ist Legacy.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | PositioningMode-Element @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

Setzt einen booleschen Wert, der den Zeilenumbruch in AddText-Methoden angibt. Wenn der Wert true ist, wird der Text in FormattedText umgebrochen. Standardmäßig ist der Wert false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Setzt den Zeilenumbruch-Algorithmus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | WordWrapMode-Element @see WordWrapMode |
