---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe base para elementos de estrutura na estrutura lógica."
type: docs
weight: 110
url: /pt/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

Representa uma classe base para elementos de estrutura na estrutura lógica.

## Métodos

| Método | Descrição |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Alterar o elemento pai do elemento de estrutura atual |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | Alterar o elemento pai do elemento de estrutura atual |
| [clearId](#clearId--) | Limpar ID do elemento de estrutura. |
| [generateId](#generateId--) | Gerar ID para o elemento de estrutura. |
| [getActualText](#getActualText--) | Obtém ou define o texto real do elemento de estrutura. |
| [getAlternativeText](#getAlternativeText--) | Obtém ou define o texto alternativo do elemento de estrutura. |
| [getAttributes](#getAttributes--) | Obtém o objeto {@code StructureAttributeCollection}. |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | Obtém o objeto {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. Valor: objeto {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. |
| [getExpansionText](#getExpansionText--) | Obtém ou define o texto de expansão do elemento de estrutura. |
| [getID](#getID--) | Obtém o ID do elemento de estrutura. Valor: ID do elemento de estrutura. |
| [getLanguage](#getLanguage--) | Obtém ou define o idioma do elemento de estrutura. |
| [getPage](#getPage--) | Obtém a página na qual alguns ou todos os elementos filhos serão renderizados. |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | Obtém o tipo do elemento de estrutura. |
| [getTitle](#getTitle--) | Obtém ou define o título do elemento de estrutura. |
| [remove](#remove--) | Remove: um elemento da estrutura, uma referência a ele do objeto pai, referências a ele dos objetos filhos, o objeto correspondente do documento. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | Remove um elemento da estrutura, uma referência a ele do objeto pai, referências a ele dos objetos filhos e o objeto correspondente do documento. Insere os objetos filhos do objeto removido na coleção de objetos filhos do seu antigo pai, começando no índice do objeto removido. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | Remove um elemento da estrutura, uma referência a ele do objeto pai, referências a ele dos objetos filhos e o objeto correspondente do documento. Insere os objetos filhos do objeto removido na coleção de objetos filhos do seu antigo pai, começando no índice do objeto removido. |
| [setActualText](#setActualText-java.lang.String-) | Obtém ou define o texto real do elemento de estrutura. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Obtém ou define o texto alternativo do elemento de estrutura. |
| [setExpansionText](#setExpansionText-java.lang.String-) | Obtém ou define o texto de expansão do elemento de estrutura. |
| [setId](#setId-java.lang.String-) | Define o ID para o elemento de estrutura. |
| [setLanguage](#setLanguage-java.lang.String-) | Obtém ou define o idioma do elemento de estrutura. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | definir Elemento Pai |
| [setTag](#setTag-java.lang.String-) | Define a tag personalizada para o elemento de estrutura. |
| [setTitle](#setTitle-java.lang.String-) | Obtém ou define o título do elemento de estrutura. |
| [tag](#tag-com.aspose.pdf.Annotation-) | Vincule um elemento de estrutura à Anotação. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Vincule um elemento de estrutura ao Artefato. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Vincule um elemento de estrutura ao operador BDC do fluxo de conteúdo. |
| [tag](#tag-com.aspose.pdf.XForm-) | Vincule um elemento de estrutura ao XForm do fluxo de conteúdo. |
| [tag](#tag-com.aspose.pdf.XImage-) | Vincule um elemento de estrutura ao XImage. |
| [toString](#toString--) | Retorna uma string que representa o objeto atual. |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Alterar o elemento pai do elemento de estrutura atual

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
Alterar o elemento pai do elemento de estrutura atual

### clearId {#clearId--}
```
public final void clearId()
```

Limpar ID do elemento de estrutura.

### generateId {#generateId--}
```
public final void generateId()
```

Gerar ID para o elemento de estrutura.

### getActualText {#getActualText--}
```
public final String getActualText()
```

Obtém ou define o texto real do elemento de estrutura.

**Returns:**
Valor: Texto real do elemento de estrutura.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Obtém ou define o texto alternativo do elemento de estrutura.

**Returns:**
Valor: Texto alternativo do elemento de estrutura.

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

Obtém o objeto {@code StructureAttributeCollection}.

**Returns:**
{@code StructureAttributeCollection} objeto.

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

Obtém o objeto {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. Valor: objeto {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}.

**Returns:**
Instância de AttributeOwnerStandard

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

Obtém ou define o texto de expansão do elemento de estrutura.

**Returns:**
Valor: Texto de expansão do elemento de estrutura.

### getID {#getID--}
```
public final String getID()
```

Obtém o ID do elemento de estrutura. Valor: ID do elemento de estrutura.

**Returns:**
valor String

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

Obtém ou define o idioma do elemento de estrutura.

**Returns:**
Valor: Idioma do elemento de estrutura.

### getPage {#getPage--}
```
public final Page getPage()
```

Obtém a página na qual alguns ou todos os elementos filhos serão renderizados.

**Returns:**
Instância da Página

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

Obtém o tipo do elemento de estrutura.

**Returns:**
Valor: {@code StructureTypeStandard} objeto do elemento de estrutura.

### getTitle {#getTitle--}
```
public final String getTitle()
```

Obtém ou define o título do elemento de estrutura.

**Returns:**
Valor: Título do elemento de estrutura.

### remove {#remove--}
```
public final void remove()
```

Remove: um elemento da estrutura, uma referência a ele do objeto pai, referências a ele dos objetos filhos, o objeto correspondente do documento.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

Remove um elemento da estrutura, uma referência a ele do objeto pai, referências a ele dos objetos filhos e o objeto correspondente do documento. Insere os objetos filhos do objeto removido na coleção de objetos filhos do seu antigo pai, começando no índice do objeto removido.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

Remove um elemento da estrutura, uma referência a ele do objeto pai, referências a ele dos objetos filhos e o objeto correspondente do documento. Insere os objetos filhos do objeto removido na coleção de objetos filhos do seu antigo pai, começando no índice do objeto removido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | Verifique se os objetos filhos do objeto removido podem ser inseridos na coleção de objetos filhos do seu pai. |

### setActualText {#setActualText-java.lang.String-}
Obtém ou define o texto real do elemento de estrutura.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Obtém ou define o texto alternativo do elemento de estrutura.

### setExpansionText {#setExpansionText-java.lang.String-}
Obtém ou define o texto de expansão do elemento de estrutura.

### setId {#setId-java.lang.String-}
Define o ID para o elemento de estrutura.

### setLanguage {#setLanguage-java.lang.String-}
Obtém ou define o idioma do elemento de estrutura.

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
definir Elemento Pai

### setTag {#setTag-java.lang.String-}
Define a tag personalizada para o elemento de estrutura.

### setTitle {#setTitle-java.lang.String-}
Obtém ou define o título do elemento de estrutura.

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
