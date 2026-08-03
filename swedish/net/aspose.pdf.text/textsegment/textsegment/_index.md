---
title: "TextSegment.TextSegment"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextSegment-konstruktor. Skapar TextSegment-objekt"
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Skapar TextSegment‑objekt.

```csharp
public TextSegment()
```

## Exempel

Exemplet visar hur man skapar ett textfragmentobjekt, lägger till ett textsegment i textfragmentsamlingen och lägger till det på Pdf-sidan.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// skapa textfragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// ange dess textegenskaper
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// lägg till ett segment till textfragmentets Segments-samling
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// skapa TextBuilder-objekt
TextBuilder builder = new TextBuilder(page);

// lägg till textfragmentet på Pdf-sidan
builder.AppendText(tf);

//spara dokumentet
doc.Save(outFile);
```

### Se även

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Skapar TextSegment‑objekt.

```csharp
public TextSegment(string text)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | String | Textsegmentets text. |

## Exempel

Exemplet visar hur man skapar ett textfragmentobjekt, lägger till ett textsegment i textfragmentsamlingen och lägger till det på Pdf-sidan.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// skapa textfragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// ange dess textegenskaper
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// lägg till ett segment till textfragmentets Segments-samling
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// skapa TextBuilder-objekt
TextBuilder builder = new TextBuilder(page);

// lägg till textfragmentet på Pdf-sidan
builder.AppendText(tf);

//spara dokumentet
doc.Save(outFile);
```

### Se även

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


