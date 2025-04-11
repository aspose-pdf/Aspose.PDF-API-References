---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder 方法。将文本片段附加到 Pdf 页面
type: docs
weight: 30
url: /zh/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

将文本片段附加到 Pdf 页面

```csharp
public void AppendText(TextFragment textFragment)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textFragment | TextFragment | 文本片段对象。 |

## 示例

该示例演示如何创建文本片段对象，自定义其文本段并将其附加到 Pdf 页面。

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// create text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// set it's text properties
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// add one more segment to text fragment's Segments collection
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### 另请参阅

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

将文本片段列表附加到 Pdf 页面。

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textFragments | List`1 | 文本片段集合 |

### 另请参阅

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)