---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "此类表示在 PDF 转换为 HTML 期间与外部资源图像文件保存相关的一组数据。"
type: docs
weight: 2070
url: /zh/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

此类表示在 PDF 转换为 HTML 期间与外部资源图像文件保存相关的一组数据。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | 创建 HtmlImageSavingInfo 的新实例 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | 告知自定义代码保存的图像对应于生成的 HTML 页面文件集合中的哪一页。如果关闭了分页，此值始终为 '1'，因为在这种情况下只会生成一个 HTML 页面。 |
| [getImageType](#getImageType--) | 表示在 HTML 中引用的已保存图像的类型。由转换器设置，可在自定义代码中用于决定应执行的操作。 |
| [getParentType](#getParentType--) | 已保存的图像可以属于 HTML 本身，也可以从嵌入到 HTML 的 SVG 中提取。此属性可以告知自定义代码处理的图像的父级类型。它由转换器设置，可在自定义代码中用于决定对该图像的处理方式（例如，自定义代码可以决定将图像保存到何处或在父级内容中如何引用它）。 |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | 告知自定义代码保存的图像对应于原始 PDF 文档的哪一页。由于可能并非所有原始文档的页面都会被保存，此值指示原始 PDF 中的所在页码。如果由于某种原因原始页码未知，则始终返回 '1'。 |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | 告知自定义代码保存的图像对应于生成的 HTML 页面文件集合中的哪一页。如果关闭了分页，此值始终为 '1'，因为在这种情况下只会生成一个 HTML 页面。 |
| [setImageType](#setImageType-int-) | 表示在 HTML 中引用的已保存图像的类型。由转换器设置，可在自定义代码中用于决定应执行的操作。 |
| [setParentType](#setParentType-int-) | 已保存的图像可以属于 HTML 本身，也可以从嵌入到 HTML 的 SVG 中提取。此属性可以告知自定义代码处理的图像的父级类型。它由转换器设置，可在自定义代码中用于决定对该图像的处理方式（例如，自定义代码可以决定将图像保存到何处或在父级内容中如何引用它）。 |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | 告知自定义代码保存的图像对应于原始 PDF 文档的哪一页。由于可能并非所有原始文档的页面都会被保存，此值指示原始 PDF 中的所在页码。如果由于某种原因原始页码未知，则始终返回 '1'。 |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

创建 HtmlImageSavingInfo 的新实例

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

告知自定义代码保存的图像对应于生成的 HTML 页面文件集合中的哪一页。如果关闭了分页，此值始终为 '1'，因为在这种情况下只会生成一个 HTML 页面。

**Returns:**
int 值

### getImageType {#getImageType--}
```
public int getImageType()
```

表示在 HTML 中引用的已保存图像的类型。由转换器设置，可在自定义代码中用于决定应执行的操作。

**Returns:**
HtmlImageType 元素 @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

已保存的图像可以属于 HTML 本身，也可以从嵌入到 HTML 的 SVG 中提取。此属性可以告知自定义代码处理的图像的父级类型。它由转换器设置，可在自定义代码中用于决定对该图像的处理方式（例如，自定义代码可以决定将图像保存到何处或在父级内容中如何引用它）。

**Returns:**
ImageParentTypes 元素 @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

告知自定义代码保存的图像对应于原始 PDF 文档的哪一页。由于可能并非所有原始文档的页面都会被保存，此值指示原始 PDF 中的所在页码。如果由于某种原因原始页码未知，则始终返回 '1'。

**Returns:**
int 值

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

告知自定义代码保存的图像对应于生成的 HTML 页面文件集合中的哪一页。如果关闭了分页，此值始终为 '1'，因为在这种情况下只会生成一个 HTML 页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlHostPageNumber |  | int 值 |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

表示在 HTML 中引用的已保存图像的类型。由转换器设置，可在自定义代码中用于决定应执行的操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageType |  | HtmlImageType 元素 @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

已保存的图像可以属于 HTML 本身，也可以从嵌入到 HTML 的 SVG 中提取。此属性可以告知自定义代码处理的图像的父级类型。它由转换器设置，可在自定义代码中用于决定对该图像的处理方式（例如，自定义代码可以决定将图像保存到何处或在父级内容中如何引用它）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parentType |  | ImageParentTypes 元素 @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

告知自定义代码保存的图像对应于原始 PDF 文档的哪一页。由于可能并非所有原始文档的页面都会被保存，此值指示原始 PDF 中的所在页码。如果由于某种原因原始页码未知，则始终返回 '1'。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfHostPageNumber |  | int 值 |
