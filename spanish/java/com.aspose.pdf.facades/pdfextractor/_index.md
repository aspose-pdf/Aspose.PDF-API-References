---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase para extraer imágenes y texto de documentos PDF."
type: docs
weight: 400
url: /es/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

Clase para extraer imágenes y texto de documentos PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * Vincula un documento Pdf para edición. / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * Vincula un documento Pdf para edición. / * / * / * |

## Métodos

| Método | Descripción |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> Vincula el documento PDF desde un flujo. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> Vincula el archivo PDF de entrada. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre> |
| [extractAttachment](#extractAttachment--) | Extrae los adjuntos de un documento Pdf. |
| [extractAttachment](#extractAttachment-java.lang.String-) | Extrae los adjuntos de un documento Pdf. |
| [extractImage](#extractImage--) | <p> Extrae imágenes del archivo PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> Obtiene todos los contenedores de Contenido Marcado como imágenes separadas. </p> <p> Cada Contenido Marcado se guardará como imagen con formato png nombrada con {@code MCID_<ID number of block for the page>.png} |
| [extractText](#extractText--) | <p> Extrae texto de un documento Pdf. </p> <hr> <pre> El primer ejemplo muestra cómo extraer todo el texto del archivo PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> El segundo ejemplo muestra cómo extraer el texto de cada página en un archivo txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> Extrae texto de un documento Pdf. </p> <hr> <pre> El primer ejemplo muestra cómo extraer todo el texto del archivo PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> El segundo ejemplo muestra cómo extraer el texto de cada página en un archivo txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | Solo para uso interno |
| [getAttachment](#getAttachment--) | <p> Guarda todos los archivos adjuntos en flujos. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> Guarda todos los archivos adjuntos en flujos. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | Obtiene la lista de adjuntos. |
| [getAttachNames](#getAttachNames--) | <p> Devuelve la lista de adjuntos en el archivo PDF. Nota: ExtractAttachments debe llamarse antes de usar este método. </p> <hr> <pre> El ejemplo muestra cómo extraer los nombres de los adjuntos del archivo PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> Obtiene la página final en el rango de páginas donde se realizará la operación de extracción. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> Establece el modo para el proceso de extracción de imágenes. </p> <hr> El valor predeterminado es ExtractImageMode.DefinedInResources que extrae todas las imágenes definidas en los recursos. Para extraer las imágenes realmente mostradas debe usarse el modo ExtractImageMode.ActuallyUsed. |
| [getExtractTextMode](#getExtractTextMode--) | <p> Obtiene el modo para el resultado de extracción de texto. </p> <hr> <pre> El ejemplo muestra el uso de la propiedad {@code ExtractTextMode} en un escenario de extracción de texto. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> <p> Valor: 0 es modo de texto puro y 1 es modo de ordenamiento bruto. El predeterminado es 0. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Recupera la siguiente imagen del archivo PDF y la almacena en un flujo. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Recupera la siguiente imagen del archivo PDF y la almacena en un flujo con el formato de imagen especificado. |
| [getNextImage](#getNextImage-java.lang.String-) | <p> Recupera la siguiente imagen del documento PDF. Nota: ExtractImage debe llamarse antes de usar este método. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Recupera la siguiente imagen del documento PDF con el formato de imagen especificado. Nota: ExtractImage debe llamarse antes de usar este método. |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> Guarda el texto de una página en un flujo. </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> Guarda el texto de una página en un archivo. </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @\"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | Obtiene la contraseña del archivo de entrada. |
| [getResolution](#getResolution--) | Obtiene la resolución de las imágenes extraídas. El valor predeterminado es 150. Las imágenes que tienen un valor de resolución mayor son más nítidas. Sin embargo, aumentar el valor de resolución incrementa el tiempo y la memoria necesarios para extraer imágenes. Por lo general, para obtener una imagen clara basta con establecer la resolución en 150 o 300. |
| [getStartPage](#getStartPage--) | Objeto Pdf.Engine que representa un documento PDF. |
| [getText](#getText-java.io.OutputStream-) | Guarda el texto en un flujo. ver también:{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | Guarda el texto en un flujo. ver también:{@code ExtractText} |
| [getText](#getText-java.lang.String-) | Guarda el texto en un archivo. ver también:{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | Obtiene opciones de búsqueda de texto. |
| [hasNextImage](#hasNextImage--) | <p> Comprueba si hay más imágenes accesibles en el documento PDF. Nota: ExtractImage debe llamarse antes de usar este método. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> Indica si se pueden obtener más textos o no. </p> <hr> <pre> The example demonstrates the {@code HasNextPageText} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | Es verdadero cuando el texto contiene símbolos hebreos o árabes. Este caso debe considerarse especialmente porque las funciones de cadena cambian su comportamiento y comienzan a procesar el texto de derecha a izquierda (excepto los números y otros caracteres no textuales). |
| [setEndPage](#setEndPage-int-) | <p> Establece la página final en el rango de páginas donde se realizará la operación de extracción. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> Establece el modo para el proceso de extracción de imágenes. </p> <hr> El valor predeterminado es ExtractImageMode.DefinedInResources que extrae todas las imágenes definidas en los recursos. Para extraer las imágenes realmente mostradas debe usarse el modo ExtractImageMode.ActuallyUsed. |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> Establece el modo para el resultado de la extracción de texto. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\\\Text\\\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\\\Text\\\\text.txt\"); </pre> Valor: 0 es modo de texto puro y 1 es modo de ordenamiento bruto. El predeterminado es 0. |
| [setPassword](#setPassword-java.lang.String-) | Establece la contraseña del archivo de entrada. |
| [setResolution](#setResolution-int-) | Establezca la resolución para las imágenes extraídas. El valor predeterminado es 150. Las imágenes que tienen un valor de resolución mayor son más nítidas. Sin embargo, aumentar el valor de resolución incrementa el tiempo y la memoria necesarios para extraer imágenes. Normalmente, para obtener una imagen clara basta con establecer la resolución en 150 o 300. |
| [setStartPage](#setStartPage-int-) | <p> Establece la página inicial en el rango de páginas donde se realizará la operación de extracción. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Establece opciones de búsqueda de texto. |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * Vincula un documento Pdf para edición. / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * Vincula un documento Pdf para edición. / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> Vincula el documento PDF desde un flujo. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> Vincula el archivo PDF de entrada. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

Extrae los adjuntos de un documento Pdf.

### extractAttachment {#extractAttachment-java.lang.String-}
Extrae los adjuntos de un documento Pdf.

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> Extrae imágenes del archivo PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> Obtiene todos los contenedores de Contenido Marcado como imágenes separadas. </p> <p> Cada Contenido Marcado se guardará como imagen con formato png nombrada con {@code MCID_<ID number of block for the page>.png}

### extractText {#extractText--}
```
public void extractText()
```

<p> Extrae texto de un documento Pdf. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\Text\text.pdf"); extractor.extractText(); extractor.getText("D:\Text\text.txt"); </pre> <p> El segundo ejemplo muestra cómo extraer el texto de cada página en un archivo txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> Extrae texto de un documento Pdf. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\Text\text.pdf"); extractor.extractText(); extractor.getText("D:\Text\text.txt"); </pre> <p> El segundo ejemplo muestra cómo extraer el texto de cada página en un archivo txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
Solo para uso interno

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> Guarda todos los archivos adjuntos en flujos. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
La matriz de flujo del archivo adjunto en el documento pdf.

### getAttachment {#getAttachment-java.lang.String-}
<p> Guarda todos los archivos adjuntos en flujos. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
La matriz de flujo del archivo adjunto en el documento pdf.

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

Obtiene la lista de adjuntos.

**Returns:**
Devuelve una List<FileSpecificatio>.

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> Devuelve la lista de adjuntos en el archivo PDF. Nota: ExtractAttachments debe llamarse antes de usar este método. </p> <hr> <pre> El ejemplo muestra cómo extraer los nombres de los adjuntos del archivo PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
Lista de archivos adjuntos

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> Obtiene la página final en el rango de páginas donde se realizará la operación de extracción. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
página final.

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> Establece el modo para el proceso de extracción de imágenes. </p> <hr> El valor predeterminado es ExtractImageMode.DefinedInResources que extrae todas las imágenes definidas en los recursos. Para extraer las imágenes realmente mostradas debe usarse el modo ExtractImageMode.ActuallyUsed.

**Returns:**
Valor de ExtractImageMode @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> Obtiene el modo para el resultado de extracción de texto. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\Text\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\Text\text.txt"); </pre> <p> Valor: 0 es modo de texto puro y 1 es modo de ordenamiento bruto. El valor predeterminado es 0.

**Returns:**
resultado de extracción de texto.

### getNextImage {#getNextImage-java.io.OutputStream-}
Recupera la siguiente imagen del archivo PDF y la almacena en un flujo.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Recupera la siguiente imagen del archivo PDF y la almacena en un flujo con el formato de imagen especificado.

### getNextImage {#getNextImage-java.lang.String-}
<p> Recupera la siguiente imagen del documento PDF. Nota: ExtractImage debe llamarse antes de usar este método. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
Recupera la siguiente imagen del documento PDF con el formato de imagen especificado. Nota: ExtractImage debe llamarse antes de usar este método.

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> Guarda el texto de una página en un flujo. </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> Guarda el texto de una página en un archivo. </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @\"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @\"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

Obtiene la contraseña del archivo de entrada.

**Returns:**
valor String

### getResolution {#getResolution--}
```
public int getResolution()
```

Obtiene la resolución de las imágenes extraídas. El valor predeterminado es 150. Las imágenes que tienen un valor de resolución mayor son más nítidas. Sin embargo, aumentar el valor de resolución incrementa el tiempo y la memoria necesarios para extraer imágenes. Por lo general, para obtener una imagen clara basta con establecer la resolución en 150 o 300.

**Returns:**
valor int

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Objeto Pdf.Engine que representa un documento PDF.

**Returns:**
página inicial en el rango de páginas.

### getText {#getText-java.io.OutputStream-}
Guarda el texto en un flujo. ver también:{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
Guarda el texto en un flujo. ver también:{@code ExtractText}

### getText {#getText-java.lang.String-}
Guarda el texto en un archivo. ver también:{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Obtiene opciones de búsqueda de texto.

**Returns:**
opciones de búsqueda de texto.

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> Comprueba si hay más imágenes accesibles en el documento PDF. Nota: ExtractImage debe llamarse antes de usar este método. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre>

**Returns:**
Verdadero si hay más imágenes accesibles.

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> Indica si se pueden obtener más textos o no. </p> <hr> <pre> The example demonstrates the {@code HasNextPageText} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
Puede obtener más textos o no, verdadero indica que puede, falso indica que no.

### isBidi {#isBidi--}
```
public boolean isBidi()
```

Es verdadero cuando el texto contiene símbolos hebreos o árabes. Este caso debe considerarse especialmente porque las funciones de cadena cambian su comportamiento y comienzan a procesar el texto de derecha a izquierda (excepto los números y otros caracteres no textuales).

**Returns:**
valor booleano

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> Establece la página final en el rango de páginas donde se realizará la operación de extracción. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | página final. |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> Establece el modo para el proceso de extracción de imágenes. </p> <hr> El valor predeterminado es ExtractImageMode.DefinedInResources que extrae todas las imágenes definidas en los recursos. Para extraer las imágenes realmente mostradas debe usarse el modo ExtractImageMode.ActuallyUsed.

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> Establece el modo para el resultado de extracción de texto. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\Text\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\Text\text.txt"); </pre> Valor: 0 es modo de texto puro y 1 es modo de ordenamiento bruto. El valor predeterminado es 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | resultado de extracción de texto. |

### setPassword {#setPassword-java.lang.String-}
Establece la contraseña del archivo de entrada.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Establezca la resolución para las imágenes extraídas. El valor predeterminado es 150. Las imágenes que tienen un valor de resolución mayor son más nítidas. Sin embargo, aumentar el valor de resolución incrementa el tiempo y la memoria necesarios para extraer imágenes. Normalmente, para obtener una imagen clara basta con establecer la resolución en 150 o 300.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> Establece la página inicial en el rango de páginas donde se realizará la operación de extracción. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | página inicial en el rango de páginas. |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Establece opciones de búsqueda de texto.
