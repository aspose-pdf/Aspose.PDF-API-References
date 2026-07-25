---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "Aspose.PDF for Java API 参考"
description: "文本渲染模式 Tmode 决定显示文本时是否会对字形轮廓进行描边、填充、用作剪裁边界，或三者的某种组合。"
type: docs
weight: 5240
url: /zh/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

文本渲染模式 Tmode 决定显示文本时是否会对字形轮廓进行描边、填充、用作剪裁边界，或三者的某种组合。

## 字段

| 字段 | 描述 |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | 将文本添加到路径以进行裁剪。 |
| [FillText](#FillText) | 填充文本。 |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | 填充文本并将其添加到路径以进行裁剪（参见 9.3.6，“Text Rendering Mode，”）。 |
| [FillThenStrokeText](#FillThenStrokeText) | 先填充后描边文本。 |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | 先填充后描边文本并将其添加到路径以进行裁剪。 |
| [Invisible](#Invisible) | 既不填充也不描边文本（不可见）。 |
| [StrokeText](#StrokeText) | 描边文本。 |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | 描边文本并将其添加到路径以进行裁剪。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

将文本添加到路径以进行裁剪。

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

填充文本。

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

填充文本并将其添加到路径以进行裁剪（参见 9.3.6，“Text Rendering Mode，”）。

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

先填充后描边文本。

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

先填充后描边文本并将其添加到路径以进行裁剪。

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

既不填充也不描边文本（不可见）。

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

描边文本。

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

描边文本并将其添加到路径以进行裁剪。

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static TextRenderingMode [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
