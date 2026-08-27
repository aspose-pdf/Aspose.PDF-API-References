---
title: "TextBuilder.AppendText"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextBuilder-metod. Lägger till textfragment till Pdf-sida"
type: docs
weight: 30
url: /sv/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Lägger till textfragment på Pdf-sida

```csharp
public void AppendText(TextFragment textFragment)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textFragment | TextFragment | Textfragment-objekt. |

## Exempel

Exemplet visar hur man skapar ett textfragment-objekt, anpassar dess textsegment och lägger till det på Pdf-sidan.

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

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Lägger till en lista med textfragment på Pdf-sida.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textFragments | List`1 | Samling av textfragment |

### Se även

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


