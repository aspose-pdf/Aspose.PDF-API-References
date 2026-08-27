---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Referência da API Aspose.PDF para Java"
description: "Dicionário de aparência da anotação que especifica como a anotação deve ser apresentada visualmente na página."
type: docs
weight: 150
url: /pt/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

Dicionário de aparência da anotação que especifica como a anotação deve ser apresentada visualmente na página.

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | Adiciona um elemento com a chave e o valor fornecidos. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Adiciona um par com chave e valor ao dicionário. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Adiciona X form para a chave especificada. |
| [clear](#clear--) | Remove todos os elementos do dicionário. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Verifica se o par chave-valor especificado está contido no dicionário. |
| [containsKey](#containsKey-java.lang.String-) | Determina se este dicionário contém a chave especificada. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * Retorna um objeto IDictionaryEnumerator para o dicionário. / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia os elementos da ICollection para um Array, começando em um índice específico do Array. |
| [get_Item](#get_Item-java.lang.String-) | Representa uma forma conveniente de obter fluxos de aparência. |
| [getDict](#getDict--) | Obtém o dicionário pdf |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | Valores D).state, onde N - aparência normal, R - aparência de rollover, D - aparência pressionada e state - o nome do estado (ex.: On, Off para caixas de seleção). |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | Valores D).state, onde N - aparência normal, R - aparência de rollover, D - aparência pressionada e state - o nome do estado (ex.: On, Off para caixas de seleção). |
| [getSyncRoot](#getSyncRoot--) | Obtém um objeto que pode ser usado para sincronizar o acesso ao dicionário. |
| [getValues_](#getValues_--) | Obtém a lista dos valores do dicionário. A coleção resultante contém a lista de objetos XForm. |
| [getValues](#getValues--) | Obtém a lista dos valores do dicionário. A coleção resultante contém a lista de objetos XForm. |
| [isFixedSize](#isFixedSize--) | Obtém um valor que indica se o dicionário tem tamanho fixo. |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se o dicionário é somente leitura. |
| [isSynchronized](#isSynchronized--) | Obtém um valor que indica se o acesso ao dicionário está sincronizado (thread safe). |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | Enumerador para a coleção. |
| [iterator](#iterator--) | Retorna um objeto IDictionaryEnumerator para o dicionário. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Remove o par chave/valor da coleção. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Remove a chave do dicionário. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | Obtém o número de elementos contidos no dicionário. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Tenta encontrar a chave no dicionário e recupera o valor se encontrado. |

### add {#add-java.lang.Object-java.lang.Object-}
Adiciona um elemento com a chave e o valor fornecidos.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Adiciona um par com chave e valor ao dicionário.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
Adiciona X form para a chave especificada.

### clear {#clear--}
```
public void clear()
```

Remove todos os elementos do dicionário.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Verifica se o par chave-valor especificado está contido no dicionário.

### containsKey {#containsKey-java.lang.String-}
Determina se este dicionário contém a chave especificada.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * Retorna um objeto IDictionaryEnumerator para o dicionário. / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia os elementos da ICollection para um Array, começando em um índice específico do Array.

### get_Item {#get_Item-java.lang.String-}
Representa uma forma conveniente de obter fluxos de aparência.

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

Obtém o dicionário pdf

**Returns:**
Objeto IPdfDictionary

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

Obtém as chaves do dicionário. Se o dicionário de aparência tem subdicionários, então {@code Keys} contém valores (N|R|D).state, onde N - aparência normal, R - aparência de rollover, D - aparência pressionada e state - o nome do estado (ex.: On, Off para caixas de seleção).

**Returns:**
Lista de valores String

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Obtém as chaves do dicionário. Se o dicionário de aparência tem subdicionários, então {@code Keys} contém valores (N|R|D).state, onde N - aparência normal, R - aparência de rollover, D - aparência pressionada e state - o nome do estado (ex.: On, Off para caixas de seleção).

**Returns:**
Lista de valores String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtém um objeto que pode ser usado para sincronizar o acesso ao dicionário.

**Returns:**
Objeto para sincronização

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

Obtém a lista dos valores do dicionário. A coleção resultante contém a lista de objetos XForm.

**Returns:**
Lista de valores XForm

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

Obtém a lista dos valores do dicionário. A coleção resultante contém a lista de objetos XForm.

**Returns:**
Lista de valores XForm

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Obtém um valor que indica se o dicionário tem tamanho fixo.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtém um valor que indica se o dicionário é somente leitura.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtém um valor que indica se o acesso ao dicionário está sincronizado (thread safe).

**Returns:**
valor booleano

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

Enumerador para a coleção.

**Returns:**
enumerador dos itens da coleção.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

Retorna um objeto IDictionaryEnumerator para o dicionário.

**Returns:**
Enumerador do dicionário.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Remove o par chave/valor da coleção.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Remove a chave do dicionário.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

Obtém o número de elementos contidos no dicionário.

**Returns:**
valor int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Tenta encontrar a chave no dicionário e recupera o valor se encontrado.
