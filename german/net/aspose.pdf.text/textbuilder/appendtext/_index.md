---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder-Methode. Fügt einen Textfragment zur Pdf-Seite hinzu
type: docs
weight: 30
url: /de/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Fügt ein Textfragment zur Pdf-Seite hinzu

```csharp
public void AppendText(TextFragment textFragment)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textFragment | TextFragment | Textfragment-Objekt. |

## Beispiele

Das Beispiel zeigt, wie man ein Textfragment-Objekt erstellt, seine Textsegmente anpasst und es zur Pdf-Seite hinzufügt.

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

* Klasse [TextFragment](../../textfragment/)
* Klasse [TextBuilder](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Fügt eine Liste von Textfragmenten zur Pdf-Seite hinzu.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textFragments | List`1 | Sammlung von Textfragmenten |

### Siehe auch

* Klasse [TextFragment](../../textfragment/)
* Klasse [TextBuilder](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)