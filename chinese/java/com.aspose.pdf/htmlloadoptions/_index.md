---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示将 html 文件加载/导入到 pdf 文档的选项。"
type: docs
weight: 1960
url: /zh/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

表示将 html 文件加载/导入到 pdf 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | 创建加载选项，以将 html 转换为 pdf 文档，且基路径为空。 |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | 创建加载选项，以将 html 转换为 pdf 文档，且基路径为空。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBasePath](#getBasePath--) | html 文件的基路径/URL。 |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | 有时需要避免使用内部加载器来加载外部资源（如图像或 CSS），并提供自定义方法以从某处获取请求的资源。例如，在云端使用 Aspose.PDF 时，无法直接访问引用的文件：在这种情况下，应使用放入特定方法的客户代码，并将指向该方法的委托分配给此属性。 |
| [getHtmlMediaType](#getHtmlMediaType--) | 获取或设置渲染期间使用的可能媒体类型。 |
| [getInputEncoding](#getInputEncoding--) | 获取指定在解析时用于此文档的编码的属性。如果此属性为 null，则编码将根据文档字符集属性确定。 |
| [getPageInfo](#getPageInfo--) | 获取文档页面信息 |
| [getPageLayoutOption](#getPageLayoutOption--) | 获取或设置布局选项。 |
| [isEmbedFonts](#isEmbedFonts--) | 获取或设置嵌入到结果文档的字体 |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | 获取或设置指定 @page 规则在 css 中将覆盖 PageInfo 中定义的值的标志。 |
| [isRenderToSinglePage](#isRenderToSinglePage--) | 获取或设置将整个文档渲染为单页 |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | 有时需要避免使用外部资源（如图像或 CSS）的内部加载器，并提供自定义方法从某处获取请求的资源。 |
| [setEmbedFonts](#setEmbedFonts-boolean-) | 获取或设置嵌入到结果文档的字体 |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | 获取或设置渲染期间使用的可能媒体类型。 |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | 设置在解析时用于此文档的编码属性。如果此属性为 null，则编码将根据文档字符集属性确定。 |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | 设置文档页面信息 |
| [setPageLayoutOption](#setPageLayoutOption-int-) | 获取或设置布局选项。 |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | 获取或设置指定 @page 规则在 css 中将覆盖 PageInfo 中定义的值的标志。 |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | 获取或设置将整个文档渲染为单页 |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

创建加载选项，以将 html 转换为 pdf 文档，且基路径为空。

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
创建加载选项，以将 html 转换为 pdf 文档，且基路径为空。

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

html 文件的基路径/URL。

**Returns:**
字符串值

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

有时需要避免使用内部加载器来加载外部资源（如图像或 CSS），并提供自定义方法以从某处获取请求的资源。例如，在云端使用 Aspose.PDF 时，无法直接访问引用的文件：在这种情况下，应使用放入特定方法的客户代码，并将指向该方法的委托分配给此属性。

**Returns:**
ResourceLoadingStrategy 实例

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

获取或设置渲染期间使用的可能媒体类型。

**Returns:**
HtmlMediaType 元素

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

获取指定在解析时用于此文档的编码的属性。如果此属性为 null，则编码将根据文档字符集属性确定。

**Returns:**
字符串值

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

获取文档页面信息

**Returns:**
页面信息

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

获取或设置布局选项。

**Returns:**
HtmlPageLayoutOption 元素 @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

获取或设置嵌入到结果文档的字体

**Returns:**
布尔值

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

获取或设置指定 @page 规则在 css 中将覆盖 PageInfo 中定义的值的标志。

**Returns:**
布尔值

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

获取或设置将整个文档渲染为单页

**Returns:**
布尔值

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
有时需要避免使用外部资源（如图像或 CSS）的内部加载器，并提供自定义方法从某处获取请求的资源。

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

获取或设置嵌入到结果文档的字体

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
获取或设置渲染期间使用的可能媒体类型。

### setInputEncoding {#setInputEncoding-java.lang.String-}
设置在解析时用于此文档的编码属性。如果此属性为 null，则编码将根据文档字符集属性确定。

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
设置文档页面信息

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

获取或设置布局选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | HtmlPageLayoutOption 元素 @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

获取或设置指定 @page 规则在 css 中将覆盖 PageInfo 中定义的值的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

获取或设置将整个文档渲染为单页

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
