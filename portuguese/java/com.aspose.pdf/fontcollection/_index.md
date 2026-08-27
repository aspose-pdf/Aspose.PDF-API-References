---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa a coleção de fontes. </p> <hr> <pre> O exemplo demonstra como tornar todas as fontes declaradas na página incorporadas. // Abrir documento Document doc = new."
type: docs
weight: 1670
url: /pt/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> Representa a coleção de fontes. </p> <hr> <pre> O exemplo demonstra como tornar todas as fontes declaradas na página incorporadas. // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // garantir que todas as fontes declaradas nos recursos da página estejam incorporadas // observar que se as fontes forem declaradas nos recursos de formulário elas não são acessíveis a partir dos recursos da página for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\Tests\\input.pdf"); </pre> <hr> <p> Coleções de fontes representadas pela classe {@code FontCollection} são usadas em vários cenários. Por exemplo, em recursos com a propriedade {@code Resources.Fonts}. </p>

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | Adiciona Fonte à coleção. |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | Adiciona nova fonte aos recursos de fontes e retorna o nome atribuído automaticamente ao recurso de fonte. |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Adicionar nova fonte à coleção de fontes. |
| [add](#add-java.lang.String-java.lang.String-) | Adiciona aos recursos de fontes uma nova entrada de fonte com o nome base de fonte especificado. |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * Adiciona Fonte à coleção. / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | Determina se a coleção contém um valor específico. |
| [contains](#contains-java.lang.String-) | Verifica se a fonte existe na coleção de fontes. |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | Copia toda a coleção para um Array unidimensional compatível, começando no índice especificado do array de destino. |
| [delete](#delete-java.lang.String-) | Exclui Fonte com o nome de recurso especificado |
| [get_Item](#get_Item-int-) | Obtém o elemento de fonte no índice especificado. |
| [get_Item](#get_Item-java.lang.String-) | Obtém a fonte da coleção pelo nome da fonte. Uma exceção é lançada se a fonte não for encontrada. |
| [getFontsDictionary](#getFontsDictionary--) | Obter objeto IPdfDictionary |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | Obtém um objeto que pode ser usado para sincronizar o acesso à coleção. |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se a coleção é somente leitura |
| [isSynchronized](#isSynchronized--) | Obtém um valor que indica se o acesso à coleção está sincronizado (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Retorna um enumerador para toda a coleção. |
| [iterator](#iterator--) | Retorna um enumerador para toda a coleção. |
| [remove](#remove-com.aspose.pdf.Font-) | Exclui o item especificado da coleção. |
| [size](#size--) | Obtém o número de elementos de objeto {@code Font} realmente contidos na coleção. |

### add {#add-com.aspose.pdf.Font-}
Adiciona Fonte à coleção.

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
Adiciona nova fonte aos recursos de fontes e retorna o nome atribuído automaticamente ao recurso de fonte.

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
Adicionar nova fonte à coleção de fontes.

### add {#add-java.lang.String-java.lang.String-}
Adiciona aos recursos de fontes uma nova entrada de fonte com o nome base de fonte especificado.

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * Adiciona Fonte à coleção. / * / *

### contains {#contains-com.aspose.pdf.Font-}
Determina se a coleção contém um valor específico.

### contains {#contains-java.lang.String-}
Verifica se a fonte existe na coleção de fontes.

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
Copia toda a coleção para um Array unidimensional compatível, começando no índice especificado do array de destino.

### delete {#delete-java.lang.String-}
Exclui Fonte com o nome de recurso especificado

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

Obtém o elemento de fonte no índice especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice dentro da coleção. |

**Returns:**
Objeto de fonte.

### get_Item {#get_Item-java.lang.String-}
Obtém a fonte da coleção pelo nome da fonte. Uma exceção é lançada se a fonte não for encontrada.

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

Obter objeto IPdfDictionary

**Returns:**
Objeto IPdfDictionary

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtém um objeto que pode ser usado para sincronizar o acesso à coleção.

**Returns:**
Objeto para sincronização

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtém um valor que indica se a coleção é somente leitura

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtém um valor que indica se o acesso à coleção está sincronizado (thread safe).

**Returns:**
valor booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Retorna um enumerador para toda a coleção.

**Returns:**
Objeto enumerador.

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

Retorna um enumerador para toda a coleção.

**Returns:**
Objeto enumerador.

### remove {#remove-com.aspose.pdf.Font-}
Exclui o item especificado da coleção.

### size {#size--}
```
public int size()
```

Obtém o número de elementos de objeto {@code Font} realmente contidos na coleção.

**Returns:**
valor int
