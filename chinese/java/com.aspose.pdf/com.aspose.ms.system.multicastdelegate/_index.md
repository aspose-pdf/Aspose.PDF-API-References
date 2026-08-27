---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Aspose.PDF for Java API 参考"
description: "表示事件的类"
type: docs
weight: 740
url: /zh/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

表示事件的类

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-T-) | 添加一个委托。 |
| [assign](#assign-T-) | 仅添加当前委托，清除其他。 |
| [clear](#clear--) | 清除委托列表 |
| [isEmpty](#isEmpty--) | 如果处理程序列表为空，则返回 true |
| [remove](#remove-T-) | 从列表中删除委托 |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

添加一个委托。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 委托 |  | 处理程序对象 |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

仅添加当前委托，清除其他。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 委托 |  | 处理程序对象 |

### clear {#clear--}
```
public final void clear()
```

清除委托列表

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

如果处理程序列表为空，则返回 true

**Returns:**
布尔值

### remove {#remove-T-}
```
public final void remove( T delegate)
```

从列表中删除委托

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 委托 |  | 处理程序对象 |
