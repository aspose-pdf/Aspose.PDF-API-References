---
title: "Classe StructureTypeStandard"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.LogicalStructure.StructureTypeStandard class. Représente les types de structure standard."
type: docs
weight: 6870
url: /fr/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

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
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | Renvoie une chaîne qui représente l’objet actuel. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Effectue une conversion explicite de String vers `StructureTypeStandard`. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Annotation ; PDF 1.5) Une association entre une partie du contenu de l'ILSE et une annotation PDF correspondante. Annot doit être utilisé pour toutes les annotations PDF sauf les annotations de lien et les annotations de widget. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Article) Un corps de texte relativement autonome constituant une narration ou une exposition unique. Les articles doivent être disjoints ; c’est‑à‑dire qu’ils ne doivent pas contenir d’autres articles comme éléments constituants. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Bibliography entry) Une référence identifiant la source externe d’un contenu cité. Elle peut contenir une étiquette (type de structure Lbl) en tant qu’enfant. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Block quotation) Un extrait de texte composé d’un ou plusieurs paragraphes attribués à quelqu’un d’autre que l’auteur du texte environnant. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Caption) Un court extrait de texte décrivant un tableau ou une figure. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Code) Un fragment de texte de programme informatique. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Division) Un élément générique de niveau bloc ou un groupe d’éléments. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Document) Un document complet. C’est l’élément racine de tout arbre de structure contenant plusieurs parties ou plusieurs articles. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figure) Un élément de contenu graphique. Son placement peut être spécifié avec l’attribut de mise en page Placement. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Form) Une annotation de widget représentant un champ de formulaire interactif. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Formula) Une formule mathématique. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Heading) Une étiquette pour une sous‑division du contenu d’un document. Elle doit être le premier enfant de la division qu’elle introduit. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Titre de niveau 1, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Titre de niveau 2, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Titre de niveau 3, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Titre de niveau 4, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Titre de niveau 5, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Titre de niveau 6, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Index) Une séquence d’entrées contenant du texte d’identification accompagné d’éléments de référence qui indiquent les occurrences du texte spécifié dans le corps principal d’un document. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (List) Une séquence d’éléments de même signification et importance. Ses enfants immédiats doivent être une légende facultative (type de structure Caption) suivie d’un ou plusieurs éléments de liste (type de structure LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Label) Un nom ou un numéro qui distingue un élément donné des autres dans la même liste ou dans un autre groupe d’éléments similaires. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (List body) Le contenu descriptif d’un élément de liste. Dans une liste de dictionnaire, par exemple, il contient la définition du terme. Il peut contenir le contenu directement ou avoir d’autres BLSE, éventuellement incluant des listes imbriquées, comme enfants. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (List item) Un membre individuel d’une liste. Ses enfants peuvent être une ou plusieurs étiquettes, des corps de liste, ou les deux (types de structure Lbl ou LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Link) Une association entre une partie du contenu de l'ILSE et une annotation de lien ou des annotations de lien correspondantes. Ses enfants doivent être un ou plusieurs éléments de contenu ou ILSE enfants et un ou plusieurs références d’objet identifiant les annotations de lien associées. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Nonstructural element) Un élément de regroupement n’ayant aucune signification structurelle inhérente ; il sert uniquement à des fins de regroupement. Ce type d’élément diffère d’une division (type de structure Div) en ce qu’il ne doit pas être interprété ou exporté vers d’autres formats de document ; cependant, ses descendants doivent être traités normalement. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Note) Un élément de texte explicatif, tel qu’une note de bas de page ou une note de fin, qui est référencé depuis le corps du document. Il peut avoir une étiquette (type de structure Lbl) comme enfant. La note peut être incluse comme enfant de l'élément de structure dans le texte principal qui s’y réfère, ou elle peut être incluse ailleurs (par exemple dans une section de notes de fin) et accessible par le biais d’une référence (type de structure Reference). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Paragraph) Une division de texte de bas niveau. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Part) Une division à grande échelle d’un document. Ce type d’élément convient pour regrouper des articles ou des sections. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Private element) Un élément de regroupement contenant du contenu privé appartenant à l’application qui le produit. La signification structurelle de ce type d’élément n’est pas spécifiée et doit être déterminée entièrement par l’auteur conforme. Ni l’élément Private ni aucun de ses descendants ne doivent être interprétés ou exportés vers d’autres formats de document. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Quotation) Une portion de texte en ligne attribuée à quelqu’un d’autre que l’auteur du texte environnant. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Ruby base text) Le texte en taille normale auquel l’annotation ruby est appliquée. RB peut contenir du texte, d’autres éléments en ligne, ou un mélange des deux. Il peut posséder l’attribut RubyAlignattribute. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Reference) Une citation vers un contenu situé ailleurs dans le document. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Ruby punctuation) Ponctuation entourant le texte de l’annotation ruby. Elle n’est utilisée que lorsqu’une annotation ruby ne peut pas être correctement formatée dans un style ruby et est alors formatée comme un commentaire normal, ou lorsqu’elle est formatée comme un warichu. Elle contient du texte (généralement une simple PARENTHÈSE GAUCHE ou DROITE ou un caractère de délimitation similaire). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Ruby annotation text) Le texte de plus petite taille qui doit être placé à côté du texte de base ruby. Il peut contenir du texte, d’autres éléments en ligne, ou un mélange des deux. Il peut posséder les attributs RubyAlign et RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) Une note marginale (annotation) écrite en taille de texte plus petite et placée à côté du texte de base auquel elle se réfère. Un élément Ruby peut également contenir les éléments RB, RT et RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Section) Un conteneur pour regrouper des éléments de contenu liés. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) Une portion de texte en ligne générique n’ayant aucune caractéristique inhérente particulière. Elle peut être utilisée, par exemple, pour délimiter une plage de texte avec un ensemble donné d’attributs de style. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Table) Une disposition bidimensionnelle de cellules de données rectangulaires, pouvant présenter une sous‑structure complexe. Elle contient soit une ou plusieurs lignes de tableau (type de structure TR) comme enfants ; soit un en‑tête de tableau optionnel (type de structure THead) suivi d’une ou plusieurs éléments de corps de tableau (type de structure TBody) et d’un pied de tableau optionnel (type de structure TFoot). De plus, un tableau peut avoir une légende (type de structure Caption) comme premier ou dernier enfant. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Table body row group; PDF 1.5) Un groupe de lignes qui constitue la partie principale du corps d’un tableau. Si le tableau est réparti sur plusieurs pages, la zone du corps peut être découpée à la limite d’une ligne. Un tableau peut comporter plusieurs éléments TBody afin de permettre le dessin d’une bordure ou d’un arrière‑plan pour un ensemble de lignes. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Table data cell) Une cellule de tableau contenant des données qui font partie du contenu du tableau. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Table footer row group; PDF 1.5) Un groupe de lignes qui constitue le pied de page d’un tableau. Si le tableau est réparti sur plusieurs pages, ces lignes peuvent être redessinées en bas de chaque fragment de tableau (bien qu’il n’y ait qu’un seul élément TFoot). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Table header cell) Une cellule de tableau contenant du texte d’en‑tête décrivant une ou plusieurs lignes ou colonnes du tableau. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Table header row group; PDF 1.5) Un groupe de lignes qui constitue l’en‑tête d’un tableau. Si le tableau est réparti sur plusieurs pages, ces lignes peuvent être redessinées en haut de chaque fragment de tableau (bien qu’il n’y ait qu’un seul élément THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Table of contents) Une liste composée d’entrées d’éléments de table des matières (type de structure TOCI) et/ou d’autres entrées de table des matières imbriquées (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Table of contents item) Un membre individuel d’une table des matières. Les enfants de cette entrée peuvent être n’importe lequel des types de structure suivants : |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Table row) Une ligne d’en-têtes ou de données dans un tableau. Elle peut contenir des cellules d’en-tête de tableau et des cellules de données de tableau (types de structure TH et TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu ; PDF 1.5) Un commentaire ou une annotation en taille de texte plus petite et formaté sur deux lignes plus petites à l’intérieur de la hauteur de la ligne de texte contenant, placé suivant (en ligne) le texte de base auquel il se réfère. Un élément Warichu peut également contenir les éléments WT et WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Warichu punctuation) La ponctuation qui entoure le texte WT. Elle contient du texte (généralement une seule PARENTHÈSE GAUCHE ou DROITE ou un caractère de délimitation similaire). Selon la norme JIS X 4051-1995, les parenthèses entourant un warichu peuvent être converties en ESPACE (nominalement 1/4 EM de largeur) à la discrétion du formatteur. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Warichu text) Le texte de taille plus petite d’un commentaire warichu qui est formaté en deux lignes et placé entre les éléments WP environnants. |

### Voir aussi

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


