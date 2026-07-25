---
title: "UnifiedSaveOptions.ProgressEventHandlerInfo"
linktitle: "UnifiedSaveOptions.ProgressEventHandlerInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "此类表示可在外部应用程序中使用的转换进度信息，以向最终用户显示转换进度。"
type: docs
weight: 5440
url: /zh/java/com.aspose.pdf/unifiedsaveoptions.progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo

```
public static class UnifiedSaveOptions.ProgressEventHandlerInfo extends Object
```

此类表示可在外部应用程序中使用的转换进度信息，以向最终用户显示转换进度。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDocumentId](#getDocumentId--) | 唯一的文档 ID。 |
| [getEventType](#getEventType--) | 发生的进度事件类型 |
| [getMaxValue](#getMaxValue--) | 进度值的最大可能值 |
| [getValue](#getValue--) | 进度值的当前值 |
| [setDocumentId](#setDocumentId-com.aspose.ms.System.Guid-) | 唯一的文档 ID。 |
| [setEventType](#setEventType-int-) | 发生的进度事件类型 |
| [setMaxValue](#setMaxValue-int-) | 进度值的最大可能值 |
| [setValue](#setValue-int-) | 进度值的当前值 |

### getDocumentId {#getDocumentId--}
```
public com.aspose.ms.System.Guid getDocumentId()
```

唯一的文档 ID。

**Returns:**
Guid 实例

### getEventType {#getEventType--}
```
public int getEventType()
```

发生的进度事件类型

**Returns:**
ProgressEventType 元素 @see ProgressEventType

### getMaxValue {#getMaxValue--}
```
public int getMaxValue()
```

进度值的最大可能值

**Returns:**
int 值

### getValue {#getValue--}
```
public int getValue()
```

进度值的当前值

**Returns:**
int 值

### setDocumentId {#setDocumentId-com.aspose.ms.System.Guid-}
唯一的文档 ID。

### setEventType {#setEventType-int-}
```
public void setEventType(int eventType)
```

发生的进度事件类型

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| eventType |  | ProgressEventType 元素 @see ProgressEventType |

### setMaxValue {#setMaxValue-int-}
```
public void setMaxValue(int maxValue)
```

进度值的最大可能值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maxValue |  | int 值 |

### setValue {#setValue-int-}
```
public void setValue(int value)
```

进度值的当前值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
