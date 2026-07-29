---
title: "PdfFileStamp"
linktitle: "PdfFileStamp"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass för att lägga till stämplar (vattenstämpel eller bakgrund) i PDF-filer."
type: docs
weight: 540
url: /sv/java/com.aspose.pdf.facades/pdffilestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStamp, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStamp, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStamp

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStamp extends SaveableFacade implements IPdfFileStamp
```

Klass för att lägga till stämplar (vattenstämpel eller bakgrund) i PDF-filer.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Nedre vänstra positionen. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Nedre mellersta positionen. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Nedre högra positionen. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Vänster position. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Höger position. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Övre vänstra positionen. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Övre mellersta positionen. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Övre högra positionen. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfFileStamp](#PdfFileStamp--) | <p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-) | <p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-) | <p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.lang.String-java.lang.String-) | <p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.lang.String-java.lang.String-boolean-) | <p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> Lägger till sidfot på dokumentets sidor. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Lägger till sidfot på dokumentets sidor. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> Lägger till bild som sidfot på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> Lägger till bild som sidfot på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> Lägger till bild som sidfot på dokumentets sidor. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Lägger till bild som sidfot på sidorna. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> Lägger till rubrik på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Lägger till rubrik på filens sidor. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> Lägger till bild som rubrik på sidorna. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> Lägger till bild högst upp på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); IjnputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> Lägger till bild som rubrik på filens sidor. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InpetuStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> Lägger till bild som rubrik på sidorna. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> Lägger till sidnummer på sidan. Sidnumret kan innehålla #‑tecken som kommer att ersättas med sidnumret. Sidnumret placeras i botten av sidan centrerat horisontellt. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> Lägger till sidnummer på den angivna positionen på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> Lägger till sidnummer på sidorna. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> Lägger till sidnummer på dokumentets sidor. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> Lägg till sidnummer i filen. Sidnummertext kan innehålla #‑tecken som kommer att ersättas med sidnumret. Sidnumret placeras i botten av sidan centrerat horisontellt. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> Lägger till sidnummer på den angivna positionen på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> Lägger till sidnummer på sidorna. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> Lägger till sidnummer på dokumentets sidor. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> Lägger till stämpel i filen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity(0.8f); stamp.isBackground(true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> Stänger öppnade filer och sparar ändringar. Varning. Om in- eller utdataflöden har angetts stängs de inte av Close()-metoden. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | Föråldrad. |
| [getAttachmentName](#getAttachmentName--) | Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [getContentDisposition](#getContentDisposition--) | Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [getInputFile](#getInputFile--) | Hämtar namn och sökväg för indatafilen. |
| [getInputStream](#getInputStream--) | Hämtar indataflöde. Obsolete("Use bindPdf(inputFile) method for facade initialization.") |
| [getKeepSecurity](#getKeepSecurity--) | Behåller säkerhet om true. (Denna funktion kommer att implementeras i kommande versioner). |
| [getNumberingStyle](#getNumberingStyle--) | Hämtar eller anger sidnumreringsstil. Möjliga värden: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [getOptimizeSize](#getOptimizeSize--) | Hämtar eller anger optimeringsflagga. |
| [getOutputFile](#getOutputFile--) | Hämtar namn och sökväg för utdatafil. Obsolete("Use Save(outputFile) method for getting facade results.") |
| [getOutputStream](#getOutputStream--) | Hämtar utmatningsström. |
| [getPageHeight](#getPageHeight--) | <p> Hämtar höjden på den första sidan i källfilen. </p> |
| [getPageNumberRotation](#getPageNumberRotation--) | Hämtar rotation för sidnummer. Rotation är i grader. Standard är 0. |
| [getPageWidth](#getPageWidth--) | <p> Hämtar bredden på den första sidan i indatafilen. </p> |
| [getSaveOptions](#getSaveOptions--) | Hämtar sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions. |
| [getStampId](#getStampId--) | Stämpel‑ID för nästa tillagda stämpel (inklusive sidhuvuden/sidfötter/sidnummer). |
| [getStartingNumber](#getStartingNumber--) | Hämtar eller anger startnummer för den första sidan i inmatningsfilen. Efterföljande sidor kommer att numreras med början från detta värde. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Ställer in hur innehållet ska lagras när resultatet av operationen lagras i ett HttpResponse-objekt. Möjligt värde: inline / attachment. Standard: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Ställer in PDF-filformat. Resultatfilen sparas i angivet filformat. Om denna egenskap inte anges sparas filen i standard PDF-format utan konvertering. |
| [setInputFile](#setInputFile-java.lang.String-) | Anger namn och sökväg för inmatningsfilen. Obsolete(\"Use bindPdf(inputFile) method for facade initialization.\") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Ställer in inmatningsström. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Behåller säkerhet om true. (Denna funktion kommer att implementeras i kommande versioner). |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Hämtar eller anger sidnumreringsstil. Möjliga värden: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Hämtar eller anger optimeringsflagga. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Anger namn och sökväg för utdatafilen. Obsolete(\"Use Save(outputFile) method for getting facade results.\") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Ställer in eller återställer utmatningsström. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Anger rotation för sidnummer. Rotation är i grader. Standard är 0. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions. |
| [setStampId](#setStampId-int-) | Stämpel‑ID för nästa tillagda stämpel (inklusive sidhuvuden/sidfötter/sidnummer). |
| [setStartingNumber](#setStartingNumber-int-) | <p> Anger startnummer för den första sidan i inmatningsfilen. Efterföljande sidor kommer att numreras med början från detta värde. Till exempel om StartingNumber är satt till 100, kommer dokumentsidorna att ha nummer 100, 101, 102... </p> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

Nedre vänstra positionen.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

Nedre mellersta positionen.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

Nedre högra positionen.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

Vänster position.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

Höger position.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

Övre vänstra positionen.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

Övre mellersta positionen.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

Övre högra positionen.

### PdfFileStamp {#PdfFileStamp--}
```
public PdfFileStamp()
```

<p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-}
<p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-}
<p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.lang.String-java.lang.String-}
<p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.lang.String-java.lang.String-boolean-}
<p> Konstruktor för PdfFileStamp. Indatafil och utdatafil kan specificeras via motsvarande egenskaper. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> Lägger till sidfot på dokumentets sidor. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Lägger till sidfot på dokumentets sidor. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> Lägger till bild som sidfot på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> Lägger till bild som sidfot på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> Lägger till bild som sidfot på dokumentets sidor. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
Lägger till bild som sidfot på sidorna.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> Lägger till rubrik på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Lägger till rubrik på filens sidor. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> Lägger till bild som rubrik på sidorna. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> Lägger till bild högst upp på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); IjnputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> Lägger till bild som rubrik på filens sidor. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InpetuStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> Lägger till bild som rubrik på sidorna. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> Lägger till sidnummer på sidan. Sidnumret kan innehålla #‑tecken som kommer att ersättas med sidnumret. Sidnumret placeras i botten av sidan centrerat horisontellt. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> Lägger till sidnummer på den angivna positionen på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> Lägger till sidnummer på sidorna. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> Lägger till sidnummer på dokumentets sidor. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> Lägg till sidnummer i filen. Sidnummertext kan innehålla #‑tecken som kommer att ersättas med sidnumret. Sidnumret placeras i botten av sidan centrerat horisontellt. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> Lägger till sidnummer på den angivna positionen på sidan. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> Lägger till sidnummer på sidorna. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> Lägger till sidnummer på dokumentets sidor. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> Lägger till stämpel i filen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity(0.8f); stamp.isBackground(true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> Stänger öppnade filer och sparar ändringar. Varning. Om in- eller utdataflöden har angetts stängs de inte av Close()-metoden. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Föråldrad.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

**Returns:**
String värde

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline.

**Returns:**
ContentDisposition-element @see com.aspose.pdf.ContentDisposition

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

Hämtar namn och sökväg för indatafilen.

**Returns:**
String värde

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Hämtar indataflöde. Obsolete("Use bindPdf(inputFile) method for facade initialization.")

**Returns:**
InputStream-objekt

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

Behåller säkerhet om true. (Denna funktion kommer att implementeras i kommande versioner).

**Returns:**
booleskt värde

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Hämtar eller anger sidnumreringsstil. Möjliga värden: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase

**Returns:**
NumberingStyle-element @see NumberingStyle

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Hämtar eller anger optimeringsflagga.

**Returns:**
booleskt värde

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Hämtar namn och sökväg för utdatafil. Obsolete("Use Save(outputFile) method for getting facade results.")

**Returns:**
String värde

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Hämtar utmatningsström.

**Returns:**
OutputStream objekt

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> Hämtar höjden på den första sidan i källfilen. </p>

**Returns:**
float‑värde <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Height = \" + fileStamp.getPageHeight()); fileStamp.close(); </pre>

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

Hämtar rotation för sidnummer. Rotation är i grader. Standard är 0.

**Returns:**
flyttalsvärde

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> Hämtar bredden på den första sidan i indatafilen. </p>

**Returns:**
float‑värde <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Width = \" + fileStamp.getPageWidth()); fileStamp.close(); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Hämtar sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions.

**Returns:**
SaveOptions-objekt

### getStampId {#getStampId--}
```
public int getStampId()
```

Stämpel‑ID för nästa tillagda stämpel (inklusive sidhuvuden/sidfötter/sidnummer).

**Returns:**
int‑värde

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Hämtar eller anger startnummer för den första sidan i inmatningsfilen. Efterföljande sidor kommer att numreras med början från detta värde.

**Returns:**
int‑värde

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Ställer in hur innehållet ska lagras när resultatet av operationen lagras i ett HttpResponse-objekt. Möjligt värde: inline / attachment. Standard: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Ställer in PDF-filformat. Resultatfilen sparas i angivet filformat. Om denna egenskap inte anges sparas filen i standard PDF-format utan konvertering.

### setInputFile {#setInputFile-java.lang.String-}
Anger namn och sökväg för inmatningsfilen. Obsolete(\"Use bindPdf(inputFile) method for facade initialization.\")

### setInputStream {#setInputStream-java.io.InputStream-}
Ställer in inmatningsström.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

Behåller säkerhet om true. (Denna funktion kommer att implementeras i kommande versioner).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Hämtar eller anger sidnumreringsstil. Möjliga värden: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Hämtar eller anger optimeringsflagga.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOutputFile {#setOutputFile-java.lang.String-}
Anger namn och sökväg för utdatafilen. Obsolete(\"Use Save(outputFile) method for getting facade results.\")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Ställer in eller återställer utmatningsström.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```

Anger rotation för sidnummer. Rotation är i grader. Standard är 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions.

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Stämpel‑ID för nästa tillagda stämpel (inklusive sidhuvuden/sidfötter/sidnummer).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> Anger startnummer för den första sidan i inmatningsfilen. Efterföljande sidor kommer att numreras med början från detta värde. Till exempel om StartingNumber är satt till 100, kommer dokumentsidorna att ha nummer 100, 101, 102... </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.setStartingNumber(100); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre> |
