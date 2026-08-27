---
title: "StructureTypeStandard"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente les types de structure standard."
type: docs
weight: 560
url: /fr/python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

Représente les types de structure standard.

Le type StructureTypeStandard expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| tag | Obtient le nom de balise de [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/). |
| category | Obtient la catégorie du type de structure standard. |
| DOCUMENT | (Document) Un document complet. C’est l’élément racine de tout arbre de structure contenant plusieurs parties ou plusieurs articles. |
| PART | (Part) Une division à grande échelle d’un document. Ce type d’élément est approprié pour regrouper des articles ou des sections. |
| ART | (Article) Un corps de texte relativement autonome constituant une narration ou une exposition unique. Les articles doivent être disjoints ; c’est‑à‑dire qu’ils ne doivent pas contenir d’autres articles comme éléments constituants. |
| SECT | (Section) Un conteneur pour regrouper des éléments de contenu liés. |
| DIV | (Division) Un élément générique de niveau bloc ou un groupe d’éléments. |
| BLOCK_QUOTE | (Block quotation) Un extrait de texte composé d’un ou plusieurs paragraphes attribué à quelqu’un d’autre que l’auteur du texte environnant. |
| CAPTION | (Caption) Un bref extrait de texte décrivant un tableau ou une figure. |
| TOC | (Table of contents) Une liste composée d’entrées d’éléments de table des matières (type de structure TOCI) et/ou d’autres entrées de table des matières imbriquées (TOC). |
| TOCI | (Table of contents item) Un membre individuel d’une table des matières. Les enfants de cette entrée peuvent être n’importe lequel des types de structure suivants : |
| INDEX | (Index) Une séquence d’entrées contenant du texte d’identification accompagné d’éléments de référence indiquant les occurrences du texte spécifié dans le corps principal d’un document. |
| NON_STRUCT | (Nonstructural element) Un élément de regroupement n’ayant aucune signification structurelle inhérente ; il sert uniquement à des fins de regroupement. Ce type d’élément diffère d’une division (type de structure Div) en ce qu’il ne doit pas être interprété ou exporté vers d’autres formats de document ; cependant, ses descendants doivent être traités normalement. |
| PRIVATE | (Private element) Un élément de regroupement contenant du contenu privé appartenant à l’application qui le produit. La signification structurelle de ce type d’élément n’est pas spécifiée et doit être déterminée entièrement par l’auteur conforme. Ni l’élément Private ni aucun de ses descendants ne doivent être interprétés ou exportés vers d’autres formats de document. |
| P | (Paragraph) Une division de texte de bas niveau. |
| H | (Heading) Une étiquette pour une subdivision du contenu d'un document. Elle doit être le premier enfant de la division qu'elle dirige. |
| H1 | Titre de niveau 1, destiné aux rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| H2 | Titre de niveau 2, destiné aux rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| H3 | Titre de niveau 3, destiné aux rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| H4 | Titre de niveau 4, destiné aux rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| H5 | Titre de niveau 5, destiné aux rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| H6 | Titre de niveau 6, destiné aux rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d'un titre à partir de son niveau d'imbrication. |
| L | (List) Une séquence d'éléments de même signification et importance. Ses enfants immédiats doivent être une légende facultative (structure type Caption) suivie d'un ou plusieurs éléments de liste (structure type LI). |
| LI | (List item) Un membre individuel d'une liste. Ses enfants peuvent être une ou plusieurs étiquettes, corps de liste, ou les deux (structure types Lbl ou LBody). |
| LBL | (Label) Un nom ou un numéro qui distingue un élément donné des autres dans la même liste ou dans un autre groupe d'éléments similaires. |
| L_BODY | (List body) Le contenu descriptif d'un élément de liste. Dans une liste de dictionnaire, par exemple, il contient la définition du terme. Il peut contenir le contenu directement ou posséder d'autres BLSEs, éventuellement incluant des listes imbriquées, comme enfants. |
| TABLE | (Table) Une disposition bidimensionnelle de cellules de données rectangulaires, pouvant avoir une sous‑structure complexe. Elle contient soit une ou plusieurs lignes de tableau (structure type TR) comme enfants ; soit un en‑tête de tableau facultatif (structure type THead) suivi d'un ou plusieurs éléments de corps de tableau (structure type TBody) et d'un pied de tableau facultatif (structure type TFoot). De plus, un tableau peut avoir une légende (structure type Caption) comme premier ou dernier enfant. |
| T_HEAD | (Table header row group; PDF 1.5) Un groupe de lignes qui constitue l'en‑tête d'un tableau. Si le tableau est réparti sur plusieurs pages, ces lignes peuvent être redessinées en haut de chaque fragment de tableau (bien qu'il n'y ait qu'un seul élément THead). |
| T_BODY | (Table body row group; PDF 1.5) Un groupe de lignes qui constitue la partie principale du corps d'un tableau. Si le tableau est réparti sur plusieurs pages, la zone du corps peut être découpée à la limite d'une ligne. Un tableau peut contenir plusieurs éléments TBody pour permettre le dessin d'une bordure ou d'un arrière‑plan pour un ensemble de lignes. |
| T_FOOT | (Table footer row group; PDF 1.5) Un groupe de lignes qui constitue le pied d'un tableau. Si le tableau est réparti sur plusieurs pages, ces lignes peuvent être redessinées en bas de chaque fragment de tableau (bien qu'il n'y ait qu'un seul élément TFoot.) |
| TR | (Table row) Une ligne d'en-têtes ou de données dans un tableau. Elle peut contenir des cellules d'en-tête de tableau et des cellules de données de tableau (types de structure TH et TD). |
| TH | (Table header cell) Une cellule de tableau contenant du texte d'en-tête décrivant une ou plusieurs lignes ou colonnes du tableau. |
| TD | (Table data cell) Une cellule de tableau contenant des données qui font partie du contenu du tableau. |
| SPAN | (Span) Une portion de texte en ligne générique n'ayant aucune caractéristique inhérente particulière. Elle peut être utilisée, par exemple, pour délimiter une plage de texte avec un ensemble donné d'attributs de style. |
| QUOTE | (Quotation) Une portion de texte en ligne attribuée à quelqu'un d'autre que l'auteur du texte environnant. |
| NOTE | (Note) Un élément de texte explicatif, tel qu'une note de bas de page ou une note de fin, auquel on fait référence depuis le corps du document. Il peut avoir une étiquette (type de structure Lbl) comme enfant. La note peut être incluse comme enfant de l'élément de structure dans le texte principal qui s'y réfère, ou bien être placée ailleurs (par exemple dans une section de notes de fin) et être accessible par le biais d'une référence (type de structure Reference). |
| REFERENCE | (Reference) Une citation d'un contenu situé ailleurs dans le document. |
| BIB_ENTRY | (Bibliography entry) Une référence identifiant la source externe d'un contenu cité. Elle peut contenir une étiquette (type de structure Lbl) comme enfant. |
| CODE | (Code) Un fragment de texte de programme informatique. |
| LINK | (Link) Une association entre une portion du contenu de l'ILSE et une annotation de lien correspondante ou des annotations de lien. Ses enfants doivent être un ou plusieurs éléments de contenu ou ILSE enfants et un ou plusieurs références d'objets identifiant les annotations de lien associées. |
| ANNOT | (Annotation; PDF 1.5) Une association entre une portion du contenu de l'ILSE et une annotation PDF correspondante. Annot doit être utilisé pour toutes les annotations PDF sauf les annotations de lien et les annotations de widget. |
| RUBY | (Ruby; PDF 1.5) Une note marginale (annotation) écrite en taille de texte plus petite et placée adjacente au texte de base auquel elle se réfère. Un élément Ruby peut également contenir les éléments RB, RT et RP. |
| RB | (Ruby base text) Le texte en taille réelle auquel l'annotation ruby est appliquée. RB peut contenir du texte, d'autres éléments en ligne, ou un mélange des deux. Il peut avoir l'attribut RubyAlignattribute. |
| RT | (Ruby annotation text) Le texte de plus petite taille qui doit être placé adjacent au texte de base ruby. Il peut contenir du texte, d'autres éléments en ligne, ou un mélange des deux. Il peut avoir les attributs RubyAlign et RubyPosition. |
| RP | (Ruby punctuation) La ponctuation entourant le texte de l'annotation ruby. Elle n'est utilisée que lorsqu'une annotation ruby ne peut pas être correctement formatée en style ruby et est plutôt formatée comme un commentaire normal, ou lorsqu'elle est formatée comme un warichu. Elle contient du texte (généralement une simple PARENTHESE GAUCHE ou DROITE ou un caractère de délimitation similaire). |
| WARICHU | (Warichu; PDF 1.5) Un commentaire ou une annotation en taille de texte plus petite et formaté sur deux lignes plus petites à l'intérieur de la hauteur de la ligne de texte contenant et placé après (en ligne) le texte de base auquel il se réfère. Un élément Warichu peut également contenir les éléments WT et WP. |
| WT | (Warichu text) Le texte de plus petite taille d'un commentaire warichu qui est formaté en deux lignes et placé entre les éléments WP environnants. |
| WP | (Warichu punctuation) La ponctuation qui entoure le texte WT. Elle contient du texte (généralement une simple PARENTHESE GAUCHE ou DROITE ou un caractère de délimitation similaire). Selon la norme JIS X 4051-1995, les parenthèses entourant un warichu peuvent être converties en un ESPACE (nominalement 1/4 EM de largeur) à la discrétion du formatteur. |
| FIGURE | (Figure) Un élément de contenu graphique. Son placement peut être spécifié avec l'attribut de mise en page Placement. |
| FORMULA | (Formula) Une formule mathématique. |
| FORM | (Form) Une annotation de widget représentant un champ de formulaire interactif. |

### Voir aussi

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

