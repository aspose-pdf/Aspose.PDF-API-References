---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el elemento estructural LI en la estructura lógica de la lista."
type: docs
weight: 110
url: /es/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

Representa el elemento estructural LI en la estructura lógica de la lista.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Agrega una referencia al {@link StructureElement} especificado dentro de este elemento de ítem del índice (TOCI). Esto se usa típicamente cuando {@code ListLIElement} sirve como encabezado del índice en tablas de contenido anidadas. |
| [getGetElement](#getGetElement--) | Obtiene el elemento PDF subyacente que representa esta estructura TOCI. |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Agrega una referencia al {@link StructureElement} especificado dentro de este elemento de ítem del índice (TOCI). Esto se usa típicamente cuando {@code ListLIElement} sirve como encabezado del índice en tablas de contenido anidadas.

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

Obtiene el elemento PDF subyacente que representa esta estructura TOCI.

**Returns:**
El Elemento que forma la representación estructural de esta entrada de tabla de contenido.

### preSave {#preSave--}
```
public void preSave()
```
