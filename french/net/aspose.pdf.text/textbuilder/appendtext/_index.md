---
title: AppendText
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ajoute un fragment de texte à la page PDF
type: docs
weight: 30
url: /fr/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Ajoute un fragment de texte à la page PDF

```csharp
public void AppendText(TextFragment textFragment)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| textFragment | TextFragment | Objet fragment de texte. |

### Exemples

L'exemple montre comment créer un objet fragment de texte, personnaliser ses segments de texte et l'ajouter à la page Pdf.

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

* class [TextFragment](../../textfragment)
* class [TextBuilder](../../textbuilder)
* espace de noms [Aspose.Pdf.Text](../../textbuilder)
* Assemblée [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Ajoute la liste des fragments de texte à la page Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| textFragments | List`1 | Collection de fragments de texte |

### Voir également

* class [TextFragment](../../textfragment)
* class [TextBuilder](../../textbuilder)
* espace de noms [Aspose.Pdf.Text](../../textbuilder)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
