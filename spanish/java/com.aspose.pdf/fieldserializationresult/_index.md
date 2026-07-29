---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el resultado de un proceso de serialización de campos de formulario."
type: docs
weight: 1390
url: /es/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

Representa el resultado de un proceso de serialización de campos de formulario.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | Inicializa una nueva instancia de la clase {@link FieldSerializationResult}. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | Inicializa una nueva instancia de la clase {@link FieldSerializationResult}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | Obtiene los mensajes de error asociados al proceso de serialización. Valor: Un conjunto de mensajes de error. |
| [getFieldFullName](#getFieldFullName--) | Obtiene el nombre completo del campo. Valor: El nombre completo del campo. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | Obtiene el estado de la serialización del campo de formulario. Valor: El estado de serialización del campo de formulario. |
| [getWarningMessages](#getWarningMessages--) | Obtiene los mensajes de advertencia asociados al proceso de serialización. Valor: Un conjunto de mensajes de advertencia. |
| [updateStatus](#updateStatus-int-java.lang.String-) | Actualiza el estado de la serialización y agrega un mensaje al conjunto correspondiente. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

Inicializa una nueva instancia de la clase {@link FieldSerializationResult}.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
Inicializa una nueva instancia de la clase {@link FieldSerializationResult}.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

Obtiene los mensajes de error asociados al proceso de serialización. Valor: Un conjunto de mensajes de error.

**Returns:**
Instancia de HashSet de String

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

Obtiene el nombre completo del campo. Valor: El nombre completo del campo.

**Returns:**
valor String

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

Obtiene el estado de la serialización del campo de formulario. Valor: El estado de serialización del campo de formulario.

**Returns:**
Elemento FieldSerializationStatus

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

Obtiene los mensajes de advertencia asociados al proceso de serialización. Valor: Un conjunto de mensajes de advertencia.

**Returns:**
Instancia de HashSet de String

### updateStatus {#updateStatus-int-java.lang.String-}
Actualiza el estado de la serialización y agrega un mensaje al conjunto correspondiente.
