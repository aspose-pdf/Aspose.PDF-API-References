---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass för att extrahera bilder och text från PDF-dokument."
type: docs
weight: 400
url: /sv/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

Klass för att extrahera bilder och text från PDF-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * Binder ett Pdf-dokument för redigering. / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * Binder ett Pdf-dokument för redigering. / * / * / * |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> Binder PDF-dokument från ström. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> Bind inmatnings-PDF-fil. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre> |
| [extractAttachment](#extractAttachment--) | Extraherar bilagor från ett Pdf-dokument. |
| [extractAttachment](#extractAttachment-java.lang.String-) | Extraherar bilagor från ett Pdf-dokument. |
| [extractImage](#extractImage--) | <p> Extraherar bilder från PDF-fil. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> Hämtar alla Marked Content-behållare som separata bilder. </p> <p> Varje Marked Content kommer att sparas som bild i png-format med namn {@code MCID_<ID number of block for the page>.png} |
| [extractText](#extractText--) | <p> Extraherar text från ett Pdf-dokument. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> Det andra exemplet visar hur man extraherar varje sidas text till en txt-fil. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> Extraherar text från ett Pdf-dokument. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> Det andra exemplet visar hur man extraherar varje sidas text till en txt-fil. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | Endast för intern användning |
| [getAttachment](#getAttachment--) | <p> Sparar alla bilagor till strömmar. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> Sparar alla bilagor till strömmar. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | Hämtar listan över bilagor. |
| [getAttachNames](#getAttachNames--) | <p> Returnerar lista över bilagor i PDF‑filen. Obs: ExtractAttachments måste anropas innan den här metoden används. </p> <hr> <pre> Example demonstrates how to extract attachment names form PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> Hämtar slutsid i sidintervallet där extraheringsoperationen kommer att utföras. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> Ställer in läget för bildextraktionsprocessen. </p> <hr> Default value is ExtractImageMode.DefinedInResources that extracts all images defined in resources. To extract actually shown images ExtractImageMode.ActuallyUsed mode should be used. |
| [getExtractTextMode](#getExtractTextMode--) | <p> Hämtar läget för resultatet av textutdrag. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> <p> Värde: 0 är rent textläge och 1 är rå ordningsläge. Standard är 0. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Hämtar nästa bild från PDF‑filen och lagrar den i en ström. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Hämtar nästa bild från PDF‑filen och lagrar den i en ström med angivet bildformat. |
| [getNextImage](#getNextImage-java.lang.String-) | <p> Hämtar nästa bild från PDF‑dokumentet. Obs: ExtractImage måste anropas innan den här metoden används. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Hämtar nästa bild från PDF‑dokumentet med angivet bildformat. Obs: ExtractImage måste anropas innan den här metoden används. |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> Sparar en sidas text till en ström. </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> Sparar en sidas text till en fil. </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | Hämtar lösenordet för indatafilen. |
| [getResolution](#getResolution--) | Hämtar upplösning för extraherade bilder. Standardvärdet är 150. Bilder som har högre upplösningsvärde är tydligare. Att öka upplösningsvärdet leder dock till ökad tid och minne som behövs för att extrahera bilder. Vanligtvis räcker det att sätta upplösning till 150 eller 300 för att få en klar bild. |
| [getStartPage](#getStartPage--) | Pdf.Engine-objekt som representerar PDF-dokument. |
| [getText](#getText-java.io.OutputStream-) | Sparar text till ström. se även:{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | Sparar text till ström. se även:{@code ExtractText} |
| [getText](#getText-java.lang.String-) | Sparar text till fil. se även:{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | Hämtar alternativ för textsökning. |
| [hasNextImage](#hasNextImage--) | <p> Kontrollerar om fler bilder är tillgängliga i PDF-dokumentet. Obs: ExtractImage måste anropas innan denna metod används. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> Anger om fler texter kan hämtas eller inte. </p> <hr> <pre> The example demonstrates the {@code HasNextPageText} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | Är sant när texten innehåller hebreiska eller arabiska tecken. Detta fall måste särskilt beaktas eftersom strängfunktioner ändrar sitt beteende och behandlar texten från höger till vänster (förutom siffror och andra icke‑texttecken). |
| [setEndPage](#setEndPage-int-) | <p> Anger slutsida i sidintervallet där extraheringsoperationen kommer att utföras. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> Ställer in läget för bildextraktionsprocessen. </p> <hr> Default value is ExtractImageMode.DefinedInResources that extracts all images defined in resources. To extract actually shown images ExtractImageMode.ActuallyUsed mode should be used. |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> Ställer in läget för extraherad texts resultat. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> Värde: 0 är rent textläge och 1 är rå ordningsläge. Standard är 0. |
| [setPassword](#setPassword-java.lang.String-) | Ställer in lösenord för inmatningsfilen. |
| [setResolution](#setResolution-int-) | Ställ in upplösning för extraherade bilder. Standardvärdet är 150. Bilder som har högre upplösningsvärde är tydligare. Att öka upplösningsvärdet leder dock till ökad tid och minne som behövs för att extrahera bilder. Vanligtvis räcker det att sätta upplösning till 150 eller 300 för att få en klar bild. |
| [setStartPage](#setStartPage-int-) | <p> Anger startsida i sidintervallet där extraheringsoperationen kommer att utföras. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Ställer in alternativ för textsökning. |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * Binder ett Pdf-dokument för redigering. / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * Binder ett Pdf-dokument för redigering. / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> Binder PDF-dokument från ström. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> Bind inmatnings-PDF-fil. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

Extraherar bilagor från ett Pdf-dokument.

### extractAttachment {#extractAttachment-java.lang.String-}
Extraherar bilagor från ett Pdf-dokument.

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> Extraherar bilder från PDF-fil. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> Hämtar alla Marked Content-behållare som separata bilder. </p> <p> Varje Marked Content kommer att sparas som bild i png-format med namn {@code MCID_<ID number of block for the page>.png}

### extractText {#extractText--}
```
public void extractText()
```

<p> Extraherar text från ett Pdf-dokument. </p> <hr> <pre> Det första exemplet visar hur man extraherar all text från en PDF-fil. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\Text\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\Text\\text.txt\"); </pre> <p> Det andra exemplet visar hur man extraherar varje sidas text till en txt-fil. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> Extraherar text från ett Pdf-dokument. </p> <hr> <pre> Det första exemplet visar hur man extraherar all text från en PDF-fil. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\Text\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\Text\\text.txt\"); </pre> <p> Det andra exemplet visar hur man extraherar varje sidas text till en txt-fil. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
Endast för intern användning

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> Sparar alla bilagor till strömmar. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
Strömarrayen för bilagan i pdf-dokumentet.

### getAttachment {#getAttachment-java.lang.String-}
<p> Sparar alla bilagor till strömmar. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
Strömarrayen för bilagan i pdf-dokumentet.

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

Hämtar listan över bilagor.

**Returns:**
Returnerar en List<FileSpecificatio>.

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> Returnerar lista över bilagor i PDF‑filen. Obs: ExtractAttachments måste anropas innan den här metoden används. </p> <hr> <pre> Example demonstrates how to extract attachment names form PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
Lista över bilagor

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> Hämtar slutsid i sidintervallet där extraheringsoperationen kommer att utföras. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
slutsida.

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> Ställer in läget för bildextraktionsprocessen. </p> <hr> Default value is ExtractImageMode.DefinedInResources that extracts all images defined in resources. To extract actually shown images ExtractImageMode.ActuallyUsed mode should be used.

**Returns:**
ExtractImageMode‑värde @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> Hämtar läget för resultatet av textutdragning. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> <p> Värde: 0 är rent textläge och 1 är rå ordningsläge. Standard är 0.

**Returns:**
resultatet av textutdragning.

### getNextImage {#getNextImage-java.io.OutputStream-}
Hämtar nästa bild från PDF‑filen och lagrar den i en ström.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Hämtar nästa bild från PDF‑filen och lagrar den i en ström med angivet bildformat.

### getNextImage {#getNextImage-java.lang.String-}
<p> Hämtar nästa bild från PDF‑dokumentet. Obs: ExtractImage måste anropas innan den här metoden används. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
Hämtar nästa bild från PDF‑dokumentet med angivet bildformat. Obs: ExtractImage måste anropas innan den här metoden används.

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> Sparar en sidas text till en ström. </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> Sparar en sidas text till en fil. </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

Hämtar lösenordet för indatafilen.

**Returns:**
String värde

### getResolution {#getResolution--}
```
public int getResolution()
```

Hämtar upplösning för extraherade bilder. Standardvärdet är 150. Bilder som har högre upplösningsvärde är tydligare. Att öka upplösningsvärdet leder dock till ökad tid och minne som behövs för att extrahera bilder. Vanligtvis räcker det att sätta upplösning till 150 eller 300 för att få en klar bild.

**Returns:**
int‑värde

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Pdf.Engine-objekt som representerar PDF-dokument.

**Returns:**
startsid i sidintervallet.

### getText {#getText-java.io.OutputStream-}
Sparar text till ström. se även:{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
Sparar text till ström. se även:{@code ExtractText}

### getText {#getText-java.lang.String-}
Sparar text till fil. se även:{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Hämtar alternativ för textsökning.

**Returns:**
alternativ för textsökning.

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> Kontrollerar om fler bilder är tillgängliga i PDF-dokumentet. Obs: ExtractImage måste anropas innan denna metod används. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

**Returns:**
Sant om fler bilder är tillgängliga.

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> Anger om fler texter kan hämtas eller inte. </p> <hr> <pre> The example demonstrates the {@code HasNextPageText} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
Kan hämta mer text eller inte, sant betyder kan, falskt betyder kan inte.

### isBidi {#isBidi--}
```
public boolean isBidi()
```

Är sant när texten innehåller hebreiska eller arabiska tecken. Detta fall måste särskilt beaktas eftersom strängfunktioner ändrar sitt beteende och behandlar texten från höger till vänster (förutom siffror och andra icke‑texttecken).

**Returns:**
booleskt värde

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> Anger slutsida i sidintervallet där extraheringsoperationen kommer att utföras. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | slutsida. |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> Ställer in läget för bildextraktionsprocessen. </p> <hr> Default value is ExtractImageMode.DefinedInResources that extracts all images defined in resources. To extract actually shown images ExtractImageMode.ActuallyUsed mode should be used.

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> Ställer in läget för resultatet av textutdragning. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> Värde: 0 är rent textläge och 1 är rå ordningsläge. Standard är 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | resultatet av textutdragning. |

### setPassword {#setPassword-java.lang.String-}
Ställer in lösenord för inmatningsfilen.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Ställ in upplösning för extraherade bilder. Standardvärdet är 150. Bilder som har högre upplösningsvärde är tydligare. Att öka upplösningsvärdet leder dock till ökad tid och minne som behövs för att extrahera bilder. Vanligtvis räcker det att sätta upplösning till 150 eller 300 för att få en klar bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> Anger startsida i sidintervallet där extraheringsoperationen kommer att utföras. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | startsid i sidintervallet. |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Ställer in alternativ för textsökning.
