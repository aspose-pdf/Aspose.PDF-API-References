---
title: TextSegment
second_title: Aspose.PDF för .NET API Referens
description: Skapar TextSegment-objekt.
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Skapar TextSegment-objekt.

```csharp
public TextSegment()
```

### Exempel

Exemplet visar hur man skapar textfragmentobjekt, lägger till ett textsegment till textfragmentsamlingen och lägger till det på Pdf-sidan.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// skapa textfragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// ställ in dess textegenskaper
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// lägg till ett segment till i textfragmentets segmentsamling
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// skapa TextBuilder-objekt
TextBuilder builder = new TextBuilder(page);

// lägg till textfragmentet till Pdf-sidan
builder.AppendText(tf);

//spara dokument
doc.Save(outFile);
```

### Se även

* class [TextSegment](../../textsegment)
* namnutrymme [Aspose.Pdf.Text](../../textsegment)
* hopsättning [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Skapar TextSegment-objekt.

```csharp
public TextSegment(string text)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | String | Textsegmentets text. |

### Exempel

Exemplet visar hur man skapar textfragmentobjekt, lägger till ett textsegment till textfragmentsamlingen och lägger till det på Pdf-sidan.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// skapa textfragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// ställ in dess textegenskaper
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// lägg till ett segment till i textfragmentets segmentsamling
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// skapa TextBuilder-objekt
TextBuilder builder = new TextBuilder(page);

// lägg till textfragmentet till Pdf-sidan
builder.AppendText(tf);

//spara dokument
doc.Save(outFile);
```

### Se även

* class [TextSegment](../../textsegment)
* namnutrymme [Aspose.Pdf.Text](../../textsegment)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->