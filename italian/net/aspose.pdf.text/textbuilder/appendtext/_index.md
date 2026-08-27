---
title: "TextBuilder.AppendText"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo TextBuilder. Aggiunge il frammento di testo alla pagina Pdf"
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
| textFragment | TextFragment | Oggetto Text fragment. |

## Esempi

L'esempio dimostra come creare un oggetto text fragment, personalizzare i suoi segmenti di testo e aggiungerlo alla pagina Pdf.

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

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
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
| textFragments | List`1 | Collezione di text fragments |

### Vedi anche

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


