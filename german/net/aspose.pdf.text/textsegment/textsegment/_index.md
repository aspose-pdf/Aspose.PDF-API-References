---
title: TextSegment
second_title: Aspose.PDF für .NET-API-Referenz
description: Erstellt ein TextSegment-Objekt.
type: docs
weight: 10
url: /de/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Erstellt ein TextSegment-Objekt.

```csharp
public TextSegment()
```

### Beispiele

Das Beispiel zeigt, wie man ein Textfragmentobjekt erstellt, ein Textsegment zur Textfragmentsammlung hinzufügt und es an die PDF-Seite anhängt.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// Textfragment erstellen
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// seine Texteigenschaften festlegen
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// ein weiteres Segment zur Segments-Sammlung des Textfragments hinzufügen
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// TextBuilder-Objekt erstellen
TextBuilder builder = new TextBuilder(page);

// Textfragment an die PDF-Seite anhängen
builder.AppendText(tf);

// Dokument speichern
doc.Save(outFile);
```

### Siehe auch

* class [TextSegment](../../textsegment)
* namensraum [Aspose.Pdf.Text](../../textsegment)
* Montage [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Erstellt ein TextSegment-Objekt.

```csharp
public TextSegment(string text)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | String | Text des Textsegments. |

### Beispiele

Das Beispiel zeigt, wie man ein Textfragmentobjekt erstellt, ein Textsegment zur Textfragmentsammlung hinzufügt und es an die PDF-Seite anhängt.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// Textfragment erstellen
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// seine Texteigenschaften festlegen
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// ein weiteres Segment zur Segments-Sammlung des Textfragments hinzufügen
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// TextBuilder-Objekt erstellen
TextBuilder builder = new TextBuilder(page);

// Textfragment an die PDF-Seite anhängen
builder.AppendText(tf);

// Dokument speichern
doc.Save(outFile);
```

### Siehe auch

* class [TextSegment](../../textsegment)
* namensraum [Aspose.Pdf.Text](../../textsegment)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->