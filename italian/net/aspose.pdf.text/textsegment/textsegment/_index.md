---
title: "TextSegment.TextSegment"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Costruttore TextSegment. Crea un oggetto TextSegment"
type: docs
weight: 10
url: /it/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Crea l'oggetto TextSegment.

```csharp
public TextSegment()
```

## Esempi

L'esempio dimostra come creare un oggetto frammento di testo, aggiungere un segmento di testo alla collezione di frammenti di testo e aggiungerlo alla pagina Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// crea text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// imposta le proprietà di testo
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// aggiungi un altro segmento alla collezione Segments del text fragment
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// crea oggetto TextBuilder
TextBuilder builder = new TextBuilder(page);

// aggiungi il text fragment alla pagina Pdf
builder.AppendText(tf);

//salva il Document
doc.Save(outFile);
```

### Vedi anche

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Crea l'oggetto TextSegment.

```csharp
public TextSegment(string text)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | String | Testo del segmento di testo. |

## Esempi

L'esempio dimostra come creare un oggetto frammento di testo, aggiungere un segmento di testo alla collezione di frammenti di testo e aggiungerlo alla pagina Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// crea text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// imposta le proprietà di testo
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// aggiungi un altro segmento alla collezione Segments del text fragment
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// crea oggetto TextBuilder
TextBuilder builder = new TextBuilder(page);

// aggiungi il text fragment alla pagina Pdf
builder.AppendText(tf);

//salva il Document
doc.Save(outFile);
```

### Vedi anche

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


