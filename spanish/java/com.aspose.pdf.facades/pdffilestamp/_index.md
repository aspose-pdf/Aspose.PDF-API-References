---
title: "PdfFileStamp"
linktitle: "PdfFileStamp"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase para añadir sellos (marca de agua o fondo) a archivos PDF."
type: docs
weight: 540
url: /es/java/com.aspose.pdf.facades/pdffilestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStamp, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStamp, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStamp

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStamp extends SaveableFacade implements IPdfFileStamp
```

Clase para añadir sellos (marca de agua o fondo) a archivos PDF.

## Campos

| Campo | Descripción |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Posición inferior izquierda. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Posición inferior central. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Posición inferior derecha. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Posición izquierda. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Posición derecha. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Posición superior izquierda. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Posición media superior. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Posición superior derecha. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFileStamp](#PdfFileStamp--) | <p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-) | <p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-) | <p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-) | <p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.lang.String-java.lang.String-) | <p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.lang.String-java.lang.String-boolean-) | <p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |

## Métodos

| Método | Descripción |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> Añade un pie de página a las páginas del documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Agrega pie de página a las páginas del documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> Agrega una imagen como pie de página de la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> Agrega una imagen como pie de página de la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> Agrega una imagen como pie de página a las páginas del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Agrega imagen como pie de página de las páginas. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> Agrega encabezado a la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Agrega encabezado a las páginas del archivo. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> Agrega una imagen como encabezado en las páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> Agrega una imagen en la parte superior de la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); IjnputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> Agrega una imagen como encabezado a las páginas del archivo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InpetuStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> Agrega una imagen como encabezado en las páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> Agrega número de página a la página. El número de página puede contener el signo # que será reemplazado por el número de página. El número de página se coloca en la parte inferior de la página centrado horizontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> Agrega número de página en la posición especificada de la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> Agrega número de página a las páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> Agrega número de página a las páginas del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> Agrega número de página al archivo. El texto del número de página puede contener el signo # que será reemplazado por el número de la página. El número de página se coloca en la parte inferior de la página centrado horizontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> Agrega número de página en la posición especificada de la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> Agrega número de página a las páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> Agrega número de página a las páginas del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> Agrega sello al archivo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity(0.8f); stamp.isBackground(true); stamp.bindImage(\"image.jpg\"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> Cierra los archivos abiertos y guarda los cambios. Advertencia. Si se especifican flujos de entrada o salida, no se cierran con el método Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | Obsoleto. |
| [getAttachmentName](#getAttachmentName--) | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [getContentDisposition](#getContentDisposition--) | Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacena en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline. |
| [getInputFile](#getInputFile--) | Obtiene el nombre y la ruta del archivo de entrada. |
| [getInputStream](#getInputStream--) | Obtiene el flujo de entrada. Obsolete(\"Use bindPdf(inputFile) method for facade initialization.\") |
| [getKeepSecurity](#getKeepSecurity--) | Mantiene la seguridad si es verdadero. (Esta función se implementará en próximas versiones). |
| [getNumberingStyle](#getNumberingStyle--) | Obtiene o establece el estilo de numeración de página. Valores posibles: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [getOptimizeSize](#getOptimizeSize--) | Obtiene o establece la bandera de optimización. |
| [getOutputFile](#getOutputFile--) | Obtiene el nombre y la ruta del archivo de salida. Obsolete(\"Use Save(outputFile) method for getting facade results.\") |
| [getOutputStream](#getOutputStream--) | Obtiene la secuencia de salida. |
| [getPageHeight](#getPageHeight--) | <p> Obtiene la altura de la primera página en el archivo de origen. </p> |
| [getPageNumberRotation](#getPageNumberRotation--) | Obtiene la rotación del número de página. La rotación está en grados. El valor predeterminado es 0. |
| [getPageWidth](#getPageWidth--) | <p> Obtiene el ancho de la primera página en el archivo de entrada. </p> |
| [getSaveOptions](#getSaveOptions--) | Obtiene las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions. |
| [getStampId](#getStampId--) | ID del sello del siguiente sello agregado (incluyendo encabezados/pies de página/números de página). |
| [getStartingNumber](#getStartingNumber--) | Obtiene o establece el número inicial para la primera página en el archivo de entrada. Las páginas siguientes se numerarán a partir de este valor. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacena en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión. |
| [setInputFile](#setInputFile-java.lang.String-) | Establece el nombre y la ruta del archivo de entrada. Obsolete(\"Use bindPdf(inputFile) method for facade initialization.\") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Establece la secuencia de entrada. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Mantiene la seguridad si es verdadero. (Esta función se implementará en próximas versiones). |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Obtiene o establece el estilo de numeración de página. Valores posibles: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Obtiene o establece la bandera de optimización. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Establece el nombre y la ruta del archivo de salida. Obsolete(\"Use Save(outputFile) method for getting facade results.\") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Establece o establece la secuencia de salida. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Establece la rotación del número de página. La rotación está en grados. El valor predeterminado es 0. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Establece las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions. |
| [setStampId](#setStampId-int-) | ID del sello del siguiente sello agregado (incluyendo encabezados/pies de página/números de página). |
| [setStartingNumber](#setStartingNumber-int-) | <p> Establece el número inicial para la primera página en el archivo de entrada. Las páginas siguientes se numerarán a partir de este valor. Por ejemplo, si StartingNumber se establece en 100, las páginas del documento tendrán los números 100, 101, 102... </p> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

Posición inferior izquierda.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

Posición inferior central.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

Posición inferior derecha.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

Posición izquierda.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

Posición derecha.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

Posición superior izquierda.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

Posición media superior.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

Posición superior derecha.

### PdfFileStamp {#PdfFileStamp--}
```
public PdfFileStamp()
```

<p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-}
<p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-}
<p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-}
<p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.lang.String-java.lang.String-}
<p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStamp {#PdfFileStamp-java.lang.String-java.lang.String-boolean-}
<p> Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> Añade un pie de página a las páginas del documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Agrega pie de página a las páginas del documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> Agrega una imagen como pie de página de la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> Agrega una imagen como pie de página de la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(new FileInputStream("image.jpg"), 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> Agrega una imagen como pie de página a las páginas del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
Agrega imagen como pie de página de las páginas.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> Agrega encabezado a la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Agrega encabezado a las páginas del archivo. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> Agrega una imagen como encabezado en las páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> Agrega una imagen en la parte superior de la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); IjnputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(new FileInputStream("image.jpg"), 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> Agrega una imagen como encabezado a las páginas del archivo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InpetuStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> Agrega una imagen como encabezado en las páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg")); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> Agrega número de página a la página. El número de página puede contener el signo # que será reemplazado por el número de página. El número de página se coloca en la parte inferior de la página centrado horizontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> Agrega número de página en la posición especificada de la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> Agrega número de página a las páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> Agrega número de página a las páginas del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> Agrega número de página al archivo. El texto del número de página puede contener el signo # que será reemplazado por el número de la página. El número de página se coloca en la parte inferior de la página centrado horizontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> Agrega número de página en la posición especificada de la página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> Agrega número de página a las páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> Agrega número de página a las páginas del documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> Agrega sello al archivo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity(0.8f); stamp.isBackground(true); stamp.bindImage(\"image.jpg\"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> Cierra los archivos abiertos y guarda los cambios. Advertencia. Si se especifican flujos de entrada o salida, no se cierran con el método Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsoleto.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

**Returns:**
valor String

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacena en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline.

**Returns:**
Elemento ContentDisposition @see com.aspose.pdf.ContentDisposition

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

Obtiene el nombre y la ruta del archivo de entrada.

**Returns:**
valor String

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Obtiene el flujo de entrada. Obsolete(\"Use bindPdf(inputFile) method for facade initialization.\")

**Returns:**
Objeto InputStream

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

Mantiene la seguridad si es verdadero. (Esta función se implementará en próximas versiones).

**Returns:**
valor booleano

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Obtiene o establece el estilo de numeración de página. Valores posibles: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase

**Returns:**
Elemento NumberingStyle @see NumberingStyle

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtiene o establece la bandera de optimización.

**Returns:**
valor booleano

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Obtiene el nombre y la ruta del archivo de salida. Obsolete(\"Use Save(outputFile) method for getting facade results.\")

**Returns:**
valor String

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Obtiene la secuencia de salida.

**Returns:**
Objeto OutputStream

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> Obtiene la altura de la primera página en el archivo de origen. </p>

**Returns:**
valor float <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Height = \" + fileStamp.getPageHeight()); fileStamp.close(); </pre>

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

Obtiene la rotación del número de página. La rotación está en grados. El valor predeterminado es 0.

**Returns:**
valor flotante

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> Obtiene el ancho de la primera página en el archivo de entrada. </p>

**Returns:**
valor float <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Width = \" + fileStamp.getPageWidth()); fileStamp.close(); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtiene las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions.

**Returns:**
Objeto SaveOptions

### getStampId {#getStampId--}
```
public int getStampId()
```

ID del sello del siguiente sello agregado (incluyendo encabezados/pies de página/números de página).

**Returns:**
valor int

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Obtiene o establece el número inicial para la primera página en el archivo de entrada. Las páginas siguientes se numerarán a partir de este valor.

**Returns:**
valor int

### setAttachmentName {#setAttachmentName-java.lang.String-}
Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Establece cómo se almacenará el contenido cuando el resultado de la operación se almacena en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión.

### setInputFile {#setInputFile-java.lang.String-}
Establece el nombre y la ruta del archivo de entrada. Obsolete(\"Use bindPdf(inputFile) method for facade initialization.\")

### setInputStream {#setInputStream-java.io.InputStream-}
Establece la secuencia de entrada.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

Mantiene la seguridad si es verdadero. (Esta función se implementará en próximas versiones).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Obtiene o establece el estilo de numeración de página. Valores posibles: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Obtiene o establece la bandera de optimización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setOutputFile {#setOutputFile-java.lang.String-}
Establece el nombre y la ruta del archivo de salida. Obsolete(\"Use Save(outputFile) method for getting facade results.\")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Establece o establece la secuencia de salida.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```

Establece la rotación del número de página. La rotación está en grados. El valor predeterminado es 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Establece las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions.

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

ID del sello del siguiente sello agregado (incluyendo encabezados/pies de página/números de página).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> Establece el número inicial para la primera página en el archivo de entrada. Las páginas siguientes se numerarán a partir de este valor. Por ejemplo, si StartingNumber se establece en 100, las páginas del documento tendrán los números 100, 101, 102... </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.setStartingNumber(100); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre> |
