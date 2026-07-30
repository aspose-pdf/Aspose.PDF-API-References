---
title: "TextSegment.TextSegment"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Constructeur TextSegment. Crée un objet TextSegment"
type: docs
weight: 10
url: /fr/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Crée un objet TextSegment.

```csharp
public TextSegment()
```

## Exemples

L'exemple montre comment créer un objet fragment de texte, ajouter un segment de texte à la collection de fragments de texte et l'ajouter à la page Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// créer un fragment de texte
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// définir ses propriétés de texte
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// ajouter un segment supplémentaire à la collection Segments du fragment de texte
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// créer un objet TextBuilder
TextBuilder builder = new TextBuilder(page);

// ajouter le fragment de texte à la page Pdf
builder.AppendText(tf);

//enregistrez le document
doc.Save(outFile);
```

### Voir aussi

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Crée un objet TextSegment.

```csharp
public TextSegment(string text)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| texte | String | Texte du segment de texte. |

## Exemples

L'exemple montre comment créer un objet fragment de texte, ajouter un segment de texte à la collection de fragments de texte et l'ajouter à la page Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// créer un fragment de texte
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// définir ses propriétés de texte
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// ajouter un segment supplémentaire à la collection Segments du fragment de texte
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// créer un objet TextBuilder
TextBuilder builder = new TextBuilder(page);

// ajouter le fragment de texte à la page Pdf
builder.AppendText(tf);

//enregistrez le document
doc.Save(outFile);
```

### Voir aussi

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


