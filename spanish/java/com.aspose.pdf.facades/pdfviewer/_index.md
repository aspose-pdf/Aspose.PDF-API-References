---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para visualizar o imprimir un PDF."
type: docs
weight: 610
url: /es/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

Representa una clase para visualizar o imprimir un PDF.

## Campos

| Campo | Descripción |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | Añade/elimina la suscripción al evento de impresión de la última página. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Añade/elimina la suscripción al evento de impresión de la última página. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfViewer](#PdfViewer--) | Inicializa un nuevo objeto {@code PdfViewer}. |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | Inicializa un nuevo objeto {@code PdfViewer}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Inicializa la fachada. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Inicializa la fachada. |
| [bindPdf](#bindPdf-java.lang.String-) | Inicializa la fachada. |
| [close](#close--) | Cierra el archivo Pdf actual. |
| [closePdfFile](#closePdfFile--) | Cierra el archivo Pdf actual. |
| [decodeAllPages](#decodeAllPages--) | Obtiene las páginas del archivo pdf actual. |
| [decodePage](#decodePage-int-) | Decodifica una página de un archivo Pdf. |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Decodifica la página a BufferedImage |
| [dispose](#dispose--) | Libera los recursos de la fachada. Este método está obsoleto, use close() en su lugar. |
| [getAutoResize](#getAutoResize--) | Establece un valor booleano que indica si el archivo debe imprimirse con tamaño optimizado. |
| [getAutoRotate](#getAutoRotate--) | Obtiene un valor booleano que indica si el archivo se imprimirá con rotación automática |
| [getAutoRotateMode](#getAutoRotateMode--) | Obtiene un valor de AutoRotateMode que indica la dirección de rotación |
| [getCoordinateType](#getCoordinateType--) | Obtiene el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [getCopiesPrinted](#getCopiesPrinted--) | Obtiene las copias impresas |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Obtiene la configuración de página predeterminada. |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | Obtiene la configuración de impresora predeterminada. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtiene el modo de presentación del formulario. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtiene un valor que indica la alineación horizontal |
| [getPageCount](#getPageCount--) | Obtiene el recuento de páginas del archivo Pdf actual. |
| [getPassword](#getPassword--) | Obtiene la contraseña del documento de entrada. |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> Obtiene o establece un valor booleano que indica si la página se imprime en escala de grises. Por defecto es false. </p> <hr> El valor predeterminado false es false. |
| [getPrintAsImage](#getPrintAsImage--) | <p> Obtiene un modo para que PdfViewer imprima como imagen. </p> |
| [getPrinterJobName](#getPrinterJobName--) | Obtiene el nombre del documento en la cola de impresión cuando se imprime el documento. El valor predeterminado es el nombre del archivo. |
| [getPrintPageDialog](#getPrintPageDialog--) | Obtiene un valor booleano que indica si se produce el cuadro de diálogo de número de página al imprimir. |
| [getPrintStatus](#getPrintStatus--) | Obtiene el resultado del trabajo de impresión. Si tiene éxito, null; de lo contrario, objeto de excepción. |
| [getRenderingOptions](#getRenderingOptions--) | Obtiene las opciones de renderizado. |
| [getResolution](#getResolution--) | Obtiene o establece la resolución durante la visualización e impresión. Cuanto mayor sea la resolución, más lenta será la velocidad. El valor predeterminado es 150. Esta propiedad cambia la resolución de imagen en los flujos de conversión de página a imagen: cuando {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) está configurado a {@code }, o cuando se llama al método {@link #decodePage(int)} o {@link #decodeAllPages}. Para establecer una resolución de impresora para impresión directa a una impresora, use la propiedad {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) en la clase {@code PageSettings}. |
| [getScaleFactor](#getScaleFactor--) | Obtiene un valor de punto flotante que indica el factor de escala. El valor predeterminado es 1.0. |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | Obtiene el uso de la conversión de la página pdf a un archivo png intermedio durante la impresión en modo archivo. Úselo cuando el tamaño del archivo de salida sea importante. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtiene un valor que indica la alineación vertical |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Este método está obsoleto. Obtiene la bandera que controla la visibilidad de áreas ocultas en la página. |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> Abre un flujo de archivo Pdf. Pero no decodifica realmente las páginas del archivo Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> Abre un archivo Pdf, pero no decodifica realmente las páginas del archivo Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> Imprime el documento Pdf usando la impresora predeterminada. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Imprime el documento Pdf con la configuración de la impresora. El tamaño de página de salida se ajustará al tamaño de la primera página del documento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Imprime el documento Pdf con configuraciones. Si el tamaño del documento no es compatible con el tamaño de página, pdf.kit lo ampliará para ajustarse al tamaño de página. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //imprime el archivo con tamaño ajustado viewer.setAutoRotate ( true); //imprime el archivo con rotación ajustada viewer.setPrintPageDialog ( false);//no generar el cuadro de diálogo de número de página al imprimir PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> Abre e imprime un flujo Pdf grande. Si su archivo Pdf tiene cientos de páginas o más o su tamaño supera los 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //imprime el archivo con tamaño ajustado viewer.setAutoRotate ( true); //imprime el archivo con rotación ajustada viewer.printPageDialog=false;//no generar el cuadro de diálogo de número de página al imprimir viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Este método integra la apertura y la impresión del archivo y no es necesario llamar a OpenPdfFile() explícitamente. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Abre e imprime un flujo Pdf grande con los ajustes de impresora especificados. Si su archivo Pdf tiene cientos de páginas o más o su tamaño supera los 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // imprime el archivo con tamaño ajustado viewer.setAutoRotate(true); // imprime el archivo con rotación ajustada viewer.setPrintPageDialog(false); // no generar el cuadro de diálogo de número de página al // imprimir PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Este método integra la apertura y la impresión del archivo y no es necesario llamar a OpenPdfFile() explícitamente. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Abre e imprime un flujo Pdf grande con los ajustes de página y de impresora especificados. Si su archivo Pdf tiene cientos de páginas o más o su tamaño supera los 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //imprime el archivo con tamaño ajustado viewer.setAutoRotate ( true); //imprime el archivo con rotación ajustada viewer.setPrintPageDialog ( false);//no generar el cuadro de diálogo de número de página al imprimir PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Este método integra la apertura y la impresión del archivo y no es necesario llamar a OpenPdfFile() explícitamente. |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> Abre e imprime un archivo Pdf grande. Si su archivo Pdf tiene cientos de páginas o más o su tamaño supera los 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // imprime el archivo con tamaño ajustado viewer.setAutoRotate(true); // imprime el archivo con rotación ajustada viewer.setPrintPageDialog(false);// no generar el cuadro de diálogo de número de página al // imprimir viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Abre e imprime un archivo Pdf grande con la configuración de impresora especificada. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Este método ha integrado la apertura y la impresión del archivo y no es necesario llamar a OpenPdfFile() explícitamente. |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Abre e imprime un archivo Pdf grande con la configuración de página y de impresora especificada. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Este método ha integrado la apertura y la impresión del archivo y no es necesario llamar a OpenPdfFile() explícitamente. |
| [save](#save-java.io.InputStream-) | Guarda el documento PDF resultante en un flujo. |
| [save](#save-java.lang.String-) | Guarda el documento PDF resultante en un archivo. |
| [setAutoResize](#setAutoResize-boolean-) | Establece un valor booleano que indica si el archivo debe imprimirse con tamaño optimizado. |
| [setAutoRotate](#setAutoRotate-boolean-) | Establece un valor booleano que indica si el archivo se imprimirá con rotación automática |
| [setAutoRotateMode](#setAutoRotateMode-int-) | Establece un valor de AutoRotateMode que indica la dirección de rotación |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Establece el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Establece el modo de presentación del formulario. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Establece un valor que indica la alineación horizontal |
| [setPassword](#setPassword-java.lang.String-) | Establece la contraseña del documento de entrada. |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> Obtiene o establece un valor booleano que indica si la página se imprime en escala de grises. Por defecto es false. </p> <hr> El valor predeterminado false es false. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> Establece un modo para que PdfViewer imprima como imagen. </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | Establece el nombre del documento en la cola de impresión cuando se imprime el documento. El valor predeterminado es el nombre del archivo. |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | Establece un valor booleano que indica si se produce el cuadro de diálogo de número de página al imprimir. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Establece las opciones de renderizado. |
| [setResolution](#setResolution-int-) | Establece la resolución durante la visualización e impresión. Cuanta mayor sea la resolución, más lenta será la velocidad. El valor predeterminado es 150. Esta propiedad cambia la resolución de imagen en los flujos de conversión de página a imagen: cuando {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) está configurado a {@code }, o cuando se llama al método {@link #decodePage(int)} o {@link #decodeAllPages}. Para establecer una resolución de impresora para impresión directa a una impresora, use la propiedad {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) en la clase {@code PageSettings}. |
| [setScaleFactor](#setScaleFactor-float-) | Establece un valor de punto flotante que indica el factor de escala. El valor predeterminado es 1.0. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Obsoleto. |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | Establece el uso de la conversión de la página pdf a un archivo png intermedio durante la impresión en modo archivo. Úselo cuando el tamaño del archivo de salida sea importante. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Establece un valor que indica la alineación vertical |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

Añade/elimina la suscripción al evento de impresión de la última página.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

Añade/elimina la suscripción al evento de impresión de la última página.

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

Inicializa un nuevo objeto {@code PdfViewer}.

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
Inicializa un nuevo objeto {@code PdfViewer}.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Inicializa la fachada.

### bindPdf {#bindPdf-java.io.InputStream-}
Inicializa la fachada.

### bindPdf {#bindPdf-java.lang.String-}
Inicializa la fachada.

### close {#close--}
```
public void close()
```

Cierra el archivo Pdf actual.

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

Cierra el archivo Pdf actual.

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

Obtiene las páginas del archivo pdf actual.

**Returns:**
devuelve la matriz de imágenes de páginas Pdf.

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

Decodifica una página de un archivo Pdf.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | El número de página de un archivo Pdf que debe estar entre 1 y PageCount. |

**Returns:**
devuelve la imagen de la página Pdf.

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
Decodifica la página a BufferedImage

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libera los recursos de la fachada. Este método está obsoleto, use close() en su lugar.

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

Establece un valor booleano que indica si el archivo debe imprimirse con tamaño optimizado.

**Returns:**
valor booleano: Si es false imprime la página sin escalarla. Si es true imprime la página con escala para ajustarse al área imprimible.

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

Obtiene un valor booleano que indica si el archivo se imprimirá con rotación automática

**Returns:**
valor booleano

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

Obtiene un valor de AutoRotateMode que indica la dirección de rotación

**Returns:**
Elemento AutoRotateMode @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtiene el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto.

**Returns:**
PageCoordinateType elemento @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

Obtiene las copias impresas

**Returns:**
valor int

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Obtiene la configuración de página predeterminada.

**Returns:**
Objeto de configuración de página.

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

Obtiene la configuración de impresora predeterminada.

**Returns:**
Objeto de configuración de página.

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtiene el modo de presentación del formulario.

**Returns:**
Elemento FormPresentationMode @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtiene un valor que indica la alineación horizontal

**Returns:**
HorizontalAlignment elemento @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Obtiene el recuento de páginas del archivo Pdf actual.

**Returns:**
devuelve el recuento de páginas.

### getPassword {#getPassword--}
```
public String getPassword()
```

Obtiene la contraseña del documento de entrada.

**Returns:**
valor String

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> Obtiene o establece un valor booleano que indica si la página se imprime en escala de grises. Por defecto es false. </p> <hr> El valor predeterminado false es false.

**Returns:**
valor booleano

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> Obtiene un modo para que PdfViewer imprima como imagen. </p>

**Returns:**
valor booleano <hr> Si es true siempre imprime como imagen (genera una imagen que se imprime) Si es false imprime directamente al dispositivo si todas las funciones son compatibles. En caso de que el documento contenga funciones no compatibles, el sistema puede decidir automáticamente imprimir como imagen. El valor predeterminado es false.

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

Obtiene el nombre del documento en la cola de impresión cuando se imprime el documento. El valor predeterminado es el nombre del archivo.

**Returns:**
valor String

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

Obtiene un valor booleano que indica si se produce el cuadro de diálogo de número de página al imprimir.

**Returns:**
valor booleano

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

Obtiene el resultado del trabajo de impresión. Si tiene éxito, null; de lo contrario, objeto de excepción.

**Returns:**
objeto de excepción o null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Obtiene las opciones de renderizado.

**Returns:**
objeto RenderingOptions

### getResolution {#getResolution--}
```
public int getResolution()
```

Obtiene o establece la resolución durante la visualización e impresión. Cuanto mayor sea la resolución, más lenta será la velocidad. El valor predeterminado es 150. Esta propiedad cambia la resolución de imagen en los flujos de conversión de página a imagen: cuando {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) está configurado a {@code }, o cuando se llama al método {@link #decodePage(int)} o {@link #decodeAllPages}. Para establecer una resolución de impresora para impresión directa a una impresora, use la propiedad {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) en la clase {@code PageSettings}.

**Returns:**
valor int

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

Obtiene un valor de punto flotante que indica el factor de escala. El valor predeterminado es 1.0.

**Returns:**
valor de punto flotante.

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

Obtiene el uso de la conversión de la página pdf a un archivo png intermedio durante la impresión en modo archivo. Úselo cuando el tamaño del archivo de salida sea importante.

**Returns:**
valor booleano.

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtiene un valor que indica la alineación vertical

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Este método está obsoleto. Obtiene la bandera que controla la visibilidad de áreas ocultas en la página.

**Returns:**
valor booleano

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> Abre un flujo de archivo Pdf. Pero en realidad no decodifica las páginas del archivo Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\test.pdf"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> Abre un archivo Pdf, pero en realidad no decodifica las páginas del archivo Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> Imprime el documento Pdf usando la impresora predeterminada. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //imprime el archivo con tamaño ajustado viewer.setAutoRotate ( true); //imprime el archivo con rotación ajustada viewer.setPrintPageDialog ( false); //no generar el cuadro de diálogo de número de página al imprimir viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Imprime el documento Pdf con la configuración de la impresora. El tamaño de página de salida se ajustará al tamaño de la primera página del documento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //imprime el archivo con tamaño ajustado viewer.setAutoRotate ( true); //imprime el archivo con rotación ajustada viewer.setPrintPageDialog ( false); //no generar el cuadro de diálogo de número de página al imprimir PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Imprime el documento Pdf con configuraciones. Si el tamaño del documento no es compatible con el tamaño de página, pdf.kit lo ampliará para ajustarse al tamaño de página. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //imprime el archivo con tamaño ajustado viewer.setAutoRotate ( true); //imprime el archivo con rotación ajustada viewer.setPrintPageDialog ( false);//no generar el cuadro de diálogo de número de página al imprimir PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> Abre e imprime un flujo Pdf grande. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //imprime el archivo con tamaño ajustado viewer.setAutoRotate ( true); //imprime el archivo con rotación ajustada viewer.setPrintPageDialog=false;//no generar el cuadro de diálogo de número de página al imprimir viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Este método ha integrado la apertura y la impresión del archivo y no es necesario llamar a OpenPdfFile() explícitamente.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Abre e imprime un flujo Pdf grande con la configuración de impresora especificada. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // imprime el archivo con tamaño ajustado viewer.setAutoRotate(true); // imprime el archivo con rotación ajustada viewer.setPrintPageDialog(false); // no generar el cuadro de diálogo de número de página al imprimir PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Este método ha integrado la apertura y la impresión del archivo y no es necesario llamar a OpenPdfFile() explícitamente.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Abre e imprime una transmisión grande de Pdf con la configuración de página y de impresora especificadas. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Este método ha integrado la apertura y la impresión del archivo y no necesita llamar a OpenPdfFile() explícitamente.

### printLargePdf {#printLargePdf-java.lang.String-}
<p> Abre e imprime un archivo Pdf grande. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\test.pdf"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Abre e imprime un archivo Pdf grande con la configuración de impresora especificada. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Este método ha integrado la apertura y la impresión del archivo y no necesita llamar a OpenPdfFile() explícitamente.

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Abre e imprime un archivo Pdf grande con la configuración de página y de impresora especificadas. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener mejor rendimiento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Este método ha integrado la apertura y la impresión del archivo y no necesita llamar a OpenPdfFile() explícitamente.

### save {#save-java.io.InputStream-}
Guarda el documento PDF resultante en un flujo.

### save {#save-java.lang.String-}
Guarda el documento PDF resultante en un archivo.

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

Establece un valor booleano que indica si el archivo debe imprimirse con tamaño optimizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano: Si es false imprime la página sin escalarla. Si es true imprime la página con escala para ajustarse al área imprimible. |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

Establece un valor booleano que indica si el archivo se imprimirá con rotación automática

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

Establece un valor de AutoRotateMode que indica la dirección de rotación

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento AutoRotateMode @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Establece el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Establece el modo de presentación del formulario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento FormPresentationMode |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Establece un valor que indica la alineación horizontal

### setPassword {#setPassword-java.lang.String-}
Establece la contraseña del documento de entrada.

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> Obtiene o establece un valor booleano que indica si la página se imprime en escala de grises. Por defecto es false. </p> <hr> El valor predeterminado false es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> Establece un modo para que PdfViewer imprima como imagen. </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano <hr> Si es true siempre imprime como imagen (genera una imagen que se imprime) Si es false imprime directamente al dispositivo si todas las funciones son compatibles. En caso de que el documento contenga funciones no compatibles, el sistema puede decidir automáticamente imprimir como imagen. El valor predeterminado es false. |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
Establece el nombre del documento en la cola de impresión cuando se imprime el documento. El valor predeterminado es el nombre del archivo.

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

Establece un valor booleano que indica si se produce el cuadro de diálogo de número de página al imprimir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Establece las opciones de renderizado.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Establece la resolución durante la visualización e impresión. Cuanta mayor sea la resolución, más lenta será la velocidad. El valor predeterminado es 150. Esta propiedad cambia la resolución de imagen en los flujos de conversión de página a imagen: cuando {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) está configurado a {@code }, o cuando se llama al método {@link #decodePage(int)} o {@link #decodeAllPages}. Para establecer una resolución de impresora para impresión directa a una impresora, use la propiedad {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) en la clase {@code PageSettings}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

Establece un valor de punto flotante que indica el factor de escala. El valor predeterminado es 1.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor de punto flotante. |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Obsoleto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

Establece el uso de la conversión de la página pdf a un archivo png intermedio durante la impresión en modo archivo. Úselo cuando el tamaño del archivo de salida sea importante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano. |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Establece un valor que indica la alineación vertical
