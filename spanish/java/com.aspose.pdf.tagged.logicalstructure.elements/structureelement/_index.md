---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase base para elementos de estructura en la estructura lógica."
type: docs
weight: 110
url: /es/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

Representa una clase base para elementos de estructura en la estructura lógica.

## Métodos

| Método | Descripción |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Cambiar el elemento padre del structure element actual |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | Cambiar el elemento padre del structure element actual |
| [clearId](#clearId--) | Borrar ID del structure element. |
| [generateId](#generateId--) | Generar ID para el structure element. |
| [getActualText](#getActualText--) | Obtiene o establece el texto real del structure element. |
| [getAlternativeText](#getAlternativeText--) | Obtiene o establece el texto alternativo del structure element. |
| [getAttributes](#getAttributes--) | Obtiene {@code StructureAttributeCollection} objeto. |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | Obtiene {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} objeto. Valor: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} objeto. |
| [getExpansionText](#getExpansionText--) | Obtiene o establece el texto de expansión del structure element. |
| [getID](#getID--) | Obtiene el ID del structure element. Valor: ID del structure element. |
| [getLanguage](#getLanguage--) | Obtiene o establece el idioma del structure element. |
| [getPage](#getPage--) | Obtiene la página en la que se renderizarán algunos o todos los elementos hijos. |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | Obtiene el tipo del structure element. |
| [getTitle](#getTitle--) | Obtiene o establece el título del elemento de estructura. |
| [remove](#remove--) | Elimina: un elemento de la estructura, una referencia a él del objeto padre, referencias a él de los objetos hijo, el objeto correspondiente del documento. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | Elimina un elemento de la estructura, una referencia a él del objeto padre, referencias a él de los objetos hijo y el objeto correspondiente del documento. Inserta los objetos hijo del elemento eliminado en la colección de objetos hijo de su antiguo padre comenzando en el índice del elemento eliminado. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | Elimina un elemento de la estructura, una referencia a él del objeto padre, referencias a él de los objetos hijo y el objeto correspondiente del documento. Inserta los objetos hijo del elemento eliminado en la colección de objetos hijo de su antiguo padre comenzando en el índice del elemento eliminado. |
| [setActualText](#setActualText-java.lang.String-) | Obtiene o establece el texto real del structure element. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Obtiene o establece el texto alternativo del structure element. |
| [setExpansionText](#setExpansionText-java.lang.String-) | Obtiene o establece el texto de expansión del structure element. |
| [setId](#setId-java.lang.String-) | Establece el ID del elemento de estructura. |
| [setLanguage](#setLanguage-java.lang.String-) | Obtiene o establece el idioma del structure element. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | establecer Elemento Padre |
| [setTag](#setTag-java.lang.String-) | Establece la etiqueta personalizada del elemento de estructura. |
| [setTitle](#setTitle-java.lang.String-) | Obtiene o establece el título del elemento de estructura. |
| [tag](#tag-com.aspose.pdf.Annotation-) | Vincular un elemento estructural a la Anotación. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Vincular un elemento estructural al Artefacto. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Vincular un elemento estructural al operador BDC del flujo de contenido. |
| [tag](#tag-com.aspose.pdf.XForm-) | Vincular un elemento estructural al XForm del flujo de contenido. |
| [tag](#tag-com.aspose.pdf.XImage-) | Vincular un elemento estructural al XImage. |
| [toString](#toString--) | Devuelve una cadena que representa el objeto actual. |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Cambiar el elemento padre del structure element actual

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
Cambiar el elemento padre del structure element actual

### clearId {#clearId--}
```
public final void clearId()
```

Borrar ID del structure element.

### generateId {#generateId--}
```
public final void generateId()
```

Generar ID para el structure element.

### getActualText {#getActualText--}
```
public final String getActualText()
```

Obtiene o establece el texto real del structure element.

**Returns:**
Valor: Texto real del elemento de estructura.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Obtiene o establece el texto alternativo del structure element.

**Returns:**
Valor: Texto alternativo del elemento de estructura.

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

Obtiene {@code StructureAttributeCollection} objeto.

**Returns:**
{@code StructureAttributeCollection} objeto.

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

Obtiene {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} objeto. Valor: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} objeto.

**Returns:**
Instancia de AttributeOwnerStandard

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

Obtiene o establece el texto de expansión del structure element.

**Returns:**
Valor: Texto de expansión del elemento de estructura.

### getID {#getID--}
```
public final String getID()
```

Obtiene el ID del structure element. Valor: ID del structure element.

**Returns:**
valor String

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

Obtiene o establece el idioma del structure element.

**Returns:**
Valor: Idioma del elemento de estructura.

### getPage {#getPage--}
```
public final Page getPage()
```

Obtiene la página en la que se renderizarán algunos o todos los elementos hijos.

**Returns:**
Instancia de página

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

Obtiene el tipo del structure element.

**Returns:**
Valor: {@code StructureTypeStandard} objeto del elemento de estructura.

### getTitle {#getTitle--}
```
public final String getTitle()
```

Obtiene o establece el título del elemento de estructura.

**Returns:**
Valor: Título del elemento de estructura.

### remove {#remove--}
```
public final void remove()
```

Elimina: un elemento de la estructura, una referencia a él del objeto padre, referencias a él de los objetos hijo, el objeto correspondiente del documento.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

Elimina un elemento de la estructura, una referencia a él del objeto padre, referencias a él de los objetos hijo y el objeto correspondiente del documento. Inserta los objetos hijo del elemento eliminado en la colección de objetos hijo de su antiguo padre comenzando en el índice del elemento eliminado.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

Elimina un elemento de la estructura, una referencia a él del objeto padre, referencias a él de los objetos hijo y el objeto correspondiente del documento. Inserta los objetos hijo del elemento eliminado en la colección de objetos hijo de su antiguo padre comenzando en el índice del elemento eliminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | Verifique si los objetos hijo del elemento eliminado pueden insertarse en la colección de objetos hijo de su padre. |

### setActualText {#setActualText-java.lang.String-}
Obtiene o establece el texto real del structure element.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Obtiene o establece el texto alternativo del structure element.

### setExpansionText {#setExpansionText-java.lang.String-}
Obtiene o establece el texto de expansión del structure element.

### setId {#setId-java.lang.String-}
Establece el ID del elemento de estructura.

### setLanguage {#setLanguage-java.lang.String-}
Obtiene o establece el idioma del structure element.

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
establecer Elemento Padre

### setTag {#setTag-java.lang.String-}
Establece la etiqueta personalizada del elemento de estructura.

### setTitle {#setTitle-java.lang.String-}
Obtiene o establece el título del elemento de estructura.

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
