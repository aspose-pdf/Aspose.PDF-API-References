---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse dar, die jede Seite einer PDF-Datei in Bilder konvertiert und jetzt BMP, JPEG, PNG und TIFF unterstützt. Unterstützte Inhalte in PDFs: Bilder, Formulare, Kommentare."
type: docs
weight: 390
url: /de/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

Stellt eine Klasse zum Konvertieren jeder Seite einer PDF‑Datei in Bilder dar, unterstützt derzeit BMP, JPEG, PNG und TIFF. Unterstützte Inhalte in PDFs: Bilder, Formulare, Kommentare.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfConverter](#PdfConverter--) | Initialisiert ein neues {@code PdfConverter}-Objekt. |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | Initialisiert ein neues {@code PdfConverter}-Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Bindet ein PDF-Dokument an die {@link PdfConverter}-Instanz für die weitere Verarbeitung. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Bindet einen PDF-Stream für die Konvertierung. |
| [bindPdf](#bindPdf-java.lang.String-) | Bindet eine PDF-Datei für die Konvertierung. |
| [close](#close--) | Schließt die Instanz von PdfConverter und gibt die Ressourcen frei. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Nur für den internen Gebrauch. |
| [dispose](#dispose--) | Schließt die Instanz von PdfConverter und gibt die Ressourcen frei. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [doConvert](#doConvert--) | <p> Führen Sie einige initiale Arbeiten zur Konvertierung eines PDF-Dokuments in Bilder aus. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | Ermittelt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet. |
| [getEndPage](#getEndPage--) | Ermittelt die Endposition, die Sie konvertieren möchten. |
| [getFormPresentationMode](#getFormPresentationMode--) | Liefert den Formularpräsentationsmodus. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Speichert das Bild in einen Stream mit dem Standardbildformat - jpeg. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Speichert das Bild in einen Stream mit dem angegebenen Bildformat. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | Speichert das Bild in einen Stream mit dem angegebenen Bildformat, Größe und Qualität. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Speichert das Bild in einen Stream mit dem angegebenen Bildformat und Qualität. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | Speichert das Bild in einen Stream mit dem angegebenen Bildformat, Größe und Qualität. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | Speichert das Bild in einen Stream mit dem angegebenen Bildformat, Abmessungen und Qualität. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | Speichert das Bild in einen Stream mit der angegebenen Seitengröße. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Speichert das Bild in einen Stream mit der angegebenen Seitengröße. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Speichert das Bild in einen Stream mit der angegebenen Seitengröße, dem Bildformat und der Qualität. |
| [getNextImage](#getNextImage-java.lang.String-) | Speichert das Bild in eine Datei mit dem Standardbildformat - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> Speichert das Bild in einer Datei mit dem angegebenen Bildformat. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.DoConvert(); String prefix = @\"D:\\\\Test\\\\\"; String suffix = \".png\"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> Speichert das Bild in einer Datei mit dem angegebenen Bildformat, Bildgröße und Qualität. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); String prefix = @\"D:\\\\Test\\\\\"; String suffix = \".jpg\"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | Speichert das Bild in einer Datei mit dem angegebenen Bildformat und Qualität. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> Speichert das Bild in einer Datei mit dem angegebenen Bildformat und den Abmessungen. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(\"D:\\\\Test\\\\test.pdf\"); converter.DoConvert(); String prefix = \"D:\\\\Test\\\\\"; String suffix = \".jpg\"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> Speichert das Bild in einer Datei mit dem angegebenen Bildformat, den Abmessungen und der Qualität. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); String prefix = @\"D:\\\\Test\\\\\"; String suffix = \".jpg\"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Standardbildformat - JPEG. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Bildformat. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Speichert das Bild in einer Datei mit der angegebenen Seitengröße, dem Bildformat und der Qualität. |
| [getPageCount](#getPageCount--) | Ermittelt die Seitenanzahl. |
| [getPassword](#getPassword--) | Ermittelt das OwnerPassword des Dokuments. |
| [getRenderingOptions](#getRenderingOptions--) | Ruft Rendering-Optionen ab. |
| [getResolution](#getResolution--) | Ermittelt die Auflösung während der Konvertierung. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 150. |
| [getStartPage](#getStartPage--) | Ermittelt die Startposition, die Sie konvertieren möchten. Der Minimalwert ist 1. |
| [getUserPassword](#getUserPassword--) | Ermittelt das UserPassword des Dokuments. |
| [hasNextImage](#hasNextImage--) | Gibt an, ob die PDF-Datei weitere Bilder enthält oder nicht. |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Ermittelt das Flag, das die Sichtbarkeit versteckter Bereiche auf der Seite steuert. Die Methode ist veraltet. |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | Führt eine Liste von Bild-Streams zu einem einzigen Bild-Stream zusammen. |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | Führt eine Liste von TIFF-Streams zu einem einzigen mehrseitigen TIFF-Stream zusammen. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF-Stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzigen TIFF-Datei. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit den Abmessungen und speichert die Bilder in einem einzigen TIFF-Stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit den Abmessungen und speichert die Bilder in einem einzigen TIFF-Stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit den Abmessungen und speichert die Bilder in einem einzigen TIFF-Stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit den Abmessungen und speichert die Bilder in einem einzigen TIFF-Stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einem einzigen TIFF-Stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einem einzigen TIFF-Stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF-Stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF-Stream. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzigen TIFF-Datei. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); converter.saveAsTIFF(@\"D:\\\\Test\\\\test.tiff\"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzigen TIFF-Datei. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); converter.saveAsTIFF(@\"D:\\\\Test\\\\test.tiff\"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzigen TIFF-Datei. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzigen TIFF-Datei. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzigen TIFF-Datei. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzigen TIFF-Datei. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einer einzigen TIFF-Datei. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einer einzigen TIFF-Datei. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit und speichert die Bilder in einer einzigen TIFF-Datei. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit und speichert die Bilder in einer einzigen TIFF-Datei. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF ClassF-Stream. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF ClassF-Stream. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF ClassF-Stream. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzigen TIFF ClassF-Datei. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(\"D:\\\\\\Test\\\\\\\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(\"D:\\\\\\Test\\\\\\\\test.tiff\"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzigen TIFF ClassF-Datei. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(@\"D:\\\\Test\\\\test.tiff\",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzigen TIFF ClassF-Datei. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Setzt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet. |
| [setEndPage](#setEndPage-int-) | Setzt die Endposition, die Sie konvertieren möchten. Verwenden Sie setEndPage(int) vor setStartPage(int). |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Setzt den Formular-Präsentationsmodus. |
| [setPassword](#setPassword-java.lang.String-) | Setzt das Dokument OwnerPassword. |
| [setRangeOfPages](#setRangeOfPages-int-int-) | Setzt den Seitenbereich, den Sie konvertieren möchten. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Setzt Rendering-Optionen. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Setzt die Auflösung während der Konvertierung. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 150. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Veraltet. |
| [setStartPage](#setStartPage-int-) | Setzt die Startposition, die Sie konvertieren möchten. Der Minimalwert ist 1. Verwenden Sie setEndPage(int) vor setStartPage(int). |
| [setUserPassword](#setUserPassword-java.lang.String-) | Setzt das Dokument UserPassword. |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

Initialisiert ein neues {@code PdfConverter}-Objekt.

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
Initialisiert ein neues {@code PdfConverter}-Objekt.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Bindet ein PDF-Dokument an die {@link PdfConverter}-Instanz für die weitere Verarbeitung.

### bindPdf {#bindPdf-java.io.InputStream-}
Bindet einen PDF-Stream für die Konvertierung.

### bindPdf {#bindPdf-java.lang.String-}
Bindet eine PDF-Datei für die Konvertierung.

### close {#close--}
```
public void close()
```

Schließt die Instanz von PdfConverter und gibt die Ressourcen frei.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Nur für den internen Gebrauch.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Schließt die Instanz von PdfConverter und gibt die Ressourcen frei. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> Führt einige initiale Arbeiten für die Konvertierung eines PDF-Dokuments in Bilder aus. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); String prefix = \"D:\\\\Test\\\\\"; String suffix = \".jpg\"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Ermittelt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet.

**Returns:**
PageCoordinateType-Element @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

Ermittelt die Endposition, die Sie konvertieren möchten.

**Returns:**
int-Wert

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Liefert den Formularpräsentationsmodus.

**Returns:**
Formular-Präsentationsmodus. @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
Speichert das Bild in einen Stream mit dem Standardbildformat - jpeg.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Speichert das Bild in einen Stream mit dem angegebenen Bildformat.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
Speichert das Bild in einen Stream mit dem angegebenen Bildformat, Größe und Qualität.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Speichert das Bild in einen Stream mit dem angegebenen Bildformat und Qualität.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
Speichert das Bild in einen Stream mit dem angegebenen Bildformat, Größe und Qualität.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
Speichert das Bild in einen Stream mit dem angegebenen Bildformat, Abmessungen und Qualität.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
Speichert das Bild in einen Stream mit der angegebenen Seitengröße.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Speichert das Bild in einen Stream mit der angegebenen Seitengröße.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Speichert das Bild in einen Stream mit der angegebenen Seitengröße, dem Bildformat und der Qualität.

### getNextImage {#getNextImage-java.lang.String-}
Speichert das Bild in eine Datei mit dem Standardbildformat - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> Speichert das Bild in einer Datei mit dem angegebenen Bildformat. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.DoConvert(); String prefix = @\"D:\\\\Test\\\\\"; String suffix = \".png\"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> Speichert das Bild in einer Datei mit dem angegebenen Bildformat, der Bildgröße und der Qualität. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
Speichert das Bild in einer Datei mit dem angegebenen Bildformat und Qualität.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> Speichert das Bild in einer Datei mit dem angegebenen Bildformat und den Abmessungen. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> Speichert das Bild in einer Datei mit dem angegebenen Bildformat, den Abmessungen und der Qualität. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Standardbildformat - JPEG.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Bildformat.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Speichert das Bild in einer Datei mit der angegebenen Seitengröße, dem Bildformat und der Qualität.

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Ermittelt die Seitenanzahl.

**Returns:**
int-Wert

### getPassword {#getPassword--}
```
public String getPassword()
```

Ermittelt das OwnerPassword des Dokuments.

**Returns:**
String Wert

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Ruft Rendering-Optionen ab.

**Returns:**
Rendering-Optionen.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Ermittelt die Auflösung während der Konvertierung. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 150.

**Returns:**
Auflösungselement

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Ermittelt die Startposition, die Sie konvertieren möchten. Der Minimalwert ist 1.

**Returns:**
int-Wert

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

Ermittelt das UserPassword des Dokuments.

**Returns:**
String Wert

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

Gibt an, ob die PDF-Datei weitere Bilder enthält oder nicht.

**Returns:**
Kann weitere Bilder erhalten oder nicht, true wenn ja, sonst false.

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Ermittelt das Flag, das die Sichtbarkeit versteckter Bereiche auf der Seite steuert. Die Methode ist veraltet.

**Returns:**
boolescher Wert

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
Führt eine Liste von Bild-Streams zu einem einzigen Bild-Stream zusammen.

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
Führt eine Liste von TIFF-Streams zu einem einzigen mehrseitigen TIFF-Stream zusammen.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF-Stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzigen TIFF-Datei.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit den Abmessungen und speichert die Bilder in einem einzigen TIFF-Stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit den Abmessungen und speichert die Bilder in einem einzigen TIFF-Stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit den Abmessungen und speichert die Bilder in einem einzigen TIFF-Stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit den Abmessungen und speichert die Bilder in einem einzigen TIFF-Stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einem einzigen TIFF-Stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einem einzigen TIFF-Stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF-Stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF-Stream.

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzigen TIFF-Datei.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzigen TIFF-Datei.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzigen TIFF-Datei.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzigen TIFF-Datei.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einer einzigen TIFF-Datei.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einer einzigen TIFF-Datei.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit und speichert die Bilder in einer einzigen TIFF-Datei.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder mit und speichert die Bilder in einer einzigen TIFF-Datei.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF ClassF-Stream.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF ClassF-Stream.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzigen TIFF ClassF-Stream.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\Test\\test.tiff"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\Test\test.tiff",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzigen TIFF ClassF-Datei.

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Setzt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet.

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

Setzt die Endposition, die Sie konvertieren möchten. Verwenden Sie setEndPage(int) vor setStartPage(int).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Setzt den Formular-Präsentationsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Formular-Präsentationsmodus. @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
Setzt das Dokument OwnerPassword.

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

Setzt den Seitenbereich, den Sie konvertieren möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startPage |  | int-Wert |
| EndPage |  | int-Wert |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Setzt Rendering-Optionen.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Setzt die Auflösung während der Konvertierung. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 150.

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Veraltet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

Setzt die Startposition, die Sie konvertieren möchten. Der Minimalwert ist 1. Verwenden Sie setEndPage(int) vor setStartPage(int).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setUserPassword {#setUserPassword-java.lang.String-}
Setzt das Dokument UserPassword.
