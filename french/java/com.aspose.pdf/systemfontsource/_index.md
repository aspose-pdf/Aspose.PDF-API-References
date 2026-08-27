---
title: "SystemFontSource"
linktitle: "SystemFontSource"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente toutes les polices installées sur le système."
type: docs
weight: 4770
url: /fr/java/com.aspose.pdf/systemfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.SystemFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.SystemFontSource

```
public final class SystemFontSource extends FontSource
```

Représente toutes les polices installées sur le système.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SystemFontSource](#SystemFontSource--) | Initialise une nouvelle instance de la classe. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Vérifie si les objets de source de police système sont égaux. |
| [getFontDefinitions](#getFontDefinitions--) | Pour usage interne uniquement |
| [hashCode](#hashCode--) | Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit renvoyer de manière cohérente le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Cela est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |

### SystemFontSource {#SystemFontSource--}
```
public SystemFontSource()
```

Initialise une nouvelle instance de la classe.

### equals {#equals-java.lang.Object-}
Vérifie si les objets de source de police système sont égaux.

### getFontDefinitions {#getFontDefinitions--}
```
public com.aspose.font.FontDefinition[] getFontDefinitions()
```

Pour usage interne uniquement

**Returns:**
Objet FontDefinition[]

### hashCode {#hashCode--}
```
public int hashCode()
```

Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit renvoyer de manière cohérente le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Cela est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
une valeur de code de hachage pour cet objet. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
