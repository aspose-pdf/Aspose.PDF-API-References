---
title: "LinkElement"
linktitle: "LinkElement"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el elemento de estructura Link en la estructura lógica."
type: docs
weight: 70
url: /es/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public final class LinkElement extends AnnotationElement implements ITextElement , IAdjustPosition
```

Representa el elemento de estructura Link en la estructura lógica.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [LinkElement](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Ajustar posición. |
| [getHyperlink](#getHyperlink--) | Obtiene o establece el hipervínculo para el elemento de enlace. |
| [getStructureTextState](#getStructureTextState--) | Obtiene {@code /Aspose.Pdf.LogicalStructure.StructureTextState} objeto para el elemento actual. Valor: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} objeto para el elemento actual. |
| [preSave](#preSave--) |  |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Obtiene o establece el hipervínculo para el elemento de enlace. |
| [setText](#setText-java.lang.String-) | Añade contenido de texto al elemento de texto actual. |

### LinkElement {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Ajustar posición.

### getHyperlink {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```

Obtiene o establece el hipervínculo para el elemento de enlace.

**Returns:**
Instancia de hipervínculo

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Obtiene {@code /Aspose.Pdf.LogicalStructure.StructureTextState} objeto para el elemento actual. Valor: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} objeto para el elemento actual.

**Returns:**
Valor: objeto StructureTextState para el elemento de estructura de texto.

### preSave {#preSave--}
```
public void preSave()
```



### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Obtiene o establece el hipervínculo para el elemento de enlace.

### setText {#setText-java.lang.String-}
Añade contenido de texto al elemento de texto actual.
