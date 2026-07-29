---
title: "Elemento"
linktitle: "Elemento"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase base para un elemento en la estructura lógica."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

Representa una clase base para un elemento en la estructura lógica.

## Métodos

| Método | Descripción |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Agregar {@code /Aspose.Pdf.LogicalStructure.Element} a la colección de hijos. |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Agregar {@code /Aspose.Pdf.LogicalStructure.Element} a la colección de hijos. |
| [clearChilds](#clearChilds--) | Borrar todos los hijos. |
| [findElements](#findElements-java.lang.Class-) | Buscar elementos de un tipo dado |
| [findElements](#findElements-java.lang.Class-boolean-) | Buscar elementos de un tipo dado |
| [getChildElements](#getChildElements--) | Obtiene la colección de hijos de objetos {@code Element}. |
| [getElementEngine](#getElementEngine--) | Obtener elemento padre. |
| [getParentElement](#getParentElement--) | Obtiene la colección padre de objetos {@code Element}. |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | Método interno |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Insertar {@code /Aspose.Pdf.LogicalStructure.Element} en la colección de hijos en el índice especificado. |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | Insertar {@code /Aspose.Pdf.LogicalStructure.Element} en la colección de hijos en el índice especificado. |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | Eliminar hijo en. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | Vincular un elemento estructural a la Anotación. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Vincular un elemento estructural al Artefacto. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Vincular un elemento estructural al operador BDC del flujo de contenido. |
| [tag](#tag-com.aspose.pdf.XForm-) | Vincular un elemento estructural al XForm del flujo de contenido. |
| [tag](#tag-com.aspose.pdf.XImage-) | Vincular un elemento estructural al XImage. |
| [toString](#toString--) | Devuelve una cadena que representa el objeto actual. |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Agregar {@code /Aspose.Pdf.LogicalStructure.Element} a la colección de hijos.

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Agregar {@code /Aspose.Pdf.LogicalStructure.Element} a la colección de hijos.

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

Borrar todos los hijos.

### findElements {#findElements-java.lang.Class-}
Buscar elementos de un tipo dado

### findElements {#findElements-java.lang.Class-boolean-}
Buscar elementos de un tipo dado

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

Obtiene la colección de hijos de objetos {@code Element}.

**Returns:**
Valor: colección de hijos de objetos {@code Element}.

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

Obtener elemento padre.

**Returns:**
Valor: elemento padre.

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

Obtiene la colección padre de objetos {@code Element}.

**Returns:**
Valor: colección padre de objetos {@code Element}.

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

Método interno

**Returns:**
Elemento interno

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Insertar {@code /Aspose.Pdf.LogicalStructure.Element} en la colección de hijos en el índice especificado.

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
Insertar {@code /Aspose.Pdf.LogicalStructure.Element} en la colección de hijos en el índice especificado.

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

Eliminar hijo en.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice del elemento hijo. |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### tag {#tag-com.aspose.pdf.Annotation-}
Vincular un elemento estructural a la Anotación.

### tag {#tag-com.aspose.pdf.Artifact-}
Vincular un elemento estructural al Artefacto.

### tag {#tag-com.aspose.pdf.operators.BDC-}
Vincular un elemento estructural al operador BDC del flujo de contenido.

### tag {#tag-com.aspose.pdf.XForm-}
Vincular un elemento estructural al XForm del flujo de contenido.

### tag {#tag-com.aspose.pdf.XImage-}
Vincular un elemento estructural al XImage.

### toString {#toString--}
```
public String toString()
```

Devuelve una cadena que representa el objeto actual.

**Returns:**
Cadena que representa el objeto actual.
