---
title: "LinkElement"
linktitle: "LinkElement"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o elemento de estrutura Link na estrutura lógica."
type: docs
weight: 70
url: /pt/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public final class LinkElement extends AnnotationElement implements ITextElement , IAdjustPosition
```

Representa o elemento de estrutura Link na estrutura lógica.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [LinkElement](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Ajustar posição. |
| [getHyperlink](#getHyperlink--) | Obtém ou define o hiperlink para o elemento de link. |
| [getStructureTextState](#getStructureTextState--) | Obtém o objeto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} para o elemento atual. Valor: objeto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} para o elemento atual. |
| [preSave](#preSave--) |  |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Obtém ou define o hiperlink para o elemento de link. |
| [setText](#setText-java.lang.String-) | Anexa conteúdo de texto ao elemento de texto atual. |

### LinkElement {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Ajustar posição.

### getHyperlink {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```

Obtém ou define o hiperlink para o elemento de link.

**Returns:**
Instância de hiperlink

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Obtém o objeto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} para o elemento atual. Valor: objeto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} para o elemento atual.

**Returns:**
Valor: objeto StructureTextState para o elemento de estrutura de texto.

### preSave {#preSave--}
```
public void preSave()
```



### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Obtém ou define o hiperlink para o elemento de link.

### setText {#setText-java.lang.String-}
Anexa conteúdo de texto ao elemento de texto atual.
