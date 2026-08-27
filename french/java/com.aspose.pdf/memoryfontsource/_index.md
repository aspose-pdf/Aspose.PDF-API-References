---
title: "MemoryFontSource"
linktitle: "MemoryFontSource"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une source de fichier de police unique."
type: docs
weight: 3040
url: /fr/java/com.aspose.pdf/memoryfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.MemoryFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.MemoryFontSource

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public final class MemoryFontSource extends FontSource implements com.aspose.ms.System.IDisposable, Closeable
```

Représente une source de fichier de police unique.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MemoryFontSource](#MemoryFontSource-byte:A-) | Initialise une nouvelle instance de la classe {@code MemoryFontSource}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [close](#close--) | Ferme toutes les ressources utilisées par ce document. |
| [dispose](#dispose--) | Libère les ressources internes. Cette méthode est obsolète, utilisez close() à la place. |
| [equals](#equals-java.lang.Object-) | Vérifie si les objets source de fichier de police sont égaux. |
| [getFontBytes](#getFontBytes--) | Tableau d'octets du fichier de police. |
| [hashCode](#hashCode--) | Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit renvoyer de manière cohérente le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Cela est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |

### MemoryFontSource {#MemoryFontSource-byte:A-}
```
public MemoryFontSource(byte[] fontBytes)
```

Initialise une nouvelle instance de la classe {@code MemoryFontSource}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontBytes |  | Tableau d'octets du fichier de police. |

### close {#close--}
```
public void close()
```

Ferme toutes les ressources utilisées par ce document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libère les ressources internes. Cette méthode est obsolète, utilisez close() à la place.

### equals {#equals-java.lang.Object-}
Vérifie si les objets source de fichier de police sont égaux.

### getFontBytes {#getFontBytes--}
```
public byte[] getFontBytes()
```

Tableau d'octets du fichier de police.

**Returns:**
byte[] tableau

### hashCode {#hashCode--}
```
public int hashCode()
```

Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit renvoyer de manière cohérente le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont différents selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets différents peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Cela est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
une valeur de code de hachage pour cet objet. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
