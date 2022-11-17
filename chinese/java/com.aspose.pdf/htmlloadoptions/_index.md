---
title: HtmlLoadOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示将 html 文件加载/导入 pdf 文档的选项。
type: docs
weight: 158
url: /zh/java/com.aspose.pdf/htmlloadoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class HtmlLoadOptions extends LoadOptions
```

表示将 html 文件加载/导入 pdf 文档的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlLoadOptions()](#HtmlLoadOptions--) | 创建用于将 html 转换为基本路径为空的 pdf 文档的加载选项。 |
| [HtmlLoadOptions(String basePath)](#HtmlLoadOptions-java.lang.String-) | 创建用于将 html 转换为具有定义的基本路径的 pdf 文档的加载选项。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasePath()](#getBasePath--) | html 文件的基本路径/url。 |
| [getClass()](#getClass--) |  |
| [getCustomLoaderOfExternalResources()](#getCustomLoaderOfExternalResources--) | 有时有必要避免使用外部资源（如图像或 CSS）的内部加载器，并提供将从某处获取请求资源的自定义方法。 |
| [getHtmlMediaType()](#getHtmlMediaType--) | 获取或设置呈现期间可能使用的媒体类型。 |
| [getInputEncoding()](#getInputEncoding--) | 获取指定在解析时用于此文档的编码的属性。 |
| [getLoadFormat()](#getLoadFormat--) | 表示 LoadOptions 描述的文件格式。 |
| [getPageInfo()](#getPageInfo--) | 获取文档页面信息 |
| [getPageLayoutOption()](#getPageLayoutOption--) | 获取或设置布局选项。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [isEmbedFonts()](#isEmbedFonts--) | 获取或设置嵌入结果文档的字体 |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | 获取或设置将所有文档呈现为单页 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources)](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | 有时有必要避免使用外部资源（如图像或 CSS）的内部加载器，并提供将从某处获取请求资源的自定义方法。 |
| [setEmbedFonts(boolean value)](#setEmbedFonts-boolean-) | 获取或设置嵌入结果文档的字体 |
| [setHtmlMediaType(int value)](#setHtmlMediaType-int-) | 获取或设置呈现期间可能使用的媒体类型。 |
| [setInputEncoding(String value)](#setInputEncoding-java.lang.String-) | 设置指定解析时用于此文档的编码的属性。 |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | 设置文档页面信息 |
| [setPageLayoutOption(int value)](#setPageLayoutOption-int-) | 获取或设置布局选项。 |
| [setRenderToSinglePage(boolean value)](#setRenderToSinglePage-boolean-) | 获取或设置将所有文档呈现为单页 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlLoadOptions() {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```


创建用于将 html 转换为基本路径为空的 pdf 文档的加载选项。

### HtmlLoadOptions(String basePath) {#HtmlLoadOptions-java.lang.String-}
```
public HtmlLoadOptions(String basePath)
```


创建用于将 html 转换为具有定义的基本路径的 pdf 文档的加载选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| basePath | java.lang.String | html 文件的基本路径/url。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getBasePath() {#getBasePath--}
```
public String getBasePath()
```


html 文件的基本路径/url。

**退货：**
java.lang.String - 字符串值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCustomLoaderOfExternalResources() {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```


有时有必要避免使用外部资源（如图像或 CSS）的内部加载器，并提供将从某处获取请求资源的自定义方法。例如，在云中使用 Aspose.PDF 期间不可能直接访问引用的文件：在这种情况下，应该使用一些放入特殊方法的客户代码，并且应该将引用该方法的委托分配给该属性。

**退货：**
[ResourceLoadingStrategy](../../com.aspose.pdf/resourceloadingstrategy) - ResourceLoadingStrategy 实例
### getHtmlMediaType() {#getHtmlMediaType--}
```
public int getHtmlMediaType()
```


获取或设置呈现期间可能使用的媒体类型。

**退货：**
int - HtmlMediaType 元素
### getInputEncoding() {#getInputEncoding--}
```
public String getInputEncoding()
```


获取指定在解析时用于此文档的编码的属性。如果此属性为空，则编码将从文档字符集属性中确定。

**退货：**
java.lang.String - 字符串值
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


表示 LoadOptions 描述的文件格式。

**退货：**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat 元素
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


获取文档页面信息

**退货：**
[PageInfo](../../com.aspose.pdf/pageinfo) - 页面信息
### getPageLayoutOption() {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```


获取或设置布局选项。

**退货：**
int - HtmlPageLayoutOption 元素
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Load 操作继续，但是用户也可以返回 Abort，在这种情况下 Load 操作应该停止。

**退货：**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback 值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isEmbedFonts() {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```


获取或设置嵌入结果文档的字体

**退货：**
boolean - 布尔值
### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```


获取或设置将所有文档呈现为单页

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources) {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
```
public void setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources)
```


有时有必要避免使用外部资源（如图像或 CSS）的内部加载器，并提供将从某处获取请求资源的自定义方法。例如，在云中使用 Aspose.PDF 期间不可能直接访问引用的文件：在这种情况下，应该使用一些放入特殊方法的客户代码，并且应该将引用该方法的委托分配给该属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customLoaderOfExternalResources | [ResourceLoadingStrategy](../../com.aspose.pdf/resourceloadingstrategy) | ResourceLoadingStrategy 实例 |

### setEmbedFonts(boolean value) {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```


获取或设置嵌入结果文档的字体

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHtmlMediaType(int value) {#setHtmlMediaType-int-}
```
public void setHtmlMediaType(int value)
```


获取或设置呈现期间可能使用的媒体类型。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HtmlMediaType 元素 |

### setInputEncoding(String value) {#setInputEncoding-java.lang.String-}
```
public void setInputEncoding(String value)
```


设置指定解析时用于此文档的编码的属性。如果此属性为空，则编码将从文档字符集属性中确定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


设置文档页面信息

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | 页面信息 |

### setPageLayoutOption(int value) {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```


获取或设置布局选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HtmlPageLayoutOption 元素 |

### setRenderToSinglePage(boolean value) {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```


获取或设置将所有文档呈现为单页

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Load 操作继续，但是用户也可以返回 Abort，在这种情况下 Load 操作应该停止。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback 值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
