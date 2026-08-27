---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "Aspose.PDF for Java API 参考"
description: "指定打印页面边距的尺寸。"
type: docs
weight: 70
url: /zh/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

指定打印页面边距的尺寸。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | 使用 1 英寸宽的边距初始化 Margins 类的新实例。 |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | 使用指定的左、右、上、下边距初始化 Margins 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 逐成员检索此对象的副本。 |
| [equals](#equals-java.lang.Object-) | 将此 Margins 与指定的对象进行比较，以确定它们是否具有相同的尺寸。（覆盖 Object.Equals(Object)。） |
| [getBottom](#getBottom--) | 获取或设置底部边距，单位为百分之一英寸。 |
| [getLeft](#getLeft--) | 获取或设置左侧边距宽度，单位为百分之一英寸。 |
| [getRight](#getRight--) | 获取或设置右侧边距宽度，单位为百分之一英寸。 |
| [getTop](#getTop--) | 获取或设置顶部边距宽度，单位为百分之一英寸。 |
| [hashCode](#hashCode--) | 返回对象的哈希码值。此方法支持哈希表，例如 {@link java.util.HashMap} 提供的哈希表。 <p> {@code hashCode} 的一般约定是： <ul> <li>只要在 Java 应用程序的执行期间对同一对象多次调用且未修改用于 {@code equals} 比较的信息，{@code hashCode} 方法必须始终返回相同的整数。该整数在一次应用执行与另一执行之间不必保持一致。 <li>如果两个对象根据 {@code equals(Object)} 方法相等，则对这两个对象调用 {@code hashCode} 方法必须产生相同的整数结果。 <li>并<em>不</em>要求如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则对这两个对象调用 {@code hashCode} 方法必须产生不同的整数结果。不过，程序员应注意，为不相等的对象产生不同的整数可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，类 {@code Object} 定义的 hashCode 方法确实会为不同对象返回不同的整数。（通常通过将对象的内部地址转换为整数来实现，但此实现技术并非 Java<span style="font-size:70%"><sup>TM</sup></span> 编程语言所要求。） |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | 比较两个 Margins，以确定它们是否具有相同的尺寸。 |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | 比较两个 Margins，以确定它们的宽度是否不相等。 |
| [setBottom](#setBottom-int-) | 获取或设置底部边距，单位为百分之一英寸。 |
| [setLeft](#setLeft-int-) | 获取或设置左侧边距宽度，单位为百分之一英寸。 |
| [setRight](#setRight-int-) | 获取或设置右侧边距宽度，单位为百分之一英寸。 |
| [setTop](#setTop-int-) | 获取或设置顶部边距宽度，单位为百分之一英寸。 |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

使用 1 英寸宽的边距初始化 Margins 类的新实例。

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

使用指定的左、右、上、下边距初始化 Margins 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left |  | int 值 |
| 右 |  | int 值 |
| 顶部 |  | int 值 |
| bottom |  | int 值 |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

逐成员检索此对象的副本。

**Returns:**
PrinterMargins 对象

### equals {#equals-java.lang.Object-}
将此 Margins 与指定的对象进行比较，以确定它们是否具有相同的尺寸。（覆盖 Object.Equals(Object)。）

### getBottom {#getBottom--}
```
public int getBottom()
```

获取或设置底部边距，单位为百分之一英寸。

**Returns:**
int 值

### getLeft {#getLeft--}
```
public int getLeft()
```

获取或设置左侧边距宽度，单位为百分之一英寸。

**Returns:**
int 值

### getRight {#getRight--}
```
public int getRight()
```

获取或设置右侧边距宽度，单位为百分之一英寸。

**Returns:**
int 值

### getTop {#getTop--}
```
public int getTop()
```

获取或设置顶部边距宽度，单位为百分之一英寸。

**Returns:**
int 值

### hashCode {#hashCode--}
```
public int hashCode()
```

返回对象的哈希码值。此方法支持哈希表，例如 {@link java.util.HashMap} 提供的哈希表。 <p> {@code hashCode} 的一般约定是： <ul> <li>只要在 Java 应用程序的执行期间对同一对象多次调用且未修改用于 {@code equals} 比较的信息，{@code hashCode} 方法必须始终返回相同的整数。该整数在一次应用执行与另一执行之间不必保持一致。 <li>如果两个对象根据 {@code equals(Object)} 方法相等，则对这两个对象调用 {@code hashCode} 方法必须产生相同的整数结果。 <li>并<em>不</em>要求如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则对这两个对象调用 {@code hashCode} 方法必须产生不同的整数结果。不过，程序员应注意，为不相等的对象产生不同的整数可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，类 {@code Object} 定义的 hashCode 方法确实会为不同对象返回不同的整数。（通常通过将对象的内部地址转换为整数来实现，但此实现技术并非 Java<span style="font-size:70%"><sup>TM</sup></span> 编程语言所要求。）

**Returns:**
此对象的哈希码值。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
比较两个 Margins，以确定它们是否具有相同的尺寸。

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
比较两个 Margins，以确定它们的宽度是否不相等。

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

获取或设置底部边距，单位为百分之一英寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

获取或设置左侧边距宽度，单位为百分之一英寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

获取或设置右侧边距宽度，单位为百分之一英寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

获取或设置顶部边距宽度，单位为百分之一英寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
