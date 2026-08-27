---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe conteneur pour les éléments graphiques."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

Représente une classe conteneur pour les éléments graphiques.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | Instancie une classe de conteneur pour les éléments graphiques. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | Instancie une classe de conteneur pour les éléments graphiques. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | Instancie une classe de conteneur pour les éléments graphiques. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | Instancie une classe de conteneur pour les éléments graphiques. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | Instancie une classe de conteneur pour les éléments graphiques. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | Calcule la distance entre deux conteneurs. |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Compare l'objet SubPathContainer actuel avec un autre objet SubPathContainer et renvoie un entier qui indique si l'objet actuel est inférieur, égal ou supérieur à l'autre objet. Les objets sont comparés par leur ID numérique. |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Calcule la distance entre ce conteneur et un autre conteneur. |
| [getGraphElement](#getGraphElement--) | Obtient l'élément graphique contenu. |
| [getId](#getId--) | Obtient l'Id du SubPathContainer. L'Id est requis pour faciliter le débogage et le tri des éléments lors du rendu. |
| [getRect](#getRect--) | Représente un rectangle de l'élément contenu. |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

Instancie une classe de conteneur pour les éléments graphiques.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
Instancie une classe de conteneur pour les éléments graphiques.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
Instancie une classe de conteneur pour les éléments graphiques.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
Instancie une classe de conteneur pour les éléments graphiques.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
Instancie une classe de conteneur pour les éléments graphiques.

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
Calcule la distance entre deux conteneurs.

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Compare l'objet SubPathContainer actuel avec un autre objet SubPathContainer et renvoie un entier qui indique si l'objet actuel est inférieur, égal ou supérieur à l'autre objet. Les objets sont comparés par leur ID numérique.

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Calcule la distance entre ce conteneur et un autre conteneur.

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

Obtient l'élément graphique contenu.

**Returns:**
instance de GraphicElement

### getId {#getId--}
```
public final int getId()
```

Obtient l'Id du SubPathContainer. L'Id est requis pour faciliter le débogage et le tri des éléments lors du rendu.

**Returns:**
valeur int

### getRect {#getRect--}
```
public final Rectangle getRect()
```

Représente un rectangle de l'élément contenu.

**Returns:**
Instance de Rectangle

### toString {#toString--}
```
public String toString()
```

{@code }
