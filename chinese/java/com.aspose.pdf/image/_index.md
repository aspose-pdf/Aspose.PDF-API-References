---
title: "Image"
linktitle: "Image"
second_title: "Aspose.PDF for Java API 参考"
description: "表示图像。"
type: docs
weight: 2280
url: /zh/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

表示图像。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Image](#Image--) | 默认构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | 尝试将 bmp/png/gif/tiff 图像流转换为 JPG 格式图像流。 |
| [deepClone](#deepClone--) | 克隆图像。 |
| [getBitmapInfo](#getBitmapInfo--) | 获取或设置未压缩的图像字节。 |
| [getBitmapSize](#getBitmapSize--) | 获取图像位图大小。 |
| [getBufferedImage](#getBufferedImage--) | 获取 java awt 图像。 |
| [getFile](#getFile--) | 获取图像文件。 |
| [getFileType](#getFileType--) | 获取图像文件类型。 |
| [getFixHeight](#getFixHeight--) | 获取图像高度。 |
| [getFixWidth](#getFixWidth--) | 获取图像宽度。 |
| [getImageScale](#getImageScale--) | 获取图像比例。 |
| [getImageStream](#getImageStream--) | 获取图像流。 |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | 返回图像的 MIME 类型。 |
| [getTitle](#getTitle--) | 获取指示图像标题的字符串值。 |
| [isApplyResolution](#isApplyResolution--) | 获取或设置一个布尔值，指示在生成过程中是否使用图像分辨率 |
| [isBlackWhite](#isBlackWhite--) | 获取一个布尔值，指示图像是否被强制为黑白。如果使用 CCITT 子格式的 TIFF 图像，则必须将此属性设置为 true。 |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | 尝试检测并使用 1bpp 编码用于灰度图像，默认值 == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | 获取或设置一个布尔值，指示在生成过程中是否使用图像分辨率 |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | 获取或设置未压缩的图像字节。 |
| [setBlackWhite](#setBlackWhite-boolean-) | 设置一个布尔值，指示图像是否被强制为黑白。如果使用 CCITT 子格式的 TIFF 图像，则必须将此属性设置为 true。 |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | 尝试检测并使用 1bpp 编码用于灰度图像。默认值 == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | 设置 java awt 图像。 |
| [setFile](#setFile-java.lang.String-) | 设置图像文件。 |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | 设置图像文件类型。 |
| [setFixHeight](#setFixHeight-double-) | 设置图像高度。 |
| [setFixWidth](#setFixWidth-double-) | 设置图像宽度。 |
| [setImageScale](#setImageScale-double-) | 设置图像比例。 |
| [setImageStream](#setImageStream-java.io.InputStream-) | 设置图像流。 |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | 设置指示图像标题的字符串值。 |

### Image {#Image--}
```
public Image()
```

默认构造函数

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
尝试将 bmp/png/gif/tiff 图像流转换为 JPG 格式图像流。

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆图像。

**Returns:**
克隆的对象。

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

获取或设置未压缩的图像字节。

**Returns:**
BitmapInfo 实例

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

获取图像位图大小。

**Returns:**
Rectangle 实例

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

获取 java awt 图像。

**Returns:**
BufferedImage 对象

### getFile {#getFile--}
```
public String getFile()
```

获取图像文件。

**Returns:**
字符串值

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

获取图像文件类型。

**Returns:**
int 值 @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

获取图像高度。

**Returns:**
double 值

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

获取图像宽度。

**Returns:**
double 值

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

获取图像比例。

**Returns:**
double 值

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

获取图像流。

**Returns:**
InputStream 对象

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
返回图像的 MIME 类型。

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

获取指示图像标题的字符串值。

**Returns:**
TextFragment 值

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

获取或设置一个布尔值，指示在生成过程中是否使用图像分辨率

**Returns:**
布尔值

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

获取一个布尔值，指示图像是否被强制为黑白。如果使用 CCITT 子格式的 TIFF 图像，则必须将此属性设置为 true。

**Returns:**
布尔值

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

尝试检测并使用 1bpp 编码用于灰度图像，默认值 == FALSE

**Returns:**
布尔值

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

获取或设置一个布尔值，指示在生成过程中是否使用图像分辨率

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
获取或设置未压缩的图像字节。

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

设置一个布尔值，指示图像是否被强制为黑白。如果使用 CCITT 子格式的 TIFF 图像，则必须将此属性设置为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

尝试检测并使用 1bpp 编码用于灰度图像。默认值 == FALSE

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| blackWhiteForGrayScale |  | 布尔值 |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
设置 java awt 图像。

### setFile {#setFile-java.lang.String-}
设置图像文件。

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
设置图像文件类型。

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

设置图像高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

设置图像宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

设置图像比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setImageStream {#setImageStream-java.io.InputStream-}
设置图像流。

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
设置指示图像标题的字符串值。
