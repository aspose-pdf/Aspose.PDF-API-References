---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse zum Extrahieren von Bildern und Text aus PDF‑Dokumenten."
type: docs
weight: 400
url: /de/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

Klasse zum Extrahieren von Bildern und Text aus PDF‑Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * Bindet ein Pdf-Dokument zum Bearbeiten. / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * Bindet ein Pdf-Dokument zum Bearbeiten. / * / * / * |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> Bindet PDF-Dokument aus einem Stream. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> Bindet Eingabe-PDF-Datei. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre> |
| [extractAttachment](#extractAttachment--) | Extrahiert Anhänge aus einem Pdf-Dokument. |
| [extractAttachment](#extractAttachment-java.lang.String-) | Extrahiert Anhänge aus einem Pdf-Dokument. |
| [extractImage](#extractImage--) | <p> Extrahiert Bilder aus einer PDF-Datei. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> Erhält alle Marked Content-Container als separate Bilder. </p> <p> Jeder Marked Content wird als Bild im PNG-Format gespeichert, benannt mit {@code MCID_<ID number of block for the page>.png} |
| [extractText](#extractText--) | <p> Extrahiert Text aus einem Pdf-Dokument. </p> <hr> <pre> Das erste Beispiel zeigt, wie man den gesamten Text aus einer PDF-Datei extrahiert. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> Das zweite Beispiel zeigt, wie man den Text jeder Seite in eine txt-Datei extrahiert. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> Extrahiert Text aus einem Pdf-Dokument. </p> <hr> <pre> Das erste Beispiel zeigt, wie man den gesamten Text aus einer PDF-Datei extrahiert. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> Das zweite Beispiel zeigt, wie man den Text jeder Seite in eine txt-Datei extrahiert. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | Nur für den internen Gebrauch |
| [getAttachment](#getAttachment--) | <p> Speichert alle Anhangdateien in Streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> Speichert alle Anhangdateien in Streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | Erhält die Liste der Anhänge. |
| [getAttachNames](#getAttachNames--) | <p> Gibt die Liste der Anhänge in einer PDF-Datei zurück. Hinweis: ExtractAttachments muss vor der Verwendung dieser Methode aufgerufen werden. </p> <hr> <pre> Das Beispiel zeigt, wie man Anhangsnamen aus einer PDF-Datei extrahiert. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> Erhält die Endseite im Seitenbereich, in dem die Extraktionsoperation durchgeführt wird. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> Legt den Modus für den Bildextraktionsprozess fest. </p> <hr> Standardwert ist ExtractImageMode.DefinedInResources, das alle in Ressourcen definierten Bilder extrahiert. Um tatsächlich angezeigte Bilder zu extrahieren, sollte der Modus ExtractImageMode.ActuallyUsed verwendet werden. |
| [getExtractTextMode](#getExtractTextMode--) | <p> Ermittelt den Modus für das Ergebnis der Textextraktion. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\\\Text\\\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\\\Text\\\\text.txt\"); </pre> <p> Wert: 0 ist reiner Textmodus und 1 ist Rohreihenfolgemodus. Standard ist 0.</p> |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Ruft das nächste Bild aus der PDF-Datei ab und speichert es in einen Stream. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Ruft das nächste Bild aus der PDF-Datei ab und speichert es in einen Stream mit dem angegebenen Bildformat. |
| [getNextImage](#getNextImage-java.lang.String-) | <p> Ruft das nächste Bild aus dem PDF-Dokument ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Ruft das nächste Bild aus dem PDF-Dokument mit dem angegebenen Bildformat ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> Speichert den Text einer Seite in einen Stream. </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> Speichert den Text einer Seite in eine Datei. </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @\"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | Ermittelt das Passwort der Eingabedatei. |
| [getResolution](#getResolution--) | Ermittelt die Auflösung für extrahierte Bilder. Der Standardwert ist 150. Bilder mit höherer Auflösung sind klarer. Allerdings führt eine höhere Auflösung zu mehr Zeit- und Speicheraufwand für die Bildextraktion. In der Regel reicht es aus, die Auflösung auf 150 oder 300 zu setzen, um ein klares Bild zu erhalten. |
| [getStartPage](#getStartPage--) | Pdf.Engine-Objekt, das ein PDF-Dokument darstellt. |
| [getText](#getText-java.io.OutputStream-) | Speichert Text in einen Stream. Siehe auch:{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | Speichert Text in einen Stream. Siehe auch:{@code ExtractText} |
| [getText](#getText-java.lang.String-) | Speichert Text in eine Datei. Siehe auch:{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | Erhält Textsuchoptionen. |
| [hasNextImage](#hasNextImage--) | <p> Prüft, ob weitere Bilder im PDF-Dokument verfügbar sind. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> Gibt an, ob weitere Texte abgerufen werden können oder nicht. </p> <hr> <pre> Das Beispiel demonstriert die Verwendung der {@code HasNextPageText} Eigenschaft im Szenario der Textextraktion. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | Ist wahr, wenn der Text hebräische oder arabische Symbole enthält. Dieser Fall muss besonders berücksichtigt werden, weil String‑Funktionen ihr Verhalten ändern und die Textverarbeitung von rechts nach links starten (außer Zahlen und anderen Nicht‑Text‑Zeichen). |
| [setEndPage](#setEndPage-int-) | <p> Legt die Endseite im Seitenbereich fest, in dem die Extraktionsoperation durchgeführt wird. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> Legt den Modus für den Bildextraktionsprozess fest. </p> <hr> Standardwert ist ExtractImageMode.DefinedInResources, das alle in Ressourcen definierten Bilder extrahiert. Um tatsächlich angezeigte Bilder zu extrahieren, sollte der Modus ExtractImageMode.ActuallyUsed verwendet werden. |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> Legt den Modus für das Ergebnis der Textextraktion fest. </p> <hr> <pre> Das Beispiel demonstriert die Verwendung der {@code ExtractTextMode} Eigenschaft im Szenario der Textextraktion. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\\\Text\\\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\\\Text\\\\text.txt\"); </pre> Wert: 0 ist reiner Textmodus und 1 ist Rohreihenfolgemodus. Standard ist 0. |
| [setPassword](#setPassword-java.lang.String-) | Setzt das Passwort der Eingabedatei. |
| [setResolution](#setResolution-int-) | Setzt die Auflösung für extrahierte Bilder. Der Standardwert ist 150. Bilder mit höherer Auflösung sind klarer. Allerdings führt eine Erhöhung der Auflösung zu mehr Zeit- und Speicheraufwand für die Bildextraktion. In der Regel reicht es, die Auflösung auf 150 oder 300 zu setzen, um ein klares Bild zu erhalten. |
| [setStartPage](#setStartPage-int-) | <p> Legt die Startseite im Seitenbereich fest, in dem die Extraktionsoperation durchgeführt wird. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Legt Optionen für die Textsuche fest. |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * Bindet ein Pdf-Dokument zum Bearbeiten. / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * Bindet ein Pdf-Dokument zum Bearbeiten. / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> Bindet PDF-Dokument aus einem Stream. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> Bindet Eingabe-PDF-Datei. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

Extrahiert Anhänge aus einem Pdf-Dokument.

### extractAttachment {#extractAttachment-java.lang.String-}
Extrahiert Anhänge aus einem Pdf-Dokument.

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> Extrahiert Bilder aus einer PDF-Datei. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> Erhält alle Marked Content-Container als separate Bilder. </p> <p> Jeder Marked Content wird als Bild im PNG-Format gespeichert, benannt mit {@code MCID_<ID number of block for the page>.png}

### extractText {#extractText--}
```
public void extractText()
```

<p> Extrahiert Text aus einem PDF‑Dokument. </p> <hr> <pre> Erstes Beispiel demonstriert, wie man den gesamten Text aus einer PDF‑Datei extrahiert. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\Text\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\Text\\text.txt\"); </pre> <p> Zweites Beispiel demonstriert, wie man den Text jeder Seite in eine txt‑Datei extrahiert. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> Extrahiert Text aus einem PDF‑Dokument. </p> <hr> <pre> Erstes Beispiel demonstriert, wie man den gesamten Text aus einer PDF‑Datei extrahiert. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\Text\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\Text\\text.txt\"); </pre> <p> Zweites Beispiel demonstriert, wie man den Text jeder Seite in eine txt‑Datei extrahiert. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
Nur für den internen Gebrauch

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> Speichert alle Anhangdateien in Streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
Das Stream‑Array der Anhangsdatei im PDF‑Dokument.

### getAttachment {#getAttachment-java.lang.String-}
<p> Speichert alle Anhangdateien in Streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
Das Stream‑Array der Anhangsdatei im PDF‑Dokument.

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

Erhält die Liste der Anhänge.

**Returns:**
Gibt eine List<FileSpecificatio> zurück.

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> Gibt die Liste der Anhänge in einer PDF-Datei zurück. Hinweis: ExtractAttachments muss vor der Verwendung dieser Methode aufgerufen werden. </p> <hr> <pre> Das Beispiel zeigt, wie man Anhangsnamen aus einer PDF-Datei extrahiert. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
Liste der Anhänge

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> Erhält die Endseite im Seitenbereich, in dem die Extraktionsoperation durchgeführt wird. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
Endseite.

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> Legt den Modus für den Bildextraktionsprozess fest. </p> <hr> Standardwert ist ExtractImageMode.DefinedInResources, das alle in Ressourcen definierten Bilder extrahiert. Um tatsächlich angezeigte Bilder zu extrahieren, sollte der Modus ExtractImageMode.ActuallyUsed verwendet werden.

**Returns:**
ExtractImageMode‑Wert @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> Gibt den Modus für das Ergebnis der Textextraktion zurück. </p> <hr> <pre> Das Beispiel demonstriert die Verwendung der {@code ExtractTextMode} Eigenschaft im Szenario der Textextraktion. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> <p> Wert: 0 ist reiner Textmodus und 1 ist Rohreihenfolgemodus. Standard ist 0.

**Returns:**
Ergebnis der Textextraktion.

### getNextImage {#getNextImage-java.io.OutputStream-}
Ruft das nächste Bild aus der PDF-Datei ab und speichert es in einen Stream.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Ruft das nächste Bild aus der PDF-Datei ab und speichert es in einen Stream mit dem angegebenen Bildformat.

### getNextImage {#getNextImage-java.lang.String-}
<p> Ruft das nächste Bild aus dem PDF-Dokument ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
Ruft das nächste Bild aus dem PDF-Dokument mit dem angegebenen Bildformat ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden.

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> Speichert den Text einer Seite in einen Stream. </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> Speichert den Text einer Seite in eine Datei. </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @\"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

Ermittelt das Passwort der Eingabedatei.

**Returns:**
String Wert

### getResolution {#getResolution--}
```
public int getResolution()
```

Ermittelt die Auflösung für extrahierte Bilder. Der Standardwert ist 150. Bilder mit höherer Auflösung sind klarer. Allerdings führt eine höhere Auflösung zu mehr Zeit- und Speicheraufwand für die Bildextraktion. In der Regel reicht es aus, die Auflösung auf 150 oder 300 zu setzen, um ein klares Bild zu erhalten.

**Returns:**
int-Wert

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Pdf.Engine-Objekt, das ein PDF-Dokument darstellt.

**Returns:**
Startseite im Seitenbereich.

### getText {#getText-java.io.OutputStream-}
Speichert Text in einen Stream. Siehe auch:{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
Speichert Text in einen Stream. Siehe auch:{@code ExtractText}

### getText {#getText-java.lang.String-}
Speichert Text in eine Datei. Siehe auch:{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Erhält Textsuchoptionen.

**Returns:**
Optionen für die Textsuche.

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> Prüft, ob weitere Bilder im PDF-Dokument verfügbar sind. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre>

**Returns:**
Wahr, wenn weitere Bilder zugänglich sind.

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> Gibt an, ob weitere Texte abgerufen werden können oder nicht. </p> <hr> <pre> Das Beispiel demonstriert die Verwendung der {@code HasNextPageText} Eigenschaft im Szenario der Textextraktion. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
Kann weitere Texte erhalten oder nicht, wahr bedeutet ja, falsch bedeutet nein.

### isBidi {#isBidi--}
```
public boolean isBidi()
```

Ist wahr, wenn der Text hebräische oder arabische Symbole enthält. Dieser Fall muss besonders berücksichtigt werden, weil String‑Funktionen ihr Verhalten ändern und die Textverarbeitung von rechts nach links starten (außer Zahlen und anderen Nicht‑Text‑Zeichen).

**Returns:**
boolescher Wert

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> Legt die Endseite im Seitenbereich fest, in dem die Extraktionsoperation durchgeführt wird. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Endseite. |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> Legt den Modus für den Bildextraktionsprozess fest. </p> <hr> Standardwert ist ExtractImageMode.DefinedInResources, das alle in Ressourcen definierten Bilder extrahiert. Um tatsächlich angezeigte Bilder zu extrahieren, sollte der Modus ExtractImageMode.ActuallyUsed verwendet werden.

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> Legt den Modus für das Ergebnis der Textextraktion fest. </p> <hr> <pre> Das Beispiel demonstriert die Verwendung der {@code ExtractTextMode} Eigenschaft im Szenario der Textextraktion. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> Wert: 0 ist reiner Textmodus und 1 ist Rohreihenfolgemodus. Standard ist 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Ergebnis der Textextraktion. |

### setPassword {#setPassword-java.lang.String-}
Setzt das Passwort der Eingabedatei.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Setzt die Auflösung für extrahierte Bilder. Der Standardwert ist 150. Bilder mit höherer Auflösung sind klarer. Allerdings führt eine Erhöhung der Auflösung zu mehr Zeit- und Speicheraufwand für die Bildextraktion. In der Regel reicht es, die Auflösung auf 150 oder 300 zu setzen, um ein klares Bild zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> Legt die Startseite im Seitenbereich fest, in dem die Extraktionsoperation durchgeführt wird. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Startseite im Seitenbereich. |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Legt Optionen für die Textsuche fest.
