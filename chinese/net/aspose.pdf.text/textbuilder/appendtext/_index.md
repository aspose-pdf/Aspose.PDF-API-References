---
title: "TextBuilder.AppendText"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextBuilder 方法。将文本片段追加到 Pdf 页面。"
type: docs
weight: 30
url: /zh/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

将文本片段追加到 Pdf 页面

```csharp
public void AppendText(TextFragment textFragment)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textFragment | TextFragment | 文本片段对象。 |

## 示例

示例演示了如何创建文本片段对象、定制其文本段并将其追加到 Pdf 页面。

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

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

将文本片段列表追加到 Pdf 页面。

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textFragments | List`1 | 文本片段的集合 |

### 另请参见

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


