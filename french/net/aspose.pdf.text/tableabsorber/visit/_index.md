---
title: "TableAbsorber.Visit"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode TableAbsorber. Extrait les tables de la page spécifiée"
type: docs
weight: 70
url: /fr/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Extrait les tables de la page spécifiée

```csharp
public virtual void Visit(Page page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | Objet de page de document PDF. |

## Exemples

L'exemple montre comment extraire une table sur la première page du document PDF.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créez un objet TableAbsorber pour trouver des tables
TableAbsorber absorber = new TableAbsorber();

// Visitez la première page avec l'absorbeur
absorber.Visit(doc.Pages[1]);

// Obtenez l'accès à la première table de la page, à sa première cellule et aux fragments de texte qu'elle contient
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Modifiez le texte du premier fragment de texte dans la cellule
fragment.Text = "hi world";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extrait les tables du document spécifié.

```csharp
public void Visit(Document pdf)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pdf | Document | Objet Pdf pocument. |

## Exemples

L'exemple montre comment extraire une table sur la première page du document PDF.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créez un objet TableAbsorber pour trouver des tables
TableAbsorber absorber = new TableAbsorber();

// Visitez la première page avec l'absorbeur
absorber.Visit(doc);

// Obtenez l'accès à la première table de la page, à sa première cellule et aux fragments de texte qu'elle contient
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Modifiez le texte du premier fragment de texte dans la cellule
fragment.Text = "hi world";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


