---
title: Visit
second_title: Référence de l'API Aspose.PDF pour .NET
description: Extrait les tables sur la page spécifiée
type: docs
weight: 70
url: /fr/net/aspose.pdf.text/tableabsorber/visit/
---
## TableAbsorber.Visit method

Extrait les tables sur la page spécifiée

```csharp
public virtual void Visit(Page page)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| page | Page | Objet de page de document PDF. |

### Exemples

L'exemple montre comment extraire un tableau sur la première page du document PDF.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Crée un objet TableAbsorber pour trouver des tables
TableAbsorber absorber = new TableAbsorber();

// Visiter la première page avec absorbeur
absorber.Visit(pdfDocument.Pages[1]);

// Accéder au premier tableau de la page, sa première cellule et ses fragments de texte
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change le texte du premier fragment de texte dans la cellule
fragment.Text = "hi world";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir également

* class [Page](../../../aspose.pdf/page)
* class [TableAbsorber](../../tableabsorber)
* espace de noms [Aspose.Pdf.Text](../../tableabsorber)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->