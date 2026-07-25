---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Spécifie les dimensions des marges d'une page imprimée."
type: docs
weight: 70
url: /fr/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

Spécifie les dimensions des marges d'une page imprimée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | Initialise une nouvelle instance de la classe Margins avec des marges de 1 pouce de large. |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | Initialise une nouvelle instance de la classe Margins avec les marges gauche, droite, supérieure et inférieure spécifiées. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone](#deepClone--) | Récupère un duplicata de cet objet, membre par membre. |
| [equals](#equals-java.lang.Object-) | Compare ce Margins à l'Object spécifié pour déterminer s'ils ont les mêmes dimensions. (Remplace Object.Equals(Object).) |
| [getBottom](#getBottom--) | Obtient ou définit la marge inférieure, en centièmes de pouce. |
| [getLeft](#getLeft--) | Obtient ou définit la largeur de la marge gauche, en centièmes de pouce. |
| [getRight](#getRight--) | Obtient ou définit la largeur de la marge droite, en centièmes de pouce. |
| [getTop](#getTop--) | Obtient ou définit la largeur de la marge supérieure, en centièmes de pouce. |
| [hashCode](#hashCode--) | Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit renvoyer de manière cohérente le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Cela est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Compare deux Margins pour déterminer s'ils ont les mêmes dimensions. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Compare deux Margins pour déterminer s'ils ont des largeurs inégales. |
| [setBottom](#setBottom-int-) | Obtient ou définit la marge inférieure, en centièmes de pouce. |
| [setLeft](#setLeft-int-) | Obtient ou définit la largeur de la marge gauche, en centièmes de pouce. |
| [setRight](#setRight-int-) | Obtient ou définit la largeur de la marge droite, en centièmes de pouce. |
| [setTop](#setTop-int-) | Obtient ou définit la largeur de la marge supérieure, en centièmes de pouce. |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

Initialise une nouvelle instance de la classe Margins avec des marges de 1 pouce de large.

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

Initialise une nouvelle instance de la classe Margins avec les marges gauche, droite, supérieure et inférieure spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche |  | valeur int |
| droite |  | valeur int |
| haut |  | valeur int |
| bas |  | valeur int |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

Récupère un duplicata de cet objet, membre par membre.

**Returns:**
Objet PrinterMargins

### equals {#equals-java.lang.Object-}
Compare ce Margins à l'Object spécifié pour déterminer s'ils ont les mêmes dimensions. (Remplace Object.Equals(Object).)

### getBottom {#getBottom--}
```
public int getBottom()
```

Obtient ou définit la marge inférieure, en centièmes de pouce.

**Returns:**
valeur int

### getLeft {#getLeft--}
```
public int getLeft()
```

Obtient ou définit la largeur de la marge gauche, en centièmes de pouce.

**Returns:**
valeur int

### getRight {#getRight--}
```
public int getRight()
```

Obtient ou définit la largeur de la marge droite, en centièmes de pouce.

**Returns:**
valeur int

### getTop {#getTop--}
```
public int getTop()
```

Obtient ou définit la largeur de la marge supérieure, en centièmes de pouce.

**Returns:**
valeur int

### hashCode {#hashCode--}
```
public int hashCode()
```

Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit renvoyer de manière cohérente le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Cela est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
une valeur de code de hachage pour cet objet. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Compare deux Margins pour déterminer s'ils ont les mêmes dimensions.

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Compare deux Margins pour déterminer s'ils ont des largeurs inégales.

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

Obtient ou définit la marge inférieure, en centièmes de pouce.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

Obtient ou définit la largeur de la marge gauche, en centièmes de pouce.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

Obtient ou définit la largeur de la marge droite, en centièmes de pouce.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

Obtient ou définit la largeur de la marge supérieure, en centièmes de pouce.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
