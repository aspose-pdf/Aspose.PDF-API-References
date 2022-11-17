---
title: Font
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示字体对象。
type: docs
weight: 130
url: /zh/java/com.aspose.pdf/font/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Cloneable
```
public final class Font implements Cloneable
```

表示字体对象。

--------------------

```
The example demonstrates how to search text on first page and change font of a first search occurrence.
 
  
  //打开文档
  Document doc = new Document("input.pdf");
  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  //接受第一页的吸收器
  doc.getPages().get_Item(1).accept(absorber);
  
  //创建字体并将其标记为嵌入
  Font font = FontRepository.findFont("Arial");
  font.isEmbedded(true);
  
  //更改第一个文本出现的字体
  absorber.getTextFragments().get_Item(1).getTextState().setFont( font);
  
  
  //保存文件
  doc.save("output.pdf");
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [doesFontContainAllCharacters(String value)](#doesFontContainAllCharacters-java.lang.String-) | 确定字体是否包含指定的字符 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseFont()](#getBaseFont--) | 获取 PDF 字体对象的 BaseFont 值。 |
| [getClass()](#getClass--) |  |
| [getDecodedFontName()](#getDecodedFontName--) | 有时 PDF 字体（通常是中文/日文/韩文字体）可能有特定的字体名称。 |
| [getFontName()](#getFontName--) | 获取 Font 对象的字体名称。 |
| [getFontOptions()](#getFontOptions--) | 调整字体行为的有用属性 |
| [getIFont()](#getIFont--) | 系统字体对象。 |
| [getIPdfFont()](#getIPdfFont--) | PDF 字体对象。 |
| [getLastFontEmbeddingError()](#getLastFontEmbeddingError--) | 此方法的一个目标 - 如果尝试嵌入字体失败，则返回错误描述。 |
| [getType()](#getType--) | 字体类型名称 |
| [hashCode()](#hashCode--) |  |
| [isAccessible()](#isAccessible--) | 获取指示字体是否存在（安装）在系统中。 |
| [isEmbedded()](#isEmbedded--) | 获取一个值，该值指示是否嵌入字体。 |
| [isSubset()](#isSubset--) | 获取一个值，该值指示该字体是否是一个子集。 |
| [measureString(String str, float fontSize)](#measureString-java.lang.String-float-) | 测量字符串。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将字体保存到流中。 |
| [setEmbedded(boolean value)](#setEmbedded-boolean-) | 设置一个值，该值指示是否嵌入字体。 |
| [setSubset(boolean value)](#setSubset-boolean-) | 设置一个值，该值指示字体是否为子集。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### doesFontContainAllCharacters(String value) {#doesFontContainAllCharacters-java.lang.String-}
```
public boolean doesFontContainAllCharacters(String value)
```


确定字体是否包含指定的字符

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

**退货：**
boolean - 如果文本中的所有字符都出现在当前字体中，则为 true。
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
### getBaseFont() {#getBaseFont--}
```
public final String getBaseFont()
```


获取 PDF 字体对象的 BaseFont 值。也称为字体的 PostScript 名称。

**退货：**
java.lang.String - 字符串值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDecodedFontName() {#getDecodedFontName--}
```
public String getDecodedFontName()
```


有时 PDF 字体（通常是中文/日文/韩文字体）可能有特定的字体名称。此名称是 PDF 字体属性“BaseFont”的值，有时此属性可以用十六进制形式表示。如果直接读取这个名称，它可能会以不可读的形式表示。为了获得可读形式，有必要根据该字体的特定规则解码字体名称。此属性返回解码后的字体名称，因此在遇到不可读的 FontName 时使用它。如果属性 FontName 具有可读形式，则此属性将与 FontName 相同，因此您可以在需要以可读形式获取字体名称的任何情况下使用此属性。

**退货：**
java.lang.String - 字符串值
### getFontName() {#getFontName--}
```
public String getFontName()
```


获取 Font 对象的字体名称。

**退货：**
java.lang.String - 字符串值

--------------------

```
The example demonstrates how to search text on first page and view font name of a first text occurrence.
 
  //打开文档
  Document doc = new Document(@"D:\Tests\input.pdf");
  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  //接受第一页的吸收器
  doc.getPages().get_Item(1).accept(absorber);
  
  //查看第一个文本出现的字体名称
  System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName());
```
### getFontOptions() {#getFontOptions--}
```
public IFontOptions getFontOptions()
```


调整字体行为的有用属性

**退货：**
[IFontOptions](../../com.aspose.pdf/ifontoptions) IFontOptions 对象
### getIFont() {#getIFont--}
```
public IFont getIFont()
```


系统字体对象。

--------------------

仅供内部使用

**退货：**
[IFont](../../com.aspose.font/ifont)-IFont 对象
### getIPdfFont() {#getIPdfFont--}
```
public IPdfFont getIPdfFont()
```


PDF 字体对象。

--------------------

仅供内部使用

**退货：**
[IPdfFont](../../com.aspose.pdf.engine.commondata.text.fonts/ipdffont) IPdfFont 对象
### getLastFontEmbeddingError() {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```


此方法的一个目标 - 如果尝试嵌入字体失败，则返回错误描述。如果没有错误情况，它返回空字符串。

**退货：**
java.lang.String - 错误描述
### getType() {#getType--}
```
public String getType()
```


字体类型名称

**退货：**
java.lang.String - 字符串对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isAccessible() {#isAccessible--}
```
public boolean isAccessible()
```


获取指示字体是否存在（安装）在系统中。

**退货：**
boolean - 布尔值

--------------------

```
The example demonstrates how to search text on first page and get the value that indicates whether the font is installed in the system.
 
 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 
 //接受第一页的吸收器
 doc.getPages().get_Item(1).accept(absorber);
 
 //查看第一个文本出现的字体的 IsSubset 值
 if (absorber.getTextFragments().get_Item(1).getTextState().getFont()
 		.isAccessible())
 	System.out.println("the font is installed in the system");
```

--------------------

对于系统中找不到的字体，某些操作不可用。
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


获取一个值，该值指示是否嵌入字体。基于IFont的字体会自动进行子集嵌入

--------------------

```
The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font.
 
	      //创建字体并将其标记为嵌入
	      com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial");
	      font.isEmbedded ( true);
	      //打开文件
	      com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\Tests\\input.pdf");
	      //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
	      com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world");
	      //接受第一页的吸收器
	      doc.getPages().get_Item(1).accept(absorber);
	      //更改第一个文本出现的字体
	      absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
	      //保存文档
	      doc.save("D:\\Tests\\output.pdf");
```

**退货：**
boolean - 布尔值
### isSubset() {#isSubset--}
```
public boolean isSubset()
```


获取一个值，该值指示该字体是否是一个子集。基于IFont的字体会自动进行子集嵌入

--------------------

```
The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset.
  
	       //打开文档
	       Document doc = new Document("D:\\Tests\\input.pdf");
	       //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
	       TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
	       
	       //接受第一页的吸收器
	       doc.getPages().get_Item(1).accept(absorber);
	       
	       //查看第一个文本出现的字体的 IsSubset 值
	       if(absorber.TextFragments[1].TextState.Font.IsSubset)
	          System.out.println("the font is a subset");
```

**退货：**
boolean - 布尔值
### measureString(String str, float fontSize) {#measureString-java.lang.String-float-}
```
public double measureString(String str, float fontSize)
```


测量字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| str | java.lang.String | 字符串。 |
| fontSize | float | 字体大小。 |

**退货：**
double - 使用此字体和指定大小表示的字符串的宽度。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


将字体保存到流中。请注意，字体保存为中间 TTF 格式，仅用于原始文档的转换副本。字体文件不打算在原始文档上下文之外使用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream 来保存字体。 |

### setEmbedded(boolean value) {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```


设置一个值，该值指示是否嵌入字体。基于IFont的字体会自动进行子集嵌入

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSubset(boolean value) {#setSubset-boolean-}
```
public void setSubset(boolean value)
```


设置一个值，该值指示字体是否为子集。基于IFont的字体会自动进行子集嵌入

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

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
