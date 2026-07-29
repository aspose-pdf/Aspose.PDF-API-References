---
title: "TextSegment.TextSegment"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextSegment 构造函数。创建 TextSegment 对象"
type: docs
weight: 10
url: /zh/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

创建 TextSegment 对象。

```csharp
public TextSegment()
```

## 示例

示例演示如何创建文本片段对象，将文本段添加到文本片段集合中，并将其附加到 Pdf 页面。

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// 创建文本片段
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// 设置其文本属性
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// 向文本片段的 Segments 集合添加另一个段
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// 创建 TextBuilder 对象
TextBuilder builder = new TextBuilder(page);

// 将文本片段追加到 Pdf 页面
builder.AppendText(tf);

//保存文档
doc.Save(outFile);
```

### 另请参见

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

创建 TextSegment 对象。

```csharp
public TextSegment(string text)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | String | 文本段的文本。 |

## 示例

示例演示如何创建文本片段对象，将文本段添加到文本片段集合中，并将其附加到 Pdf 页面。

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// 创建文本片段
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// 设置其文本属性
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// 向文本片段的 Segments 集合添加另一个段
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// 创建 TextBuilder 对象
TextBuilder builder = new TextBuilder(page);

// 将文本片段追加到 Pdf 页面
builder.AppendText(tf);

//保存文档
doc.Save(outFile);
```

### 另请参见

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


