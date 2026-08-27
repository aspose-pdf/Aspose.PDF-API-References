---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe de campo de esquema de coleção de documentos."
type: docs
weight: 620
url: /pt/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

Representa uma classe de campo de esquema de coleção de documentos.

## Métodos

| Método | Descrição |
| --- | --- |
| [getE](#getE--) | Obtém um sinalizador que indica se o processador de PDF interativo deve fornecer suporte para edição do valor do campo. Valor padrão: false |
| [getFiledType](#getFiledType--) | Obtém o tipo de um valor de campo em uma coleção de esquema. Este campo descreve o tipo de valor correspondente a {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}). |
| [getN](#getN--) | Obtém o nome textual do campo que deve ser apresentado ao usuário pelo processador de PDF interativo |
| [getO](#getO--) | Obtém a ordem relativa do nome do campo na interface do usuário. Os campos devem ser ordenados pelo processador de PDF interativo em ordem crescente. |
| [getSubtype](#getSubtype--) | Obtém o subtipo de um valor de campo em uma coleção de esquema. O subtipo do campo de coleção ou do campo relacionado a arquivo que este dicionário descreve. Esta entrada identifica o tipo de dados que deve ser armazenado no campo. |
| [getV](#getV--) | Obtém a visibilidade inicial do campo na interface do usuário. Valor padrão: true. |

### getE {#getE--}
```
public final boolean getE()
```

Obtém um sinalizador que indica se o processador de PDF interativo deve fornecer suporte para edição do valor do campo. Valor padrão: false

**Returns:**
valor booleano

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

Obtém o tipo de um valor de campo em uma coleção de esquema. Este campo descreve o tipo de valor correspondente a {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}).

**Returns:**
Elemento FieldValueType

### getN {#getN--}
```
public final String getN()
```

Obtém o nome textual do campo que deve ser apresentado ao usuário pelo processador de PDF interativo

**Returns:**
valor String

### getO {#getO--}
```
public final Integer [] getO()
```

Obtém a ordem relativa do nome do campo na interface do usuário. Os campos devem ser ordenados pelo processador de PDF interativo em ordem crescente.

**Returns:**
array de Integer

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

Obtém o subtipo de um valor de campo em uma coleção de esquema. O subtipo do campo de coleção ou do campo relacionado a arquivo que este dicionário descreve. Esta entrada identifica o tipo de dados que deve ser armazenado no campo.

**Returns:**
Elemento CollectionFieldSubtype

### getV {#getV--}
```
public final boolean getV()
```

Obtém a visibilidade inicial do campo na interface do usuário. Valor padrão: true.

**Returns:**
valor booleano
