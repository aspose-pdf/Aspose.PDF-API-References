---
title: "TabStops"
linktitle: "TabStops"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 {@code TabStop} 对象的集合。"
type: docs
weight: 4850
url: /zh/java/com.aspose.pdf/tabstops/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStops

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TabStops extends Object implements com.aspose.ms.System.ICloneable
```

表示 {@code TabStop} 对象的集合。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TabStops](#TabStops--) | 初始化 {@code TabStops} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add--) | 初始化 {@code TabStop} 类的新实例并将其添加到 TabStops 集合中。 |
| [add](#add-float-) | 使用指定位置初始化 {@code TabStop} 类的新实例，并将其添加到 TabStops 集合中。 |
| [add](#add-float-int-) | 使用指定位置和前导字符类型初始化 {@code TabStop} 类的新实例，并将其添加到 TabStops 集合中。 |
| [add](#add-com.aspose.pdf.TabStop-) | 初始化 {@code TabStop} 类的新实例并将其添加到 TabStops 集合中。 |
| [deepClone](#deepClone--) | 克隆一个新的 {@code TabStops} 对象。 |
| [get_Item](#get_Item-int-) | 根据 TabStop 索引从集合中获取 {@code TabStop} 对象。 |
| [getCount](#getCount--) | 返回 tabStops 数量。 |
| [isReadOnly](#isReadOnly--) | 获取值，指示此 {@code TabStops} 实例已附加到 {@code TextFragment} 并变为只读。 |
| [set_Item](#set_Item-int-com.aspose.pdf.TabStop-) | 根据 TabStop 索引从集合中设置 {@code TabStop} 对象。 |

### TabStops {#TabStops--}
```
public TabStops()
```

初始化 {@code TabStops} 类的新实例。

### add {#add--}
```
public TabStop add()
```

初始化 {@code TabStop} 类的新实例并将其添加到 TabStops 集合中。

**Returns:**
新的 {@code TabStop} 对象。

### add {#add-float-}
```
public TabStop add(float position)
```

使用指定位置初始化 {@code TabStop} 类的新实例，并将其添加到 TabStops 集合中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 |  | 制表位的位置。 |

**Returns:**
新的 {@code TabStop} 对象。

### add {#add-float-int-}
```
public TabStop add(float position, int leaderType)
```

使用指定位置和前导字符类型初始化 {@code TabStop} 类的新实例，并将其添加到 TabStops 集合中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 |  | 制表位的位置。 |
| leaderType |  | 制表位的前导类型。 |

**Returns:**
新的 {@code TabStop} 对象。

### add {#add-com.aspose.pdf.TabStop-}
初始化 {@code TabStop} 类的新实例并将其添加到 TabStops 集合中。

**Returns:**
新的 {@code TabStop} 对象。

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆一个新的 {@code TabStops} 对象。

**Returns:**
新的 {@code TabStops} 对象。

### get_Item {#get_Item-int-}
```
public TabStop get_Item(int index)
```

根据 TabStop 索引从集合中获取 {@code TabStop} 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 在 {@code TabStops} 集合中的元素的零基索引。 |

**Returns:**
{@code TabStop} 对象。

### getCount {#getCount--}
```
public int getCount()
```

返回 tabStops 数量。

**Returns:**
int 值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取值，指示此 {@code TabStops} 实例已附加到 {@code TextFragment} 并变为只读。

**Returns:**
布尔值

### set_Item {#set_Item-int-com.aspose.pdf.TabStop-}
根据 TabStop 索引从集合中设置 {@code TabStop} 对象。
