---
title: TextSegment
second_title: Référence de l'API Aspose.PDF pour .NET
description: Crée un objet TextSegment.
type: docs
weight: 10
url: /fr/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Crée un objet TextSegment.

```csharp
public TextSegment()
```

### Exemples

L'exemple montre comment créer un objet fragment de texte, ajouter un segment de texte à la collection de fragments de texte et l'ajouter à la page Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// crée un fragment de texte
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// définit ses propriétés de texte
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// ajoute un segment supplémentaire à la collection Segments du fragment de texte
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// crée un objet TextBuilder
TextBuilder builder = new TextBuilder(page);

// ajoute le fragment de texte à la page Pdf
builder.AppendText(tf);

//sauvegarder le document
doc.Save(outFile);
```

### Voir également

* class [TextSegment](../../textsegment)
* espace de noms [Aspose.Pdf.Text](../../textsegment)
* Assemblée [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Crée un objet TextSegment.

```csharp
public TextSegment(string text)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| text | String | Texte du segment de texte. |

### Exemples

L'exemple montre comment créer un objet fragment de texte, ajouter un segment de texte à la collection de fragments de texte et l'ajouter à la page Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// crée un fragment de texte
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// définit ses propriétés de texte
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// ajoute un segment supplémentaire à la collection Segments du fragment de texte
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// crée un objet TextBuilder
TextBuilder builder = new TextBuilder(page);

// ajoute le fragment de texte à la page Pdf
builder.AppendText(tf);

//sauvegarder le document
doc.Save(outFile);
```

### Voir également

* class [TextSegment](../../textsegment)
* espace de noms [Aspose.Pdf.Text](../../textsegment)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
