---
title: "UnifiedSaveOptions.ProgressEventHandlerInfo"
linktitle: "UnifiedSaveOptions.ProgressEventHandlerInfo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase representa información sobre el progreso de la conversión que puede usarse en una aplicación externa para mostrar el progreso de la conversión al usuario final."
type: docs
weight: 5440
url: /es/java/com.aspose.pdf/unifiedsaveoptions.progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo

```
public static class UnifiedSaveOptions.ProgressEventHandlerInfo extends Object
```

Esta clase representa información sobre el progreso de la conversión que puede usarse en una aplicación externa para mostrar el progreso de la conversión al usuario final.

## Métodos

| Método | Descripción |
| --- | --- |
| [getDocumentId](#getDocumentId--) | El ID de documento único. |
| [getEventType](#getEventType--) | Tipo de evento de progreso que ocurrió |
| [getMaxValue](#getMaxValue--) | valor máximo posible del valor de progreso |
| [getValue](#getValue--) | valor actual del valor de progreso |
| [setDocumentId](#setDocumentId-com.aspose.ms.System.Guid-) | El ID de documento único. |
| [setEventType](#setEventType-int-) | Tipo de evento de progreso que ocurrió |
| [setMaxValue](#setMaxValue-int-) | valor máximo posible del valor de progreso |
| [setValue](#setValue-int-) | valor actual del valor de progreso |

### getDocumentId {#getDocumentId--}
```
public com.aspose.ms.System.Guid getDocumentId()
```

El ID de documento único.

**Returns:**
Instancia Guid

### getEventType {#getEventType--}
```
public int getEventType()
```

Tipo de evento de progreso que ocurrió

**Returns:**
Elemento ProgressEventType @see ProgressEventType

### getMaxValue {#getMaxValue--}
```
public int getMaxValue()
```

valor máximo posible del valor de progreso

**Returns:**
valor int

### getValue {#getValue--}
```
public int getValue()
```

valor actual del valor de progreso

**Returns:**
valor int

### setDocumentId {#setDocumentId-com.aspose.ms.System.Guid-}
El ID de documento único.

### setEventType {#setEventType-int-}
```
public void setEventType(int eventType)
```

Tipo de evento de progreso que ocurrió

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eventType |  | Elemento ProgressEventType @see ProgressEventType |

### setMaxValue {#setMaxValue-int-}
```
public void setMaxValue(int maxValue)
```

valor máximo posible del valor de progreso

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxValue |  | valor int |

### setValue {#setValue-int-}
```
public void setValue(int value)
```

valor actual del valor de progreso

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
