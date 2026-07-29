---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Referência da API Aspose.PDF para Java"
description: "Uma classe para acessar o dicionário de um objeto."
type: docs
weight: 20
url: /pt/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

Uma classe para acessar o dicionário de um objeto.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | Cria um dicionário a partir dos recursos. @exception ArgumentNullException Os recursos são nulos. |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Defina ICosPdfPrimitive no dicionário. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Define {@link ICosPdfPrimitive} no dicionário. @exception ArgumentException Lança exceção se a chave/valor não puderem ser editados ou removidos. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Adicionar par de itens. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Adicionar item. |
| [clear](#clear--) | Remove todos os itens do {@link CosPdfDictionary}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determina se o CosPdfDictionary contém um valor específico. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Retorna true se contém o item |
| [containsKey](#containsKey-java.lang.String-) | Determina se o {@link CosPdfDictionary} contém um elemento com a chave especificada. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia os elementos do CosPdfDictionary para um Array, começando em um índice específico do Array. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copiar para Array |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | Cria um dicionário vazio que será anexado ao documento. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | Cria um dicionário vazio que será anexado à página. |
| [get_Item](#get_Item-java.lang.String-) | Obtém ou define o elemento com a chave especificada. |
| [getAllKeys](#getAllKeys--) | Coleção completa de chaves. Contém chaves editáveis e não editáveis. |
| [getKeys](#getKeys--) | Coleção de chaves editáveis. |
| [getValues](#getValues--) | Obtém um {@link ICollection} contendo os valores no {@link CosPdfDictionary}. |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se o {@link CosPdfDictionary} é somente leitura. |
| [iterator](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Remove a primeira ocorrência de um objeto específico do CosPdfDictionary. |
| [remove](#remove-java.lang.String-) | Remove o elemento com a chave especificada do {@link CosPdfDictionary}. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Remover Item |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Remover item por chave. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Obtém ou define o elemento com a chave especificada. @exception ArgumentNullException A chave é nula. @exception KeyNotFoundException A propriedade foi recuperada e a chave não foi encontrada. @exception ArgumentException Lança exceção se a chave não puder ser editada/definida. |
| [size](#size--) | Obtém o número de elementos contidos no {@link CosPdfDictionary}. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | Tenta converter esta instância para {@link CosPdfDictionary}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Para acesso a tipos de dados simples como string, name, bool, number. Retorna nulo para outros tipos. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Tentar obter valor |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
Cria um dicionário a partir dos recursos. @exception ArgumentNullException Os recursos são nulos.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Defina ICosPdfPrimitive no dicionário.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Define {@link ICosPdfPrimitive} no dicionário. @exception ArgumentException Lança exceção se a chave/valor não puderem ser editados ou removidos.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Adicionar par de itens.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Adicionar item.

### clear {#clear--}
```
public final void clear()
```

Remove todos os itens do {@link CosPdfDictionary}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determina se o CosPdfDictionary contém um valor específico.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Retorna true se contém o item

### containsKey {#containsKey-java.lang.String-}
Determina se o {@link CosPdfDictionary} contém um elemento com a chave especificada.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia os elementos do CosPdfDictionary para um Array, começando em um índice específico do Array.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copiar para Array

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
Cria um dicionário vazio que será anexado ao documento.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
Cria um dicionário vazio que será anexado à página.

### get_Item {#get_Item-java.lang.String-}
Obtém ou define o elemento com a chave especificada.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Coleção completa de chaves. Contém chaves editáveis e não editáveis.

**Returns:**
Lista de valores String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Coleção de chaves editáveis.

**Returns:**
Lista de valores String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Obtém um {@link ICollection} contendo os valores no {@link CosPdfDictionary}.

**Returns:**
Lista de instâncias de ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtém um valor que indica se o {@link CosPdfDictionary} é somente leitura.

**Returns:**
true se o {@link CosPdfDictionary} for somente leitura; caso contrário, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Retorna um enumerador que itera através da coleção.

**Returns:**
Um enumerador que pode ser usado para iterar através da coleção.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Remove a primeira ocorrência de um objeto específico do CosPdfDictionary.

### remove {#remove-java.lang.String-}
Remove o elemento com a chave especificada do {@link CosPdfDictionary}.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Remover Item

### removeItemByKey {#removeItemByKey-java.lang.String-}
Remover item por chave.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Obtém ou define o elemento com a chave especificada. @exception ArgumentNullException A chave é nula. @exception KeyNotFoundException A propriedade foi recuperada e a chave não foi encontrada. @exception ArgumentException Lança exceção se a chave não puder ser editada/definida.

### size {#size--}
```
public final int size()
```

Obtém o número de elementos contidos no {@link CosPdfDictionary}.

**Returns:**
valor int

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

Tenta converter esta instância para {@link CosPdfDictionary}.

**Returns:**
null se a instância não for {@link CosPdfDictionary}, caso contrário {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Para acesso a tipos de dados simples como string, name, bool, number. Retorna nulo para outros tipos.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Tentar obter valor
