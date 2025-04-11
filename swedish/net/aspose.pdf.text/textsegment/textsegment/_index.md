---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: TextSegment-konstruktör. Skapar TextSegment-objekt
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Skapar TextSegment-objekt.

```csharp
public TextSegment()
```

## Exempel

Exemplet visar hur man skapar ett textfragmentobjekt, lägger till ett textsegment i textfragmentkollektionen och lägger till det på Pdf-sidan.

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

* klass [TextSegment](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Skapar TextSegment-objekt.

```csharp
public TextSegment(string text)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | Sträng | Textsegmentets text. |

## Exempel

Exemplet visar hur man skapar ett textfragmentobjekt, lägger till ett textsegment i textfragmentkollektionen och lägger till det på Pdf-sidan.

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

### Se Även

* klass [TextSegment](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)