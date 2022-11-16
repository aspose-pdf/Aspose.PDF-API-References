---
title: TextFragmentAbsorber
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文本片段的吸收器对象。
type: docs
weight: 373
url: /zh/java/com.aspose.pdf/textfragmentabsorber/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.TextAbsorber](../../com.aspose.pdf/textabsorber)
```
public final class TextFragmentAbsorber extends TextAbsorber
```

表示文本片段的吸收器对象。执行文本搜索并通过 TextFragmentAbsorber.TextFragments 集合提供对搜索结果的访问。

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text and it's font.

 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //查找将用于更改文档文本字体的字体
 com.aspose.pdf.Font font = FontRepository.findFont("Arial");
 //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 //接受第一页的吸收器
 doc.getPages().get(1).accept(absorber);
 //更改第一个文本出现的文本和字体
 absorber.getTextFragments().get_Item(1).setText ( "hi world");
 absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
 //保存文件
 doc.save("D:\\Tests\\output.pdf");
```

--------------------

TextFragmentAbsorber 对象主要用于文本搜索场景。搜索完成后，出现的事件用 TextFragmentAbsorber.TextFragments 集合包含的 TextFragment 对象表示。 TextFragment 对象提供对搜索出现文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字体大小、颜色等）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextFragmentAbsorber()](#TextFragmentAbsorber--) | 初始化 TextFragmentAbsorber 的新实例，该实例执行对文档或页面的所有文本段的搜索。 |
| [TextFragmentAbsorber(TextEditOptions textEditOptions)](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | 使用文本编辑选项初始化 TextFragmentAbsorber 的新实例，该实例执行对文档或页面的所有文本段的搜索。 |
| [TextFragmentAbsorber(String phrase)](#TextFragmentAbsorber-java.lang.String-) | 为指定的文本短语初始化 TextFragmentAbsorber 类的新实例。 |
| [TextFragmentAbsorber(Pattern regex)](#TextFragmentAbsorber-java.util.regex.Pattern-) | 初始化一个新的实例[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)指定 System.Text.RegularExpressions.Regex 类对象的类。 |
| [TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | 为指定的文本短语和文本搜索选项初始化 TextFragmentAbsorber 类的新实例。 |
| [TextFragmentAbsorber(Pattern regex, TextSearchOptions textSearchOptions)](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | 初始化一个新的实例[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)指定文本短语和文本搜索选项的类。 |
| [TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | 为指定的文本短语、文本搜索选项和文本编辑选项初始化 TextFragmentAbsorber 类的新实例。 |
| [TextFragmentAbsorber(Pattern regex, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | 初始化一个新的实例[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)指定文本短语和文本编辑选项的类。 |
| [TextFragmentAbsorber(String phrase, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | 为指定的文本短语和文本编辑选项初始化 TextFragmentAbsorber 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [applyForAllFragments(Font font)](#applyForAllFragments-com.aspose.pdf.Font-) | 为吸收的所有文本片段应用字体。 |
| [applyForAllFragments(Font font, float fontSize)](#applyForAllFragments-com.aspose.pdf.Font-float-) | 为吸收的所有文本片段应用字体和大小。 |
| [applyForAllFragments(float fontSize)](#applyForAllFragments-float-) | 为吸收的所有文本片段应用字体大小。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrors()](#getErrors--) | TextExtractionError 对象列表。 |
| [getExtractionOptions()](#getExtractionOptions--) | 获取文本提取选项。 |
| [getPhrase()](#getPhrase--) | 获取 TextFragmentAbsorber 在 PDF 文档或页面上搜索的短语。 |
| [getText()](#getText--) | 获取 TextAbsorber 在 PDF 文档或页面上提取的提取文本。 |
| [getTextEditOptions()](#getTextEditOptions--) | 获取文本编辑选项。 |
| [getTextFragments()](#getTextFragments--) | 获取与 TextFragment 对象一起出现的搜索事件的集合。 |
| [getTextReplaceOptions()](#getTextReplaceOptions--) | 获取文本替换选项。 |
| [getTextSearchOptions()](#getTextSearchOptions--) | 获取搜索选项。 |
| [hasErrors()](#hasErrors--) | 值指示在文本提取期间是否发现错误。 |
| [hasErrors_Fragment()](#hasErrors-Fragment--) | 值指示在文本提取期间是否发现错误。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAllText(Document document)](#removeAllText-com.aspose.pdf.Document-) | 从文档中删除所有文本。 |
| [removeAllText(Page page)](#removeAllText-com.aspose.pdf.Page-) | 从指定页面中删除所有文本。 |
| [removeAllText(Page page, Rectangle rect)](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 从指定页面移除指定矩形内的文本。 |
| [reset()](#reset--) | 清除此 TextFragmentAbsorber 对象的 TextFragments 集合。 |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | 设置文本提取选项。 |
| [setPhrase(String value)](#setPhrase-java.lang.String-) | 设置 TextFragmentAbsorber 在 PDF 文档或页面上搜索的短语。 |
| [setTextEditOptions(TextEditOptions value)](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | 设置文本编辑选项。 |
| [setTextFragments(TextFragmentCollection value)](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | 设置与 TextFragment 对象一起出现的搜索事件的集合。 |
| [setTextReplaceOptions(TextReplaceOptions value)](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | 设置文本替换选项。 |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | 设置搜索选项。 |
| [toString()](#toString--) |  |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | 对指定文档执行搜索。 |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | 在指定页面上执行搜索。 |
| [visit(XForm xForm)](#visit-com.aspose.pdf.XForm-) | 对指定的表单对象执行搜索。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextFragmentAbsorber() {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```


初始化 TextFragmentAbsorber 的新实例，该实例执行对文档或页面的所有文本段的搜索。

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text.

 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //查找将用于更改文档文本字体的字体
 Font font = FontRepository.findFont("Arial");
 //创建 TextFragmentAbsorber 对象
 TextFragmentAbsorber absorber = new TextFragmentAbsorber();
 //让吸收器搜索所有“hello world”文本出现
 absorber.setPhrase ( "hello world");
 //接受第一页的吸收器
 doc.getPages().get(1).accept(absorber);
 //更改第一个文本出现的文本
 absorber.getTextFragments().get_Item(1).setText ( "hi world");
 //保存文件
 doc.save("D:\\Tests\\output.pdf");
```

--------------------

执行文本搜索并通过 TextFragmentAbsorber.TextFragments 集合提供对搜索结果的访问。

### TextFragmentAbsorber(TextEditOptions textEditOptions) {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```


使用文本编辑选项初始化 TextFragmentAbsorber 的新实例，该实例执行对文档或页面的所有文本段的搜索。

--------------------

```
The example demonstrates how to find all text fragments on the first PDF document page and replace font for them.

  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");

  //创建 TextFragmentAbsorber 对象
  TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace
  .RemoveUnusedFonts));

  //接受第一页的吸收器
  doc.getPages()get(1).accept(absorber);

  //查找 Courier 字体
  Font font = FontRepository.findFont("Courier");
  //设置所有文本片段的字体
  for (TextFragment textFragment : ```
(Iterable)
```absorber.TextFragments)
  {
      textFragment.getTextState().setFont ( font);
  }
  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | 文本编辑选项（允许打开某些编辑功能）。

--------------------

执行文本搜索并通过 TextFragmentAbsorber.TextFragments 集合提供对搜索结果的访问。|

### TextFragmentAbsorber(String phrase) {#TextFragmentAbsorber-java.lang.String-}
```
public TextFragmentAbsorber(String phrase)
```


为指定的文本短语初始化 TextFragmentAbsorber 类的新实例。

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text and it's font.

 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //查找将用于更改文档文本字体的字体
 com.aspose.pdf.Font font = FontRepository.findFont("Arial");
 //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 //接受第一页的吸收器
 doc.getPages().get_Item(1).accept(absorber);
 //更改第一个文本出现的文本和字体
 absorber.getTextFragments().get_Item(1).setText ( "hi world");
 absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
 //保存文件
 doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| phrase | java.lang.String | TextFragmentAbsorber 搜索的短语

--------------------

执行指定短语的文本搜索，并通过 TextFragmentAbsorber.TextFragments 集合提供对搜索结果的访问。|

### TextFragmentAbsorber(Pattern regex) {#TextFragmentAbsorber-java.util.regex.Pattern-}
```
public TextFragmentAbsorber(Pattern regex)
```


初始化一个新的实例[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)指定 System.Text.RegularExpressions.Regex 类对象的类。

--------------------

该示例演示了如何在第一个 PDF 文档页面上查找文本并替换文本及其字体。

```
//打开文档
  Document doc = new Document("input.pdf");
  //查找将用于更改文档文本字体的字体
  Font font = FontRepository.findFont("Arial");
  //创建 TextAbsorber 对象以查找输入正则表达式的所有实例
  TextFragmentAbsorber absorber = new TextFragmentAbsorber(new Regex("h\\w*?o"));
  //接受第一页的吸收器
  doc.getPages().get_item(1).accept(absorber);
  //我们应该找到“你好”这个词并将其替换为“嗨”
  absorber.getTextFragments().get_item(1).setText("Hi");
  //保存文件
  doc.save("output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern |  System.Text.RegularExpressions.Regex 类对象，[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)搜索

--------------------

执行指定短语的文本搜索，并通过 TextFragmentAbsorber.TextFragments (\#getTextFragments.getTextFragments/\ #setTextFragments(TextFragmentCollection).setTextFragments(TextFragmentCollection)) 集合。|

### TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
```
public TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions)
```


为指定的文本短语和文本搜索选项初始化 TextFragmentAbsorber 类的新实例。

--------------------

```
The example demonstrates how to find text with regular expression on the first PDF document page and replace
 the text.

 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //创建 TextFragmentAbsorber 对象，该对象使用正则搜索以“h”开头和以“o”结尾的所有单词
 expression.
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("h\\w*?o", new TextSearchOptions(true));
 //我们应该找到“你好”这个词并将其替换为“嗨”
 doc.getPages().get_Item(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");

 //保存文件
 doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| phrase | java.lang.String | TextFragmentAbsorber 搜索的短语 |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | 文本搜索选项（允许打开一些搜索功能。例如，使用正则表达式搜索）

--------------------

执行指定短语的文本搜索，并通过 TextFragmentAbsorber.TextFragments 集合提供对搜索结果的访问。|

### TextFragmentAbsorber(Pattern regex, TextSearchOptions textSearchOptions) {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
```
public TextFragmentAbsorber(Pattern regex, TextSearchOptions textSearchOptions)
```


初始化一个新的实例[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)指定文本短语和文本搜索选项的类。

--------------------

该示例演示如何在第一个 PDF 文档页面上使用正则表达式查找文本并替换文本。

```
//打开文档
  Document doc = new Document("input.pdf");
  //创建 TextFragmentAbsorber 对象，该对象使用正则表达式搜索以“h”开头和以“o”结尾的所有单词。
  TextFragmentAbsorber absorber = new TextFragmentAbsorber(new Regex("h\\w*?o"), new TextSearchOptions(true));
  //我们应该找到“你好”这个词并将其替换为“嗨”
  doc.getPages().get_Item(1).accept(absorber);
  absorber.getTextFragments.get_Item(1).setText("Hi");
  //保存文件
  doc.save("output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 正则表达式类对象，[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)搜索 |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | 文本搜索选项（允许打开某些搜索功能。）

--------------------

执行指定短语的文本搜索，并通过 TextFragmentAbsorber.TextFragments (\#getTextFragments.getTextFragments/\ #setTextFragments(TextFragmentCollection).setTextFragments(TextFragmentCollection)) 集合。|

### TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions)
```


为指定的文本短语、文本搜索选项和文本编辑选项初始化 TextFragmentAbsorber 类的新实例。尚不支持文本编辑选项。

--------------------

```
The example demonstrates how to find text with regular expression on the first PDF document page and replace
 the text.

 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //创建 TextFragmentAbsorber 对象，该对象使用正则搜索以“h”开头和以“o”结尾的所有单词
 expression.
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("h\w*?o", new TextSearchOptions(true));
 //我们应该找到“你好”这个词并将其替换为“嗨”
 doc.getPages().get_item(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");
 //保存文件
 doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| phrase | java.lang.String | TextFragmentAbsorber 搜索的短语 |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | 文本搜索选项（允许打开一些搜索功能。例如，使用正则表达式搜索） |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | 文本编辑选项（允许打开一些编辑功能。例如，当请求的符号不能用字体书写时定义特殊行为）。尚不支持该参数。

--------------------

执行指定短语的文本搜索，并通过 TextFragmentAbsorber.TextFragments 集合提供对搜索结果的访问。|

### TextFragmentAbsorber(Pattern regex, TextEditOptions textEditOptions) {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(Pattern regex, TextEditOptions textEditOptions)
```


初始化一个新的实例[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)指定文本短语和文本编辑选项的类。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern |  System.Text.RegularExpressions.Regex 类对象，[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)搜索 |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | 文本编辑选项（允许打开某些编辑功能）。

--------------------

执行指定短语的文本搜索，并通过 TextFragmentAbsorber.TextFragments (\#getTextFragments.getTextFragments/\ #setTextFragments(TextFragmentCollection).setTextFragments(TextFragmentCollection)) 集合。|

### TextFragmentAbsorber(String phrase, TextEditOptions textEditOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(String phrase, TextEditOptions textEditOptions)
```


为指定的文本短语和文本编辑选项初始化 TextFragmentAbsorber 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| phrase | java.lang.String | TextFragmentAbsorber 搜索的短语 |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | 文本编辑选项（允许打开某些编辑功能）。

--------------------

执行指定短语的文本搜索，并通过 TextFragmentAbsorber.TextFragments 集合提供对搜索结果的访问。|

### applyForAllFragments(Font font) {#applyForAllFragments-com.aspose.pdf.Font-}
```
public void applyForAllFragments(Font font)
```


为吸收的所有文本片段应用字体。如果页面上的所有片段都被吸收，它比循环片段更快。否则它与循环类似。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) |  文本的字体。 |

### applyForAllFragments(Font font, float fontSize) {#applyForAllFragments-com.aspose.pdf.Font-float-}
```
public void applyForAllFragments(Font font, float fontSize)
```


为吸收的所有文本片段应用字体和大小。如果页面上的所有片段都被吸收，它比循环片段更快。否则它与循环类似。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) |  文本的字体。 |
| fontSize | float | 文本的字体大小。 |

### applyForAllFragments(float fontSize) {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```


为吸收的所有文本片段应用字体大小。如果页面上的所有片段都被吸收，它比循环片段更快。否则它与循环类似。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontSize | float | 文本的字体大小。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getErrors() {#getErrors--}
```
public List<TextExtractionError> getErrors()
```


TextExtractionError 对象列表。它包含有关在文本提取期间发现的错误的信息。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；它可能会降低性能。

**退货：**
java.util.List<com.aspose.pdf.TextExtractionError> - TextExtractionError 对象列表
### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


获取文本提取选项。

**退货：**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) - TextExtractionOptions 对象
### getPhrase() {#getPhrase--}
```
public String getPhrase()
```


获取 TextFragmentAbsorber 在 PDF 文档或页面上搜索的短语。

**退货：**
java.lang.String - 字符串值

--------------------

```
The example demonstrates how to perform search text several times and perform text replacements.

 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //创建 TextFragmentAbsorber 对象以查找所有出现的“hello”文本
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");
 doc.getPages().get(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");
 //搜索另一个词并替换它
 absorber.setPhrase ( "world");
 doc.getPages().get(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "John");
 //保存文件
 doc.save("D:\\Tests\\output.pdf");
```
### getText() {#getText--}
```
public String getText()
```


获取 TextAbsorber 在 PDF 文档或页面上提取的提取文本。

**退货：**
java.lang.字符串
### getTextEditOptions() {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```


获取文本编辑选项。这些选项定义了请求的符号不能用字体书写时的特殊行为。

**退货：**
[TextEditOptions](../../com.aspose.pdf/texteditoptions) - 文本编辑选项对象
### getTextFragments() {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```


获取与 TextFragment 对象一起出现的搜索事件的集合。

**退货：**
[TextFragmentCollection](../../com.aspose.pdf/textfragmentcollection) TextFragmentCollection 对象

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace all search occurrences
 with new text.

 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //查找将用于更改文档文本字体的字体
 Font font = FontRepository.findFont("Arial");
 //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 //接受第一页的吸收器
 doc.getPages().get(1).accept(absorber);
 //更改所有搜索事件的文本
 for (TextFragment textFragment : ```
(Iterable)
```absorber.getTextFragments())
 {
     textFragment.setText ( "hi world");
 }
 //保存文件
 doc.save("D:\\Tests\\output.pdf");
```
### getTextReplaceOptions() {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```


获取文本替换选项。这些选项定义了将片段文本替换为更短/更长时的行为。

**退货：**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) TextReplaceOptions 值
### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


获取搜索选项。这些选项允许使用正则表达式进行搜索。

**退货：**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - TextSearchOptions 对象

--------------------

```
The example demonstrates how to perform search text using regular expression.

 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //创建 TextFragmentAbsorber 对象
 TextFragmentAbsorber absorber = new TextFragmentAbsorber();
 //让吸收器使用正则表达式搜索以“h”开头和以“o”结尾的所有单词。
 absorber.setPhrase ( "h\w*?o");
 absorber.setTextSearchOptions ( new TextSearchOptions(true));
 //我们应该找到“你好”这个词并将其替换为“嗨”
 doc.getPages().get(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");
 //保存文件
 doc.save("D:\\Tests\\output.pdf");
```
### hasErrors() {#hasErrors--}
```
public boolean hasErrors()
```


值指示在文本提取期间是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；它可能会降低性能。

**退货：**
boolean - 布尔值
### hasErrors_Fragment() {#hasErrors-Fragment--}
```
public boolean hasErrors_Fragment()
```


值指示在文本提取期间是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；它可能会降低性能。

**退货：**
boolean - 布尔值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAllText(Document document) {#removeAllText-com.aspose.pdf.Document-}
```
public void removeAllText(Document document)
```


从文档中删除所有文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | PDF 文档对象。 |

### removeAllText(Page page) {#removeAllText-com.aspose.pdf.Page-}
```
public void removeAllText(Page page)
```


从指定页面中删除所有文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | PDF 文档页面对象。 |

### removeAllText(Page page, Rectangle rect) {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public final void removeAllText(Page page, Rectangle rect)
```


从指定页面移除指定矩形内的文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | PDF 文档页面对象。 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | [Rectangle](../../com.aspose.pdf/rectangle)删除里面的文字。 |

### reset() {#reset--}
```
public void reset()
```


清除此 TextFragmentAbsorber 对象的 TextFragments 集合。

### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions(TextExtractionOptions value)
```


设置文本提取选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | TextExtractionOptions 对象 |

### setPhrase(String value) {#setPhrase-java.lang.String-}
```
public void setPhrase(String value)
```


设置 TextFragmentAbsorber 在 PDF 文档或页面上搜索的短语。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值

--------------------

```
The example demonstrates how to perform search text several times and perform text replacements.

              //打开文档
              Document doc = new Document("D:\\Tests\\input.pdf");
              //创建 TextFragmentAbsorber 对象以查找所有出现的“hello”文本
              TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");
              doc.getPages().get(1).accept(absorber);
              absorber.getTextFragments().get_Item(1).setText ( "Hi");
              //搜索另一个词并替换它
              absorber.setPhrase ( "world");
              doc.getPages().get(1).accept(absorber);
              absorber.getTextFragments().get_Item(1).setText ( "John");
              //保存文件
              doc.save("D:\\Tests\\output.pdf");
``` |

### setTextEditOptions(TextEditOptions value) {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
```
public void setTextEditOptions（TextEditOptions 值）
```


Sets text edit options. The options define special behavior when requested symbol cannot be written with font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | TextEditOptions object |

### setTextFragments(TextFragmentCollection value) {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
```
public void setTextFragments（TextFragmentCollection 值）
```


Sets collection of search occurrences that are presented with  TextFragment  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragmentCollection](../../com.aspose.pdf/textfragmentcollection) | TextFragmentCollection object

--------------------

```
该示例演示如何在第一个 PDF 文档页面上查找文本并替换所有搜索
              出现新文本。

              // Open document
              Document doc = new Document("D:\\Tests\\input.pdf");
              // Find font that will be used to change document text font
              Font font = FontRepository.findFont("Arial");
              // Create TextFragmentAbsorber object to find all "hello world" text occurrences
              TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
              // Accept the absorber for first page
              doc.getPages().get(1).accept(absorber);
              // Change text of all search occurrences
              for (TextFragment textFragment : ```
（可迭代）
```absorber.getTextFragments())
              {
                  textFragment.setText ( "hi world");
              }
              //保存文件
              doc.save("D:\\Tests\\output.pdf");
``` |

### setTextReplaceOptions(TextReplaceOptions value) {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
```
public void setTextReplaceOptions（TextReplaceOptions 值）
```


Sets text replace options. The options define behavior when fragment text is replaced to more short/long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) | TextReplaceOptions value |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions（TextSearchOptions 值）
```


Sets search options. The options enable search using regular expressions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | TextSearchOptions object

--------------------

```
该示例演示了如何使用正则表达式执行搜索文本。

              // Open document
              Document doc = new Document("D:\\Tests\\input.pdf");
              // Create TextFragmentAbsorber object
              TextFragmentAbsorber absorber = new TextFragmentAbsorber();
              // make the absorber to search all words starting 'h' and ending 'o' using regular expression.
              absorber.setPhrase ( "h\w*?o");
              absorber.setTextSearchOptions ( new TextSearchOptions(true));
              // we should find "hello" word and replace it with "Hi"
              doc.getPages().get(1).accept(absorber);
              absorber.getTextFragments().get_Item(1).setText ( "Hi");
              // Save document
              doc.save("D:\\Tests\\output.pdf");
``` |

### toString() {#toString--}
```
公共字符串 toString()
```




**Returns:**
java.lang.String
### visit(IDocument pdf) {#visit-com.aspose.pdf.IDocument-}
```
public void visit(IDocument pdf)
```


Performs search on the specified document.

--------------------

```
该示例演示了如何在 PDF 文档中查找文本并替换所有搜索事件的文本。

 // 打开文档
 文档 doc = 新文档("D:\\测试\\输入.pdf");
 // 查找将用于更改文档文本字体的字体
 Font font = FontRepository.findFont("宋体");
 // 创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
 TextFragmentAbsorber 吸收器 = new TextFragmentAbsorber("hello world");
 // 接受第一页的吸收器
 吸收器.访问（文档）；
 // 更改第一个文本出现的文本
 absorber.getTextFragments().get_Item(1).setText("hi world");
 // 保存文件
 doc.save("D:\\测试\\输出.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) | PDF document object. |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void 访问(Page page)
```


Performs search on the specified page.

--------------------

```
该示例演示了如何在第一个 PDF 文档页面上查找文本并替换文本。

 // 打开文档
 文档 doc = 新文档("D:\\测试\\输入.pdf");
 // 查找将用于更改文档文本字体的字体
 Font font = FontRepository.findFont("宋体");
 // 创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
 TextFragmentAbsorber 吸收器 = new TextFragmentAbsorber("hello world");
 // 接受第一页的吸收器
 absorber.visit(doc.getPages().get(1));
 // 更改所有搜索事件的文本
 对于（文本片段文本片段：```
（可迭代）
```absorber.getTextFragments())
 {
     textFragment.setText ( "hi world");
 }
 //保存文件
 doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | PDF 文档页面对象。 |

### visit(XForm xForm) {#visit-com.aspose.pdf.XForm-}
```
public void visit(XForm xForm)
```


对指定的表单对象执行搜索。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xForm | [XForm](../../com.aspose.pdf/xform) | PDF 表单对象。 |

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
