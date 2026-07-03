---
title: UnifiedSaveOptions.ProgressEventHandlerInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents information about conversion progress that can be used in external application to show conversion progress to end user
type: docs
weight: 5440
url: /java/com.aspose.pdf/unifiedsaveoptions.progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo

```
public static class UnifiedSaveOptions.ProgressEventHandlerInfo extends Object
```

This class represents information about conversion progress that can be used in external application to show conversion progress to end user

## Methods

| Method | Description |
| --- | --- |
| [getDocumentId](#getDocumentId--) | The unique document ID. |
| [getEventType](#getEventType--) | Type of progress event that occured |
| [getMaxValue](#getMaxValue--) | maximum possible value of progress value |
| [getValue](#getValue--) | current value of progress value |
| [setDocumentId](#setDocumentId-com.aspose.ms.System.Guid-) | The unique document ID. |
| [setEventType](#setEventType-int-) | Type of progress event that occured |
| [setMaxValue](#setMaxValue-int-) | maximum possible value of progress value |
| [setValue](#setValue-int-) | current value of progress value |

### getDocumentId {#getDocumentId--}
```
public com.aspose.ms.System.Guid getDocumentId()
```

The unique document ID.

**Returns:**
Guid instance

### getEventType {#getEventType--}
```
public int getEventType()
```

Type of progress event that occured

**Returns:**
ProgressEventType element @see ProgressEventType

### getMaxValue {#getMaxValue--}
```
public int getMaxValue()
```

maximum possible value of progress value

**Returns:**
int value

### getValue {#getValue--}
```
public int getValue()
```

current value of progress value

**Returns:**
int value

### setDocumentId {#setDocumentId-com.aspose.ms.System.Guid-}
The unique document ID.

### setEventType {#setEventType-int-}
```
public void setEventType(int eventType)
```

Type of progress event that occured

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventType |  | ProgressEventType element @see ProgressEventType |

### setMaxValue {#setMaxValue-int-}
```
public void setMaxValue(int maxValue)
```

maximum possible value of progress value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxValue |  | int value |

### setValue {#setValue-int-}
```
public void setValue(int value)
```

current value of progress value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
