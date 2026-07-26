---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per convertire ogni pagina di un file pdf in immagini, supportando ora BMP, JPEG, PNG e TIFF. Contenuto supportato nei pdf: immagini, moduli, commenti."
type: docs
weight: 390
url: /it/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

Rappresenta una classe per convertire ogni pagina di un file pdf in immagini, supportando attualmente BMP, JPEG, PNG e TIFF. Contenuto supportato nei pdf: immagini, moduli, commenti.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfConverter](#PdfConverter--) | Inizializza un nuovo oggetto {@code PdfConverter}. |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | Inizializza un nuovo oggetto {@code PdfConverter}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Associa un documento PDF all'istanza {@link PdfConverter} per ulteriori elaborazioni. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Associa un flusso Pdf per la conversione. |
| [bindPdf](#bindPdf-java.lang.String-) | Associa un file Pdf per la conversione. |
| [close](#close--) | Chiude l'istanza di PdfConverter e rilascia le risorse. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Solo per uso interno |
| [dispose](#dispose--) | Chiude l'istanza di PdfConverter e rilascia le risorse. Questo metodo è obsoleto, usa close() invece. |
| [doConvert](#doConvert--) | <p> Esegui alcune operazioni iniziali per convertire un documento pdf in immagini. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | Ottiene il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [getEndPage](#getEndPage--) | Ottiene la posizione finale che desideri convertire. |
| [getFormPresentationMode](#getFormPresentationMode--) | Ottiene la modalità di presentazione del modulo. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Salva l'immagine nello stream con il formato immagine predefinito - jpeg. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Salva l'immagine nello stream con il formato immagine specificato. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | Salva l'immagine nello stream con il formato immagine fornito, dimensione e qualità. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Salva l'immagine nello stream con il formato immagine specificato e qualità. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | Salva l'immagine nello stream con il formato immagine fornito, dimensione e qualità. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | Salva l'immagine nello stream con il formato immagine fornito, dimensioni e qualità. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | Salva l'immagine nello stream con la dimensione di pagina specificata. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Salva l'immagine nello stream con la dimensione di pagina specificata. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Salva l'immagine nello stream con la dimensione di pagina specificata, formato immagine e qualità. |
| [getNextImage](#getNextImage-java.lang.String-) | Salva l'immagine su file con il formato immagine predefinito - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> Salva l'immagine su file con il formato immagine fornito. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = @"D:\\Test\\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> Salva l'immagine su file con il formato immagine fornito, le dimensioni dell'immagine e la qualità. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | Salva l'immagine su file con il formato immagine fornito e la qualità. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> Salva l'immagine su file con il formato immagine fornito e le dimensioni. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> Salva l'immagine su file con il formato immagine fornito, le dimensioni e la qualità. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | Salva l'immagine su file con la dimensione di pagina fornita e il formato immagine predefinito - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Salva l'immagine su file con la dimensione di pagina fornita e il formato immagine. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Salva l'immagine su file con la dimensione di pagina fornita, il formato immagine e la qualità. |
| [getPageCount](#getPageCount--) | Restituisce il conteggio delle pagine. |
| [getPassword](#getPassword--) | Restituisce la OwnerPassword del documento. |
| [getRenderingOptions](#getRenderingOptions--) | Ottiene le opzioni di rendering. |
| [getResolution](#getResolution--) | Restituisce la risoluzione durante la conversione. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 150. |
| [getStartPage](#getStartPage--) | Restituisce la posizione iniziale da convertire. Il valore minimo è 1. |
| [getUserPassword](#getUserPassword--) | Restituisce la UserPassword del documento. |
| [hasNextImage](#hasNextImage--) | Indica se il file PDF contiene altre immagini o meno. |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Restituisce il flag che controlla la visibilità delle aree nascoste nella pagina. Il metodo è deprecato. |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | Unisce l'elenco di stream di immagini in un unico stream di immagini. |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | Unisce l'elenco di stream TIFF in un unico stream TIFF a più fotogrammi. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico stream TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico stream TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico stream TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico stream TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Converte ogni pagina di un documento PDF in immagini con dimensione di pagina e salva le immagini in un unico stream TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Converte ogni pagina di un documento PDF in immagini con dimensione di pagina e salva le immagini in un unico stream TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico file TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico file TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | Converte ogni pagina di un documento PDF in immagini con dimensione di pagina e salva le immagini in un unico file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Converte ogni pagina di un documento PDF in immagini con dimensione di pagina e salva le immagini in un unico file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | Converte ogni pagina di un documento PDF in immagini con e salva le immagini in un unico file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converte ogni pagina di un documento PDF in immagini con e salva le immagini in un unico file TIFF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\\Test\\test.tiff",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Imposta il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [setEndPage](#setEndPage-int-) | Imposta la posizione finale che desideri convertire. usa setEndPage(int) prima di setStartPage(int) |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Imposta la modalità di presentazione del modulo. |
| [setPassword](#setPassword-java.lang.String-) | Imposta la OwnerPassword del documento. |
| [setRangeOfPages](#setRangeOfPages-int-int-) | Imposta l'intervallo di pagine tra le quali desideri convertire. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Imposta le opzioni di rendering. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Imposta la risoluzione durante la conversione. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 150. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Obsoleto. |
| [setStartPage](#setStartPage-int-) | Imposta la posizione iniziale che desideri convertire. Il valore minimo è 1. usa setEndPage(int) prima di setStartPage(int) |
| [setUserPassword](#setUserPassword-java.lang.String-) | Imposta la UserPassword del documento. |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

Inizializza un nuovo oggetto {@code PdfConverter}.

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
Inizializza un nuovo oggetto {@code PdfConverter}.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Associa un documento PDF all'istanza {@link PdfConverter} per ulteriori elaborazioni.

### bindPdf {#bindPdf-java.io.InputStream-}
Associa un flusso Pdf per la conversione.

### bindPdf {#bindPdf-java.lang.String-}
Associa un file Pdf per la conversione.

### close {#close--}
```
public void close()
```

Chiude l'istanza di PdfConverter e rilascia le risorse.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Solo per uso interno

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Chiude l'istanza di PdfConverter e rilascia le risorse. Questo metodo è obsoleto, usa close() invece.

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> Esegui alcune operazioni iniziali per convertire un documento pdf in immagini. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Ottiene il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita.

**Returns:**
Elemento PageCoordinateType @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

Ottiene la posizione finale che desideri convertire.

**Returns:**
valore int

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Ottiene la modalità di presentazione del modulo.

**Returns:**
modalità di presentazione del modulo. @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
Salva l'immagine nello stream con il formato immagine predefinito - jpeg.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Salva l'immagine nello stream con il formato immagine specificato.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
Salva l'immagine nello stream con il formato immagine fornito, dimensione e qualità.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Salva l'immagine nello stream con il formato immagine specificato e qualità.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
Salva l'immagine nello stream con il formato immagine fornito, dimensione e qualità.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
Salva l'immagine nello stream con il formato immagine fornito, dimensioni e qualità.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
Salva l'immagine nello stream con la dimensione di pagina specificata.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Salva l'immagine nello stream con la dimensione di pagina specificata.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Salva l'immagine nello stream con la dimensione di pagina specificata, formato immagine e qualità.

### getNextImage {#getNextImage-java.lang.String-}
Salva l'immagine su file con il formato immagine predefinito - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> Salva l'immagine su file con il formato immagine fornito. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.DoConvert(); String prefix = @"D:\Test\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> Salva l'immagine su file con il formato immagine fornito, le dimensioni dell'immagine e la qualità. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
Salva l'immagine su file con il formato immagine fornito e la qualità.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> Salva l'immagine su file con il formato immagine fornito e le dimensioni. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> Salva l'immagine su file con il formato immagine fornito, le dimensioni e la qualità. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
Salva l'immagine su file con la dimensione di pagina fornita e il formato immagine predefinito - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Salva l'immagine su file con la dimensione di pagina fornita e il formato immagine.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Salva l'immagine su file con la dimensione di pagina fornita, il formato immagine e la qualità.

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Restituisce il conteggio delle pagine.

**Returns:**
valore int

### getPassword {#getPassword--}
```
public String getPassword()
```

Restituisce la OwnerPassword del documento.

**Returns:**
valore String

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Ottiene le opzioni di rendering.

**Returns:**
opzioni di rendering.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Restituisce la risoluzione durante la conversione. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 150.

**Returns:**
Elemento Resolution

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Restituisce la posizione iniziale da convertire. Il valore minimo è 1.

**Returns:**
valore int

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

Restituisce la UserPassword del documento.

**Returns:**
valore String

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

Indica se il file PDF contiene altre immagini o meno.

**Returns:**
Può ottenere altre immagini o no, true se può, false altrimenti.

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Restituisce il flag che controlla la visibilità delle aree nascoste nella pagina. Il metodo è deprecato.

**Returns:**
valore booleano

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
Unisce l'elenco di stream di immagini in un unico stream di immagini.

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
Unisce l'elenco di stream TIFF in un unico stream TIFF a più fotogrammi.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico file TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico stream TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico stream TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico stream TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico stream TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Converte ogni pagina di un documento PDF in immagini con dimensione di pagina e salva le immagini in un unico stream TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Converte ogni pagina di un documento PDF in immagini con dimensione di pagina e salva le immagini in un unico stream TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converte ogni pagina di un documento PDF in immagini con dimensioni e salva le immagini in un unico file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
Converte ogni pagina di un documento PDF in immagini con dimensione di pagina e salva le immagini in un unico file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Converte ogni pagina di un documento PDF in immagini con dimensione di pagina e salva le immagini in un unico file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
Converte ogni pagina di un documento PDF in immagini con e salva le immagini in un unico file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converte ogni pagina di un documento PDF in immagini con e salva le immagini in un unico file TIFF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Converte ogni pagina di un documento PDF in immagini e salva le immagini in un unico stream TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\Test\test.tiff",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF.

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Imposta il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita.

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

Imposta la posizione finale che desideri convertire. usa setEndPage(int) prima di setStartPage(int)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Imposta la modalità di presentazione del modulo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | modalità di presentazione del modulo. @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
Imposta la OwnerPassword del documento.

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

Imposta l'intervallo di pagine tra le quali desideri convertire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startPage |  | valore int |
| EndPage |  | valore int |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Imposta le opzioni di rendering.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Imposta la risoluzione durante la conversione. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 150.

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Obsoleto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

Imposta la posizione iniziale che desideri convertire. Il valore minimo è 1. usa setEndPage(int) prima di setStartPage(int)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setUserPassword {#setUserPassword-java.lang.String-}
Imposta la UserPassword del documento.
