---
title: "UnifiedSaveOptions.ProgressEventHandlerInfo"
linktitle: "UnifiedSaveOptions.ProgressEventHandlerInfo"
second_title: "Справочник API Aspose.PDF для Java"
description: "Этот класс представляет информацию о прогрессе конвертации, которую можно использовать во внешнем приложении для отображения прогресса конвертации конечному пользователю"
type: docs
weight: 5440
url: /ru/java/com.aspose.pdf/unifiedsaveoptions.progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo

```
public static class UnifiedSaveOptions.ProgressEventHandlerInfo extends Object
```

Этот класс представляет информацию о прогрессе конвертации, которую можно использовать во внешнем приложении для отображения прогресса конвертации конечному пользователю

## Методы

| Метод | Описание |
| --- | --- |
| [getDocumentId](#getDocumentId--) | Уникальный идентификатор документа. |
| [getEventType](#getEventType--) | Тип события прогресса, которое произошло |
| [getMaxValue](#getMaxValue--) | максимальное возможное значение прогресса |
| [getValue](#getValue--) | текущее значение прогресса |
| [setDocumentId](#setDocumentId-com.aspose.ms.System.Guid-) | Уникальный идентификатор документа. |
| [setEventType](#setEventType-int-) | Тип события прогресса, которое произошло |
| [setMaxValue](#setMaxValue-int-) | максимальное возможное значение прогресса |
| [setValue](#setValue-int-) | текущее значение прогресса |

### getDocumentId {#getDocumentId--}
```
public com.aspose.ms.System.Guid getDocumentId()
```

Уникальный идентификатор документа.

**Returns:**
Экземпляр Guid

### getEventType {#getEventType--}
```
public int getEventType()
```

Тип события прогресса, которое произошло

**Returns:**
Элемент ProgressEventType @see ProgressEventType

### getMaxValue {#getMaxValue--}
```
public int getMaxValue()
```

максимальное возможное значение прогресса

**Returns:**
int значение

### getValue {#getValue--}
```
public int getValue()
```

текущее значение прогресса

**Returns:**
int значение

### setDocumentId {#setDocumentId-com.aspose.ms.System.Guid-}
Уникальный идентификатор документа.

### setEventType {#setEventType-int-}
```
public void setEventType(int eventType)
```

Тип события прогресса, которое произошло

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType |  | Элемент ProgressEventType @see ProgressEventType |

### setMaxValue {#setMaxValue-int-}
```
public void setMaxValue(int maxValue)
```

максимальное возможное значение прогресса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxValue |  | int значение |

### setValue {#setValue-int-}
```
public void setValue(int value)
```

текущее значение прогресса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | int значение |
