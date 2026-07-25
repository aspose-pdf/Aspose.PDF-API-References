---
title: "Group"
linktitle: "Group"
second_title: "Aspose.PDF for Java API 参考"
description: "一个组属性类，指定页面组的属性，以在透明成像模型中使用。"
type: docs
weight: 1850
url: /zh/java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Group

```
public final class Group extends Object
```

一个组属性类，指定页面组的属性，以在透明成像模型中使用。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Group](#Group-com.aspose.pdf.Page-) | 构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorSpace](#getColorSpace--) | 获取 ColorSpace <p> |
| [isKnockout](#isKnockout--) | 仅供内部使用 如果此标志为 false，则组内后面的对象与它们重叠的前面对象进行合成；如果为 true，则与组的初始背景进行合成，并覆盖（"knock out"）任何先前重叠的对象。 |
| [isTransparency](#isTransparency--) | 仅供内部使用，返回组透明度标志。 |
| [setColorSpace](#setColorSpace-com.aspose.pdf.ColorSpace-) | 组颜色空间。 |
| [setKnockout](#setKnockout-com.aspose.pdf.ExtendedBoolean-) | 如果此标志为 false，则组内后面的对象与它们重叠的前面对象进行合成；如果为 true，则与组的初始背景进行合成，并覆盖（"knock out"）任何先前重叠的对象。 |

### Group {#Group-com.aspose.pdf.Page-}
构造函数。

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

获取 ColorSpace <p>

**Returns:**
ColorSpace 值。@see ColorSpace

### isKnockout {#isKnockout--}
```
public ExtendedBoolean isKnockout()
```

仅供内部使用 如果此标志为 false，则组内后面的对象与它们重叠的前面对象进行合成；如果为 true，则与组的初始背景进行合成，并覆盖（"knock out"）任何先前重叠的对象。

**Returns:**
ExtendedBoolean 元素 @see ExtendedBoolean

### isTransparency {#isTransparency--}
```
public boolean isTransparency()
```

仅供内部使用，返回组透明度标志。

**Returns:**
布尔值

### setColorSpace {#setColorSpace-com.aspose.pdf.ColorSpace-}
组颜色空间。

### setKnockout {#setKnockout-com.aspose.pdf.ExtendedBoolean-}
如果此标志为 false，则组内后面的对象与它们重叠的前面对象进行合成；如果为 true，则与组的初始背景进行合成，并覆盖（"knock out"）任何先前重叠的对象。
