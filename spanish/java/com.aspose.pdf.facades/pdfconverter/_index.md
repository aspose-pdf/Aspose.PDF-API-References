---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para convertir cada página de un archivo pdf a imágenes, soportando ahora BMP, JPEG, PNG y TIFF. Contenido soportado en los pdfs: imágenes, formularios, comentarios."
type: docs
weight: 390
url: /es/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

Representa una clase para convertir cada página de un archivo pdf a imágenes, soportando ahora BMP, JPEG, PNG y TIFF. Contenido soportado en PDFs: imágenes, formularios, comentarios.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfConverter](#PdfConverter--) | Inicializa un nuevo objeto {@code PdfConverter}. |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | Inicializa un nuevo objeto {@code PdfConverter}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Asocia un documento PDF a la instancia {@link PdfConverter} para su posterior procesamiento. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Asocia un flujo Pdf para la conversión. |
| [bindPdf](#bindPdf-java.lang.String-) | Asocia un archivo Pdf para la conversión. |
| [close](#close--) | Cierra la instancia de PdfConverter y libera los recursos. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Solo para uso interno |
| [dispose](#dispose--) | Cierra la instancia de PdfConverter y libera los recursos. Este método está obsoleto, use close() en su lugar. |
| [doConvert](#doConvert--) | <p> Realiza algunos trabajos iniciales para convertir un documento pdf a imágenes. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | Obtiene el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [getEndPage](#getEndPage--) | Obtiene la posición final que desea convertir. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtiene el modo de presentación del formulario. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Guarda la imagen en el flujo con el formato de imagen predeterminado - jpeg. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Guarda la imagen en el flujo con el formato de imagen especificado. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | Guarda la imagen en el flujo con el formato de imagen dado, tamaño y calidad. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Guarda la imagen en el flujo con el formato de imagen y calidad especificados. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | Guarda la imagen en el flujo con el formato de imagen dado, tamaño y calidad. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | Guarda la imagen en el flujo con el formato de imagen dado, dimensiones y calidad. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | Guarda la imagen en el flujo con el tamaño de página especificado. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Guarda la imagen en el flujo con el tamaño de página especificado. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Guarda la imagen en el flujo con el tamaño de página, formato de imagen y calidad especificados. |
| [getNextImage](#getNextImage-java.lang.String-) | Guarda la imagen en el archivo con el formato de imagen predeterminado - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> Guarda la imagen en el archivo con el formato de imagen dado. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = @"D:\\Test\\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> Guarda la imagen en un archivo con el formato de imagen dado, el tamaño de la imagen y la calidad. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | Guarda la imagen en un archivo con el formato de imagen dado y la calidad. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> Guarda la imagen en un archivo con el formato de imagen y las dimensiones dadas. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> Guarda la imagen en un archivo con el formato de imagen, dimensiones y calidad dados. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | Guarda la imagen en un archivo con el tamaño de página dado y el formato de imagen predeterminado - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Guarda la imagen en un archivo con el tamaño de página y el formato de imagen dados. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Guarda la imagen en un archivo con el tamaño de página, formato de imagen y calidad dados. |
| [getPageCount](#getPageCount--) | Obtiene el recuento de páginas. |
| [getPassword](#getPassword--) | Obtiene la OwnerPassword del documento. |
| [getRenderingOptions](#getRenderingOptions--) | Obtiene las opciones de renderizado. |
| [getResolution](#getResolution--) | Obtiene la resolución durante la conversión. Cuanta mayor sea la resolución, más lenta será la velocidad de conversión. El valor predeterminado es 150. |
| [getStartPage](#getStartPage--) | Obtiene la posición inicial que desea convertir. El valor mínimo es 1. |
| [getUserPassword](#getUserPassword--) | Obtiene la UserPassword del documento. |
| [hasNextImage](#hasNextImage--) | Indica si el archivo pdf tiene más imágenes o no. |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Obtiene la bandera que controla la visibilidad de áreas ocultas en la página. El método está obsoleto. |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | Fusiona una lista de flujos de imagen en un solo flujo de imagen. |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | Fusiona una lista de flujos tiff en un solo flujo tiff de múltiples fotogramas. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único flujo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único flujo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | Convierte cada página de un documento pdf a imágenes con y guarda las imágenes en un único archivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Convierte cada página de un documento pdf a imágenes con y guarda las imágenes en un único archivo TIFF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\\Test\\test.tiff",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Establece el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [setEndPage](#setEndPage-int-) | Establece la posición final que deseas convertir. usa setEndPage(int) antes de setStartPage(int) |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Establece el modo de presentación del formulario. |
| [setPassword](#setPassword-java.lang.String-) | Establece la OwnerPassword del documento. |
| [setRangeOfPages](#setRangeOfPages-int-int-) | Establece el rango de páginas entre las cuales deseas convertir. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Establece las opciones de renderizado. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Establece la resolución durante la conversión. Cuanta mayor sea la resolución, más lenta será la velocidad de conversión. El valor predeterminado es 150. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Obsoleto. |
| [setStartPage](#setStartPage-int-) | Establece la posición inicial que deseas convertir. El valor mínimo es 1. usa setEndPage(int) antes de setStartPage(int) |
| [setUserPassword](#setUserPassword-java.lang.String-) | Establece la UserPassword del documento. |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

Inicializa un nuevo objeto {@code PdfConverter}.

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
Inicializa un nuevo objeto {@code PdfConverter}.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Asocia un documento PDF a la instancia {@link PdfConverter} para su posterior procesamiento.

### bindPdf {#bindPdf-java.io.InputStream-}
Asocia un flujo Pdf para la conversión.

### bindPdf {#bindPdf-java.lang.String-}
Asocia un archivo Pdf para la conversión.

### close {#close--}
```
public void close()
```

Cierra la instancia de PdfConverter y libera los recursos.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Solo para uso interno

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Cierra la instancia de PdfConverter y libera los recursos. Este método está obsoleto, use close() en su lugar.

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> Realiza algunas tareas iniciales para convertir un documento pdf a imágenes. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtiene el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto.

**Returns:**
PageCoordinateType elemento @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

Obtiene la posición final que desea convertir.

**Returns:**
valor int

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtiene el modo de presentación del formulario.

**Returns:**
modo de presentación de formulario. @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
Guarda la imagen en el flujo con el formato de imagen predeterminado - jpeg.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Guarda la imagen en el flujo con el formato de imagen especificado.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
Guarda la imagen en el flujo con el formato de imagen dado, tamaño y calidad.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Guarda la imagen en el flujo con el formato de imagen y calidad especificados.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
Guarda la imagen en el flujo con el formato de imagen dado, tamaño y calidad.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
Guarda la imagen en el flujo con el formato de imagen dado, dimensiones y calidad.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
Guarda la imagen en el flujo con el tamaño de página especificado.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Guarda la imagen en el flujo con el tamaño de página especificado.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Guarda la imagen en el flujo con el tamaño de página, formato de imagen y calidad especificados.

### getNextImage {#getNextImage-java.lang.String-}
Guarda la imagen en el archivo con el formato de imagen predeterminado - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> Guarda la imagen en un archivo con el formato de imagen proporcionado. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.DoConvert(); String prefix = @"D:\Test\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> Guarda la imagen en un archivo con el formato de imagen proporcionado, el tamaño de la imagen y la calidad. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
Guarda la imagen en un archivo con el formato de imagen dado y la calidad.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> Guarda la imagen en un archivo con el formato de imagen y dimensiones dados. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> Guarda la imagen en un archivo con el formato de imagen, dimensiones y calidad dados. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
Guarda la imagen en un archivo con el tamaño de página dado y el formato de imagen predeterminado - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Guarda la imagen en un archivo con el tamaño de página y el formato de imagen dados.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Guarda la imagen en un archivo con el tamaño de página, formato de imagen y calidad dados.

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Obtiene el recuento de páginas.

**Returns:**
valor int

### getPassword {#getPassword--}
```
public String getPassword()
```

Obtiene la OwnerPassword del documento.

**Returns:**
valor String

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Obtiene las opciones de renderizado.

**Returns:**
opciones de renderizado.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtiene la resolución durante la conversión. Cuanta mayor sea la resolución, más lenta será la velocidad de conversión. El valor predeterminado es 150.

**Returns:**
Elemento Resolution

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Obtiene la posición inicial que desea convertir. El valor mínimo es 1.

**Returns:**
valor int

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

Obtiene la UserPassword del documento.

**Returns:**
valor String

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

Indica si el archivo pdf tiene más imágenes o no.

**Returns:**
Puede obtener más imágenes o no, verdadero si puede, o falso.

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Obtiene la bandera que controla la visibilidad de áreas ocultas en la página. El método está obsoleto.

**Returns:**
valor booleano

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
Fusiona una lista de flujos de imagen en un solo flujo de imagen.

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
Fusiona una lista de flujos tiff en un solo flujo tiff de múltiples fotogramas.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único flujo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único flujo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
Convierte cada página de un documento pdf a imágenes con y guarda las imágenes en un único archivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Convierte cada página de un documento pdf a imágenes con y guarda las imágenes en un único archivo TIFF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un único archivo TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(@\"D:\\Test\\test.tiff\",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF.

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Establece el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto.

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

Establece la posición final que deseas convertir. usa setEndPage(int) antes de setStartPage(int)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Establece el modo de presentación del formulario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | modo de presentación de formulario. @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
Establece la OwnerPassword del documento.

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

Establece el rango de páginas entre las cuales deseas convertir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startPage |  | valor int |
| EndPage |  | valor int |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Establece las opciones de renderizado.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Establece la resolución durante la conversión. Cuanta mayor sea la resolución, más lenta será la velocidad de conversión. El valor predeterminado es 150.

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Obsoleto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

Establece la posición inicial que deseas convertir. El valor mínimo es 1. usa setEndPage(int) antes de setStartPage(int)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setUserPassword {#setUserPassword-java.lang.String-}
Establece la UserPassword del documento.
