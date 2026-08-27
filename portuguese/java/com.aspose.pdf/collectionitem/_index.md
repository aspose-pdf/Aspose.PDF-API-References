---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe de item de coleção. O item de coleção contém os dados descritos pelo esquema da coleção."
type: docs
weight: 640
url: /pt/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

Representa uma classe de item de coleção. O item de coleção contém os dados descritos pelo esquema da coleção.

## Métodos

| Método | Descrição |
| --- | --- |
| [getAllNames](#getAllNames--) | Obtém uma coleção de todos os nomes dos valores do item de coleção. |
| [hasName](#hasName-java.lang.String-) | Verifica se o nome fornecido existe no item de coleção. |
| [isEmpty](#isEmpty--) | Obtém um valor que indica se o item de coleção está vazio. |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tenta obter o valor do tipo DateTime do item de coleção pelo nome especificado. |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tenta obter o valor double para o nome especificado do item de coleção. |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tenta obter o valor inteiro para um nome especificado do item de coleção. |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tenta obter o valor de texto com o nome especificado do item de coleção. |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

Obtém uma coleção de todos os nomes dos valores do item de coleção.

**Returns:**
lista de String

### hasName {#hasName-java.lang.String-}
Verifica se o nome fornecido existe no item de coleção.

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

Obtém um valor que indica se o item de coleção está vazio.

**Returns:**
true se o item de coleção estiver vazio; caso contrário, false. Esta propriedade retorna true se o item de coleção não contiver nenhum valor, incluindo valores de string, valores double, valores inteiros e valores de data. Se algum desses tipos de valor estiver presente no item de coleção, esta propriedade retorna false.

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tenta obter o valor do tipo DateTime do item de coleção pelo nome especificado.

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tenta obter o valor double para o nome especificado do item de coleção.

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tenta obter o valor inteiro para um nome especificado do item de coleção.

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tenta obter o valor de texto com o nome especificado do item de coleção.
