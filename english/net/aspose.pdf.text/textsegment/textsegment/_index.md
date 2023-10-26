---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: TextSegment constructor. Creates TextSegment object
type: docs
weight: 10
url: /net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Creates TextSegment object.

```csharp
public TextSegment()
```

## Examples

The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page.

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

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Creates TextSegment object.

```csharp
public TextSegment(string text)
```

| Parameter | Type | Description |
| --- | --- | --- |
| text | String | Text segment's text. |

## Examples

The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page.

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
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### See Also

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


