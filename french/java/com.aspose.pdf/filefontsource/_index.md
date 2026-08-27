---
title: "FileFontSource"
linktitle: "FileFontSource"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une source de fichier de police unique."
type: docs
weight: 1450
url: /fr/java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FileFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FileFontSource

```
public final class FileFontSource extends FontSource
```

Représente une source de fichier de police unique.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FileFontSource](#FileFontSource-java.lang.String-) | Initialise une nouvelle instance de la classe {@code FileFontSource}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Vérifie si les objets source de fichier de police sont égaux. |
| [getFilePath](#getFilePath--) | Chemin vers le fichier de police. |
| [hashCode](#hashCode--) | Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'il est invoqué sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit toujours renvoyer le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Dans la mesure du raisonnable, la méthode hashCode définie par la classe {@code Object} renvoie bien des entiers distincts pour des objets distincts. (Ceci est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java <span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [setFilePath](#setFilePath-java.lang.String-) | Chemin vers le fichier de police. |

### FileFontSource {#FileFontSource-java.lang.String-}
Initialise une nouvelle instance de la classe {@code FileFontSource}.

### equals {#equals-java.lang.Object-}
Vérifie si les objets source de fichier de police sont égaux.

### getFilePath {#getFilePath--}
```
public String getFilePath()
```

Chemin vers le fichier de police.

**Returns:**
valeur String

### hashCode {#hashCode--}
```
public int hashCode()
```

Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'il est invoqué sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit toujours renvoyer le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Dans la mesure du raisonnable, la méthode hashCode définie par la classe {@code Object} renvoie bien des entiers distincts pour des objets distincts. (Ceci est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java <span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
une valeur de code de hachage pour cet objet. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFilePath {#setFilePath-java.lang.String-}
Chemin vers le fichier de police.
