---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Implémente la récupération d'un flux de sortie depuis la mémoire. Vous pouvez l'utiliser, par exemple, lorsque vous ne voulez pas que la sortie associée (comme un fichier journal) soit écrite sur le disque mais que vous le souhaitez."
type: docs
weight: 4880
url: /fr/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

Implémente la récupération d'un flux de sortie depuis la mémoire. Vous pouvez l'utiliser, par exemple, lorsque vous ne souhaitez pas que la sortie associée (comme un fichier journal) soit écrite sur le disque mais que vous souhaitez la lire ensuite depuis la mémoire.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | Crée une nouvelle instance. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [close](#close--) | Libère l'instance. @throws IOException L'exception IOException peut être levée si une erreur d'E/S se produit |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | Renvoie le flux à lire. Sans rechercher un fichier dans les sous‑répertoires. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | Renvoie le flux à lire. |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | Renvoie le flux d'écriture. |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

Crée une nouvelle instance.

### close {#close--}
```
public void close() throws IOException
```

Libère l'instance. @throws IOException L'exception IOException peut être levée si une erreur d'E/S se produit

### getFile {#getFile-java.lang.String-java.lang.String:A-}
Renvoie le flux à lire. Sans rechercher un fichier dans les sous‑répertoires.

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
Renvoie le flux à lire.

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
Renvoie le flux d'écriture.
