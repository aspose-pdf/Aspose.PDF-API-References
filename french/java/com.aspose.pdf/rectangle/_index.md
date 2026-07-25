---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant un rectangle."
type: docs
weight: 4100
url: /fr/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

Classe représentant un rectangle.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Constructeur de Rectangle. |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Constructeur de Rectangle. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | Intersecte des rectangles. Méthode obsolète. Veuillez utiliser Intersect à la place. |
| [center](#center--) | Renvoie les coordonnées du centre du rectangle. |
| [clone](#clone--) | Clone l'objet Rectangle. |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | Détermine si le point donné est à l'intérieur du rectangle. |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | Détermine si le point donné est à l'intérieur du rectangle. |
| [containsLine](#containsLine-double-double-double-double-) | Détermine si le rectangle contient une ligne représentée par deux points. |
| [containsPoint](#containsPoint-double-double-) | Détermine si le point donné est contenu dans le rectangle. |
| [deepClone](#deepClone--) | Clone l'objet Rectangle. |
| [equals](#equals-java.lang.Object-) | Vérifie si les rectangles sont égaux, c.-à-d. ont la même position et les mêmes dimensions. |
| [fromRect](#fromRect-java.awt.Rectangle-) | Initialise un nouveau rectangle à partir de l'instance donnée de System.Drawing.Rectangle. |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | Initialise un nouveau rectangle à partir de l'instance donnée de System.Drawing.Rectangle. |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | Calcule la surface du rectangle. |
| [getEmpty](#getEmpty--) | Obtient le rectangle vide |
| [getHeight](#getHeight--) | Obtient la hauteur du rectangle. |
| [getLLX](#getLLX--) | Obtient la coordonnée X du coin inférieur gauche. |
| [getLLY](#getLLY--) | Obtient la coordonnée Y du coin inférieur gauche. |
| [getTrivial](#getTrivial--) | Initialise un rectangle trivial, c.-à-d. un rectangle avec une position et une taille nulles. |
| [getURX](#getURX--) | Obtient la coordonnée X du coin supérieur droit. |
| [getURY](#getURY--) | Obtient la coordonnée Y du coin supérieur droit. |
| [getWidth](#getWidth--) | Obtient la largeur du rectangle. |
| [hashCode](#hashCode--) | Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit renvoyer de manière cohérente le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Cela est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | Intersecte deux rectangles. |
| [isEmpty](#isEmpty--) | Vérifie si le rectangle est vide. |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | Vérifie que ce rectangle inclut entièrement un autre rectangle. C.-à-d. l'autre rectangle est entièrement à l'intérieur de ce rectangle. La différence avec la méthode IsIntersect est que IsIntersect sera vraie pour des rectangles partiellement intersectés, alors que IsInclude sera fausse. |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | Détermine si ce rectangle intersecte un autre rectangle. |
| [isPoint](#isPoint--) | Vérifie si le rectangle est un point c.-à-d. LLX est égal à URX et LLY est égal à URY. |
| [isTrivial](#isTrivial--) | Vérifie si le rectangle est trivial c.-à-d. a une taille et une position nulles. |
| [join](#join-com.aspose.pdf.Rectangle-) | Joint les rectangles. |
| [moveBy](#moveBy-double-double-) | Décale le rectangle des deltas spécifiés. |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | Vérifie si les rectangles sont presque égaux c.-à-d. ont une position et des tailles presque identiques (jusqu'à delta). |
| [parse](#parse-java.lang.String-) | Essaye d'analyser la chaîne et d'en extraire les composants du rectangle llx, lly, urx, ury. |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | Fait pivoter le rectangle de l'angle spécifié. |
| [rotateAngle](#rotateAngle-int-) | Fait pivoter le rectangle de l'angle spécifié. |
| [setLLX](#setLLX-double-) | Définit la coordonnée X du coin inférieur gauche. |
| [setLLY](#setLLY-double-) | Définit la coordonnée Y du coin inférieur gauche. |
| [setURX](#setURX-double-) | Définit la coordonnée X du coin supérieur droit. |
| [setURY](#setURY-double-) | Définit la coordonnée Y du coin supérieur droit. |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | Convertit le rectangle en tableau de points ("QuadPoints"). |
| [toRect](#toRect--) | Convertit le rectangle en instance de System.Drawing.Rectangle. Les positions et la taille en virgule flottante sont tronquées. |
| [toString](#toString--) | Obtient la représentation sous forme de chaîne du rectangle. |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Constructeur de Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| llx |  | X du coin inférieur gauche. |
| lly |  | Y du coin inférieur gauche. |
| urx |  | X du coin supérieur droit. |
| ury |  | Y du coin supérieur droit. |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Constructeur de Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| llx |  | X du coin inférieur gauche. |
| lly |  | Y du coin inférieur gauche. |
| urx |  | X du coin supérieur droit. |
| ury |  | Y du coin supérieur droit. |
| normalizeCoordinates |  | Normalise les coordonnées du rectangle. |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
Intersecte des rectangles. Méthode obsolète. Veuillez utiliser Intersect à la place.

### center {#center--}
```
public Point center()
```

Renvoie les coordonnées du centre du rectangle.

**Returns:**
Point qui est le centre du rectangle.

### clone {#clone--}
```
public Rectangle clone()
```

Clone l'objet Rectangle.

**Returns:**
Cloner l'objet.

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
Détermine si le point donné est à l'intérieur du rectangle.

### contains {#contains-com.aspose.pdf.Point-boolean-}
Détermine si le point donné est à l'intérieur du rectangle.

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

Détermine si le rectangle contient une ligne représentée par deux points.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 |  | La coordonnée X du point de départ de la ligne. |
| y1 |  | La coordonnée Y du point de départ de la ligne. |
| x2 |  | La coordonnée X du point d'arrivée de la ligne. |
| y2 |  | La coordonnée Y du point d'arrivée de la ligne. |

**Returns:**
{@code true} si le rectangle contient la ligne ; sinon, {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

Détermine si le point donné est contenu dans le rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x |  | Coordonnée X du point. |
| y |  | Coordonnée Y du point. |

**Returns:**
{@code true} si le point est contenu dans le rectangle ; sinon, {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

Clone l'objet Rectangle.

**Returns:**
Cloner l'objet.

### equals {#equals-java.lang.Object-}
Vérifie si les rectangles sont égaux, c.-à-d. ont la même position et les mêmes dimensions.

### fromRect {#fromRect-java.awt.Rectangle-}
Initialise un nouveau rectangle à partir de l'instance donnée de System.Drawing.Rectangle.

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
Initialise un nouveau rectangle à partir de l'instance donnée de System.Drawing.Rectangle.

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

Calcule la surface du rectangle.

**Returns:**
L'aire du rectangle en double, calculée en multipliant la largeur et la hauteur.

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

Obtient le rectangle vide

**Returns:**
nouvel objet Rectangle

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtient la hauteur du rectangle.

**Returns:**
valeur double

### getLLX {#getLLX--}
```
public double getLLX()
```

Obtient la coordonnée X du coin inférieur gauche.

**Returns:**
valeur double

### getLLY {#getLLY--}
```
public double getLLY()
```

Obtient la coordonnée Y du coin inférieur gauche.

**Returns:**
valeur double

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

Initialise un rectangle trivial, c.-à-d. un rectangle avec une position et une taille nulles.

**Returns:**
nouvel objet Rectangle

### getURX {#getURX--}
```
public double getURX()
```

Obtient la coordonnée X du coin supérieur droit.

**Returns:**
valeur double

### getURY {#getURY--}
```
public double getURY()
```

Obtient la coordonnée Y du coin supérieur droit.

**Returns:**
valeur double

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtient la largeur du rectangle.

**Returns:**
valeur double

### hashCode {#hashCode--}
```
public int hashCode()
```

Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit renvoyer de manière cohérente le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Cela est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
une valeur de code de hachage pour cet objet. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
Intersecte deux rectangles.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Vérifie si le rectangle est vide.

**Returns:**
valeur booléenne

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
Vérifie que ce rectangle inclut entièrement un autre rectangle. C.-à-d. l'autre rectangle est entièrement à l'intérieur de ce rectangle. La différence avec la méthode IsIntersect est que IsIntersect sera vraie pour des rectangles partiellement intersectés, alors que IsInclude sera fausse.

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
Détermine si ce rectangle intersecte un autre rectangle.

### isPoint {#isPoint--}
```
public boolean isPoint()
```

Vérifie si le rectangle est un point c.-à-d. LLX est égal à URX et LLY est égal à URY.

**Returns:**
valeur booléenne

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

Vérifie si le rectangle est trivial c.-à-d. a une taille et une position nulles.

**Returns:**
valeur booléenne

### join {#join-com.aspose.pdf.Rectangle-}
Joint les rectangles.

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

Décale le rectangle des deltas spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx |  | Valeur du déplacement selon l'axe X. |
| dy |  | Valeur du déplacement selon l'axe Y. |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
Vérifie si les rectangles sont presque égaux c.-à-d. ont une position et des tailles presque identiques (jusqu'à delta).

### parse {#parse-java.lang.String-}
Essaye d'analyser la chaîne et d'en extraire les composants du rectangle llx, lly, urx, ury.

### rotate {#rotate-com.aspose.pdf.Rotation-}
Fait pivoter le rectangle de l'angle spécifié.

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

Fait pivoter le rectangle de l'angle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle |  | Angle de rotation en degrés entre 0 et 360. |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

Définit la coordonnée X du coin inférieur gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

Définit la coordonnée Y du coin inférieur gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

Définit la coordonnée X du coin supérieur droit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

Définit la coordonnée Y du coin supérieur droit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

Convertit le rectangle en tableau de points ("QuadPoints").

**Returns:**
Tableau de points.

### toRect {#toRect--}
```
public Rectangle toRect()
```

Convertit le rectangle en instance de System.Drawing.Rectangle. Les positions et la taille en virgule flottante sont tronquées.

**Returns:**
Résultat de la conversion.

### toString {#toString--}
```
public String toString()
```

Obtient la représentation sous forme de chaîne du rectangle.

**Returns:**
La chaîne a le format llx,lly,urx,ury.
