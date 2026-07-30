---
title: "TextBuilder.AppendText"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode TextBuilder. Ajoute un fragment de texte à la page Pdf"
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

L'exemple montre comment créer un objet fragment de texte, personnaliser ses segments de texte et l'ajouter à la page Pdf.

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


