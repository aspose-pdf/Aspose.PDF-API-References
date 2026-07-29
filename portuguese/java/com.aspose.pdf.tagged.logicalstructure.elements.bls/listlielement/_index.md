---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o elemento de estrutura LI na estrutura lógica da lista."
type: docs
weight: 110
url: /pt/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

Representa o elemento de estrutura LI na estrutura lógica da lista.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Adiciona uma referência ao {@link StructureElement} especificado dentro deste elemento Table of Contents Item (TOCI). Isso normalmente é usado quando {@code ListLIElement} serve como cabeçalho de TOC em tabelas de conteúdo aninhadas. |
| [getGetElement](#getGetElement--) | Obtém o elemento PDF subjacente que representa esta estrutura TOCI. |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Adiciona uma referência ao {@link StructureElement} especificado dentro deste elemento Table of Contents Item (TOCI). Isso normalmente é usado quando {@code ListLIElement} serve como cabeçalho de TOC em tabelas de conteúdo aninhadas.

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

Obtém o elemento PDF subjacente que representa esta estrutura TOCI.

**Returns:**
O Element que forma a representação estrutural desta entrada de índice.

### preSave {#preSave--}
```
public void preSave()
```
