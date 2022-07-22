---
title: TableTRElement
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente lélément de structure TR dans la structure logique de la table.
type: docs
weight: 4680
url: /fr/net/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement class

Représente l'élément de structure TR dans la structure logique de la table.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Obtient ou définit le texte réel de l'élément de structure. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Obtient ou définit le texte alternatif pour l'élément de structure. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | ObtientStructureAttributeCollection objet. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor) { get; set; } | Obtient ou définit la couleur d'arrière-plan de la ligne. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border) { get; set; } | Obtient ou définit la bordure de ligne. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Obtient la collection enfants deElement objets. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | ObtientAttributeOwnerStandard objet. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder) { get; set; } | Obtient la bordure de cellule par défaut. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding) { get; set; } | Obtient ou définit la marge par défaut pour les cellules de ligne. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate) { get; set; } | Obtient ou définit l'état du texte par défaut pour les cellules de ligne |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Obtient ou définit le texte d'expansion pour l'élément de structure. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight) { get; set; } | Obtient une hauteur de ligne fixe - la ligne peut avoir une hauteur fixe. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Obtient l'ID de l'élément de structure. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage) { get; set; } | Obtient la ligne fixe dans une nouvelle page - la page avec cette propriété doit être imprimée sur la page suivante Par défaut false. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken) { get; set; } | Obtient que la ligne peut être fractionnée entre deux pages. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Obtient ou définit la langue de l'élément de structure. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight) { get; set; } | Obtient la hauteur de la ligne. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Obtenir l'élément parent. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Obtient le type d'élément de structure. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Obtient ou définit le titre de l'élément de structure. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment) { get; set; } | Obtient ou définit l'alignement vertical. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | AjouterElement à la collecte des enfants. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Modifier l'élément parent pour l'élément de structure actuel |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Effacer l'ID de l'élément de structure. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd)() | Crée[`TableTHElement`](../tablethelement) et l'a ajouté à la table actuelle. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth)() | Crée[`TableTHElement`](../tablethelement) et l'a ajouté à la table actuelle. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Rechercher des éléments d'un type donné |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Générer un ID pour l'élément de structure. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Définit l'ID de l'élément de structure. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Définit une balise personnalisée pour l'élément de structure. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir également

* class [TableChildElement](../tablechildelement)
* espace de noms [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
