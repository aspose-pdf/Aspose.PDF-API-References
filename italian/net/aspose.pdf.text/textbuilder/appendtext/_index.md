---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: Metodo TextBuilder. Aggiunge un frammento di testo alla pagina Pdf
type: docs
weight: 30
url: /it/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Aggiunge un frammento di testo alla pagina Pdf

```csharp
public void AppendText(TextFragment textFragment)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textFragment | TextFragment | Oggetto frammento di testo. |

## Esempi

L'esempio dimostra come creare un oggetto frammento di testo, personalizzare i suoi segmenti di testo e aggiungerlo alla pagina Pdf.

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

* classe [TextFragment](../../textfragment/)
* classe [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Aggiunge un elenco di frammenti di testo alla pagina Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textFragments | List`1 | Collezione di frammenti di testo |

### Vedi Anche

* classe [TextFragment](../../textfragment/)
* classe [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)