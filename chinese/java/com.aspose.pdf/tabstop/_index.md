---
title: "TabStop"
linktitle: "TabStop"
second_title: "Aspose.PDF for Java API 参考"
description: "表示段落中自定义的制表位位置。"
type: docs
weight: 4840
url: /zh/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

表示段落中自定义的制表位位置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TabStop](#TabStop--) | 初始化 {@code TabStop} 类的新实例。 |
| [TabStop](#TabStop-float-) | 使用指定位置初始化 {@code TabStop} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | 获取或设置指示制表符对齐类型的 {@code AlignmentType} 枚举。 |
| [getLeaderType](#getLeaderType--) | 获取或设置指示制表符前导类型的 {@code TabLeaderType} 枚举。 |
| [getPosition](#getPosition--) | 获取或设置指示制表位位置的 float 值。 |
| [isReadOnly](#isReadOnly--) | 获取指示此 {@code TabStop} 实例已附加到 {@code TextFragment} 并变为只读的值 |
| [setAlignmentType](#setAlignmentType-int-) | 获取或设置指示制表符对齐类型的 {@code AlignmentType} 枚举。 |
| [setLeaderType](#setLeaderType-int-) | 获取或设置指示制表符前导类型的 {@code TabLeaderType} 枚举。 |
| [setPosition](#setPosition-float-) | 设置指示制表位位置的 float 值。 |

### TabStop {#TabStop--}
```
public TabStop()
```

初始化 {@code TabStop} 类的新实例。

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

使用指定位置初始化 {@code TabStop} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 |  | 制表位的位置。 |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

获取或设置指示制表符对齐类型的 {@code AlignmentType} 枚举。

**Returns:**
TabAlignmentType 元素 @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

获取或设置指示制表符前导类型的 {@code TabLeaderType} 枚举。

**Returns:**
TabLeaderType 元素 @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

获取或设置指示制表位位置的 float 值。

**Returns:**
float 值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取指示此 {@code TabStop} 实例已附加到 {@code TextFragment} 并变为只读的值

**Returns:**
布尔值

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

获取或设置指示制表符对齐类型的 {@code AlignmentType} 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | TabAlignmentType 元素 @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

获取或设置指示制表符前导类型的 {@code TabLeaderType} 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | TabLeaderType 元素 @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

设置指示制表位位置的 float 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |
