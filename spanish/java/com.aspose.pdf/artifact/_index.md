---
title: "Artefacto"
linktitle: "Artefacto"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un objeto PDF Artifact."
type: docs
weight: 190
url: /es/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

Clase que representa un objeto PDF Artifact.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | Constructor de artefacto con tipo y subtipo especificados |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | Este constructor se usa cuando el artefacto se lee de la página. |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | Constructor de artefacto con tipo y subtipo especificados |

## Métodos

| Método | Descripción |
| --- | --- |
| [beginUpdates](#beginUpdates--) | Inicie actualizaciones eliminadas. Use esta función si necesita realizar varios cambios al mismo artefacto para mejorar el rendimiento. Normalmente los operadores del artefacto se cambian cada vez que se modifica una propiedad del artefacto. Esto provoca que el contenido de la página cambie cada vez que el artefacto se modifica. Para evitar este efecto, coloque todas las actualizaciones del artefacto entre llamadas a StartUpdates/SaveUpdates. Esto permite cambiar el contenido de la página solo una vez. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | Cierra todos los recursos utilizados por este documento. |
| [dispose](#dispose--) | Elimina el artefacto. Este método está obsoleto, use close() en su lugar. |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | Obtiene la alineación horizontal del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | Obtiene la alineación vertical del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [getBottomMargin](#getBottomMargin--) | Obtiene el margen inferior del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [getContents](#getContents--) | Obtiene la colección de operadores internos del artefacto. |
| [getCustomSubtype](#getCustomSubtype--) | Obtiene el nombre del subtipo del artefacto. Puede usarse si el subtipo del artefacto no es un subtipo estándar. |
| [getCustomType](#getCustomType--) | Obtiene el nombre del tipo del artefacto. Puede usarse si el tipo del artefacto no es estándar. |
| [getForm](#getForm--) | Obtiene XForm del artefacto (si se usa XForm). |
| [getImage](#getImage--) | Obtiene la imagen del artefacto (si está presente). |
| [getLeftMargin](#getLeftMargin--) | Obtiene el margen izquierdo del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [getLines](#getLines--) | Líneas del artefacto de texto multilínea. |
| [getOpacity](#getOpacity--) | Obtiene la opacidad del artefacto. Los valores posibles están en el rango 0..1. |
| [getPosition](#getPosition--) | Obtiene la posición del artefacto. Si se especifica esta propiedad, los márgenes y alineaciones se ignoran. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo del artefacto. |
| [getRightMargin](#getRightMargin--) | Obtiene el margen derecho del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [getRotation](#getRotation--) | Obtiene el ángulo de rotación del artefacto. |
| [getSubtype](#getSubtype--) | Obtiene el subtipo del artefacto. Si el artefacto tiene un subtipo no estándar, el nombre del subtipo puede leerse mediante CustomSubtype. |
| [getText](#getText--) | Obtiene el texto del artefacto. |
| [getTextState](#getTextState--) | Estado de texto para el texto del artefacto. |
| [getTopMargin](#getTopMargin--) | Obtiene el margen superior del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [getType](#getType--) | Obtiene el tipo de artefacto. |
| [getValue](#getValue-java.lang.String-) | Obtiene el valor personalizado del artefacto. |
| [isBackground](#isBackground--) | Si es verdadero, el artefacto se coloca detrás del contenido de la página. |
| [removeValue](#removeValue-java.lang.String-) | Elimina el valor personalizado del artefacto. |
| [saveUpdates](#saveUpdates--) | Guarda todas las actualizaciones en el artefacto que se realizaron después de la llamada a BeginUpdates(). |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Obtiene la alineación horizontal del artefacto. |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Establece la alineación vertical del artefacto. |
| [setBackground](#setBackground-boolean-) | Si es verdadero, el artefacto se coloca detrás del contenido de la página. |
| [setBottomMargin](#setBottomMargin-double-) | Establece el margen inferior del artefacto. |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | Establece el nombre del tipo de artefacto. Puede usarse si el tipo de artefacto no es estándar. |
| [setImage](#setImage-java.io.InputStream-) | Establece la imagen del artefacto. |
| [setImage](#setImage-java.lang.String-) | Establece la imagen del artefacto. |
| [setLeftMargin](#setLeftMargin-double-) | Establece el margen izquierdo del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | Establece el texto y las propiedades de texto del artefacto. Permite especificar múltiples líneas. |
| [setOpacity](#setOpacity-double-) | Establece la opacidad del artefacto. Los valores posibles están en el rango 0..1. |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | Establece qué cadena será reemplazada por el número de página. El valor predeterminado es #. |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | Establece la página PDF que se coloca en la página del documento como artefacto. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Establece la posición del artefacto. |
| [setRightMargin](#setRightMargin-double-) | Establece el margen derecho del artefacto. |
| [setRotation](#setRotation-double-) | Establece el ángulo de rotación del artefacto. |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | Establece el subtipo del artefacto. |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | Establece el texto del artefacto. |
| [setText](#setText-java.lang.String-) | Establece el texto del artefacto. |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Establece el texto y las propiedades de texto del artefacto. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Estado de texto para el texto del artefacto. |
| [setTopMargin](#setTopMargin-double-) | Establece el margen superior del artefacto. |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | Establece el tipo de artefacto. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Establece el valor personalizado del artefacto. |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
Constructor de artefacto con tipo y subtipo especificados

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
Este constructor se usa cuando el artefacto se lee de la página.

### Artifact {#Artifact-java.lang.String-java.lang.String-}
Constructor de artefacto con tipo y subtipo especificados

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

Inicie actualizaciones eliminadas. Use esta función si necesita realizar varios cambios al mismo artefacto para mejorar el rendimiento. Normalmente los operadores del artefacto se cambian cada vez que se modifica una propiedad del artefacto. Esto provoca que el contenido de la página cambie cada vez que el artefacto se modifica. Para evitar este efecto, coloque todas las actualizaciones del artefacto entre llamadas a StartUpdates/SaveUpdates. Esto permite cambiar el contenido de la página solo una vez. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

Cierra todos los recursos utilizados por este documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Elimina el artefacto. Este método está obsoleto, use close() en su lugar.

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

Obtiene la alineación horizontal del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

Obtiene la alineación vertical del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora.

**Returns:**
Valor de VerticalAlignment. @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Obtiene el margen inferior del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora.

**Returns:**
margen inferior.

### getContents {#getContents--}
```
public List < Operator > getContents()
```

Obtiene la colección de operadores internos del artefacto.

**Returns:**
lista de operadores internos del artefacto.

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

Obtiene el nombre del subtipo del artefacto. Puede usarse si el subtipo del artefacto no es un subtipo estándar.

**Returns:**
valor String

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

Obtiene el nombre del tipo del artefacto. Puede usarse si el tipo del artefacto no es estándar.

**Returns:**
Nombre del artefacto String

### getForm {#getForm--}
```
public XForm getForm()
```

Obtiene XForm del artefacto (si se usa XForm).

**Returns:**
objeto XForm

### getImage {#getImage--}
```
public XImage getImage()
```

Obtiene la imagen del artefacto (si está presente).

**Returns:**
objeto XImage

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Obtiene el margen izquierdo del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora.

**Returns:**
margen izquierdo del artefacto.

### getLines {#getLines--}
```
public final List < String > getLines()
```

Líneas del artefacto de texto multilínea.

**Returns:**
Lista de Strings

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Obtiene la opacidad del artefacto. Los valores posibles están en el rango 0..1.

**Returns:**
opacidad del artefacto.

### getPosition {#getPosition--}
```
public Point getPosition()
```

Obtiene la posición del artefacto. Si se especifica esta propiedad, los márgenes y alineaciones se ignoran.

**Returns:**
posición del artefacto.

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo del artefacto.

**Returns:**
objeto Rectangle

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Obtiene el margen derecho del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora.

**Returns:**
margen derecho del artefacto.

### getRotation {#getRotation--}
```
public double getRotation()
```

Obtiene el ángulo de rotación del artefacto.

**Returns:**
ángulo de rotación del artefacto.

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

Obtiene el subtipo del artefacto. Si el artefacto tiene un subtipo no estándar, el nombre del subtipo puede leerse mediante CustomSubtype.

**Returns:**
subtipo del artefacto. @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

Obtiene el texto del artefacto.

**Returns:**
valor String

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

Estado de texto para el texto del artefacto.

**Returns:**
instancia TextState

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Obtiene el margen superior del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora.

**Returns:**
margen superior del artefacto.

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

Obtiene el tipo de artefacto.

**Returns:**
valor del tipo de artefacto. @see ArtifactType

### getValue {#getValue-java.lang.String-}
Obtiene el valor personalizado del artefacto.

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Si es verdadero, el artefacto se coloca detrás del contenido de la página.

**Returns:**
valor booleano

### removeValue {#removeValue-java.lang.String-}
Elimina el valor personalizado del artefacto.

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

Guarda todas las actualizaciones en el artefacto que se realizaron después de la llamada a BeginUpdates().

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Obtiene la alineación horizontal del artefacto.

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Establece la alineación vertical del artefacto.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Si es verdadero, el artefacto se coloca detrás del contenido de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Establece el margen inferior del artefacto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | margen inferior. |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
Establece el nombre del tipo de artefacto. Puede usarse si el tipo de artefacto no es estándar.

### setImage {#setImage-java.io.InputStream-}
Establece la imagen del artefacto.

### setImage {#setImage-java.lang.String-}
Establece la imagen del artefacto.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Establece el margen izquierdo del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | margen izquierdo del artefacto. |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
Establece el texto y las propiedades de texto del artefacto. Permite especificar múltiples líneas.

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Establece la opacidad del artefacto. Los valores posibles están en el rango 0..1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | opacidad del artefacto. |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
Establece qué cadena será reemplazada por el número de página. El valor predeterminado es #.

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
Establece la página PDF que se coloca en la página del documento como artefacto.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Establece la posición del artefacto.

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Establece el margen derecho del artefacto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | margen derecho del artefacto. |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Establece el ángulo de rotación del artefacto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | ángulo de rotación del artefacto. |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
Establece el subtipo del artefacto.

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
Establece el texto del artefacto.

### setText {#setText-java.lang.String-}
Establece el texto del artefacto.

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
Establece el texto y las propiedades de texto del artefacto.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Estado de texto para el texto del artefacto.

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Establece el margen superior del artefacto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | margen superior del artefacto. |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
Establece el tipo de artefacto.

### setValue {#setValue-java.lang.String-java.lang.String-}
Establece el valor personalizado del artefacto.
