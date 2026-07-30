---
title: "TextFragmentAbsorber.Visit"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode TextFragmentAbsorber. Effectue une recherche sur la page spécifiée"
type: docs
weight: 150
url: /fr/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Effectue une recherche sur la page spécifiée.

```csharp
public override void Visit(Page page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | Objet de page de document PDF. |

## Exemples

L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouver la police qui sera utilisée pour modifier la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
absorber.Visit(doc.Pages[1]);

// Modifier le texte de toutes les occurrences de recherche
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Effectue une recherche sur le document spécifié.

```csharp
public override void Visit(Document pdf)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pdf | Document | Objet de document PDF. |

## Exemples

L'exemple montre comment trouver du texte dans un document PDF et remplacer le texte de toutes les occurrences de recherche.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouver la police qui sera utilisée pour modifier la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
absorber.Visit(doc);

// Modifier le texte de la première occurrence de texte
absorber.TextFragments[1].Text = "hi world";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Effectue une recherche sur l'objet de formulaire spécifié.

```csharp
public void Visit(XForm xForm)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| xForm | XForm | Objet de formulaire Pdf. |

### Voir aussi

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


