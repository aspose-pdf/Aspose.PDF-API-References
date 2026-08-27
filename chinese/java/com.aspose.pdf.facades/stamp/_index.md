---
title: "印章"
linktitle: "印章"
second_title: "Aspose.PDF for Java API 参考"
description: "表示印章的类。"
type: docs
weight: 700
url: /zh/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

表示印章的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Stamp](#Stamp--) | Stamp 对象的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | 设置将用作印章的图像。 |
| [bindImage](#bindImage-java.lang.String-) | <p> 将图像设置为印章。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | 将文本设置为印章。 |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> 设置将用作印章的 PDF 文件和页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> 设置将用作印章的 PDF 文件和页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | 设置印章文本的文本状态。 |
| [close](#close--) | 关闭此实例 |
| [getBlendingSpace](#getBlendingSpace--) | 获取一个 BlendingColorSpace 值，该值定义用于在页面上执行透明度和混合操作的颜色空间。 |
| [getOpacity](#getOpacity--) | 获取印章的不透明度。 |
| [getPageNumber](#getPageNumber--) | 获取页码。 |
| [getPages](#getPages--) | 获取受印章影响的页面编号数组。 |
| [getQuality](#getQuality--) | 获取图像印章的质量（百分比）。有效值 0..100%。 |
| [getRotation](#getRotation--) | 获取印章的旋转角度（度）。 |
| [getStampId](#getStampId--) | 获取印章的标识符。 |
| [isBackground](#isBackground--) | 获取背景状态。如果为 true，印章将作为页面的背景放置。默认设置为 false。 |
| [setBackground](#setBackground-boolean-) | 设置背景状态。如果为 true，印章将作为页面的背景放置。默认设置为 false。 |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | 设置一个 BlendingColorSpace 值，该值定义用于在页面上执行透明度和混合操作的颜色空间。 |
| [setImageSize](#setImageSize-float-float-) | 设置图像印章的大小。图像将根据指定的值进行缩放。 |
| [setOpacity](#setOpacity-float-) | 设置印章的不透明度。 |
| [setOrigin](#setOrigin-float-float-) | 设置印章将在页面上的放置位置。 |
| [setPageNumber](#setPageNumber-int-) | 设置页码。 |
| [setPages](#setPages-int:A-) | <p> 设置受印章影响的页面编号数组。如果 Pages = null，则文档的所有页面都会受到影响。 </p> |
| [setQuality](#setQuality-int-) | 设置图像印章的质量（百分比）。有效值 0..100%。 |
| [setRotation](#setRotation-float-) | <p> 获取或设置印章的旋转角度（以度为单位）。 </p> |
| [setStampId](#setStampId-int-) | 设置印章的标识符。 |

### Stamp {#Stamp--}
```
public Stamp()
```

Stamp 对象的构造函数。

### bindImage {#bindImage-java.io.InputStream-}
设置将用作印章的图像。

### bindImage {#bindImage-java.lang.String-}
<p> 将图像设置为印章。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
将文本设置为印章。

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> 设置将用作印章的 PDF 文件和页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> 设置将用作印章的 PDF 文件和页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
设置印章文本的文本状态。

### close {#close--}
```
public void close()
```

关闭此实例

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

获取一个 BlendingColorSpace 值，该值定义用于在页面上执行透明度和混合操作的颜色空间。

**Returns:**
int 值 @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

获取印章的不透明度。

**Returns:**
float 值

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

获取页码。

**Returns:**
int 值

### getPages {#getPages--}
```
public int[] getPages()
```

获取受印章影响的页面编号数组。

**Returns:**
int 数组

### getQuality {#getQuality--}
```
public int getQuality()
```

获取图像印章的质量（百分比）。有效值 0..100%。

**Returns:**
int 值

### getRotation {#getRotation--}
```
public float getRotation()
```

获取印章的旋转角度（度）。

**Returns:**
float 值

### getStampId {#getStampId--}
```
public int getStampId()
```

获取印章的标识符。

**Returns:**
int 值

### isBackground {#isBackground--}
```
public boolean isBackground()
```

获取背景状态。如果为 true，印章将作为页面的背景放置。默认设置为 false。

**Returns:**
布尔值

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

设置背景状态。如果为 true，印章将作为页面的背景放置。默认设置为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
设置一个 BlendingColorSpace 值，该值定义用于在页面上执行透明度和混合操作的颜色空间。

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

设置图像印章的大小。图像将根据指定的值进行缩放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 图像宽度。 |
| 高度 |  | 图像高度。 |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

设置印章的不透明度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

设置印章将在页面上的放置位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| originX |  | 印章的 X 坐标。 |
| originY |  | 印章的 Y 坐标。 |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

设置页码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> 设置受印章影响的页面编号数组。如果 Pages = null，则文档的所有页面都会受到影响。 </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 数组 <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //put stamp only on 1st, 4th and 6th page. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

设置图像印章的质量（百分比）。有效值 0..100%。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> 获取或设置印章的旋转角度（以度为单位）。 </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

设置印章的标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
