---
title: "字体"
linktitle: "字体"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示字体对象。 </p> <hr> <pre> 示例演示如何在首页搜索文本并更改首次搜索出现的字体。 // Open document Document doc."
type: docs
weight: 1650
url: /zh/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Cloneable

```
public final class Font extends Object implements Cloneable
```

<p> 表示字体对象。 </p> <hr> <pre> 示例演示如何在首页搜索文本并更改首次搜索出现的字体。 // Open document Document doc = new Document(\"input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## 方法

| 方法 | 描述 |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | 确定字体是否包含指定字符 |
| [getActualFontName](#getActualFontName--) | <p> 获取已初始化的 {@code Font} 对象的实际字体名称。即使字体已被替换或在 PDF 中有内部名称。如果字体未初始化，则返回空字符串。 </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | 测量最大上升点。 |
| [getBaseFont](#getBaseFont--) | 获取 PDF 字体对象的 BaseFont 值。也称为字体的 PostScript 名称。 |
| [getDecodedFontName](#getDecodedFontName--) | 有时 PDF 字体（通常是中、日、韩字体）可能具有特定的字体名称。该名称是 PDF 字体属性 \"BaseFont\" 的值，有时该属性会以十六进制形式表示。如果直接读取此名称，可能会呈现为不可读的形式。要获取可读形式，需要按照该字体的特定规则解码字体名称。此属性返回解码后的字体名称，因此在遇到不可读的 {@code FontName} 时使用它。如果属性 {@code FontName} 已是可读形式，则此属性与 {@code FontName} 相同，因此在任何需要获取可读字体名称的情况下都可以使用此属性。 |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | 测量最大下降点。 |
| [getFontName](#getFontName--) | <p> 获取 {@code Font} 对象的字体名称。 </p> |
| [getFontOptions](#getFontOptions--) | 用于调节字体行为的有用属性 |
| [getIFont](#getIFont--) | <p> 系统字体对象。 </p> <hr> <p> 仅供内部使用 </p> |
| [getIPdfFont](#getIPdfFont--) | <p> Pdf 字体对象。 </p> <hr> <p> 仅供内部使用 </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | 此方法的目标是返回嵌入字体失败时的错误描述。如果没有错误情况，则返回空字符串。 |
| [getType](#getType--) | 字体的类型名称 |
| [isAccessible](#isAccessible--) | <p> 获取指示字体是否已在系统中存在（已安装）的状态。 </p> |
| [isEmbedded](#isEmbedded--) | <p> 获取指示字体是否已嵌入的值。基于 IFont 的字体将自动进行子集化并嵌入 </p> <hr> <pre> 以下示例演示如何查找字体、标记为嵌入、在文档页面上搜索文本并替换文本字体。 // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Arial\"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document(\"D:\\\\Tests\\\\input.pdf\"); // create TextFragmentAbsorber object to find all \"hello world\" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber(\"hello world\"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [isSubset](#isSubset--) | <p> 获取指示字体是否为子集的值。基于 IFont 的字体将自动进行子集化并嵌入 </p> <hr> <pre> 示例演示如何在首页搜索文本并获取指示字体是否为子集的值。 // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println(\"the font is a subset\"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | 测量字符串。 |
| [save](#save-java.io.OutputStream-) | 将字体保存到流中。请注意，字体会保存为中间的 TTF 格式，仅用于原始文档的转换副本。该字体文件不应在原始文档上下文之外使用。 |
| [setEmbedded](#setEmbedded-boolean-) | 设置一个指示字体是否已嵌入的值。基于 IFont 的字体将自动进行子集化并嵌入。 |
| [setSubset](#setSubset-boolean-) | 设置一个指示字体是否为子集的值。基于 IFont 的字体将自动进行子集化并嵌入。 |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
确定字体是否包含指定字符

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> 获取已初始化的 {@code Font} 对象的实际字体名称。即使字体已被替换或在 PDF 中有内部名称。如果字体未初始化，则返回空字符串。 </p>

**Returns:**
字符串值 <hr> <pre> 示例演示如何在首页搜索文本并查看首次文本出现的实际字体名称。 // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View actual font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
测量最大上升点。

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

获取 PDF 字体对象的 BaseFont 值。也称为字体的 PostScript 名称。

**Returns:**
字符串值

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

有时 PDF 字体（通常是中、日、韩字体）可能具有特定的字体名称。该名称是 PDF 字体属性 \"BaseFont\" 的值，有时该属性会以十六进制形式表示。如果直接读取此名称，可能会呈现为不可读的形式。要获取可读形式，需要按照该字体的特定规则解码字体名称。此属性返回解码后的字体名称，因此在遇到不可读的 {@code FontName} 时使用它。如果属性 {@code FontName} 已是可读形式，则此属性与 {@code FontName} 相同，因此在任何需要获取可读字体名称的情况下都可以使用此属性。

**Returns:**
字符串值

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
测量最大下降点。

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> 获取 {@code Font} 对象的字体名称。 </p>

**Returns:**
字符串值 <hr> <pre> 示例演示如何在首页搜索文本并查看首次文本出现的字体名称。 // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

用于调节字体行为的有用属性

**Returns:**
IFontOptions 对象

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> 系统字体对象。 </p> <hr> <p> 仅供内部使用 </p>

**Returns:**
IFont 对象

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> Pdf 字体对象。 </p> <hr> <p> 仅供内部使用 </p>

**Returns:**
IPdfFont 对象

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

此方法的目标是返回嵌入字体失败时的错误描述。如果没有错误情况，则返回空字符串。

**Returns:**
错误描述

### getType {#getType--}
```
public String getType()
```

字体的类型名称

**Returns:**
字符串对象

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> 获取指示字体是否已在系统中存在（已安装）的状态。 </p>

**Returns:**
布尔值 <hr> <pre> 示例演示如何在首页搜索文本并获取指示字体是否已安装在系统中的值。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println("the font is installed in the system"); </pre> <hr> <p> 某些操作在系统中找不到的字体上不可用。 </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> 获取一个指示字体是否已嵌入的值。基于 IFont 的字体将自动进行子集化并嵌入 </p> <hr> <pre> 以下示例演示如何查找字体、将其标记为嵌入、在文档页面上搜索文本并替换文本的字体。 // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\Tests\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\Tests\\output.pdf"); </pre>

**Returns:**
布尔值 @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> 获取一个指示字体是否为子集的值。基于 IFont 的字体将自动进行子集化并嵌入 </p> <hr> <pre> 示例演示如何在首页搜索文本并获取指示字体是否为子集的值。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre>

**Returns:**
布尔值 @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
测量字符串。

### save {#save-java.io.OutputStream-}
将字体保存到流中。请注意，字体会保存为中间的 TTF 格式，仅用于原始文档的转换副本。该字体文件不应在原始文档上下文之外使用。

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

设置一个指示字体是否已嵌入的值。基于 IFont 的字体将自动进行子集化并嵌入。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

设置一个指示字体是否为子集的值。基于 IFont 的字体将自动进行子集化并嵌入。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
