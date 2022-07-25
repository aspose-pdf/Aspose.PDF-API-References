---
title: StructureTypeStandard
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente les types de structure standard.
type: docs
weight: 4560
url: /fr/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

Représente les types de structure standard.

```csharp
public sealed class StructureTypeStandard
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category) { get; } | Obtient la catégorie du type de structure standard. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag) { get; } | Obtient le nom de la balise de[`StructureElement`](../structureelement) . |

## Méthodes

| Nom | La description |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit) | Effectue une conversion explicite à partirString à[`StructureTypeStandard`](../structuretypestandard) . |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot) | (Annotation ; PDF 1.5) Une association entre une partie du contenu de l'ILSE et une annotation PDF correspondante. Annot doit être utilisé pour toutes les annotations PDF, à l'exception des annotations de lien et des annotations de widget. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art) | (Article) Un corps de texte relativement autonome constituant un récit ou une exposition unique. Les articles doivent être disjoints ; c'est-à-dire qu'ils ne doivent pas contenir d'autres articles en tant qu'éléments constitutifs. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry) | (Entrée bibliographique) Référence identifiant la source externe d'un contenu cité. Il peut contenir une étiquette (type de structure Lbl) en tant qu'enfant. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote) | (Citation en bloc) Une portion de texte composée d'un ou plusieurs paragraphes attribués à quelqu'un d'autre que l'auteur du texte environnant. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption) | (Légende) Brève portion de texte décrivant un tableau ou une figure. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code) | (Code) Un fragment de texte de programme informatique. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div) | (Division) Un élément générique de niveau bloc ou un groupe d'éléments. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document) | (Document) Un document complet. Il s'agit de l'élément racine de tout arbre de structure contenant plusieurs parties ou plusieurs articles. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure) | (Figure) Un élément de contenu graphique. Son placement peut être spécifié avec l'attribut de mise en page Placement. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form) | (Formulaire) Une annotation de widget représentant un champ de formulaire interactif. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula) | (Formule) Une formule mathématique. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h) | (Titre) Une étiquette pour une subdivision du contenu d'un document. Il devrait être le premier enfant de la division qu'il dirige. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1) | Titre de niveau 1, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2) | Titre de niveau 2, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3) | Titre de niveau 3, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4) | Titre de niveau 4, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5) | Titre de niveau 5, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6) | Titre de niveau 6, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index) | (Index) Une séquence d'entrées contenant un texte d'identification accompagné d'éléments de référence qui indiquent les occurrences du texte spécifié dans le corps principal d'un document. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l) | (Liste) Une séquence d'éléments de même signification et importance. Ses enfants immédiats doivent être une légende facultative (type de structure Légende) suivie d'un ou plusieurs éléments de liste (type de structure LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl) | (Étiquette) Un nom ou un numéro qui distingue un élément donné des autres dans la même liste ou un autre groupe d'éléments similaires. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody) | (Corps de la liste) Le contenu descriptif d'un élément de la liste. Dans une liste de dictionnaires, par exemple, il contient la définition du terme. Il peut soit contenir le contenu directement, soit avoir d'autres BLSE, y compris peut-être des listes imbriquées, comme enfants. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li) | (élément de liste) Un membre individuel d'une liste. Ses enfants peuvent être une ou plusieurs étiquettes, des corps de liste ou les deux (types de structure Lbl ou LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link) | (Lien) Une association entre une partie du contenu de l'ILSE et une ou des annotations de lien correspondantes. Ses enfants doivent être un ou plusieurs éléments de contenu ou ILSE enfants et une ou plusieurs références d'objet identifiant les annotations de lien associées. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct) | (Élément non structurel) Un élément de regroupement n'ayant aucune signification structurelle inhérente ; il sert uniquement à des fins de regroupement. Ce type d'élément diffère d'une division (type de structure Div) en ce qu'il ne doit pas être interprété ou exporté vers d'autres formats de document ; cependant, ses descendants seront traités normalement. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note) | (Remarque) Elément de texte explicatif, tel qu'une note de bas de page ou une note de fin, auquel il est fait référence dans le corps du document. Il peut avoir une étiquette (type de structure Lbl) en tant qu'enfant. La note peut être incluse en tant qu'enfant de l'élément de structure dans le corps du texte qui y fait référence, ou elle peut être incluse ailleurs (comme dans une section de notes de fin) et accessible au moyen d'une référence (type de structure Référence). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p) | (Paragraphe) Une division de texte de bas niveau. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part) | (Part) Division à grande échelle d'un document. Ce type d'élément est approprié pour regrouper des articles ou des rubriques. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private) | (Élément privé) Un élément de regroupement contenant un contenu privé appartenant à l'application qui le produit. La signification structurelle de ce type d'élément n'est pas spécifiée et doit être entièrement déterminée par l'auteur conforme. Ni l'élément Private ni aucun de ses descendants ne doivent être interprétés ou exportés vers d'autres formats de document. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote) | (Citation) Une portion de texte en ligne attribuée à quelqu'un d'autre que l'auteur du texte environnant. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb) | (Texte de base Ruby) Le texte en taille réelle auquel l'annotation ruby est appliquée. RB peut contenir du texte, d'autres éléments en ligne ou un mélange des deux. Il peut avoir l'attribut RubyAlign. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference) | (Référence) Une citation du contenu ailleurs dans le document. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp) | (ponctuation rubis) Ponctuation entourant le texte d'annotation rubis. Il est utilisé uniquement lorsqu'une annotation ruby ne peut pas être correctement formatée dans un style ruby et est plutôt formatée comme un commentaire normal, ou lorsqu'elle est formatée comme un warichu. Il contient du texte (généralement une seule PARENTHÈSE GAUCHE ou DROITE ou un caractère entre parenthèses similaire). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt) | (texte d'annotation Ruby) Le texte de plus petite taille qui doit être placé à côté du texte de base ruby. Il peut contenir du texte, d'autres éléments en ligne ou un mélange des deux. Il peut avoir les attributs RubyAlign et RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby) | (Ruby ; PDF 1.5) Une note latérale (annotation) écrite dans une taille de texte plus petite et placée à côté du texte de base auquel elle se réfère. Un élément Ruby peut également contenir les éléments RB, RT et RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect) | (Section) Un conteneur pour regrouper les éléments de contenu associés. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span) | (Span) Une portion de texte en ligne générique n'ayant aucune caractéristique inhérente particulière. Il peut être utilisé, par exemple, pour délimiter une plage de texte avec un ensemble donné d'attributs de style. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table) | (Table) Une disposition bidimensionnelle de cellules de données rectangulaires, ayant éventuellement une sous-structure complexe. Il contient une ou plusieurs lignes de table (type de structure TR) en tant qu'enfants ; ou un en-tête de tableau facultatif (type de structure THead) suivi d'un ou plusieurs éléments de corps de tableau (type de structure TBody) et d'un pied de tableau facultatif (type de structure TFoot). De plus, un tableau peut avoir une légende (type de structure Légende) comme premier ou dernier enfant. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody) | (Groupe de lignes du corps du tableau ; PDF 1.5) Groupe de lignes constituant la partie principale du corps d'un tableau. Si le tableau est réparti sur plusieurs pages, la zone du corps peut être divisée sur une limite de ligne. Un tableau peut avoir plusieurs éléments TBody pour permettre le dessin d'une bordure ou d'un arrière-plan pour un ensemble de lignes. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td) | (Cellule de données de tableau) Une cellule de tableau contenant des données faisant partie du contenu du tableau. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot) | (Groupe de lignes de pied de tableau ; PDF 1.5) Groupe de lignes constituant le pied de page d'un tableau. Si le tableau est réparti sur plusieurs pages, ces lignes peuvent être redessinées au bas de chaque fragment de tableau (bien qu'il n'y ait qu'un seul élément TFoot.) |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th) | (Cellule d'en-tête de tableau) Une cellule de tableau contenant un texte d'en-tête décrivant une ou plusieurs lignes ou colonnes du tableau. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead) | (Groupe de lignes d'en-tête de tableau ; PDF 1.5) Groupe de lignes constituant l'en-tête d'un tableau. Si le tableau est réparti sur plusieurs pages, ces lignes peuvent être redessinées en haut de chaque fragment de tableau (bien qu'il n'y ait qu'un seul élément THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc) | (Table des matières) Liste composée d'entrées d'éléments de table des matières (type de structure TOCI) et/ou d'autres entrées de table des matières imbriquées (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci) | (élément de la table des matières) Membre individuel d'une table des matières. Les enfants de cette entrée peuvent être l'un des types de structure suivants : |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr) | (ligne de tableau) Une ligne d'en-têtes ou de données dans un tableau. Il peut contenir des cellules d'en-tête de tableau et des cellules de données de tableau (types de structure TH et TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu) | (Warichu; PDF 1.5) Un commentaire ou une annotation dans une taille de texte plus petite et formaté sur deux lignes plus petites dans la hauteur de la ligne de texte contenante et placé après (en ligne) le texte de base auquel il se réfère. Un élément Warichu peut également contenir les éléments WT et WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp) | (ponctuation Warichu) La ponctuation qui entoure le texte WT. Il contient du texte (généralement une seule PARENTHÈSE GAUCHE ou DROITE ou un caractère entre parenthèses similaire). Selon JIS X 4051-1995, les parenthèses entourant un warichu peuvent être converties en ESPACE (nominalement 1/4 EM de largeur) à la discrétion du formateur. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt) | (texte Warichu) Le texte de plus petite taille d'un commentaire warichu qui est formaté en deux lignes et placé entre les éléments WP environnants. |

### Voir également

* espace de noms [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
