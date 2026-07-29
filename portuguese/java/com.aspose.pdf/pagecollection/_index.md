---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Coleção de páginas de documento PDF."
type: docs
weight: 3340
url: /pt/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

Coleção de páginas de documento PDF.

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita o objeto visitante {@code AnnotationSelector} que fornece funcionalidade para trabalhar com anotações. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Aceita o objeto visitante {@code ImagePlacementAbsorber} que fornece funcionalidade para trabalhar com objetos de posicionamento de imagem. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Aceita o objeto visitante {@code TextAbsorber} que fornece funcionalidade para trabalhar com objetos de texto. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Aceita o objeto visitante {@code TextFragmentAbsorber} que fornece funcionalidade para trabalhar com objetos de texto. |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | Adiciona página à coleção. |
| [add](#add--) | Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado. |
| [add](#add-java.lang.Iterable-) | Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado. |
| [add](#add-java.util.List-) | Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado. |
| [add](#add-com.aspose.pdf.Page-) | Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado. |
| [add](#add-com.aspose.pdf.Page:A-) | Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado. |
| [beginUpdate](#beginUpdate--) | Atualiza quando as alterações de grupo começam. |
| [clear](#clear--) | Limpa a coleção de páginas. |
| [contains](#contains-com.aspose.pdf.Page-) | Determina se esta instância contém o objeto. |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | Copia páginas para o documento. |
| [delete](#delete--) | Exclui todas as páginas da coleção. |
| [delete](#delete-int-) | Exclui a página especificada. |
| [delete](#delete-java.lang.Integer:A-) | Exclui todas as páginas da coleção. |
| [endUpdate](#endUpdate--) | Atualiza quando as alterações de grupo são concluídas. |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | Remove todos os campos localizados nas páginas e coloca seus valores no lugar. |
| [freeMemory](#freeMemory--) | Limpa os dados em cache |
| [get_Item](#get_Item-int-) | Obtém a página por índice. |
| [getSyncRoot](#getSyncRoot--) | Obtém o objeto de sincronização da coleção. |
| [getUnrestricted](#getUnrestricted-int-) | Retorna a página pelo seu índice. {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> Retorna o índice da página especificada. </p> |
| [insert](#insert-int-) | Insere uma página vazia na coleção na posição especificada. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado. |
| [insert](#insert-int-java.lang.Iterable-) | Insere páginas da coleção no documento. |
| [insert](#insert-int-java.util.List-) | Insere páginas da coleção no documento. |
| [insert](#insert-int-com.aspose.pdf.Page-) | Insere a página na coleção de páginas no local especificado. |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | Insere páginas do array no documento. |
| [isEmpty](#isEmpty--) | Retorna TRUE se a coleção estiver vazia. |
| [isReadOnly](#isReadOnly--) | Obtém o valor que indica se a coleção é somente leitura. Sempre retorna false. |
| [isSynchronized](#isSynchronized--) | Retorna true se o objeto está sincronizado. |
| [iterator](#iterator--) | Retorna o enumerador das páginas. |
| [remove](#remove-com.aspose.pdf.Page-) | Remove o item especificado, lança exceção. |
| [size](#size--) | Obtém a contagem de páginas no documento. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita o objeto visitante {@code AnnotationSelector} que fornece funcionalidade para trabalhar com anotações.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Aceita o objeto visitante {@code ImagePlacementAbsorber} que fornece funcionalidade para trabalhar com objetos de posicionamento de imagem.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Aceita o objeto visitante {@code TextAbsorber} que fornece funcionalidade para trabalhar com objetos de texto.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Aceita o objeto visitante {@code TextFragmentAbsorber} que fornece funcionalidade para trabalhar com objetos de texto.

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
Adiciona página à coleção.

### add {#add--}
```
public Page add()
```

Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado.

**Returns:**
Página adicionada.

### add {#add-java.lang.Iterable-}
Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado.

**Returns:**
Página adicionada.

### add {#add-java.util.List-}
Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado.

**Returns:**
Página adicionada.

### add {#add-com.aspose.pdf.Page-}
Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado.

**Returns:**
Página adicionada.

### add {#add-com.aspose.pdf.Page:A-}
Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado.

**Returns:**
Página adicionada.

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

Atualiza quando as alterações de grupo começam.

### clear {#clear--}
```
public void clear()
```

Limpa a coleção de páginas.

### contains {#contains-com.aspose.pdf.Page-}
Determina se esta instância contém o objeto.

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
Copia páginas para o documento.

### delete {#delete--}
```
public void delete()
```

Exclui todas as páginas da coleção.

### delete {#delete-int-}
```
public void delete(int index)
```

Exclui a página especificada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Número da página que será excluída. Os números das páginas começam em 1. |

### delete {#delete-java.lang.Integer:A-}
Exclui todas as páginas da coleção.

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

Atualiza quando as alterações de grupo são concluídas.

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

Remove todos os campos localizados nas páginas e coloca seus valores no lugar.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Limpa os dados em cache

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

Obtém a página por índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice da página. |

**Returns:**
Página recuperada.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtém o objeto de sincronização da coleção.

**Returns:**
Objeto para sincronização

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

Retorna a página pelo seu índice. {@code Page}

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice da página solicitada. As páginas são numeradas a partir de 1. |

**Returns:**
Página solicitada

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> Retorna o índice da página especificada. </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

Insere uma página vazia na coleção na posição especificada. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. Caso existam apenas duas páginas diferentes, o tamanho da primeira página será usado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | Posição da nova página. |

**Returns:**
Página inserida.

### insert {#insert-int-java.lang.Iterable-}
Insere páginas da coleção no documento.

### insert {#insert-int-java.util.List-}
Insere páginas da coleção no documento.

### insert {#insert-int-com.aspose.pdf.Page-}
Insere a página na coleção de páginas no local especificado.

### insert {#insert-int-com.aspose.pdf.Page:A-}
Insere páginas do array no documento.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Retorna TRUE se a coleção estiver vazia.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtém o valor que indica se a coleção é somente leitura. Sempre retorna false.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Retorna true se o objeto está sincronizado.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public Iterator < Page > iterator()
```

Retorna o enumerador das páginas.

**Returns:**
Enumerador de páginas

### remove {#remove-com.aspose.pdf.Page-}
Remove o item especificado, lança exceção.

### size {#size--}
```
public int size()
```

Obtém a contagem de páginas no documento.

**Returns:**
valor int
