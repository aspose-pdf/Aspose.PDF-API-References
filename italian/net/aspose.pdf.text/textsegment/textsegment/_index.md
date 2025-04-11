---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Costruttore TextSegment. Crea un oggetto TextSegment
type: docs
weight: 10
url: /it/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Crea un oggetto TextSegment.

```csharp
public TextSegment()
```

## Esempi

L'esempio dimostra come creare un oggetto frammento di testo, aggiungere un segmento di testo alla collezione di frammenti di testo e aggiungerlo alla pagina Pdf.

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

### Vedi Anche

* classe [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Crea un oggetto TextSegment.

```csharp
public TextSegment(string text)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | String | Testo del segmento di testo. |

## Esempi

L'esempio dimostra come creare un oggetto frammento di testo, aggiungere un segmento di testo alla collezione di frammenti di testo e aggiungerlo alla pagina Pdf.

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

### Vedi Anche

* classe [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)