---
title: "XForm"
linktitle: "XForm"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa XForm"
type: docs
weight: 5590
url: /es/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

Clase que representa XForm

## Métodos

| Método | Descripción |
| --- | --- |
| [close](#close--) | Libera memoria |
| [containsOwnResources](#containsOwnResources--) | Devuelve True si contiene Recursos Propios |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Crea un nuevo XForm en el documento. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Crea un XForm que duplica el contenido de la página. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | Libera memoria |
| [freeMemory](#freeMemory--) | Borra los datos en caché |
| [getBBox](#getBBox--) | Obtiene el cuadro delimitador del formulario. |
| [getContents](#getContents--) | Obtiene los operadores del formulario. |
| [getEngineObj](#getEngineObj--) | Solo interno |
| [getIT](#getIT--) | Obtiene el IT del formulario. El IT del formulario es un nombre que describe la intención del XObject. |
| [getMatrix](#getMatrix--) | Obtiene la matriz del formulario. |
| [getName](#getName--) | Obtiene el nombre del formulario. El nombre del formulario es el nombre que se usa para referenciar el formulario en el diccionario XObejct de los recursos de la página. |
| [getOpi](#getOpi--) | Obtiene la Open Prepress Interface (OPI). |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo del formulario. |
| [getResources](#getResources--) | Devuelve los recursos del Form X-Object. Si For no tiene recursos y allowCreate es verdadero, Resources se crearán automáticamente para el formulario. |
| [getResources](#getResources-boolean-) | Devuelve los recursos del Form X-Object |
| [getResourcesField](#getResourcesField--) | Obtiene los recursos del Form XObject. |
| [getSubtype](#getSubtype--) | Obtiene el subtipo del formulario. |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | Establece el cuadro delimitador del formulario. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Establece la matriz del formulario. |
| [setName](#setName-java.lang.String-) | Establece el nombre del formulario. El nombre del formulario es el nombre que se usa para referenciar el formulario en el diccionario XObejct de los recursos de la página. |

### close {#close--}
```
public final void close()
```

Libera memoria

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

Devuelve True si contiene Recursos Propios

**Returns:**
valor booleano

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
Crea un nuevo XForm en el documento.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
Crea un XForm que duplica el contenido de la página.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

Libera memoria

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Borra los datos en caché

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

Obtiene el cuadro delimitador del formulario.

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

Obtiene los operadores del formulario.

**Returns:**
Objeto OperatorCollection

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Solo interno

**Returns:**
Objeto IPdfObject

### getIT {#getIT--}
```
public final String getIT()
```

Obtiene el IT del formulario. El IT del formulario es un nombre que describe la intención del XObject.

**Returns:**
valor String

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Obtiene la matriz del formulario.

**Returns:**
Matriz

### getName {#getName--}
```
public String getName()
```

Obtiene el nombre del formulario. El nombre del formulario es el nombre que se usa para referenciar el formulario en el diccionario XObejct de los recursos de la página.

**Returns:**
Cadena

### getOpi {#getOpi--}
```
public Opi getOpi()
```

Obtiene la Open Prepress Interface (OPI).

**Returns:**
Instancia Opi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo del formulario.

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

Devuelve los recursos del Form X-Object. Si For no tiene recursos y allowCreate es verdadero, Resources se crearán automáticamente para el formulario.

**Returns:**
Instancia Resources

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

Devuelve los recursos del Form X-Object

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| allowCreate |  | Si For no tiene recursos y allowCreate es verdadero, Resources se crearán automáticamente para el formulario. |

**Returns:**
Instancia Resources

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

Obtiene los recursos del Form XObject.

**Returns:**
Instancia Resources. Si For no tiene recursos, Resources se crearán automáticamente para el formulario.

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Obtiene el subtipo del formulario.

**Returns:**
valor String

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
Establece el cuadro delimitador del formulario.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Establece la matriz del formulario.

### setName {#setName-java.lang.String-}
Establece el nombre del formulario. El nombre del formulario es el nombre que se usa para referenciar el formulario en el diccionario XObejct de los recursos de la página.
