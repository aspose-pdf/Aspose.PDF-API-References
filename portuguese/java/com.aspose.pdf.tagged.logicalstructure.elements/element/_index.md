---
title: "Elemento"
linktitle: "Elemento"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe base para elemento na estrutura lógica."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

Representa uma classe base para elemento na estrutura lógica.

## Métodos

| Método | Descrição |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Anexa {@code /Aspose.Pdf.LogicalStructure.Element} à coleção de filhos. |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Anexa {@code /Aspose.Pdf.LogicalStructure.Element} à coleção de filhos. |
| [clearChilds](#clearChilds--) | Limpa todos os filhos. |
| [findElements](#findElements-java.lang.Class-) | Encontre elementos de um determinado tipo |
| [findElements](#findElements-java.lang.Class-boolean-) | Encontre elementos de um determinado tipo |
| [getChildElements](#getChildElements--) | Obtém a coleção de filhos de objetos {@code Element}. |
| [getElementEngine](#getElementEngine--) | Obtém o elemento pai. |
| [getParentElement](#getParentElement--) | Obtém a coleção pai de objetos {@code Element}. |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | Método interno |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Insere {@code /Aspose.Pdf.LogicalStructure.Element} na coleção de filhos no índice especificado. |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | Insere {@code /Aspose.Pdf.LogicalStructure.Element} na coleção de filhos no índice especificado. |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | Remove o filho em. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | Vincule um elemento de estrutura à Anotação. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Vincule um elemento de estrutura ao Artefato. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Vincule um elemento de estrutura ao operador BDC do fluxo de conteúdo. |
| [tag](#tag-com.aspose.pdf.XForm-) | Vincule um elemento de estrutura ao XForm do fluxo de conteúdo. |
| [tag](#tag-com.aspose.pdf.XImage-) | Vincule um elemento de estrutura ao XImage. |
| [toString](#toString--) | Retorna uma string que representa o objeto atual. |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Anexa {@code /Aspose.Pdf.LogicalStructure.Element} à coleção de filhos.

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Anexa {@code /Aspose.Pdf.LogicalStructure.Element} à coleção de filhos.

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

Limpa todos os filhos.

### findElements {#findElements-java.lang.Class-}
Encontre elementos de um determinado tipo

### findElements {#findElements-java.lang.Class-boolean-}
Encontre elementos de um determinado tipo

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

Obtém a coleção de filhos de objetos {@code Element}.

**Returns:**
Valor: Coleção de filhos de objetos {@code Element}.

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

Obtém o elemento pai.

**Returns:**
Valor: Elemento pai.

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

Obtém a coleção pai de objetos {@code Element}.

**Returns:**
Valor: Coleção pai de objetos {@code Element}.

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
Insere {@code /Aspose.Pdf.LogicalStructure.Element} na coleção de filhos no índice especificado.

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
Insere {@code /Aspose.Pdf.LogicalStructure.Element} na coleção de filhos no índice especificado.

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

Remove o filho em.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do elemento filho. |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### tag {#tag-com.aspose.pdf.Annotation-}
Vincule um elemento de estrutura à Anotação.

### tag {#tag-com.aspose.pdf.Artifact-}
Vincule um elemento de estrutura ao Artefato.

### tag {#tag-com.aspose.pdf.operators.BDC-}
Vincule um elemento de estrutura ao operador BDC do fluxo de conteúdo.

### tag {#tag-com.aspose.pdf.XForm-}
Vincule um elemento de estrutura ao XForm do fluxo de conteúdo.

### tag {#tag-com.aspose.pdf.XImage-}
Vincule um elemento de estrutura ao XImage.

### toString {#toString--}
```
public String toString()
```

Retorna uma string que representa o objeto atual.

**Returns:**
String que representa o objeto atual.
