---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Uma classe para acessar a árvore de dicionário de um documento (dicionário do documento, dicionário de página, dicionário de recursos)."
type: docs
weight: 70
url: /pt/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

Uma classe para acessar a árvore de dicionário de um documento (dicionário do documento, dicionário de página, dicionário de recursos).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException Os recursos são nulos. |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Defina ICosPdfPrimitive no dicionário. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Defina {@link ICosPdfPrimitive} no dicionário. |
| [clear](#clear--) | Remove todos os itens do {@link DictionaryEditor}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determina se o DictionaryEditor contém um valor específico. |
| [containsKey](#containsKey-java.lang.String-) | Determina se o {@link DictionaryEditor} contém um elemento com a chave especificada. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia os elementos do DictionaryEditor para um Array, começando em um índice específico do Array. |
| [get_Item](#get_Item-java.lang.String-) | Obtém ou define o elemento com a chave especificada. |
| [getAllKeys](#getAllKeys--) | Coleção completa de chaves. Contém chaves editáveis e não editáveis. |
| [getKeys](#getKeys--) | Coleção de chaves editáveis. |
| [getValues](#getValues--) | Obtém um {@link ICollection} contendo os valores no {@link DictionaryEditor}. |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se o {@link DictionaryEditor} é somente leitura. |
| [iterator](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Remove a primeira ocorrência de um objeto específico do DictionaryEditor. |
| [remove](#remove-java.lang.String-) | Remove o elemento com a chave especificada do {@link DictionaryEditor}. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Obtém ou define o elemento com a chave especificada. |
| [size](#size--) | Obtém o número de elementos contidos no {@link DictionaryEditor}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Para acesso a tipos de dados simples como string, name, bool, number. Retorna nulo para outros tipos. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException Os recursos são nulos.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Defina ICosPdfPrimitive no dicionário.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Defina {@link ICosPdfPrimitive} no dicionário.

### clear {#clear--}
```
public final void clear()
```

Remove todos os itens do {@link DictionaryEditor}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determina se o DictionaryEditor contém um valor específico.

### containsKey {#containsKey-java.lang.String-}
Determina se o {@link DictionaryEditor} contém um elemento com a chave especificada.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia os elementos do DictionaryEditor para um Array, começando em um índice específico do Array.

### get_Item {#get_Item-java.lang.String-}
Obtém ou define o elemento com a chave especificada.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Coleção completa de chaves. Contém chaves editáveis e não editáveis.

**Returns:**
Iterável de instância String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Coleção de chaves editáveis.

**Returns:**
Iterável de instância String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Obtém um {@link ICollection} contendo os valores no {@link DictionaryEditor}.

**Returns:**
Iterável de instância ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtém um valor que indica se o {@link DictionaryEditor} é somente leitura.

**Returns:**
true se o {@link DictionaryEditor} for somente leitura; caso contrário, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Retorna um enumerador que itera através da coleção.

**Returns:**
Um enumerador que pode ser usado para iterar através da coleção.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Remove a primeira ocorrência de um objeto específico do DictionaryEditor.

### remove {#remove-java.lang.String-}
Remove o elemento com a chave especificada do {@link DictionaryEditor}.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Obtém ou define o elemento com a chave especificada.

### size {#size--}
```
public final int size()
```

Obtém o número de elementos contidos no {@link DictionaryEditor}.

**Returns:**
valor int

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Para acesso a tipos de dados simples como string, name, bool, number. Retorna nulo para outros tipos.
