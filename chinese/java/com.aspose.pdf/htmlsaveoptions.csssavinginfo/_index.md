---
title: "HtmlSaveOptions.CssSavingInfo"
linktitle: "HtmlSaveOptions.CssSavingInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "此类表示与 PDF 转换为 HTML 格式时自定义 CSS 保存相关的一组数据"
type: docs
weight: 2010
url: /zh/java/com.aspose.pdf/htmlsaveoptions.csssavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.CssSavingInfo

```
public static class HtmlSaveOptions.CssSavingInfo extends Object
```

此类表示与 PDF 转换为 HTML 格式时自定义 CSS 保存相关的一组数据

## 方法

| 方法 | 描述 |
| --- | --- |
| [getContentStream](#getContentStream--) | 由转换器设置。表示已保存 CSS 的二进制内容 |
| [getCssNumber](#getCssNumber--) | 由转换器设置。转换期间会创建多个 CSS 文件。此属性显示在转换过程中已保存 CSS 文件的序号。可在自定义代码逻辑中使用，以决定如何处理或将 CSS 内容保存到何处 |
| [getSupposedURL](#getSupposedURL--) | 由转换器设置。假定的文件名，从转换器传递给自定义方法的代码。可在自定义代码中用于决定如何处理或保存内容。 |
| [setContentStream](#setContentStream-java.io.InputStream-) | 由转换器设置。表示已保存 CSS 的二进制内容 |
| [setCssNumber](#setCssNumber-int-) | 由转换器设置。转换期间会创建多个 CSS 文件。此属性显示在转换过程中已保存 CSS 文件的序号。可在自定义代码逻辑中使用，以决定如何处理或将 CSS 内容保存到何处 |
| [setSupposedURL](#setSupposedURL-java.lang.String-) | 由转换器设置。假定的文件名，从转换器传递给自定义方法的代码。可在自定义代码中用于决定如何处理或保存内容。 |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

由转换器设置。表示已保存 CSS 的二进制内容

**Returns:**
InputStream 实例

### getCssNumber {#getCssNumber--}
```
public int getCssNumber()
```

由转换器设置。转换期间会创建多个 CSS 文件。此属性显示在转换过程中已保存 CSS 文件的序号。可在自定义代码逻辑中使用，以决定如何处理或将 CSS 内容保存到何处

**Returns:**
int 值

### getSupposedURL {#getSupposedURL--}
```
public String getSupposedURL()
```

由转换器设置。假定的文件名，从转换器传递给自定义方法的代码。可在自定义代码中用于决定如何处理或保存内容。

**Returns:**
字符串值

### setContentStream {#setContentStream-java.io.InputStream-}
由转换器设置。表示已保存 CSS 的二进制内容

### setCssNumber {#setCssNumber-int-}
```
public void setCssNumber(int cssNumber)
```

由转换器设置。转换期间会创建多个 CSS 文件。此属性显示在转换过程中已保存 CSS 文件的序号。可在自定义代码逻辑中使用，以决定如何处理或将 CSS 内容保存到何处

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cssNumber |  | int 值 |

### setSupposedURL {#setSupposedURL-java.lang.String-}
由转换器设置。假定的文件名，从转换器传递给自定义方法的代码。可在自定义代码中用于决定如何处理或保存内容。
