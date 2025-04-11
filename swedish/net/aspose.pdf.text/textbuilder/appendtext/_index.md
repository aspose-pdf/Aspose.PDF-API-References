---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder-metod. Lägger till textfragment till Pdf-sidan
type: docs
weight: 30
url: /sv/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Lägger till textfragment till Pdf-sidan

```csharp
public void AppendText(TextFragment textFragment)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textFragment | TextFragment | Textfragmentobjekt. |

## Exempel

Exemplet visar hur man skapar ett textfragmentobjekt, anpassar dess textsegment och lägger till det på Pdf-sidan.

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

### Se Även

* klass [TextFragment](../../textfragment/)
* klass [TextBuilder](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Lägger till en lista med textfragment till Pdf-sidan.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textFragments | List`1 | Samling av textfragment |

### Se Även

* klass [TextFragment](../../textfragment/)
* klass [TextBuilder](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)