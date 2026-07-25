---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示将 XSL-FO 文件加载/导入到 pdf 文档的选项。"
type: docs
weight: 5780
url: /zh/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

表示将 XSL-FO 文件加载/导入到 pdf 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | 创建不带 xsl 数据的 {@code XslFoLoadOptions} 对象。 |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | 创建不带 xsl 数据的 {@code XslFoLoadOptions} 对象。 |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | 创建不带 xsl 数据的 {@code XslFoLoadOptions} 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBasePath](#getBasePath--) | 用于搜索加载的 SVG 文件中引用的外部资源（如果有）的基础路径/URL。 |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | 源 XSLFO 文档可能包含格式错误。此枚举列举了处理这些错误的可能策略。 |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | 源 XSLFO 文档可能包含格式错误。此枚举列举了处理这些错误的可能策略。 |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

创建不带 xsl 数据的 {@code XslFoLoadOptions} 对象。

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
创建不带 xsl 数据的 {@code XslFoLoadOptions} 对象。

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
创建不带 xsl 数据的 {@code XslFoLoadOptions} 对象。

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

用于搜索加载的 SVG 文件中引用的外部资源（如果有）的基础路径/URL。

**Returns:**
字符串

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

源 XSLFO 文档可能包含格式错误。此枚举列举了处理这些错误的可能策略。

**Returns:**
ParsingErrorsHandlingTypes 元素 @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

源 XSLFO 文档可能包含格式错误。此枚举列举了处理这些错误的可能策略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parsingErrorsHandlingType |  | ParsingErrorsHandlingTypes 元素 @see ParsingErrorsHandlingTypes |
