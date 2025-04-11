---
title: Class StructureTypeStandard
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.StructureTypeStandard. Représente les types de structure standard
type: docs
weight: 6730
url: /fr/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## Classe StructureTypeStandard

Représente les types de structure standard.

```csharp
public sealed class StructureTypeStandard
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | Obtient la catégorie du type de structure standard. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | Obtient le nom de balise de [`StructureElement`](../structureelement/). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | Renvoie une chaîne qui représente l'objet actuel. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Effectue une conversion explicite de String à `StructureTypeStandard`. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Annotation; PDF 1.5) Une association entre une partie du contenu de l'ILSE et une annotation PDF correspondante. Annot doit être utilisé pour toutes les annotations PDF sauf les annotations de lien et les annotations de widget. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Article) Un corps de texte relativement autonome constituant un récit ou une exposition unique. Les articles doivent être disjoints ; c'est-à-dire qu'ils ne doivent pas contenir d'autres articles comme éléments constitutifs. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Entrée de bibliographie) Une référence identifiant la source externe de certains contenus cités. Elle peut contenir une étiquette (type de structure Lbl) comme enfant. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Citation en bloc) Une portion de texte composée d'un ou plusieurs paragraphes attribués à quelqu'un d'autre que l'auteur du texte environnant. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Légende) Une brève portion de texte décrivant un tableau ou une figure. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Code) Un fragment de texte de programme informatique. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Division) Un élément ou groupe d'éléments de niveau bloc générique. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Document) Un document complet. C'est l'élément racine de tout arbre de structure contenant plusieurs parties ou plusieurs articles. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figure) Un élément de contenu graphique. Son placement peut être spécifié avec l'attribut de mise en page Placement. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Formulaire) Une annotation de widget représentant un champ de formulaire interactif. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Formule) Une formule mathématique. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Titre) Une étiquette pour une subdivision du contenu d'un document. Elle doit être le premier enfant de la division qu'elle dirige. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Titre de niveau 1, à utiliser dans des rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Titre de niveau 2, à utiliser dans des rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Titre de niveau 3, à utiliser dans des rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Titre de niveau 4, à utiliser dans des rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Titre de niveau 5, à utiliser dans des rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Titre de niveau 6, à utiliser dans des rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Index) Une séquence d'entrées contenant du texte identifiant accompagné d'éléments de référence qui indiquent les occurrences du texte spécifié dans le corps principal d'un document. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (Liste) Une séquence d'éléments de même signification et importance. Ses enfants immédiats doivent être une légende optionnelle (type de structure Caption) suivie d'un ou plusieurs éléments de liste (type de structure LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Étiquette) Un nom ou un numéro qui distingue un élément donné des autres dans la même liste ou autre groupe d'éléments similaires. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (Corps de liste) Le contenu descriptif d'un élément de liste. Dans une liste de dictionnaire, par exemple, il contient la définition du terme. Il peut contenir le contenu directement ou avoir d'autres BLSEs, peut-être y compris des listes imbriquées, comme enfants. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (Élément de liste) Un membre individuel d'une liste. Ses enfants peuvent être une ou plusieurs étiquettes, corps de liste, ou les deux (types de structure Lbl ou LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Lien) Une association entre une portion du contenu de l'ILSE et une annotation ou des annotations de lien correspondantes. Ses enfants doivent être un ou plusieurs éléments de contenu ou ILSEs enfants et une ou plusieurs références d'objet identifiant les annotations de lien associées. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Élément non structurel) Un élément de regroupement n'ayant aucune signification structurelle inhérente ; il sert uniquement à des fins de regroupement. Ce type d'élément diffère d'une division (type de structure Div) en ce qu'il ne doit pas être interprété ou exporté vers d'autres formats de document ; cependant, ses descendants doivent être traités normalement. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Note) Un élément de texte explicatif, tel qu'une note de bas de page ou une note de fin, qui est référencé depuis le corps du document. Il peut avoir une étiquette (type de structure Lbl) comme enfant. La note peut être incluse comme enfant de l'élément de structure dans le texte du corps qui y fait référence, ou elle peut être incluse ailleurs (comme dans une section de notes de fin) et accessible par le biais d'une référence (type de structure Reference). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Paragraphe) Une division de texte de bas niveau. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Partie) Une division à grande échelle d'un document. Ce type d'élément est approprié pour regrouper des articles ou des sections. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Élément privé) Un élément de regroupement contenant du contenu privé appartenant à l'application qui le produit. La signification structurelle de ce type d'élément est non spécifiée et doit être déterminée entièrement par le rédacteur conforme. Ni l'élément privé ni aucun de ses descendants ne doivent être interprétés ou exportés vers d'autres formats de document. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Citation) Une portion de texte en ligne attribuée à quelqu'un d'autre que l'auteur du texte environnant. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Texte de base Ruby) Le texte de taille normale auquel l'annotation ruby est appliquée. RB peut contenir du texte, d'autres éléments en ligne, ou un mélange des deux. Il peut avoir l'attribut RubyAlign. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Référence) Une citation à un contenu ailleurs dans le document. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Ponctuation Ruby) Ponctuation entourant le texte de l'annotation ruby. Elle est utilisée uniquement lorsqu'une annotation ruby ne peut pas être correctement formatée dans un style ruby et est plutôt formatée comme un commentaire normal, ou lorsqu'elle est formatée comme un warichu. Elle contient du texte (généralement une seule parenthèse GAUCHE ou DROITE ou un caractère de délimitation similaire). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Texte d'annotation Ruby) Le texte de taille réduite qui doit être placé à côté du texte de base ruby. Il peut contenir du texte, d'autres éléments en ligne, ou un mélange des deux. Il peut avoir les attributs RubyAlign et RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) Une note de côté (annotation) écrite dans une taille de texte plus petite et placée à côté du texte de base auquel elle se réfère. Un élément Ruby peut également contenir les éléments RB, RT et RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Section) Un conteneur pour regrouper des éléments de contenu connexes. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) Une portion de texte en ligne générique n'ayant pas de caractéristiques inhérentes particulières. Elle peut être utilisée, par exemple, pour délimiter une plage de texte avec un ensemble donné d'attributs de style. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Table) Une disposition bidimensionnelle de cellules de données rectangulaires, pouvant avoir une sous-structure complexe. Elle contient soit une ou plusieurs lignes de tableau (type de structure TR) comme enfants ; soit une tête de tableau optionnelle (type de structure THead) suivie d'un ou plusieurs éléments de corps de tableau (type de structure TBody) et d'un pied de tableau optionnel (type de structure TFoot). De plus, une table peut avoir une légende (type de structure Caption) comme premier ou dernier enfant. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Groupe de lignes de corps de tableau ; PDF 1.5) Un groupe de lignes qui constitue la partie principale d'un tableau. Si le tableau est divisé sur plusieurs pages, la zone de corps peut être séparée à une limite de ligne. Un tableau peut avoir plusieurs éléments TBody pour permettre le dessin d'une bordure ou d'un arrière-plan pour un ensemble de lignes. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Cellule de données de tableau) Une cellule de tableau contenant des données qui font partie du contenu du tableau. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Groupe de lignes de pied de tableau ; PDF 1.5) Un groupe de lignes qui constitue le pied d'un tableau. Si le tableau est divisé sur plusieurs pages, ces lignes peuvent être redessinées au bas de chaque fragment de tableau (bien qu'il n'y ait qu'un seul élément TFoot). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Cellule d'en-tête de tableau) Une cellule de tableau contenant du texte d'en-tête décrivant une ou plusieurs lignes ou colonnes du tableau. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Groupe de lignes d'en-tête de tableau ; PDF 1.5) Un groupe de lignes qui constitue l'en-tête d'un tableau. Si le tableau est divisé sur plusieurs pages, ces lignes peuvent être redessinées en haut de chaque fragment de tableau (bien qu'il n'y ait qu'un seul élément THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Table des matières) Une liste composée d'entrées d'éléments de table des matières (type de structure TOCI) et/ou d'autres entrées de table des matières imbriquées (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Élément de table des matières) Un membre individuel d'une table des matières. Les enfants de cette entrée peuvent être n'importe lequel des types de structure suivants : |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Ligne de tableau) Une ligne d'en-têtes ou de données dans un tableau. Elle peut contenir des cellules d'en-tête de tableau et des cellules de données de tableau (types de structure TH et TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) Un commentaire ou une annotation dans une taille de texte plus petite et formaté sur deux lignes plus petites dans la hauteur de la ligne de texte contenant et placé après (en ligne) le texte de base auquel il se réfère. Un élément Warichu peut également contenir les éléments WT et WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Ponctuation Warichu) La ponctuation qui entoure le texte WT. Elle contient du texte (généralement une seule parenthèse GAUCHE ou DROITE ou un caractère de délimitation similaire). Selon JIS X 4051-1995, les parenthèses entourant un warichu peuvent être converties en un ESPACE (nominalement 1/4 EM de largeur) à la discrétion du formateur. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Texte Warichu) Le texte de taille réduite d'un commentaire warichu qui est formaté en deux lignes et placé entre les éléments WP environnants. |

### Voir aussi

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)