---
title: "com.aspose.pdf.vector"
linktitle: "com.aspose.pdf.vector"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le namespace Aspose.Pdf.Vector est un espace de noms racine pour les opérations graphiques."
type: docs
weight: 390
url: /fr/java/com.aspose.pdf.vector/
---
Le namespace Aspose.Pdf.Vector est un espace de noms racine pour les opérations graphiques.

## Classes

| Classe | Description |
| --- | --- |
| [GraphicElement](./graphicelement/) | Représente la classe de base pour l'objet graphique sur la page. |
| [GraphicElementCollection](./graphicelementcollection/) | Représente la collection {@link GraphicElement}. |
| [GraphicsAbsorber](./graphicsabsorber/) | Représente un objet absorbeur d'éléments graphiques. Effectue la recherche graphique et fournit l'accès aux résultats de recherche via la collection {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}). |
| [GraphicState](./graphicstate/) | Représente l'état graphique du {@link GraphicElement} actuel. |
| [InternalHelper](./internalhelper/) |  |
| [SubPath](./subpath/) | Représente un objet graphique vectoriel sur la page. En principe, les objets graphiques vectoriels sont représentés par deux groupes de SubPaths. L'un d'eux est représenté par un ensemble de lignes et de courbes. Les autres sont présentés sous forme de rectangles et peuvent parfois prêter à confusion. Habituellement, il s'agit d'une zone rectangulaire qui possède une couleur, mais très souvent ce rectangle est placé au début de la page et définit tout l'espace de la page en blanc. Ainsi vous obtenez le SubPath, mais visuellement vous ne voyez que le texte sur la page. |
| [XFormPlacement](./xformplacement/) | Représente le placement XForm. Si le XForm est affiché sur la page plus d'une fois, tous les XformPlacements associés à ce XForm partageront les mêmes éléments graphiques, mais auront des états graphiques différents. |
