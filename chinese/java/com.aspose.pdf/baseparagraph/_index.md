---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Aspose.PDF for Java API 参考"
description: "表示可以添加到页面的抽象基对象（doc.Paragraphs.Add()）。"
type: docs
weight: 280
url: /zh/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

表示可以添加到页面的抽象基对象（doc.Paragraphs.Add()）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆此实例。虚方法。始终返回 null。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 获取段落的水平对齐方式 |
| [getHyperlink](#getHyperlink--) | / * / * 获取或设置段落是否为脚注。默认值为 false。（用于 pdf 生成） / * / * |
| [getMargin](#getMargin--) | 获取段落的外边距（用于 pdf 生成） |
| [getVerticalAlignment](#getVerticalAlignment--) | 获取段落的垂直对齐方式 |
| [getZIndex](#getZIndex--) | 获取一个整数值，指示图形的 Z 顺序。ZIndex 较大的图形将覆盖 ZIndex 较小的图形。ZIndex 可以为负数。ZIndex 为负的图形将位于页面文本之后。 |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | 获取或设置一个布尔值，指示此段落是否位于下一列。默认值为 false。（用于 pdf 生成） |
| [isInLineParagraph](#isInLineParagraph--) | 获取段落是否为内联。默认值为 false。（用于 pdf 生成） |
| [isInNewPage](#isInNewPage--) | 获取一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 pdf 生成） |
| [isKeptWithNext](#isKeptWithNext--) | 获取一个布尔值，指示当前段落是否与下一段落保持在同一页。默认值为 false。（用于 pdf 生成） |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | 获取或设置一个布尔值，指示此段落是否位于下一列。默认值为 false。（用于 pdf 生成） |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 设置段落的水平对齐方式 |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置超链接（用于 pdf 生成器）。 |
| [setInLineParagraph](#setInLineParagraph-boolean-) | 设置段落为内联。默认值为 false。（用于 pdf 生成） |
| [setInNewPage](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 pdf 生成） |
| [setKeptWithNext](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段落保持在同一页。默认值为 false。（用于 pdf 生成） |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于 pdf 生成） |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 设置段落的垂直对齐方式 |
| [setZIndex](#setZIndex-int-) | 设置一个整数值，指示图形的 Z 顺序。ZIndex 较大的图形将覆盖 ZIndex 较小的图形。ZIndex 可以为负数。ZIndex 为负的图形将位于页面文本之后。 |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆此实例。虚方法。始终返回 null。

**Returns:**
空

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

获取段落的水平对齐方式

**Returns:**
HorizontalAlignment 值 @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * 获取或设置段落是否为脚注。默认值为 false。（用于 pdf 生成） / * / *

**Returns:**
布尔值 /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

获取段落的外边距（用于 pdf 生成）

**Returns:**
MarginInfo 值

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

获取段落的垂直对齐方式

**Returns:**
VerticalAlignment 元素 @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

获取一个整数值，指示图形的 Z 顺序。ZIndex 较大的图形将覆盖 ZIndex 较小的图形。ZIndex 可以为负数。ZIndex 为负的图形将位于页面文本之后。

**Returns:**
int 值

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

获取或设置一个布尔值，指示此段落是否位于下一列。默认值为 false。（用于 pdf 生成）

**Returns:**
布尔值

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

获取段落是否为内联。默认值为 false。（用于 pdf 生成）

**Returns:**
布尔值

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

获取一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 pdf 生成）

**Returns:**
布尔值

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

获取一个布尔值，指示当前段落是否与下一段落保持在同一页。默认值为 false。（用于 pdf 生成）

**Returns:**
布尔值

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

获取或设置一个布尔值，指示此段落是否位于下一列。默认值为 false。（用于 pdf 生成）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
设置段落的水平对齐方式

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
设置超链接（用于 pdf 生成器）。

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

设置段落为内联。默认值为 false。（用于 pdf 生成）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

设置一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 pdf 生成）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

设置一个布尔值，指示当前段落是否与下一段落保持在同一页。默认值为 false。（用于 pdf 生成）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
设置段落的外边距（用于 pdf 生成）

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
设置段落的垂直对齐方式

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

设置一个整数值，指示图形的 Z 顺序。ZIndex 较大的图形将覆盖 ZIndex 较小的图形。ZIndex 可以为负数。ZIndex 为负的图形将位于页面文本之后。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
