---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: Méthode TextBuilder. Ajoute un fragment de texte à la page Pdf
type: docs
weight: 30
url: /fr/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Ajoute un fragment de texte à la page Pdf

```csharp
public void AppendText(TextFragment textFragment)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| textFragment | TextFragment | Objet fragment de texte. |

## Exemples

L'exemple démontre comment créer un objet fragment de texte, personnaliser ses segments de texte et l'ajouter à la page Pdf.

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

### Voir aussi

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Ajoute une liste de fragments de texte à la page Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| textFragments | List`1 | Collection de fragments de texte |

### Voir aussi

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)