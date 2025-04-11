---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Constructor de TextSegment. Crea un objeto TextSegment
type: docs
weight: 10
url: /es/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Crea un objeto TextSegment.

```csharp
public TextSegment()
```

## Ejemplos

El ejemplo demuestra cómo crear un objeto fragmento de texto, agregar un segmento de texto a la colección de fragmentos de texto y adjuntarlo a la página de Pdf.

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

### Ver También

* clase [TextSegment](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Crea un objeto TextSegment.

```csharp
public TextSegment(string text)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | String | Texto del segmento de texto. |

## Ejemplos

El ejemplo demuestra cómo crear un objeto fragmento de texto, agregar un segmento de texto a la colección de fragmentos de texto y adjuntarlo a la página de Pdf.

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

### Ver También

* clase [TextSegment](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)