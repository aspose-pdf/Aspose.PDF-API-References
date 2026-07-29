---
title: "StructureTypeStandard"
linktitle: "StructureTypeStandard"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les types de structure standard."
type: docs
weight: 130
url: /fr/java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard

```
public final class StructureTypeStandard extends Object
```

Représente les types de structure standard.

## Champs

| Champ | Description |
| --- | --- |
| [Annot](#Annot) | (Annotation ; PDF 1.5) Une association entre une partie du contenu de l’ILSE et une annotation PDF correspondante. Annot doit être utilisé pour toutes les annotations PDF sauf les annotations de lien et les annotations widget. |
| [Art](#Art) | (Article) Un corps de texte relativement autonome constituant une narration ou une exposition unique. Les articles doivent être disjoints ; c’est‑à‑dire qu’ils ne doivent pas contenir d’autres articles comme éléments constituants. |
| [BibEntry](#BibEntry) | (Entrée de bibliographie) Une référence identifiant la source externe d’un contenu cité. Elle peut contenir une étiquette (type de structure Lbl) comme enfant. Bien qu’une entrée de bibliographie inclue probablement des parties composantes identifiant l’auteur, l’œuvre, l’éditeur du contenu cité, etc., aucun type de structure standard n’est défini à ce niveau de détail. |
| [BlockQuote](#BlockQuote) | (Citation en bloc) Un extrait de texte composé d’un ou plusieurs paragraphes attribués à quelqu’un d’autre que l’auteur du texte environnant. |
| [Caption](#Caption) | (Légende) Un bref extrait de texte décrivant un tableau ou une figure. |
| [Code](#Code) | (Code) Un fragment de texte de programme informatique. |
| [Div](#Div) | (Division) Un élément générique de niveau bloc ou un groupe d’éléments. |
| [Document](#Document) | (Document) Un document complet. C’est l’élément racine de tout arbre de structure contenant plusieurs parties ou plusieurs articles. |
| [Figure](#Figure) | (Figure) Un élément de contenu graphique. Son placement peut être spécifié avec l’attribut de mise en page Placement. |
| [Form](#Form) | (Form) Une annotation widget représentant un champ de formulaire interactif. |
| [Formula](#Formula) | (Formula) Une formule mathématique. Ce type de structure n’est utile que pour identifier un élément de contenu entier comme une formule. Aucun type de structure standard n’est défini pour identifier les composants individuels au sein de la formule. D’un point de vue formatage, la formule doit être traitée de manière similaire à une figure (type de structure Figure). |
| [H](#H) | (Heading) Une étiquette pour une sous‑division du contenu d’un document. Elle doit être le premier enfant de la division qu’elle introduit. |
| [H1](#H1) | Titre de niveau 1, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| [H2](#H2) | Titre de niveau 2, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| [H3](#H3) | Titre de niveau 3, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| [H4](#H4) | Titre de niveau 4, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| [H5](#H5) | Titre de niveau 5, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| [H6](#H6) | Titre de niveau 6, destiné aux rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication. |
| [Index](#Index) | (Index) Une séquence d’entrées contenant du texte d’identification accompagné d’éléments de référence qui indiquent les occurrences du texte spécifié dans le corps principal d’un document. |
| [L](#L) | (Liste) Une séquence d’éléments de même signification et importance. Ses enfants immédiats doivent être une légende facultative (type de structure Caption) suivie d’un ou plusieurs éléments de liste (type de structure LI). |
| [Lbl](#Lbl) | (Étiquette) Un nom ou un numéro qui distingue un élément donné des autres dans la même liste ou dans un autre groupe d’éléments similaires. |
| [LBody](#LBody) | (Corps de liste) Le contenu descriptif d’un élément de liste. Dans une liste de dictionnaire, par exemple, il contient la définition du terme. Il peut contenir le contenu directement ou comporter d’autres BLSE, éventuellement des listes imbriquées, en tant qu’enfants. |
| [LI](#LI) | (Élément de liste) Un membre individuel d’une liste. Ses enfants peuvent être une ou plusieurs étiquettes, corps de liste, ou les deux (types de structure Lbl ou LBody). |
| [Link](#Link) | (Lien) Une association entre une partie du contenu de l’ILSE et une annotation ou des annotations de lien correspondantes. Ses enfants doivent être un ou plusieurs éléments de contenu ou ILSE enfants ainsi qu’un ou plusieurs références d’objet identifiant les annotations de lien associées. |
| [NonStruct](#NonStruct) | (Élément non structurel) Un élément de regroupement n’ayant aucune signification structurelle inhérente ; il sert uniquement à des fins de regroupement. Ce type d’élément diffère d’une division (type de structure Div) en ce qu’il ne doit pas être interprété ou exporté vers d’autres formats de document ; cependant, ses descendants doivent être traités normalement. |
| [Note](#Note) | (Note) Un élément de texte explicatif, tel qu’une note de bas de page ou une note de fin, auquel on fait référence depuis le corps du document. Il peut avoir une étiquette (type de structure Lbl) comme enfant. La note peut être incluse comme enfant de l’élément de structure dans le texte du corps qui y fait référence, ou être placée ailleurs (par exemple dans une section de notes de fin) et accessible via une référence (type de structure Reference). Le PDF balisé ne prescrit pas le placement des notes de bas de page dans l’ordre du contenu de la page. Elles peuvent être soit en ligne, soit à la fin de la page, à la discrétion du rédacteur conforme. |
| [P](#P) | (Paragraphe) Une division de texte de bas niveau. |
| [Part](#Part) | (Partie) Une division à grande échelle d’un document. Ce type d’élément convient pour regrouper des articles ou des sections. |
| [Private](#Private) | (Élément privé) Un élément de regroupement contenant du contenu privé appartenant à l’application qui le produit. La signification structurelle de ce type d’élément n’est pas spécifiée et doit être déterminée entièrement par le rédacteur conforme. Ni l’élément Privé ni aucun de ses descendants ne doivent être interprétés ou exportés vers d’autres formats de document. |
| [Quote](#Quote) | (Citation) Une portion de texte en ligne attribuée à quelqu’un d’autre que l’auteur du texte environnant. Le texte cité doit être contenu en ligne dans un seul paragraphe. Cela diffère de l’élément de niveau bloc BlockQuote, qui se compose d’un ou plusieurs paragraphes complets (ou d’autres éléments présentés comme s’ils étaient des paragraphes complets). |
| [RB](#RB) | (Texte de base ruby) Le texte en taille normale auquel l’annotation ruby est appliquée. RB peut contenir du texte, d’autres éléments en ligne, ou un mélange des deux. Il peut posséder l’attribut RubyAlign. |
| [Reference](#Reference) | (Référence) Une citation d’un contenu situé ailleurs dans le document. |
| [RP](#RP) | (Ponctuation ruby) Ponctuation entourant le texte de l’annotation ruby. Elle n’est utilisée que lorsqu’une annotation ruby ne peut pas être correctement formatée en style ruby et est plutôt formatée comme un commentaire normal, ou lorsqu’elle est formatée comme un warichu. Elle contient du texte (généralement une seule parenthèse GAUCHE ou DROITE ou un caractère de délimitation similaire). |
| [RT](#RT) | (Texte d’annotation ruby) Le texte de plus petite taille qui doit être placé adjacent au texte de base ruby. Il peut contenir du texte, d’autres éléments en ligne, ou un mélange des deux. Il peut posséder les attributs RubyAlign et RubyPosition. |
| [Ruby](#Ruby) | (Ruby ; PDF 1.5) Une note secondaire (annotation) écrite avec une taille de texte plus petite et placée adjacente au texte de base auquel elle se réfère. Un élément Ruby peut également contenir les éléments RB, RT et RP. (Ruby) L’enveloppe autour de l’ensemble ruby complet. Elle doit contenir un élément RB suivi soit d’un élément RT, soit d’un groupe de trois éléments composé de RP, RT et RP. Les éléments Ruby et leurs éléments de contenu ne doivent pas se répartir sur plusieurs lignes. |
| [Sect](#Sect) | (Section) Un conteneur pour regrouper des éléments de contenu liés. |
| [Span](#Span) | (Span) Une portion de texte en ligne générique n’ayant aucune caractéristique inhérente particulière. Elle peut être utilisée, par exemple, pour délimiter une plage de texte avec un ensemble donné d’attributs de style. |
| [Table](#Table) | (Table) Une disposition bidimensionnelle de cellules de données rectangulaires, pouvant avoir une sous‑structure complexe. Elle contient soit une ou plusieurs lignes de tableau (type de structure TR) comme enfants ; soit un en‑tête de tableau optionnel (type de structure THead) suivi d’une ou plusieurs éléments de corps de tableau (type de structure TBody) et d’un pied de tableau optionnel (type de structure TFoot). De plus, un tableau peut avoir une légende (type de structure Caption) comme premier ou dernier enfant. |
| [TBody](#TBody) | (Table body row group ; PDF 1.5) Un groupe de lignes qui constitue la partie principale du corps d’un tableau. Si le tableau est réparti sur plusieurs pages, la zone du corps peut être découpée à la limite d’une ligne. Un tableau peut contenir plusieurs éléments TBody afin de permettre le dessin d’une bordure ou d’un arrière‑plan pour un ensemble de lignes. |
| [TD](#TD) | (Table data cell) Une cellule de tableau contenant des données faisant partie du contenu du tableau. |
| [TFoot](#TFoot) | (Table footer row group ; PDF 1.5) Un groupe de lignes qui constitue le pied de page d’un tableau. Si le tableau est réparti sur plusieurs pages, ces lignes peuvent être redessinées en bas de chaque fragment de tableau (bien qu’il n’y ait qu’un seul élément TFoot). |
| [TH](#TH) | (Table header cell) Une cellule de tableau contenant du texte d’en‑tête décrivant une ou plusieurs lignes ou colonnes du tableau. |
| [THead](#THead) | (Table header row group ; PDF 1.5) Un groupe de lignes qui constitue l’en‑tête d’un tableau. Si le tableau est réparti sur plusieurs pages, ces lignes peuvent être redessinées en haut de chaque fragment de tableau (bien qu’il n’y ait qu’un seul élément THead). |
| [TOC](#TOC) | (Table of contents) Une liste composée d’entrées d’éléments de table des matières (type de structure TOCI) et/ou d’autres entrées de table des matières imbriquées (TOC). Une entrée TOC qui ne comprend que des entrées TOCI représente une hiérarchie plate. Une entrée TOC qui comprend d’autres entrées TOC imbriquées (et éventuellement des entrées TOCI) représente une hiérarchie plus complexe. Idéalement, la hiérarchie d’une entrée TOC de niveau supérieur reflète la structure du corps principal du document. |
| [TOCI](#TOCI) | (Table of contents item) Un membre individuel d’une table des matières. Les enfants de cette entrée peuvent être l’un des types de structure suivants : Lbl – Une étiquette Reference – Une référence au titre et au numéro de page NonStruct – Éléments non structurés pour envelopper un artefact de repère P – Texte descriptif TOC – Éléments de table des matières pour des tables des matières hiérarchiques, comme décrit pour l’entrée TOC |
| [TR](#TR) | (Table row) Une ligne d’en‑têtes ou de données dans un tableau. Elle peut contenir des cellules d’en‑tête de tableau et des cellules de données de tableau (types de structure TH et TD). |
| [Warichu](#Warichu) | (Warichu ; PDF 1.5) Un commentaire ou une annotation avec une taille de texte plus petite et formaté sur deux lignes plus petites à l’intérieur de la hauteur de la ligne de texte contenant, placé après (en ligne) le texte de base auquel il se réfère. Un élément Warichu peut également contenir les éléments WT et WP. (Warichu) L’enveloppe autour de l’ensemble Warichu complet. Il peut contenir un groupe de trois éléments composé de WP, WT et WP. Les éléments Warichu (et leurs éléments de contenu) peuvent s’enrouler sur plusieurs lignes, selon les règles de rupture du Warichu décrites dans la norme industrielle japonaise (JIS) X 4051‑1995. |
| [WP](#WP) | (Warichu punctuation) La ponctuation qui entoure le texte WT. Elle contient du texte (généralement une seule PARENTHÈSE GAUCHE ou DROITE ou un caractère de parenthésage similaire). Selon la JIS X 4051‑1995, les parenthèses entourant un warichu peuvent être converties en ESPACE (nominalement 1/4 EM de largeur) à la discrétion du formateur. |
| [WT](#WT) | (Warichu text) Le texte de plus petite taille d'un commentaire warichu qui est formaté en deux lignes et placé entre les éléments WP environnants. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [canBeAppended](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
| [createElement](#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [getCategory](#getCategory--) | Obtient la catégorie du type de structure standard. |
| [getTag](#getTag--) | Obtient le nom de balise de {@code StructureElement}. |
| [to_StructureTypeStandard](#to_StructureTypeStandard-java.lang.String-) | Effectue une conversion explicite de {@link String} vers {@link StructureTypeStandard}. |
| [toString](#toString--) | Renvoie une chaîne qui représente l'objet actuel. |

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```

(Annotation ; PDF 1.5) Une association entre une partie du contenu de l’ILSE et une annotation PDF correspondante. Annot doit être utilisé pour toutes les annotations PDF sauf les annotations de lien et les annotations widget.

### Art {#Art}
```
public static final StructureTypeStandard Art
```

(Article) Un corps de texte relativement autonome constituant une narration ou une exposition unique. Les articles doivent être disjoints ; c’est‑à‑dire qu’ils ne doivent pas contenir d’autres articles comme éléments constituants.

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```

(Entrée de bibliographie) Une référence identifiant la source externe d’un contenu cité. Elle peut contenir une étiquette (type de structure Lbl) comme enfant. Bien qu’une entrée de bibliographie inclue probablement des parties composantes identifiant l’auteur, l’œuvre, l’éditeur du contenu cité, etc., aucun type de structure standard n’est défini à ce niveau de détail.

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```

(Citation en bloc) Un extrait de texte composé d’un ou plusieurs paragraphes attribués à quelqu’un d’autre que l’auteur du texte environnant.

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```

(Légende) Un bref extrait de texte décrivant un tableau ou une figure.

### Code {#Code}
```
public static final StructureTypeStandard Code
```

(Code) Un fragment de texte de programme informatique.

### Div {#Div}
```
public static final StructureTypeStandard Div
```

(Division) Un élément générique de niveau bloc ou un groupe d’éléments.

### Document {#Document}
```
public static final StructureTypeStandard Document
```

(Document) Un document complet. C’est l’élément racine de tout arbre de structure contenant plusieurs parties ou plusieurs articles.

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```

(Figure) Un élément de contenu graphique. Son placement peut être spécifié avec l’attribut de mise en page Placement.

### Form {#Form}
```
public static final StructureTypeStandard Form
```

(Form) Une annotation widget représentant un champ de formulaire interactif.

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```

(Formula) Une formule mathématique. Ce type de structure n’est utile que pour identifier un élément de contenu entier comme une formule. Aucun type de structure standard n’est défini pour identifier les composants individuels au sein de la formule. D’un point de vue formatage, la formule doit être traitée de manière similaire à une figure (type de structure Figure).

### H {#H}
```
public static final StructureTypeStandard H
```

(Heading) Une étiquette pour une sous‑division du contenu d’un document. Elle doit être le premier enfant de la division qu’elle introduit.

### H1 {#H1}
```
public static final StructureTypeStandard H1
```

Titre de niveau 1, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication.

### H2 {#H2}
```
public static final StructureTypeStandard H2
```

Titre de niveau 2, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication.

### H3 {#H3}
```
public static final StructureTypeStandard H3
```

Titre de niveau 3, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication.

### H4 {#H4}
```
public static final StructureTypeStandard H4
```

Titre de niveau 4, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication.

### H5 {#H5}
```
public static final StructureTypeStandard H5
```

Titre de niveau 5, à utiliser dans les rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication.

### H6 {#H6}
```
public static final StructureTypeStandard H6
```

Titre de niveau 6, destiné aux rédacteurs conformes qui ne peuvent pas imbriquer hiérarchiquement leurs sections et ne peuvent donc pas déterminer le niveau d’un titre à partir de son niveau d’imbrication.

### Index {#Index}
```
public static final StructureTypeStandard Index
```

(Index) Une séquence d’entrées contenant du texte d’identification accompagné d’éléments de référence qui indiquent les occurrences du texte spécifié dans le corps principal d’un document.

### L {#L}
```
public static final StructureTypeStandard L
```

(Liste) Une séquence d’éléments de même signification et importance. Ses enfants immédiats doivent être une légende facultative (type de structure Caption) suivie d’un ou plusieurs éléments de liste (type de structure LI).

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```

(Étiquette) Un nom ou un numéro qui distingue un élément donné des autres dans la même liste ou dans un autre groupe d’éléments similaires.

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```

(Corps de liste) Le contenu descriptif d’un élément de liste. Dans une liste de dictionnaire, par exemple, il contient la définition du terme. Il peut contenir le contenu directement ou comporter d’autres BLSE, éventuellement des listes imbriquées, en tant qu’enfants.

### LI {#LI}
```
public static final StructureTypeStandard LI
```

(Élément de liste) Un membre individuel d’une liste. Ses enfants peuvent être une ou plusieurs étiquettes, corps de liste, ou les deux (types de structure Lbl ou LBody).

### Link {#Link}
```
public static final StructureTypeStandard Link
```

(Lien) Une association entre une partie du contenu de l’ILSE et une annotation ou des annotations de lien correspondantes. Ses enfants doivent être un ou plusieurs éléments de contenu ou ILSE enfants ainsi qu’un ou plusieurs références d’objet identifiant les annotations de lien associées.

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```

(Élément non structurel) Un élément de regroupement n’ayant aucune signification structurelle inhérente ; il sert uniquement à des fins de regroupement. Ce type d’élément diffère d’une division (type de structure Div) en ce qu’il ne doit pas être interprété ou exporté vers d’autres formats de document ; cependant, ses descendants doivent être traités normalement.

### Note {#Note}
```
public static final StructureTypeStandard Note
```

(Note) Un élément de texte explicatif, tel qu’une note de bas de page ou une note de fin, auquel on fait référence depuis le corps du document. Il peut avoir une étiquette (type de structure Lbl) comme enfant. La note peut être incluse comme enfant de l’élément de structure dans le texte du corps qui y fait référence, ou être placée ailleurs (par exemple dans une section de notes de fin) et accessible via une référence (type de structure Reference). Le PDF balisé ne prescrit pas le placement des notes de bas de page dans l’ordre du contenu de la page. Elles peuvent être soit en ligne, soit à la fin de la page, à la discrétion du rédacteur conforme.

### P {#P}
```
public static final StructureTypeStandard P
```

(Paragraphe) Une division de texte de bas niveau.

### Part {#Part}
```
public static final StructureTypeStandard Part
```

(Partie) Une division à grande échelle d’un document. Ce type d’élément convient pour regrouper des articles ou des sections.

### Private {#Private}
```
public static final StructureTypeStandard Private
```

(Élément privé) Un élément de regroupement contenant du contenu privé appartenant à l’application qui le produit. La signification structurelle de ce type d’élément n’est pas spécifiée et doit être déterminée entièrement par le rédacteur conforme. Ni l’élément Privé ni aucun de ses descendants ne doivent être interprétés ou exportés vers d’autres formats de document.

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```

(Citation) Une portion de texte en ligne attribuée à quelqu’un d’autre que l’auteur du texte environnant. Le texte cité doit être contenu en ligne dans un seul paragraphe. Cela diffère de l’élément de niveau bloc BlockQuote, qui se compose d’un ou plusieurs paragraphes complets (ou d’autres éléments présentés comme s’ils étaient des paragraphes complets).

### RB {#RB}
```
public static final StructureTypeStandard RB
```

(Texte de base ruby) Le texte en taille normale auquel l’annotation ruby est appliquée. RB peut contenir du texte, d’autres éléments en ligne, ou un mélange des deux. Il peut posséder l’attribut RubyAlign.

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```

(Référence) Une citation d’un contenu situé ailleurs dans le document.

### RP {#RP}
```
public static final StructureTypeStandard RP
```

(Ponctuation ruby) Ponctuation entourant le texte de l’annotation ruby. Elle n’est utilisée que lorsqu’une annotation ruby ne peut pas être correctement formatée en style ruby et est plutôt formatée comme un commentaire normal, ou lorsqu’elle est formatée comme un warichu. Elle contient du texte (généralement une seule parenthèse GAUCHE ou DROITE ou un caractère de délimitation similaire).

### RT {#RT}
```
public static final StructureTypeStandard RT
```

(Texte d’annotation ruby) Le texte de plus petite taille qui doit être placé adjacent au texte de base ruby. Il peut contenir du texte, d’autres éléments en ligne, ou un mélange des deux. Il peut posséder les attributs RubyAlign et RubyPosition.

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```

(Ruby ; PDF 1.5) Une note secondaire (annotation) écrite avec une taille de texte plus petite et placée adjacente au texte de base auquel elle se réfère. Un élément Ruby peut également contenir les éléments RB, RT et RP. (Ruby) L’enveloppe autour de l’ensemble ruby complet. Elle doit contenir un élément RB suivi soit d’un élément RT, soit d’un groupe de trois éléments composé de RP, RT et RP. Les éléments Ruby et leurs éléments de contenu ne doivent pas se répartir sur plusieurs lignes.

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```

(Section) Un conteneur pour regrouper des éléments de contenu liés.

### Span {#Span}
```
public static final StructureTypeStandard Span
```

(Span) Une portion de texte en ligne générique n’ayant aucune caractéristique inhérente particulière. Elle peut être utilisée, par exemple, pour délimiter une plage de texte avec un ensemble donné d’attributs de style.

### Table {#Table}
```
public static final StructureTypeStandard Table
```

(Table) Une disposition bidimensionnelle de cellules de données rectangulaires, pouvant avoir une sous‑structure complexe. Elle contient soit une ou plusieurs lignes de tableau (type de structure TR) comme enfants ; soit un en‑tête de tableau optionnel (type de structure THead) suivi d’une ou plusieurs éléments de corps de tableau (type de structure TBody) et d’un pied de tableau optionnel (type de structure TFoot). De plus, un tableau peut avoir une légende (type de structure Caption) comme premier ou dernier enfant.

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```

(Table body row group ; PDF 1.5) Un groupe de lignes qui constitue la partie principale du corps d’un tableau. Si le tableau est réparti sur plusieurs pages, la zone du corps peut être découpée à la limite d’une ligne. Un tableau peut contenir plusieurs éléments TBody afin de permettre le dessin d’une bordure ou d’un arrière‑plan pour un ensemble de lignes.

### TD {#TD}
```
public static final StructureTypeStandard TD
```

(Table data cell) Une cellule de tableau contenant des données faisant partie du contenu du tableau.

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```

(Table footer row group ; PDF 1.5) Un groupe de lignes qui constitue le pied de page d’un tableau. Si le tableau est réparti sur plusieurs pages, ces lignes peuvent être redessinées en bas de chaque fragment de tableau (bien qu’il n’y ait qu’un seul élément TFoot).

### TH {#TH}
```
public static final StructureTypeStandard TH
```

(Table header cell) Une cellule de tableau contenant du texte d’en‑tête décrivant une ou plusieurs lignes ou colonnes du tableau.

### THead {#THead}
```
public static final StructureTypeStandard THead
```

(Table header row group ; PDF 1.5) Un groupe de lignes qui constitue l’en‑tête d’un tableau. Si le tableau est réparti sur plusieurs pages, ces lignes peuvent être redessinées en haut de chaque fragment de tableau (bien qu’il n’y ait qu’un seul élément THead).

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```

(Table of contents) Une liste composée d’entrées d’éléments de table des matières (type de structure TOCI) et/ou d’autres entrées de table des matières imbriquées (TOC). Une entrée TOC qui ne comprend que des entrées TOCI représente une hiérarchie plate. Une entrée TOC qui comprend d’autres entrées TOC imbriquées (et éventuellement des entrées TOCI) représente une hiérarchie plus complexe. Idéalement, la hiérarchie d’une entrée TOC de niveau supérieur reflète la structure du corps principal du document.

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```

(Table of contents item) Un membre individuel d’une table des matières. Les enfants de cette entrée peuvent être l’un des types de structure suivants : Lbl – Une étiquette Reference – Une référence au titre et au numéro de page NonStruct – Éléments non structurés pour envelopper un artefact de repère P – Texte descriptif TOC – Éléments de table des matières pour des tables des matières hiérarchiques, comme décrit pour l’entrée TOC

### TR {#TR}
```
public static final StructureTypeStandard TR
```

(Table row) Une ligne d’en‑têtes ou de données dans un tableau. Elle peut contenir des cellules d’en‑tête de tableau et des cellules de données de tableau (types de structure TH et TD).

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```

(Warichu ; PDF 1.5) Un commentaire ou une annotation avec une taille de texte plus petite et formaté sur deux lignes plus petites à l’intérieur de la hauteur de la ligne de texte contenant, placé après (en ligne) le texte de base auquel il se réfère. Un élément Warichu peut également contenir les éléments WT et WP. (Warichu) L’enveloppe autour de l’ensemble Warichu complet. Il peut contenir un groupe de trois éléments composé de WP, WT et WP. Les éléments Warichu (et leurs éléments de contenu) peuvent s’enrouler sur plusieurs lignes, selon les règles de rupture du Warichu décrites dans la norme industrielle japonaise (JIS) X 4051‑1995.

### WP {#WP}
```
public static final StructureTypeStandard WP
```

(Warichu punctuation) La ponctuation qui entoure le texte WT. Elle contient du texte (généralement une seule PARENTHÈSE GAUCHE ou DROITE ou un caractère de parenthésage similaire). Selon la JIS X 4051‑1995, les parenthèses entourant un warichu peuvent être converties en ESPACE (nominalement 1/4 EM de largeur) à la discrétion du formateur.

### WT {#WT}
```
public static final StructureTypeStandard WT
```

(Warichu text) Le texte de plus petite taille d'un commentaire warichu qui est formaté en deux lignes et placé entre les éléments WP environnants.

### canBeAppended {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}


### createElement {#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getCategory {#getCategory--}
```
public final StructureTypeCategory getCategory()
```

Obtient la catégorie du type de structure standard.

**Returns:**
Valeur : catégorie du type de structure standard.

### getTag {#getTag--}
```
public final String getTag()
```

Obtient le nom de balise de {@code StructureElement}.

**Returns:**
Nom de balise de {@code StructureElement}.

### to_StructureTypeStandard {#to_StructureTypeStandard-java.lang.String-}
Effectue une conversion explicite de {@link String} vers {@link StructureTypeStandard}.

### toString {#toString--}
```
public String toString()
```

Renvoie une chaîne qui représente l'objet actuel.

**Returns:**
Chaîne qui représente l'objet actuel.
