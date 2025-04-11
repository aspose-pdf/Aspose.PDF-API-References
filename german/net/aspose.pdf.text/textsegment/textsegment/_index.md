---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: TextSegment-Konstruktor. Erstellt ein TextSegment-Objekt
type: docs
weight: 10
url: /de/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Erstellt ein TextSegment-Objekt.

```csharp
public TextSegment()
```

## Beispiele

Das Beispiel zeigt, wie man ein Textfragment-Objekt erstellt, ein Textsegment zur Textfragment-Sammlung hinzufügt und es zur Pdf-Seite anfügt.

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

### Siehe auch

* Klasse [TextSegment](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Erstellt ein TextSegment-Objekt.

```csharp
public TextSegment(string text)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | String | Text des Textsegments. |

## Beispiele

Das Beispiel zeigt, wie man ein Textfragment-Objekt erstellt, ein Textsegment zur Textfragment-Sammlung hinzufügt und es zur Pdf-Seite anfügt.

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

### Siehe auch

* Klasse [TextSegment](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)