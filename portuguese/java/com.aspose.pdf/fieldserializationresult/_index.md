---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o resultado de um processo de serialização de campo de formulário."
type: docs
weight: 1390
url: /pt/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

Representa o resultado de um processo de serialização de campo de formulário.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | Inicializa uma nova instância da classe {@link FieldSerializationResult}. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | Inicializa uma nova instância da classe {@link FieldSerializationResult}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | Obtém as mensagens de erro associadas ao processo de serialização. Valor: um conjunto de mensagens de erro. |
| [getFieldFullName](#getFieldFullName--) | Obtém o nome completo do campo. Valor: o nome completo do campo. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | Obtém o status da serialização do campo de formulário. Valor: o status da serialização do campo de formulário. |
| [getWarningMessages](#getWarningMessages--) | Obtém as mensagens de aviso associadas ao processo de serialização. Valor: um conjunto de mensagens de aviso. |
| [updateStatus](#updateStatus-int-java.lang.String-) | Atualiza o status da serialização e adiciona uma mensagem ao conjunto apropriado. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

Inicializa uma nova instância da classe {@link FieldSerializationResult}.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
Inicializa uma nova instância da classe {@link FieldSerializationResult}.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

Obtém as mensagens de erro associadas ao processo de serialização. Valor: um conjunto de mensagens de erro.

**Returns:**
Instância de HashSet de String

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

Obtém o nome completo do campo. Valor: o nome completo do campo.

**Returns:**
valor String

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

Obtém o status da serialização do campo de formulário. Valor: o status da serialização do campo de formulário.

**Returns:**
Elemento FieldSerializationStatus

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

Obtém as mensagens de aviso associadas ao processo de serialização. Valor: um conjunto de mensagens de aviso.

**Returns:**
Instância de HashSet de String

### updateStatus {#updateStatus-int-java.lang.String-}
Atualiza o status da serialização e adiciona uma mensagem ao conjunto apropriado.
