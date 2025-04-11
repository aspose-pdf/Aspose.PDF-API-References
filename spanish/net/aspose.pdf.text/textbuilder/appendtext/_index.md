---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: Método TextBuilder. Agrega fragmento de texto a la página Pdf
type: docs
weight: 30
url: /es/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Agrega fragmento de texto a la página Pdf

```csharp
public void AppendText(TextFragment textFragment)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textFragment | TextFragment | Objeto de fragmento de texto. |

## Ejemplos

El ejemplo demuestra cómo crear un objeto de fragmento de texto, personalizar sus segmentos de texto y agregarlo a la página Pdf.

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

* clase [TextFragment](../../textfragment/)
* clase [TextBuilder](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Agrega lista de fragmentos de texto a la página Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textFragments | List`1 | Colección de fragmentos de texto |

### Ver También

* clase [TextFragment](../../textfragment/)
* clase [TextBuilder](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)