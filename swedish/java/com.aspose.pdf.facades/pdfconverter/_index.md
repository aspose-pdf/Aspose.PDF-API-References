---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för att konvertera varje sida i en PDF-fil till bilder, med stöd för BMP, JPEG, PNG och TIFF nu. Stödd innehåll i PDF-filer: bilder, formulär, kommentarer."
type: docs
weight: 390
url: /sv/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

Representerar en klass för att konvertera varje sida i en pdf-fil till bilder, med stöd för BMP, JPEG, PNG och TIFF nu. Stödd innehåll i pdf-filer: bilder, formulär, kommentarer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfConverter](#PdfConverter--) | Initierar ett nytt {@code PdfConverter} objekt. |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | Initierar ett nytt {@code PdfConverter} objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Kopplar ett PDF-dokument till {@link PdfConverter}-instansen för vidare bearbetning. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Kopplar en PDF‑ström för konvertering. |
| [bindPdf](#bindPdf-java.lang.String-) | Kopplar en PDF‑fil för konvertering. |
| [close](#close--) | Stäng PdfConverter‑instansen och frigör resurserna. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Endast för internt bruk |
| [dispose](#dispose--) | Stäng PdfConverter‑instansen och frigör resurserna. Denna metod är föråldrad, använd close() istället. |
| [doConvert](#doConvert--) | <p> Utför några initiala åtgärder för att konvertera ett PDF-dokument till bilder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | Hämtar sidans koordinattyp (Media-/Crop-boxar). CropBox-värdet används som standard. |
| [getEndPage](#getEndPage--) | Hämtar slutpositionen som du vill konvertera. |
| [getFormPresentationMode](#getFormPresentationMode--) | Hämtar formulärpresentationsläge. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Sparar bilden till en ström med standardbildformatet - jpeg. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Sparar bilden till en ström med angivet bildformat. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | Sparar bilden till en ström med det angivna bildformatet, storlek och kvalitet. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Sparar bilden till en ström med angivet bildformat och kvalitet. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | Sparar bilden till en ström med det angivna bildformatet, storlek och kvalitet. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | Sparar bilden till en ström med det angivna bildformatet, dimensioner och kvalitet. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | Sparar bilden till en ström med angiven sidstorlek. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Sparar bilden till en ström med angiven sidstorlek. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Sparar bilden till en ström med angiven sidstorlek, bildformat och kvalitet. |
| [getNextImage](#getNextImage-java.lang.String-) | Sparar bilden till en fil med standardbildformatet - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> Sparar bilden till en fil med det angivna bildformatet. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.DoConvert(); String prefix = @\"D:\\\\Test\\\\\"; String suffix = \".png\"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> Sparar bilden till en fil med det angivna bildformatet, bildstorlek och kvalitet. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); String prefix = @\"D:\\\\Test\\\\\"; String suffix = \".jpg\"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | Sparar bilden till en fil med angivet bildformat och kvalitet. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> Sparar bilden till en fil med det angivna bildformatet och dimensionerna. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\\\Test\\\\\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\\\Test\\\\\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> Sparar bilden till en fil med det angivna bildformatet, dimensionerna och kvaliteten. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); String prefix = @\"D:\\\\Test\\\\\"; String suffix = \".jpg\"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | Sparar bilden till en fil med den angivna sidstorleken och standardbildformatet - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Sparar bilden till en fil med angiven sidstorlek och bildformat. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Sparar bilden till en fil med angiven sidstorlek, bildformat och kvalitet. |
| [getPageCount](#getPageCount--) | Hämtar sidantalet. |
| [getPassword](#getPassword--) | Hämtar dokumentets OwnerPassword. |
| [getRenderingOptions](#getRenderingOptions--) | Hämtar renderingsalternativ. |
| [getResolution](#getResolution--) | Hämtar upplösning under konvertering. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 150. |
| [getStartPage](#getStartPage--) | Hämtar startpositionen som du vill konvertera. Minimivärdet är 1. |
| [getUserPassword](#getUserPassword--) | Hämtar dokumentets UserPassword. |
| [hasNextImage](#hasNextImage--) | Anger om pdf-filen har fler bilder eller inte. |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Hämtar flaggan som styr synligheten för dolda områden på sidan. Metoden är föråldrad. |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | Slår ihop en lista med bildströmmar till en bildström. |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | Slår ihop en lista med tiff-strömmar till en tiff-ström med flera ramar. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-ström. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-ström. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-ström. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-ström. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-ström. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); converter.saveAsTIFF(@\"D:\\\\Test\\\\test.tiff\"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); converter.saveAsTIFF(@\"D:\\\\Test\\\\test.tiff\"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\\Test\\test.tiff",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Ställer in sidkoordinattypen (Media/Crop-boxar). CropBox-värdet används som standard. |
| [setEndPage](#setEndPage-int-) | Ställer in slutpositionen som du vill konvertera. Använd setEndPage(int) före setStartPage(int). |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Ställer in formulärets presentationsläge. |
| [setPassword](#setPassword-java.lang.String-) | Ställer in dokumentets OwnerPassword. |
| [setRangeOfPages](#setRangeOfPages-int-int-) | Ställer in intervallet av sidor mellan vilka du vill konvertera. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Ställer in renderingsalternativ. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Ställer in upplösning under konvertering. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 150. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Föråldrad. |
| [setStartPage](#setStartPage-int-) | Ställer in startpositionen som du vill konvertera. Minsta värde är 1. Använd setEndPage(int) före setStartPage(int). |
| [setUserPassword](#setUserPassword-java.lang.String-) | Ställer in dokumentets UserPassword. |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

Initierar ett nytt {@code PdfConverter} objekt.

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
Initierar ett nytt {@code PdfConverter} objekt.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Kopplar ett PDF-dokument till {@link PdfConverter}-instansen för vidare bearbetning.

### bindPdf {#bindPdf-java.io.InputStream-}
Kopplar en PDF‑ström för konvertering.

### bindPdf {#bindPdf-java.lang.String-}
Kopplar en PDF‑fil för konvertering.

### close {#close--}
```
public void close()
```

Stäng PdfConverter‑instansen och frigör resurserna.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Endast för internt bruk

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Stäng PdfConverter‑instansen och frigör resurserna. Denna metod är föråldrad, använd close() istället.

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> Utför några initiala åtgärder för att konvertera ett pdf-dokument till bilder. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Hämtar sidans koordinattyp (Media-/Crop-boxar). CropBox-värdet används som standard.

**Returns:**
PageCoordinateType-element @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

Hämtar slutpositionen som du vill konvertera.

**Returns:**
int‑värde

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Hämtar formulärpresentationsläge.

**Returns:**
formulärspresentationstillstånd. @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
Sparar bilden till en ström med standardbildformatet - jpeg.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Sparar bilden till en ström med angivet bildformat.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
Sparar bilden till en ström med det angivna bildformatet, storlek och kvalitet.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Sparar bilden till en ström med angivet bildformat och kvalitet.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
Sparar bilden till en ström med det angivna bildformatet, storlek och kvalitet.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
Sparar bilden till en ström med det angivna bildformatet, dimensioner och kvalitet.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
Sparar bilden till en ström med angiven sidstorlek.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Sparar bilden till en ström med angiven sidstorlek.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Sparar bilden till en ström med angiven sidstorlek, bildformat och kvalitet.

### getNextImage {#getNextImage-java.lang.String-}
Sparar bilden till en fil med standardbildformatet - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> Sparar bilden till fil med det angivna bildformatet. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.DoConvert(); String prefix = @"D:\Test\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> Sparar bilden till fil med det angivna bildformatet, bildstorlek och kvalitet. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
Sparar bilden till en fil med angivet bildformat och kvalitet.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> Sparar bilden till fil med det angivna bildformatet och dimensionerna. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> Sparar bilden till en fil med det angivna bildformatet, dimensionerna och kvaliteten. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); String prefix = @\"D:\\Test\\\"; String suffix = \".jpg\"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
Sparar bilden till en fil med den angivna sidstorleken och standardbildformatet - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Sparar bilden till en fil med angiven sidstorlek och bildformat.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Sparar bilden till en fil med angiven sidstorlek, bildformat och kvalitet.

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Hämtar sidantalet.

**Returns:**
int‑värde

### getPassword {#getPassword--}
```
public String getPassword()
```

Hämtar dokumentets OwnerPassword.

**Returns:**
String värde

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Hämtar renderingsalternativ.

**Returns:**
renderingsalternativ.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Hämtar upplösning under konvertering. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 150.

**Returns:**
Upplösningselement

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Hämtar startpositionen som du vill konvertera. Minimivärdet är 1.

**Returns:**
int‑värde

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

Hämtar dokumentets UserPassword.

**Returns:**
String värde

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

Anger om pdf-filen har fler bilder eller inte.

**Returns:**
Kan hämta fler bilder eller inte, true om det går, annars false.

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Hämtar flaggan som styr synligheten för dolda områden på sidan. Metoden är föråldrad.

**Returns:**
booleskt värde

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
Slår ihop en lista med bildströmmar till en bildström.

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
Slår ihop en lista med tiff-strömmar till en tiff-ström med flera ramar.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-ström.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-ström.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-ström.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-ström.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-ström.

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFF(@\"D:\\Test\\test.tiff\"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFF(@\"D:\\Test\\test.tiff\"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(\"D:\\\\Test\\\\test.tiff\"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(@\"D:\\Test\\test.tiff\",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil.

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Ställer in sidkoordinattypen (Media/Crop-boxar). CropBox-värdet används som standard.

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

Ställer in slutpositionen som du vill konvertera. Använd setEndPage(int) före setStartPage(int).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Ställer in formulärets presentationsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | formulärspresentationstillstånd. @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
Ställer in dokumentets OwnerPassword.

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

Ställer in intervallet av sidor mellan vilka du vill konvertera.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startPage |  | int‑värde |
| EndPage |  | int‑värde |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Ställer in renderingsalternativ.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Ställer in upplösning under konvertering. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 150.

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Föråldrad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

Ställer in startpositionen som du vill konvertera. Minsta värde är 1. Använd setEndPage(int) före setStartPage(int).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setUserPassword {#setUserPassword-java.lang.String-}
Ställer in dokumentets UserPassword.
