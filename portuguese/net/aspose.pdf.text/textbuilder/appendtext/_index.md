---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: Método TextBuilder. Anexa fragmento de texto à página Pdf
type: docs
weight: 30
url: /pt/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Anexa fragmento de texto à página Pdf

```csharp
public void AppendText(TextFragment textFragment)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| textFragment | TextFragment | Objeto de fragmento de texto. |

## Exemplos

O exemplo demonstra como criar um objeto de fragmento de texto, personalizar seus segmentos de texto e anexá-lo à página Pdf.

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

### Veja Também

* classe [TextFragment](../../textfragment/)
* classe [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Anexa lista de fragmentos de texto à página Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| textFragments | List`1 | Coleção de fragmentos de texto |

### Veja Também

* classe [TextFragment](../../textfragment/)
* classe [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)