---
title: "SoundData"
linktitle: "SoundData"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل بيانات صوتية تحدد الصوت الذي سيُشغل عند تفعيل التعليق."
type: docs
weight: 4540
url: /ar/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

يمثل بيانات صوتية تحدد الصوت الذي سيُشغل عند تفعيل التعليق.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBits](#getBits--) | يحصل على عدد البتات لكل عينة لكل قناة. |
| [getChannels](#getChannels--) | يحصل على عدد قنوات الصوت. |
| [getContents](#getContents--) | يحصل على تدفق الصوت الذي سيُشغل عندما يتم تنشيط التعليق. |
| [getContentsInternal](#getContentsInternal--) | يحصل على تدفق الصوت الذي سيُشغل عندما يتم تنشيط التعليق. |
| [getEncoding](#getEncoding--) | يحصل على تنسيق الترميز لبيانات العينة. |
| [getRate](#getRate--) | يحصل على معدل العينة، بالعينات في الثانية. |
| [setBits](#setBits-int-) | يضبط عدد البتات لكل عينة لكل قناة. |
| [setChannels](#setChannels-int-) | يضبط عدد قنوات الصوت. |
| [setEncoding](#setEncoding-int-) | يضبط تنسيق الترميز لبيانات العينة. |
| [setRate](#setRate-int-) | يضبط معدل العينة، بالعينات في الثانية. |

### getBits {#getBits--}
```
public int getBits()
```

يحصل على عدد البتات لكل عينة لكل قناة.

**Returns:**
قيمة int عدد البتات

### getChannels {#getChannels--}
```
public int getChannels()
```

يحصل على عدد قنوات الصوت.

**Returns:**
عدد قنوات الصوت.

### getContents {#getContents--}
```
public InputStream getContents()
```

يحصل على تدفق الصوت الذي سيُشغل عندما يتم تنشيط التعليق.

**Returns:**
قيمة InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

يحصل على تدفق الصوت الذي سيُشغل عندما يتم تنشيط التعليق.

**Returns:**
قيمة Stream

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

يحصل على تنسيق الترميز لبيانات العينة.

**Returns:**
قيمة SoundEncoding @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

يحصل على معدل العينة، بالعينات في الثانية.

**Returns:**
قيمة int

### setBits {#setBits-int-}
```
public void setBits(int value)
```

يضبط عدد البتات لكل عينة لكل قناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عدد البتات |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

يضبط عدد قنوات الصوت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عدد قنوات الصوت. |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

يضبط تنسيق الترميز لبيانات العينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة SoundEncoding @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

يضبط معدل العينة، بالعينات في الثانية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
