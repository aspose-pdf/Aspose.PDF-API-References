---
title: "UnifiedSaveOptions.ProgressEventHandlerInfo"
linktitle: "UnifiedSaveOptions.ProgressEventHandlerInfo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe representa informações sobre o progresso da conversão que podem ser usadas em uma aplicação externa para mostrar o progresso da conversão ao usuário final."
type: docs
weight: 5440
url: /pt/java/com.aspose.pdf/unifiedsaveoptions.progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo

```
public static class UnifiedSaveOptions.ProgressEventHandlerInfo extends Object
```

Esta classe representa informações sobre o progresso da conversão que podem ser usadas em uma aplicação externa para mostrar o progresso da conversão ao usuário final.

## Métodos

| Método | Descrição |
| --- | --- |
| [getDocumentId](#getDocumentId--) | O ID único do documento. |
| [getEventType](#getEventType--) | Tipo de evento de progresso que ocorreu |
| [getMaxValue](#getMaxValue--) | valor máximo possível do progresso |
| [getValue](#getValue--) | valor atual do progresso |
| [setDocumentId](#setDocumentId-com.aspose.ms.System.Guid-) | O ID único do documento. |
| [setEventType](#setEventType-int-) | Tipo de evento de progresso que ocorreu |
| [setMaxValue](#setMaxValue-int-) | valor máximo possível do progresso |
| [setValue](#setValue-int-) | valor atual do progresso |

### getDocumentId {#getDocumentId--}
```
public com.aspose.ms.System.Guid getDocumentId()
```

O ID único do documento.

**Returns:**
Instância Guid

### getEventType {#getEventType--}
```
public int getEventType()
```

Tipo de evento de progresso que ocorreu

**Returns:**
Elemento ProgressEventType @see ProgressEventType

### getMaxValue {#getMaxValue--}
```
public int getMaxValue()
```

valor máximo possível do progresso

**Returns:**
valor int

### getValue {#getValue--}
```
public int getValue()
```

valor atual do progresso

**Returns:**
valor int

### setDocumentId {#setDocumentId-com.aspose.ms.System.Guid-}
O ID único do documento.

### setEventType {#setEventType-int-}
```
public void setEventType(int eventType)
```

Tipo de evento de progresso que ocorreu

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| eventType |  | Elemento ProgressEventType @see ProgressEventType |

### setMaxValue {#setMaxValue-int-}
```
public void setMaxValue(int maxValue)
```

valor máximo possível do progresso

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| maxValue |  | valor int |

### setValue {#setValue-int-}
```
public void setValue(int value)
```

valor atual do progresso

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
