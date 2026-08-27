---
title: "Metadados"
linktitle: "Metadados"
second_title: "Referência da API Aspose.PDF para Java"
description: "Fornece acesso ao fluxo de metadados XMP."
type: docs
weight: 3050
url: /pt/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Fornece acesso ao fluxo de metadados XMP.

## Métodos

| Método | Descrição |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Adiciona um par com chave e valor ao dicionário. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Adiciona valor aos metadados. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | Adiciona extensão pdf aos metadados. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Adiciona valor aos metadados. |
| [clear](#clear--) | Limpa os metadados. |
| [contains](#contains-java.lang.String-) | Verifica se a chave está contida nos metadados. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Verifica se o par chave-valor especificado está contido no dicionário. |
| [containsKey](#containsKey-java.lang.String-) | Determina se este dicionário contém a chave especificada. |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | Copia os elementos da coleção para um array. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia os elementos da coleção para um array. |
| [get_Item](#get_Item-java.lang.String-) | Obtém dados dos metadados. |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | Somente para uso interno. Obtém o dicionário de campos de extensão. |
| [getExtensionFields](#getExtensionFields--) | <p> Obtém o dicionário de campos de extensão. </p> |
| [getItem](#getItem-java.lang.String-) | Obtém dados dos metadados. |
| [getKeys](#getKeys--) | Obtém a coleção de chaves dos metadados. |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | Retorna o URI do namespace pelo prefixo. |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | Retorna o prefixo pelo URI do namespace. |
| [getSyncRoot](#getSyncRoot--) | Obtém o objeto de sincronização da coleção. |
| [getValues](#getValues--) | Obtém valores nos metadados. |
| [isFixedSize](#isFixedSize--) | Verifica se a coleção tem tamanho fixo. |
| [isReadOnly](#isReadOnly--) | Verifica se a coleção é somente leitura. |
| [isSynchronized](#isSynchronized--) | Verifica se a coleção está sincronizada. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Retorna o enumerador do dicionário. |
| [iteratorIE](#iteratorIE--) | Obtém o enumerador da coleção. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | Registra o URI do namespace. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Registra o URI do namespace. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Remove o par chave/valor da coleção. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Remove a entrada dos metadados. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | Define os dados a partir dos metadados. |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | Define os dados a partir dos metadados. |
| [size](#size--) | Obtém a contagem de elementos na coleção. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Tenta encontrar a chave no dicionário e recupera o valor se encontrado. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | Tenta encontrar a chave no dicionário e recupera o valor se encontrado. |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Adiciona um par com chave e valor ao dicionário.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Adiciona valor aos metadados.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
Adiciona extensão pdf aos metadados.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
Adiciona valor aos metadados.

### clear {#clear--}
```
public void clear()
```

Limpa os metadados.

### contains {#contains-java.lang.String-}
Verifica se a chave está contida nos metadados.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Verifica se o par chave-valor especificado está contido no dicionário.

### containsKey {#containsKey-java.lang.String-}
Determina se este dicionário contém a chave especificada.

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
Copia os elementos da coleção para um array.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia os elementos da coleção para um array.

### get_Item {#get_Item-java.lang.String-}
Obtém dados dos metadados.

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

Somente para uso interno. Obtém o dicionário de campos de extensão.

**Returns:**
objeto interno

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Obtém o dicionário de campos de extensão. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} objeto

### getItem {#getItem-java.lang.String-}
Obtém dados dos metadados.

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Obtém a coleção de chaves dos metadados.

**Returns:**
objeto ICollection

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
Retorna o URI do namespace pelo prefixo.

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
Retorna o prefixo pelo URI do namespace.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtém o objeto de sincronização da coleção.

**Returns:**
Objeto para sincronização

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Obtém valores nos metadados.

**Returns:**
objeto ICollection

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Verifica se a coleção tem tamanho fixo.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Verifica se a coleção é somente leitura.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Verifica se a coleção está sincronizada.

**Returns:**
valor booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Retorna o enumerador do dicionário.

**Returns:**
Enumerador.

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

Obtém o enumerador da coleção.

**Returns:**
objeto IEnumerator @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
Registra o URI do namespace.

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
Registra o URI do namespace.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Remove o par chave/valor da coleção.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Remove a entrada dos metadados.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
Define os dados a partir dos metadados.

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
Define os dados a partir dos metadados.

### size {#size--}
```
public int size()
```

Obtém a contagem de elementos na coleção.

**Returns:**
valor int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Tenta encontrar a chave no dicionário e recupera o valor se encontrado.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
Tenta encontrar a chave no dicionário e recupera o valor se encontrado.
