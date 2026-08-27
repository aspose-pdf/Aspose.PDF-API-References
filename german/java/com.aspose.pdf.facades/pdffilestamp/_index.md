---
title: "PdfFileStamp"
linktitle: "PdfFileStamp"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF‑Dateien."
type: docs
weight: 540
url: /de/java/com.aspose.pdf.facades/pdffilestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStamp, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStamp, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStamp

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStamp extends SaveableFacade implements IPdfFileStamp
```

Klasse zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF‑Dateien.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Untere linke Position. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Untere mittlere Position. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Untere rechte Position. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Linke Position. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Rechte Position. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Obere linke Position. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Obere mittlere Position. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Obere rechte Position. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFileStamp](#PdfFileStamp--) | <p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-) | <p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-) | <p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.lang.String-java.lang.String-) | <p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.lang.String-java.lang.String-boolean-) | <p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> Fügt den Seiten des Dokuments eine Fußzeile hinzu. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Fügt den Seiten des Dokuments eine Fußzeile hinzu. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> Fügt ein Bild als Fußzeile der Seite hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(new FileInputStream(\"image.jpg\"), 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> Fügt ein Bild als Fußzeile der Seite hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(new FileInputStream(\"image.jpg\"), 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> Fügt ein Bild als Fußzeile zu den Seiten des Dokuments hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(\"image.jpg\", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Fügt Bild als Fußzeile der Seiten hinzu. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> Fügt der Seite eine Kopfzeile hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addHeader(new FormattedText(\"Head of the page\"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Fügt den Seiten der Datei eine Kopfzeile hinzu. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addHeader(new FormattedText(\"Head of the page\"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> Fügt Bild als Kopfzeile auf den Seiten hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(new FileInputStream(\"image.jpg\"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> Fügt Bild am oberen Rand der Seite hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); IjnputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(new FileInputStream(\"image.jpg\"), 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> Fügt Bild als Kopfzeile zu den Seiten der Datei hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InpetuStream input = new FileInputStream(TestSettings.GetInputFile(\"test.jpg\")); fileStamp.addHeader(\"image.jpg\", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> Fügt Bild als Kopfzeile auf den Seiten hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(TestSettings.GetInputFile(\"test.jpg\")); fileStamp.addHeader(\"image.jpg\", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> Fügt Seitenzahl zur Seite hinzu. Die Seitenzahl kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. Die Seitenzahl wird am unteren Rand der Seite horizontal zentriert platziert. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> Fügt Seitenzahl an der angegebenen Position auf der Seite hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> Fügt Seitenzahl zu den Seiten hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> Fügt Seitenzahl zu den Seiten des Dokuments hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> Fügt Seitenzahl zur Datei hinzu. Der Text der Seitenzahl kann das Zeichen # enthalten, das durch die Seitennummer ersetzt wird. Die Seitenzahl wird am unteren Rand der Seite horizontal zentriert platziert. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> Fügt Seitenzahl an der angegebenen Position auf der Seite hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> Fügt Seitenzahl zu den Seiten hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> Fügt Seitenzahl zu den Seiten des Dokuments hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> Fügt dem Dokument einen Stempel hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity(0.8f); stamp.isBackground(true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> Schließt geöffnete Dateien und speichert Änderungen. Warnung. Wenn Eingabe- oder Ausgabeströme angegeben sind, werden sie nicht durch die Close()-Methode geschlossen. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | Veraltet. |
| [getAttachmentName](#getAttachmentName--) | Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [getContentDisposition](#getContentDisposition--) | Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in einem HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline. |
| [getInputFile](#getInputFile--) | Ermittelt Name und Pfad der Eingabedatei. |
| [getInputStream](#getInputStream--) | Liest Eingabestream. Obsolete("Use bindPdf(inputFile) method for facade initialization.") |
| [getKeepSecurity](#getKeepSecurity--) | Behält Sicherheit bei true. (Dieses Feature wird in nächsten Versionen implementiert.) |
| [getNumberingStyle](#getNumberingStyle--) | Liest oder setzt Seiten-Nummerierungsstil. Mögliche Werte: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [getOptimizeSize](#getOptimizeSize--) | Liest oder setzt Optimierungs-Flag. |
| [getOutputFile](#getOutputFile--) | Liest Name und Pfad der Ausgabedatei. Obsolete("Use Save(outputFile) method for getting facade results.") |
| [getOutputStream](#getOutputStream--) | Ermittelt Ausgabestream. |
| [getPageHeight](#getPageHeight--) | <p> Ermittelt die Höhe der ersten Seite in der Quellendatei. </p> |
| [getPageNumberRotation](#getPageNumberRotation--) | Liest die Drehung der Seitenzahl. Die Drehung ist in Grad angegeben. Standardwert ist 0. |
| [getPageWidth](#getPageWidth--) | <p> Ermittelt die Breite der ersten Seite in der Eingabedatei. </p> |
| [getSaveOptions](#getSaveOptions--) | Ermittelt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [getStampId](#getStampId--) | Stempel-ID des als Nächstes hinzugefügten Stempels (einschließlich Seitenkopf-/Fußzeilen/Seitenzahlen). |
| [getStartingNumber](#getStartingNumber--) | Liest oder setzt die Startnummer für die erste Seite in der Eingabedatei. Folgende Seiten werden ab diesem Wert nummeriert. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Legt fest, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Legt das PDF‑Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard‑PDF‑Format ohne Konvertierung gespeichert. |
| [setInputFile](#setInputFile-java.lang.String-) | Setzt Name und Pfad der Eingabedatei. Obsolete("Use bindPdf(inputFile) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Legt den Eingabestream fest. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Behält Sicherheit bei true. (Dieses Feature wird in nächsten Versionen implementiert.) |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Liest oder setzt Seiten-Nummerierungsstil. Mögliche Werte: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Liest oder setzt Optimierungs-Flag. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Setzt Name und Pfad der Ausgabedatei. Obsolete("Use Save(outputFile) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Setzt den Ausgabestream. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Setzt die Drehung der Seitenzahl. Die Drehung ist in Grad angegeben. Standardwert ist 0. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Legt Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [setStampId](#setStampId-int-) | Stempel-ID des als Nächstes hinzugefügten Stempels (einschließlich Seitenkopf-/Fußzeilen/Seitenzahlen). |
| [setStartingNumber](#setStartingNumber-int-) | <p> Setzt die Startnummer für die erste Seite in der Eingabedatei. Folgende Seiten werden ab diesem Wert nummeriert. Zum Beispiel, wenn StartingNumber auf 100 gesetzt ist, erhalten die Dokumentseiten die Nummern 100, 101, 102... </p> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

Untere linke Position.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

Untere mittlere Position.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

Untere rechte Position.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

Linke Position.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

Rechte Position.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

Obere linke Position.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

Obere mittlere Position.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

Obere rechte Position.

### PdfFileStamp {#PdfFileStamp--}
```
public PdfFileStamp()
```

<p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-}
<p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-}
<p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-java.lang.String-java.lang.String-}
<p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-java.lang.String-java.lang.String-boolean-}
<p> Konstruktor von PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> Fügt den Seiten des Dokuments eine Fußzeile hinzu. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Fügt den Seiten des Dokuments eine Fußzeile hinzu. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> Fügt ein Bild als Fußzeile der Seite hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(new FileInputStream(\"image.jpg\"), 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> Fügt ein Bild als Fußzeile der Seite hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(new FileInputStream(\"image.jpg\"), 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> Fügt ein Bild als Fußzeile zu den Seiten des Dokuments hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(\"image.jpg\", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
Fügt Bild als Fußzeile der Seiten hinzu.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> Fügt der Seite eine Kopfzeile hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addHeader(new FormattedText(\"Head of the page\"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Fügt den Seiten der Datei eine Kopfzeile hinzu. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addHeader(new FormattedText(\"Head of the page\"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> Fügt Bild als Kopfzeile auf den Seiten hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(new FileInputStream(\"image.jpg\"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> Fügt Bild am oberen Rand der Seite hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); IjnputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(new FileInputStream(\"image.jpg\"), 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> Fügt Bild als Kopfzeile zu den Seiten der Datei hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InpetuStream input = new FileInputStream(TestSettings.GetInputFile(\"test.jpg\")); fileStamp.addHeader(\"image.jpg\", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> Fügt Bild als Kopfzeile auf den Seiten hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(TestSettings.GetInputFile(\"test.jpg\")); fileStamp.addHeader(\"image.jpg\", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> Fügt Seitenzahl zur Seite hinzu. Die Seitenzahl kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. Die Seitenzahl wird am unteren Rand der Seite horizontal zentriert platziert. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> Fügt Seitenzahl an der angegebenen Position auf der Seite hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> Fügt Seitenzahl zu den Seiten hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> Fügt Seitenzahl zu den Seiten des Dokuments hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> Fügt Seitenzahl zur Datei hinzu. Der Text der Seitenzahl kann das Zeichen # enthalten, das durch die Seitennummer ersetzt wird. Die Seitenzahl wird am unteren Rand der Seite horizontal zentriert platziert. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> Fügt Seitenzahl an der angegebenen Position auf der Seite hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> Fügt Seitenzahl zu den Seiten hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> Fügt Seitenzahl zu den Seiten des Dokuments hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> Fügt dem Dokument einen Stempel hinzu. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity(0.8f); stamp.isBackground(true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> Schließt geöffnete Dateien und speichert Änderungen. Warnung. Wenn Eingabe- oder Ausgabeströme angegeben sind, werden sie nicht durch die Close()-Methode geschlossen. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Veraltet.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

**Returns:**
String Wert

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in einem HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline.

**Returns:**
ContentDisposition-Element @see com.aspose.pdf.ContentDisposition

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

Ermittelt Name und Pfad der Eingabedatei.

**Returns:**
String Wert

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Liest Eingabestream. Obsolete("Use bindPdf(inputFile) method for facade initialization.")

**Returns:**
InputStream‑Objekt

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

Behält Sicherheit bei true. (Dieses Feature wird in nächsten Versionen implementiert.)

**Returns:**
boolescher Wert

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Liest oder setzt Seiten-Nummerierungsstil. Mögliche Werte: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase

**Returns:**
NumberingStyle-Element @see NumberingStyle

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Liest oder setzt Optimierungs-Flag.

**Returns:**
boolescher Wert

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Liest Name und Pfad der Ausgabedatei. Obsolete("Use Save(outputFile) method for getting facade results.")

**Returns:**
String Wert

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Ermittelt Ausgabestream.

**Returns:**
OutputStream-Objekt

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> Ermittelt die Höhe der ersten Seite in der Quellendatei. </p>

**Returns:**
float-Wert <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre>

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

Liest die Drehung der Seitenzahl. Die Drehung ist in Grad angegeben. Standardwert ist 0.

**Returns:**
float-Wert

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> Ermittelt die Breite der ersten Seite in der Eingabedatei. </p>

**Returns:**
float-Wert <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Ermittelt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions.

**Returns:**
SaveOptions-Objekt

### getStampId {#getStampId--}
```
public int getStampId()
```

Stempel-ID des als Nächstes hinzugefügten Stempels (einschließlich Seitenkopf-/Fußzeilen/Seitenzahlen).

**Returns:**
int-Wert

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Liest oder setzt die Startnummer für die erste Seite in der Eingabedatei. Folgende Seiten werden ab diesem Wert nummeriert.

**Returns:**
int-Wert

### setAttachmentName {#setAttachmentName-java.lang.String-}
Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Legt fest, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Legt das PDF‑Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard‑PDF‑Format ohne Konvertierung gespeichert.

### setInputFile {#setInputFile-java.lang.String-}
Setzt Name und Pfad der Eingabedatei. Obsolete("Use bindPdf(inputFile) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Legt den Eingabestream fest.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

Behält Sicherheit bei true. (Dieses Feature wird in nächsten Versionen implementiert.)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Liest oder setzt Seiten-Nummerierungsstil. Mögliche Werte: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Liest oder setzt Optimierungs-Flag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOutputFile {#setOutputFile-java.lang.String-}
Setzt Name und Pfad der Ausgabedatei. Obsolete("Use Save(outputFile) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Setzt den Ausgabestream.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```

Setzt die Drehung der Seitenzahl. Die Drehung ist in Grad angegeben. Standardwert ist 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Legt Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions.

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Stempel-ID des als Nächstes hinzugefügten Stempels (einschließlich Seitenkopf-/Fußzeilen/Seitenzahlen).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> Setzt die Startnummer für die erste Seite in der Eingabedatei. Folgende Seiten werden ab diesem Wert nummeriert. Zum Beispiel, wenn StartingNumber auf 100 gesetzt ist, erhalten die Dokumentseiten die Nummern 100, 101, 102... </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber(100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
