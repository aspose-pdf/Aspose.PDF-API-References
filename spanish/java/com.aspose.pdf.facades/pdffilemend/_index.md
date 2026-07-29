---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para añadir textos e imágenes en las páginas de un documento PDF existente."
type: docs
weight: 500
url: /es/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

Representa una clase para añadir textos e imágenes en las páginas de un documento PDF existente.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | Constructor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | Constructor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Constructor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Constructor. |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Constructor. |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Constructor. |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | Constructor. |

## Métodos

| Método | Descripción |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | No implementado. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | No implementado. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | No implementado. |
| [close](#close--) | Cierra el objeto PdfFileMend. |
| [dispose](#dispose--) | Cierra el objeto PdfFileMend. Este método está obsoleto, use close() en su lugar. |
| [getDocument](#getDocument--) | Obtiene el documento {@code PdfFileMend} en el que está trabajando. |
| [getInputFile](#getInputFile--) | Obtiene el archivo de entrada. |
| [getInputStream](#getInputStream--) | Obtiene el flujo de entrada. |
| [getOutputFile](#getOutputFile--) | Obtiene el archivo de salida. |
| [getOutputStream](#getOutputStream--) | Obtiene el flujo de salida. |
| [getTextPositioningMode](#getTextPositioningMode--) | Obtiene la estrategia de posicionamiento de texto. {@code PositioningMode} El modo predeterminado es Legacy. |
| [getWrapMode](#getWrapMode--) | Obtiene el algoritmo de ajuste de línea. |
| [save](#save-java.io.OutputStream-) | Guarda el documento PDF en el archivo especificado. |
| [save](#save-java.lang.String-) | Guarda el documento PDF en el archivo especificado. |
| [setInputFile](#setInputFile-java.lang.String-) | Obsoleto. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Establece el flujo de entrada. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Establece el archivo de salida. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Este método está obsoleto. Use el método Save(outputStream) para obtener los resultados de la fachada. |
| [setTextPositioningMode](#setTextPositioningMode-int-) | Establece la estrategia de posicionamiento de texto. {@code PositioningMode} El modo predeterminado es Legacy. |
| [setWordWrap](#setWordWrap-boolean-) | Establece un valor booleano que indica el ajuste de línea en los métodos AddText. Si el valor es true, el texto en FormattedText se ajustará. Por defecto, el valor es false. |
| [setWrapMode](#setWrapMode-int-) | Establece el algoritmo de ajuste de línea. |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

Constructor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
Constructor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Constructor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
Constructor.

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
Constructor.

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
Constructor.

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
Constructor.

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
No implementado.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
No implementado.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
No implementado.

### close {#close--}
```
public void close()
```

Cierra el objeto PdfFileMend.

### dispose {#dispose--}
```
public void dispose()
```

Cierra el objeto PdfFileMend. Este método está obsoleto, use close() en su lugar.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obtiene el documento {@code PdfFileMend} en el que está trabajando.

**Returns:**
Objeto IDocument

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Obtiene el archivo de entrada.

**Returns:**
valor String

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Obtiene el flujo de entrada.

**Returns:**
flujo de entrada.

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Obtiene el archivo de salida.

**Returns:**
valor String

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Obtiene el flujo de salida.

**Returns:**
flujo de salida.

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

Obtiene la estrategia de posicionamiento de texto. {@code PositioningMode} El modo predeterminado es Legacy.

**Returns:**
Elemento PositioningMode @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Obtiene el algoritmo de ajuste de línea.

**Returns:**
valor WordWrapMode @see WordWrapMode

### save {#save-java.io.OutputStream-}
Guarda el documento PDF en el archivo especificado.

### save {#save-java.lang.String-}
Guarda el documento PDF en el archivo especificado.

### setInputFile {#setInputFile-java.lang.String-}
Obsoleto.

### setInputStream {#setInputStream-java.io.InputStream-}
Establece el flujo de entrada.

### setOutputFile {#setOutputFile-java.lang.String-}
Establece el archivo de salida.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Este método está obsoleto. Use el método Save(outputStream) para obtener los resultados de la fachada.

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

Establece la estrategia de posicionamiento de texto. {@code PositioningMode} El modo predeterminado es Legacy.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento PositioningMode @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

Establece un valor booleano que indica el ajuste de línea en los métodos AddText. Si el valor es true, el texto en FormattedText se ajustará. Por defecto, el valor es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Establece el algoritmo de ajuste de línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | WordWrapMode elemento @see WordWrapMode |
