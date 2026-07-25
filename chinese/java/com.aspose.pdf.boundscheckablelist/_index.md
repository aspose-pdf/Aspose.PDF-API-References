---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 BoundsCheckableList —— 对 System.Collections.Generic.List 的包装。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

表示 BoundsCheckableList —— 对 System.Collections.Generic.List 的包装。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | 初始化 BoundsCheckableList 类的新实例。 |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | 初始化 BoundsCheckableList 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addItem](#addItem-T-) | 根据 "boundsCheckMode" 参数，将对象添加到 System.Collections.Generic.List 的末尾。 |
| [clear](#clear--) | 从 System.Collections.Generic.List 中移除所有元素。 |
| [containsItem](#containsItem-T-) | 确定元素是否在 System.Collections.Generic.List 中。 |
| [copyToTArray](#copyToTArray-T:A-int-) | 将整个 System.Collections.Generic.List 复制到兼容的一维数组中，从目标数组的指定索引开始。 |
| [get_Item](#get_Item-int-) | 获取或设置集合中的段落。 |
| [indexOfItem](#indexOfItem-T-) | 搜索指定对象，并返回整个 System.Collections.Generic.List 中首次出现的零基索引。 |
| [insertItem](#insertItem-int-T-) | 在指定索引处向 System.Collections.Generic.List 插入元素。 |
| [isReadOnly](#isReadOnly--) | 获取指示集合是否为只读的值。 |
| [iterator](#iterator--) | 返回遍历 System.Collections.Generic.List 的枚举器。 |
| [removeAt](#removeAt-int-) | 删除 System.Collections.Generic.List 中指定索引处的元素。 |
| [removeItem](#removeItem-T-) | 从 System.Collections.Generic.List 中移除特定对象的第一次出现。 |
| [set_Item](#set_Item-int-T-) | 获取或设置集合中的段落。 |
| [size](#size--) | 获取 System.Collections.Generic.List 中包含的元素数量。 |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | 更新已初始化集合的 boundsCheckMode 参数。 |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | 更新已初始化集合的 boundsCheckMode 参数。 |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

初始化 BoundsCheckableList 类的新实例。

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

初始化 BoundsCheckableList 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| boundsCheckMode |  | 该 bounds cCheck 模式。 |
| containerWidth |  | 容器宽度。 |
| containerHeight |  | 容器高度。 |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

根据 "boundsCheckMode" 参数，将对象添加到 System.Collections.Generic.List 的末尾。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item |  | 要添加到 System.Collections.Generic.List 末尾的对象。对于引用类型，该值可以为 "null"。 |

### clear {#clear--}
```
public final void clear()
```

从 System.Collections.Generic.List 中移除所有元素。

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

确定元素是否在 System.Collections.Generic.List 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item |  | 在 System.Collections.Generic.List 中要定位的对象。对于引用类型，该值可以为 null。 |

**Returns:**
如果在 System.Collections.Generic.List 中找到 itemitem，则为 true；否则为 false。

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

将整个 System.Collections.Generic.List 复制到兼容的一维数组中，从目标数组的指定索引开始。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array |  | 从 System.Collections.Generic.List 复制的元素的目标是一维 System.Array。该 System.Array 必须使用零基索引。 |
| arrayIndex |  | 数组中复制开始的零基索引。 |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

获取或设置集合中的段落。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 段落索引。 |

**Returns:**
指定索引处的元素。

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

搜索指定对象，并返回整个 System.Collections.Generic.List 中首次出现的零基索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item |  | 在 System.Collections.Generic.List 中要定位的对象。对于引用类型，该值可以为 null。 |

**Returns:**
在整个 System.Collections.Generic.List 中首次出现 itemitem 的零基索引，如果找到；否则为 –1。

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

在指定索引处向 System.Collections.Generic.List 插入元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 应插入 item 的零基索引。 |
| item |  | 要插入的对象。对于引用类型，该值可以为 null。 |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取指示集合是否为只读的值。

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

返回遍历 System.Collections.Generic.List 的枚举器。

**Returns:**
System.Collections.Generic.List 的枚举器。

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

删除 System.Collections.Generic.List 中指定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 要移除的元素的零基索引。 |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

从 System.Collections.Generic.List 中移除特定对象的第一次出现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item |  | 要从 System.Collections.Generic.List 中移除的对象。对于引用类型，该值可以为 null。 |

**Returns:**
如果成功移除 itemitem 则返回 true；否则返回 false。如果在 System.Collections.Generic.List 中未找到 itemitem，此方法也返回 false。

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

获取或设置集合中的段落。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 段落索引。 |

### size {#size--}
```
public final int size()
```

获取 System.Collections.Generic.List 中包含的元素数量。

**Returns:**
System.Collections.Generic.List 中包含的元素数量。

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

更新已初始化集合的 boundsCheckMode 参数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| boundsCheckMode |  | 边界检查模式。 |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

更新已初始化集合的 boundsCheckMode 参数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| boundsCheckMode |  | 边界检查模式。 |
| containerWidth |  | 容器宽度。 |
| containerHeight |  | 容器高度。 |
