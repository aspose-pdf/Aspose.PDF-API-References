---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe de base abstraite pour les artefacts de pagination dans un document."
type: docs
weight: 3460
url: /fr/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

Représente une classe de base abstraite pour les artefacts de pagination dans un document.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getEndPage](#getEndPage--) | Obtient ou définit le numéro de page de fin pour l'artefact. La valeur doit être supérieure ou égale à 0. Si une valeur inférieure à 0 est définie, elle sera ajustée à 0. La valeur par défaut de 0 signifie qu'il n'y a pas de limites de page de fin. |
| [getStartPage](#getStartPage--) | Obtient ou définit le numéro de page de début pour l'artefact. La valeur doit être supérieure ou égale à 1. Si une valeur inférieure à 1 est définie, elle sera ajustée à 1. |
| [getSubset](#getSubset--) | Obtient ou définit le sous-ensemble de pages auquel l'artefact s'applique (par ex., toutes les pages, les pages paires, les pages impaires). |
| [setEndPage](#setEndPage-int-) | Obtient ou définit le numéro de page de fin pour l'artefact. La valeur doit être supérieure ou égale à 0. Si une valeur inférieure à 0 est définie, elle sera ajustée à 0. La valeur par défaut de 0 signifie qu'il n'y a pas de limites de page de fin. |
| [setStartPage](#setStartPage-int-) | Obtient ou définit le numéro de page de début pour l'artefact. La valeur doit être supérieure ou égale à 1. Si une valeur inférieure à 1 est définie, elle sera ajustée à 1. |
| [setSubset](#setSubset-int-) | Obtient ou définit le sous-ensemble de pages auquel l'artefact s'applique (par ex., toutes les pages, les pages paires, les pages impaires). |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

Obtient ou définit le numéro de page de fin pour l'artefact. La valeur doit être supérieure ou égale à 0. Si une valeur inférieure à 0 est définie, elle sera ajustée à 0. La valeur par défaut de 0 signifie qu'il n'y a pas de limites de page de fin.

**Returns:**
valeur int

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

Obtient ou définit le numéro de page de début pour l'artefact. La valeur doit être supérieure ou égale à 1. Si une valeur inférieure à 1 est définie, elle sera ajustée à 1.

**Returns:**
valeur int

### getSubset {#getSubset--}
```
public final int getSubset()
```

Obtient ou définit le sous-ensemble de pages auquel l'artefact s'applique (par ex., toutes les pages, les pages paires, les pages impaires).

**Returns:**
valeur int

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

Obtient ou définit le numéro de page de fin pour l'artefact. La valeur doit être supérieure ou égale à 0. Si une valeur inférieure à 0 est définie, elle sera ajustée à 0. La valeur par défaut de 0 signifie qu'il n'y a pas de limites de page de fin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

Obtient ou définit le numéro de page de début pour l'artefact. La valeur doit être supérieure ou égale à 1. Si une valeur inférieure à 1 est définie, elle sera ajustée à 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

Obtient ou définit le sous-ensemble de pages auquel l'artefact s'applique (par ex., toutes les pages, les pages paires, les pages impaires).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
