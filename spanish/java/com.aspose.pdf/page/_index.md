---
title: "Page"
linktitle: "Page"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa una página de un documento PDF."
type: docs
weight: 3310
url: /es/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

Clase que representa una página de un documento PDF.

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta el objeto visitante {@code AnnotationSelector} que proporciona funcionalidad para trabajar con anotaciones. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Acepta el objeto visitante {@code ImagePlacementAbsorber} que proporciona funcionalidad para trabajar con objetos de colocación de imágenes. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Acepta el objeto visitante {@code TextAbsorber} que proporciona funcionalidad para trabajar con objetos de texto. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Acepta el objeto visitante {@code TextFragmentAbsorber} que proporciona funcionalidad para trabajar con objetos de texto. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Agrega gráficos a la página. Funciona más rápido que agregar elementos uno por uno con el método GraphicElement#addOnPage(Page). |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | Agrega gráficos a la página. Funciona más rápido que agregar elementos uno por uno con el método GraphicElement#addOnPage(Page). |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Agrega una imagen buscable a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | Agrega una imagen buscable a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Agrega una imagen buscable a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Agrega una imagen buscable a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | Coloca un sello en la página. El sello puede ser el número de página, una imagen o texto simple, p. ej., algún logotipo. |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | Convierte la página actual a un mapa de bits BMP y luego devuelve una matriz de bytes. |
| [asXml](#asXml--) | Convierte la página actual a XML con codificación UTF-8. |
| [calculateContentBBox](#calculateContentBBox--) | Calcula el valor bbox: rectángulo que contiene el contenido sin márgenes visibles. |
| [clearContents](#clearContents--) | Solo para uso interno |
| [close](#close--) | Cierra todos los recursos utilizados por este documento. |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | Convierte la página a PNG para el flujo de imagen DSR, OMR, OCR. |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Elimina gráficos de la página. Funciona más rápido que eliminar elementos uno por uno con el método {@link GraphicElement#remove}. |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | Libera memoria. Este método está obsoleto, use close() en su lugar. |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Devuelve una lista de operadores que usan el recurso con el nombre especificado. |
| [findReferences](#findReferences-java.lang.String-) | <p> Encontrar referencias </p> |
| [flatten](#flatten--) | Elimina todos los campos estáticos ubicados en la página y coloca sus valores en su lugar. |
| [freeMemory](#freeMemory--) | Borra los datos en caché |
| [getActions](#getActions--) | Obtiene la colección de propiedades de la página. |
| [getAnnotations](#getAnnotations--) | Obtiene la colección de anotaciones de la página. {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> Obtiene el cuadro de arte de la página. </p> |
| [getArtifacts](#getArtifacts--) | Obtiene la colección de artefactos en la página. |
| [getBackground](#getBackground--) | Obtiene el color de fondo de la página. |
| [getBackgroundImage](#getBackgroundImage--) | Obtiene o establece la imagen de fondo para la página (solo para el generador, no se completa al leer el documento). |
| [getBleedBox](#getBleedBox--) | <p> Obtiene el cuadro de sangrado de la página. </p> |
| [getColorType](#getColorType--) | Obtiene el tipo de color de las páginas basado en la información obtenida de los operadores SetColor, imágenes y formularios. |
| [getContents](#getContents--) | <p> Obtiene la colección de operadores en el flujo de contenido de la página. {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | Obtiene el agregador de contenidos actual. {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> Obtiene el cuadro de recorte de la página. </p> |
| [getDocument](#getDocument--) | Obtener documento |
| [getDuration](#getDuration--) | <p> Obtiene la duración de visualización de la página. Este es el tiempo en segundos que la página se mostrará durante la presentación. Devuelve -1 si la duración no está definida. </p> <hr> El ejemplo muestra cómo obtener la duración de la página <p> Document document = new Document(\"sample.pdf\"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | Solo para uso interno |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | Obtiene la lista de objetos Field en orden de tabulación en esta página. |
| [getFooter](#getFooter--) | Obtiene el pie de página. |
| [getGroup](#getGroup--) | Obtiene una clase de atributos de grupo que especifica los atributos del grupo de página de la página para su uso en el modelo de imágenes transparentes. |
| [getHeader](#getHeader--) | Obtiene el encabezado de la página. |
| [getLayers](#getLayers--) | Obtiene la colección de capas. |
| [getMediaBox](#getMediaBox--) | <p> Obtiene el cuadro de medios de la página. </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | Obtiene el estilo de línea para notas. (solo para generador, no se completa al leer el documento) |
| [getNotifications](#getNotifications--) | Devuelve notificaciones sobre operaciones internas con el contenido de la página. (Actualmente solo se admiten notificaciones sobre eventos de párrafo en escenarios de adición de texto.) |
| [getNumber](#getNumber--) | Obtener número de la página. |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | Evento para personalizar el encabezado y el pie de página. |
| [getPageInfo](#getPageInfo--) | Obtiene la información de la página. (solo para generador, no se completa al leer el documento). |
| [getPageRect](#getPageRect-boolean-) | Devuelve el rectángulo de la página según su CropBox (o MediaBox si CropBox es nulo). |
| [getParagraphs](#getParagraphs--) | Obtiene los párrafos. |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> Devuelve el rectángulo de la página según su CropBox y MediaBox; </p> Internal |
| [getRect](#getRect--) | <p> Devuelve el rectángulo de la página según su CropBox y MediaBox; Para obtener: se devuelve el crop box de la página si está especificado, de lo contrario se devuelve el media box de la página. Para establecer: siempre se establece el media box de la página. </p> |
| [getResources](#getResources--) | Recupera los recursos asociados con la página. |
| [getResourcesField](#getResourcesField--) | <p> Obtiene los recursos de la página. El objeto Resources contiene colecciones de imágenes, formularios y fuentes. {@code Resources} </p> |
| [getRotate](#getRotate--) | <p> Obtiene la rotación de la página. </p> |
| [getRotationMatrix](#getRotationMatrix--) | Obtiene la matriz de transformación de la página. |
| [getTabOrder](#getTabOrder--) | Obtiene el orden de pestañas de la página. Valores posibles: Row, Column. Predeterminado, Manual |
| [getTocInfo](#getTocInfo--) | Obtiene la información del índice. |
| [getTrimBox](#getTrimBox--) | <p> Obtiene el recuadro de recorte de la página. </p> |
| [getUserUnit](#getUserUnit--) | Obtiene o establece el valor UserUnit. Un número positivo que indica el tamaño de las unidades de espacio de usuario predeterminadas, en múltiplos de 1/72 de pulgada. El valor predeterminado es 1. Por favor, establezca un valor cero o negativo para borrar esta entrada en la página. |
| [getWatermark](#getWatermark--) | Obtiene la marca de agua de la página. |
| [hasVectorGraphics](#hasVectorGraphics--) | Detecta la presencia de gráficos vectoriales, si está presente en la página. |
| [intToRotation](#intToRotation-int-) | Traduce el valor entero al miembro de enumeración de rotación correspondiente. |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | Obtiene o establece la adición de párrafos después del último párrafo de la página Valor: Valor indica si los párrafos se añadirán después del último párrafo de la página. Los párrafos se añadirán después del último párrafo de la página si el valor es verdadero. |
| [isBlank](#isBlank-double-) | Obtiene la bandera que indica si la página está en blanco o no. |
| [isBlank](#isBlank-double-boolean-) | Obtiene la bandera que indica si la página está en blanco o no. |
| [makeGrayscale](#makeGrayscale--) | Convierte la página a escala de grises. |
| [mergeLayers](#mergeLayers-java.lang.String-) | Fusiona todas las capas de la página en una sola capa con el nombre de capa nuevo especificado. |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | Fusiona todas las capas de la página en una sola capa con el nombre de capa nuevo especificado y el Id de grupo de contenido opcional. |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Eliminar referencias de objetos |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | Eliminar referencias a XObject del contenido de la página (p. ej., todos los operadores Do que usan el nombre del objeto). |
| [resize](#resize-com.aspose.pdf.PageSize-) | Redimensiona la página. |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | Traduce el miembro de enumeración de rotación a un valor entero. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Envía la página al proceso con el dispositivo de página dado. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Envía la página al proceso con el dispositivo de página dado. |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | Obtiene o establece la adición de párrafos después del último párrafo de la página Valor: Valor indica si los párrafos se añadirán después del último párrafo de la página. Los párrafos se añadirán después del último párrafo de la página si el valor es verdadero. |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | Establece el recuadro de arte de la página. |
| [setBackground](#setBackground-java.awt.Color-) | Establece el color de fondo de la página. |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | Establece el color de fondo de la página. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Obtiene o establece la imagen de fondo para la página (solo para el generador, no se completa al leer el documento). |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | Establece el recuadro de sangrado de la página. |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> Establece el recuadro de recorte de la página. </p> <hr> <pre> Ejemplo que muestra cómo obtener el recuadro de recorte de la página: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | Establece la duración de visualización de la página. Este es el tiempo en segundos que la página se mostrará durante la presentación. Devuelve -1 si la duración no está definida. |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | Solo para uso interno |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | Establece el pie de página. |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | Establece una clase de atributos de grupo que especifica los atributos del grupo de páginas de la página para su uso en el modelo de imágenes transparentes. |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | Establece el encabezado de la página. |
| [setLayers](#setLayers-java.util.ArrayList-) | Establece la colección de capas. |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | Establece la colección de capas. |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | Establece el cuadro de medios de la página. |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Establece el estilo de línea para notas.(solo para el generador, no se completa al leer el documento) |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Establece la información de la página.(solo para el generador, no se completa al leer el documento). |
| [setPageSize](#setPageSize-double-double-) | Establece el tamaño de la página. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Establece los párrafos. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Obtiene o establece el rectángulo de la página. Para obtener: se devuelve el cuadro de recorte de la página si está especificado, de lo contrario se devuelve el cuadro de medios de la página. Para establecer: siempre se establece el cuadro de medios de la página. Se devuelve. Tenga en cuenta que esta propiedad no considera la rotación de la página. Para obtener el rectángulo de la página considerando la rotación, use ActualRect. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Establece la rotación de la página. |
| [setTabOrder](#setTabOrder-int-) | Establece el orden de pestañas de la página. Valores posibles: Row, Column. Predeterminado, Manual |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | Establece la información del índice. |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Establecer transición |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | Establece el trim box de la página. |
| [setUserUnit](#setUserUnit-double-) | Obtiene o establece el valor UserUnit. Un número positivo que indica el tamaño de las unidades de espacio de usuario predeterminadas, en múltiplos de 1/72 de pulgada. El valor predeterminado es 1. Por favor, establezca un valor cero o negativo para borrar esta entrada en la página. |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | Establece la marca de agua de la página. |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | Intenta guardar los gráficos vectoriales si están presentes en la página. El formato de guardado es SVG. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta el objeto visitante {@code AnnotationSelector} que proporciona funcionalidad para trabajar con anotaciones.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Acepta el objeto visitante {@code ImagePlacementAbsorber} que proporciona funcionalidad para trabajar con objetos de colocación de imágenes.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Acepta el objeto visitante {@code TextAbsorber} que proporciona funcionalidad para trabajar con objetos de texto.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Acepta el objeto visitante {@code TextFragmentAbsorber} que proporciona funcionalidad para trabajar con objetos de texto.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Agrega gráficos a la página. Funciona más rápido que agregar elementos uno por uno con el método GraphicElement#addOnPage(Page).

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
Agrega gráficos a la página. Funciona más rápido que agregar elementos uno por uno con el método GraphicElement#addOnPage(Page).

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
Agrega una imagen buscable a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
Agrega una imagen buscable a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
Agrega una imagen buscable a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Agrega una imagen buscable a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
Coloca un sello en la página. El sello puede ser el número de página, una imagen o texto simple, p. ej., algún logotipo.

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
Convierte la página actual a un mapa de bits BMP y luego devuelve una matriz de bytes.

### asXml {#asXml--}
```
public String asXml()
```

Convierte la página actual a XML con codificación UTF-8.

**Returns:**
Cadena XML convertida.

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

Calcula el valor bbox: rectángulo que contiene el contenido sin márgenes visibles.

**Returns:**
Valor Bbox - rectángulo que contiene el contenido sin márgenes visibles

### clearContents {#clearContents--}
```
public void clearContents()
```

Solo para uso interno

### close {#close--}
```
public void close()
```

Cierra todos los recursos utilizados por este documento.

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

Convierte la página a PNG para el flujo de imagen DSR, OMR, OCR.

**Returns:**
Secuencia de imagen en un arreglo byte[] .

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Elimina gráficos de la página. Funciona más rápido que eliminar elementos uno por uno con el método {@link GraphicElement#remove}.

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libera memoria. Este método está obsoleto, use close() en su lugar.

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Devuelve una lista de operadores que usan el recurso con el nombre especificado.

### findReferences {#findReferences-java.lang.String-}
<p> Encontrar referencias </p>

### flatten {#flatten--}
```
public void flatten()
```

Elimina todos los campos estáticos ubicados en la página y coloca sus valores en su lugar.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Borra los datos en caché

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

Obtiene la colección de propiedades de la página.

**Returns:**
Valor PageActionCollection

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

Obtiene la colección de anotaciones de la página. {@code Annotations}

**Returns:**
Valor AnnotationCollection

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> Obtiene el cuadro de arte de la página. </p>

**Returns:**
Valor Rectangle <hr> <pre> Ejemplo que muestra cómo obtener el art box de la página: Document document = new Document("sample.pdf"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

Obtiene la colección de artefactos en la página.

**Returns:**
Valor ArtifactCollection

### getBackground {#getBackground--}
```
public Color getBackground()
```

Obtiene el color de fondo de la página.

**Returns:**
Valor de color

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Obtiene o establece la imagen de fondo para la página (solo para el generador, no se completa al leer el documento).

**Returns:**
Instancia de imagen

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> Obtiene el cuadro de sangrado de la página. </p>

**Returns:**
Valor Rectangle <hr> <pre> Ejemplo que muestra cómo obtener el bleed box de la página: Document document = new Document("sample.pdf"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Obtiene el tipo de color de las páginas basado en la información obtenida de los operadores SetColor, imágenes y formularios.

**Returns:**
Elemento ColorType @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> Obtiene la colección de operadores en el flujo de contenido de la página. {@code OperatorCollection} </p>

**Returns:**
Objeto OperatorCollection <hr> <pre> Ejemplo que muestra cómo escanear el flujo de operadores de la página. Document document = new Document("sample.pdf"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

Obtiene el agregador de contenidos actual. {@code ContentsAppender}

**Returns:**
Valor de ContentsAppender

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> Obtiene el cuadro de recorte de la página. </p>

**Returns:**
Valor de Rectangle <hr> <pre> Ejemplo muestra cómo obtener el recuadro de recorte de la página: Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obtener documento

**Returns:**
Objeto IDocument

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> Obtiene la duración de visualización de la página. Este es el tiempo en segundos que la página se mostrará durante la presentación. Devuelve -1 si la duración no está definida. </p> <hr> El ejemplo muestra cómo obtener la duración de la página <p> Document document = new Document(\"sample.pdf\"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
valor double

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

Solo para uso interno

**Returns:**
instancia interna

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

Obtiene la lista de objetos Field en orden de tabulación en esta página.

**Returns:**
Lista de objetos de campo

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

Obtiene el pie de página.

**Returns:**
El pie de página.

### getGroup {#getGroup--}
```
public Group getGroup()
```

Obtiene una clase de atributos de grupo que especifica los atributos del grupo de página de la página para su uso en el modelo de imágenes transparentes.

**Returns:**
Valor de Group

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

Obtiene el encabezado de la página.

**Returns:**
El encabezado de la página.

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

Obtiene la colección de capas.

**Returns:**
Valor: la colección de capas.

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> Obtiene el cuadro de medios de la página. </p>

**Returns:**
Valor de Rectangle <hr> <pre> Ejemplo muestra cómo obtener el recuadro de medios de la página: Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

Obtiene el estilo de línea para notas. (solo para generador, no se completa al leer el documento)

**Returns:**
Valor de GraphInfo

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

Devuelve notificaciones sobre operaciones internas con el contenido de la página. (Actualmente solo se admiten notificaciones sobre eventos de párrafo en escenarios de adición de texto.)

**Returns:**
Cadena que representa notificaciones sobre operaciones internas con el contenido de la página.

### getNumber {#getNumber--}
```
public final int getNumber()
```

Obtener número de la página.

**Returns:**
valor int

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

Evento para personalizar el encabezado y el pie de página.

**Returns:**
{@code PdfEvent<BeforePageGenerate> instance}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtiene la información de la página. (solo para generador, no se completa al leer el documento).

**Returns:**
La información de la página.

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

Devuelve el rectángulo de la página según su CropBox (o MediaBox si CropBox es nulo).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| considerRotation |  | Si es verdadero, la rotación de la página se considerará en el cálculo del rectángulo. |

**Returns:**
Rectángulo de la página.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Obtiene los párrafos.

**Returns:**
Los párrafos.

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> Devuelve el rectángulo de la página según su CropBox y MediaBox; </p> Internal

**Returns:**
Valor de Rectangle <hr> <pre> Ejemplo muestra cómo obtener el rectángulo de la página: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> Devuelve el rectángulo de la página según su CropBox y MediaBox; Para obtener: se devuelve el crop box de la página si está especificado, de lo contrario se devuelve el media box de la página. Para establecer: siempre se establece el media box de la página. </p>

**Returns:**
Valor de Rectangle <hr> <pre> Ejemplo muestra cómo obtener el rectángulo de la página: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

Recupera los recursos asociados con la página.

**Returns:**
Un objeto {@code Resources}({@link #getResources()}) que representa los recursos de la página.

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> Obtiene los recursos de la página. El objeto Resources contiene colecciones de imágenes, formularios y fuentes. {@code Resources} </p>

**Returns:**
Valor de Resources <hr> <pre> Ejemplo muestra cómo escanear imágenes de la página: Document document = new Document("sample.pdf"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + ":" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> Obtiene la rotación de la página. </p>

**Returns:**
Elemento Rotation <hr> <pre> Ejemplo muestra cómo determinar la rotación de la página. Document document = new Document("sample.pdf"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

Obtiene la matriz de transformación de la página.

**Returns:**
Valor de Matrix

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Obtiene el orden de pestañas de la página. Valores posibles: Row, Column. Predeterminado, Manual

**Returns:**
Valor de TabOrder @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

Obtiene la información del índice.

**Returns:**
La información del índice - null por defecto. Si se establece, esta página contendrá el índice.

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> Obtiene el recuadro de recorte de la página. </p>

**Returns:**
Valor de Rectangle <hr> <pre> Ejemplo muestra cómo obtener el recuadro de recorte (trim box) de la página: Document document = new Document("sample.pdf"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

Obtiene o establece el valor UserUnit. Un número positivo que indica el tamaño de las unidades de espacio de usuario predeterminadas, en múltiplos de 1/72 de pulgada. El valor predeterminado es 1. Por favor, establezca un valor cero o negativo para borrar esta entrada en la página.

**Returns:**
valor double

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

Obtiene la marca de agua de la página.

**Returns:**
Valor de Watermark

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

Detecta la presencia de gráficos vectoriales, si está presente en la página.

**Returns:**
Verdadero si la página contiene operadores de construcción de rutas; de lo contrario, Falso.

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

Traduce el valor entero al miembro de enumeración de rotación correspondiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotación |  | Valor entero a convertir |

**Returns:**
Miembro de enumeración Rotation @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

Obtiene o establece la adición de párrafos después del último párrafo de la página Valor: Valor indica si los párrafos se añadirán después del último párrafo de la página. Los párrafos se añadirán después del último párrafo de la página si el valor es verdadero.

**Returns:**
valor booleano

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

Obtiene la bandera que indica si la página está en blanco o no.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillThresholdFactor |  | El valor de umbral de relleno que gestiona la sensibilidad de la detección. Debe estar en el rango [0..1). Para determinar si una página está vacía o no, se calcula la proporción del espacio rellenado respecto al espacio total de la página. Esta proporción se compara con el parámetro fillThresholdFactor y, si es menor, la página se considera vacía. |

**Returns:**
valor booleano True - si la página está en blanco; de lo contrario, false.

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

Obtiene la bandera que indica si la página está en blanco o no.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillThresholdFactor |  | El valor de umbral de relleno que gestiona la sensibilidad de la detección. Debe ser igual o mayor que 0.01. |
| parseWhiteContent |  | True para escaneo completo de la página con análisis de contenido blanco, False (por defecto) - algoritmo rápido, donde los gráficos blancos se cuentan como página no en blanco. |

**Returns:**
valor booleano True - si la página está en blanco; de lo contrario, false.

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

Convierte la página a escala de grises.

### mergeLayers {#mergeLayers-java.lang.String-}
Fusiona todas las capas de la página en una sola capa con el nombre de capa nuevo especificado.

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
Fusiona todas las capas de la página en una sola capa con el nombre de capa nuevo especificado y el Id de grupo de contenido opcional.

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Eliminar referencias de objetos

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
Eliminar referencias a XObject del contenido de la página (p. ej., todos los operadores Do que usan el nombre del objeto).

### resize {#resize-com.aspose.pdf.PageSize-}
Redimensiona la página.

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
Traduce el miembro de enumeración de rotación a un valor entero.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
Envía la página al proceso con el dispositivo de página dado.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
Envía la página al proceso con el dispositivo de página dado.

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

Obtiene o establece la adición de párrafos después del último párrafo de la página Valor: Valor indica si los párrafos se añadirán después del último párrafo de la página. Los párrafos se añadirán después del último párrafo de la página si el valor es verdadero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
Establece el recuadro de arte de la página.

### setBackground {#setBackground-java.awt.Color-}
Establece el color de fondo de la página.

### setBackground {#setBackground-com.aspose.pdf.Color-}
Establece el color de fondo de la página.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Obtiene o establece la imagen de fondo para la página (solo para el generador, no se completa al leer el documento).

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
Establece el recuadro de sangrado de la página.

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> Establece el recuadro de recorte de la página. </p> <hr> <pre> Ejemplo que muestra cómo obtener el recuadro de recorte de la página: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

Establece la duración de visualización de la página. Este es el tiempo en segundos que la página se mostrará durante la presentación. Devuelve -1 si la duración no está definida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | duración de visualización de la página. |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
Solo para uso interno

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
Establece el pie de página.

### setGroup {#setGroup-com.aspose.pdf.Group-}
Establece una clase de atributos de grupo que especifica los atributos del grupo de páginas de la página para su uso en el modelo de imágenes transparentes.

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
Establece el encabezado de la página.

### setLayers {#setLayers-java.util.ArrayList-}
Establece la colección de capas.

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
Establece la colección de capas.

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
Establece el cuadro de medios de la página.

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
Establece el estilo de línea para notas.(solo para el generador, no se completa al leer el documento)

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Establece la información de la página.(solo para el generador, no se completa al leer el documento).

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

Establece el tamaño de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Ancho de página. |
| altura |  | Tamaño de página. |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Establece los párrafos.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Obtiene o establece el rectángulo de la página. Para obtener: se devuelve el cuadro de recorte de la página si está especificado, de lo contrario se devuelve el cuadro de medios de la página. Para establecer: siempre se establece el cuadro de medios de la página. Se devuelve. Tenga en cuenta que esta propiedad no considera la rotación de la página. Para obtener el rectángulo de la página considerando la rotación, use ActualRect.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Establece la rotación de la página.

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Establece el orden de pestañas de la página. Valores posibles: Row, Column. Predeterminado, Manual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Objeto TabOrder @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
Establece la información del índice.

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
Establecer transición

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
Establece el trim box de la página.

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

Obtiene o establece el valor UserUnit. Un número positivo que indica el tamaño de las unidades de espacio de usuario predeterminadas, en múltiplos de 1/72 de pulgada. El valor predeterminado es 1. Por favor, establezca un valor cero o negativo para borrar esta entrada en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
Establece la marca de agua de la página.

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
Intenta guardar los gráficos vectoriales si están presentes en la página. El formato de guardado es SVG.
