---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Construtor de TextSegment. Cria objeto TextSegment
type: docs
weight: 10
url: /pt/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Cria objeto TextSegment.

```csharp
public TextSegment()
```

## Exemplos

O exemplo demonstra como criar um objeto fragmento de texto, adicionar um segmento de texto à coleção de fragmentos de texto e anexá-lo à página do Pdf.

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

* classe [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Cria objeto TextSegment.

```csharp
public TextSegment(string text)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | String | Texto do segmento de texto. |

## Exemplos

O exemplo demonstra como criar um objeto fragmento de texto, adicionar um segmento de texto à coleção de fragmentos de texto e anexá-lo à página do Pdf.

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

### Veja Também

* classe [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)