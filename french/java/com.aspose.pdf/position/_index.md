---
title: "Position"
linktitle: "Position"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un objet position"
type: docs
weight: 3940
url: /fr/java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

Représente un objet position

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Position](#Position-double-double-) | Initialise une nouvelle instance de la classe {@code Position} |

## Méthodes

| Méthode | Description |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Détermine si l'objet spécifié est égal à l'objet {@code Position} actuel. |
| [getXIndent](#getXIndent--) | Obtient la coordonnée X de l'objet |
| [getYIndent](#getYIndent--) | Obtient la coordonnée Y de l'objet |
| [hashCode](#hashCode--) | Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit renvoyer de manière cohérente le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Cela est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [setXIndent](#setXIndent-double-) | Définit la coordonnée X de l'objet |
| [setYIndent](#setYIndent-double-) | Définit la coordonnée Y de l'objet |
| [toString](#toString--) | Obtient la représentation sous forme de chaîne de l'objet {@code Position} actuel. |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

Initialise une nouvelle instance de la classe {@code Position}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xIndent |  | Valeur de la coordonnée X. |
| yIndent |  | Valeur de la coordonnée Y. |

### equals {#equals-java.lang.Object-}
Détermine si l'objet spécifié est égal à l'objet {@code Position} actuel.

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Obtient la coordonnée X de l'objet

**Returns:**
valeur double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Obtient la coordonnée Y de l'objet

**Returns:**
valeur double

### hashCode {#hashCode--}
```
public int hashCode()
```

Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit renvoyer de manière cohérente le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Cela est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
une valeur de code de hachage pour cet objet. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Définit la coordonnée X de l'objet

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Définit la coordonnée Y de l'objet

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### toString {#toString--}
```
public String toString()
```

Obtient la représentation sous forme de chaîne de l'objet {@code Position} actuel.

**Returns:**
Représentation sous forme de chaîne de l'objet Position.
