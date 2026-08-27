---
title: "Copier"
linktitle: "Copier"
second_title: "Aspose.PDF for Java API 参考"
description: "用于复制对象的类。"
type: docs
weight: 850
url: /zh/java/com.aspose.pdf/copier/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Copier

```
public class Copier extends Object
```

用于复制对象的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Copier](#Copier-com.aspose.pdf.engine.data.ITrailerable-) | 创建 Copier 类的实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) | 复制 IPdfPrimitive |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | 创建对象的副本，包括所有依赖对象。 |
| [getAllowReusePageContent](#getAllowReusePageContent--) | get Allow Reuse Page Content |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | get Ignore Corrupted Objects |
| [getRestrictedKeys](#getRestrictedKeys--) | get Restricted Keys |
| [getReuseStreams](#getReuseStreams--) | get Reuse Streams |
| [getUseStubs](#getUseStubs--) | 指示在复制过程中是否应使用存根。如果该选项开启，则流将被复制；否则将使用指向源流的链接。这将不允许关闭复制的文档，但可节省复制过程和内存的消耗。 |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | set Allow Reuse Page Content |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Set Ignore Corrupted Objects |
| [setRestrictedKeys](#setRestrictedKeys-java.lang.String:A-) | set Restricted Keys |
| [setReuseStreams](#setReuseStreams-boolean-) | set Reuse Streams |
| [setUseStubs](#setUseStubs-boolean-) | 指示在复制过程中是否应使用存根。如果该选项开启，则流将被复制；否则将使用指向源流的链接。这将不允许关闭复制的文档，但可节省复制过程和内存的消耗。 |

### Copier {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
创建 Copier 类的实例。

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
复制 IPdfPrimitive

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
创建对象的副本，包括所有依赖对象。

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

get Allow Reuse Page Content

**Returns:**
布尔值

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

get Ignore Corrupted Objects

**Returns:**
布尔值

### getRestrictedKeys {#getRestrictedKeys--}
```
public String [] getRestrictedKeys()
```

get Restricted Keys

**Returns:**
String[] array

### getReuseStreams {#getReuseStreams--}
```
public boolean getReuseStreams()
```

get Reuse Streams

**Returns:**
布尔值

### getUseStubs {#getUseStubs--}
```
public boolean getUseStubs()
```

指示在复制过程中是否应使用存根。如果该选项开启，则流将被复制；否则将使用指向源流的链接。这将不允许关闭复制的文档，但可节省复制过程和内存的消耗。

**Returns:**
布尔值

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

set Allow Reuse Page Content

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Set Ignore Corrupted Objects

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRestrictedKeys {#setRestrictedKeys-java.lang.String:A-}
set Restricted Keys

### setReuseStreams {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```

set Reuse Streams

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseStubs {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```

指示在复制过程中是否应使用存根。如果该选项开启，则流将被复制；否则将使用指向源流的链接。这将不允许关闭复制的文档，但可节省复制过程和内存的消耗。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
