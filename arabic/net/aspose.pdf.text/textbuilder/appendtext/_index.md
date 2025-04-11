---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: طريقة TextBuilder. تضيف جزء نصي إلى صفحة Pdf
type: docs
weight: 30
url: /ar/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

تضيف جزء نصي إلى صفحة Pdf

```csharp
public void AppendText(TextFragment textFragment)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textFragment | TextFragment | كائن جزء النص. |

## Examples

توضح هذه المثال كيفية إنشاء كائن جزء نصي، وتخصيص مقاطع النص الخاصة به وإضافته إلى صفحة Pdf.

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

### See Also

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

تضيف قائمة من أجزاء النص إلى صفحة Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textFragments | List`1 | مجموعة من أجزاء النص |

### See Also

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)