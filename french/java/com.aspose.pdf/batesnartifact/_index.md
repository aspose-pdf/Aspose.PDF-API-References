---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "La classe décrit l'artifact de numérotation Bates."
type: docs
weight: 290
url: /fr/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

La classe décrit l'artifact de numérotation Bates.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | Initialise une nouvelle instance de la classe {@link BatesNArtifact}. Ce constructeur est interne et crée une instance d'artifact d'en-tête avec des valeurs par défaut. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Obtient ou définit le nombre de chiffres pour la numérotation Bates. La valeur doit être comprise entre 3 et 15 inclus. Si une valeur inférieure à 3 est définie, elle sera ajustée à 3. Si une valeur supérieure à 15 est définie, elle sera ajustée à 15. La valeur par défaut est 6. |
| [getPrefix](#getPrefix--) | Obtient ou définit le préfixe à ajouter au numéro Bates. |
| [getStartNumber](#getStartNumber--) | Obtient ou définit le numéro de départ pour la numérotation Bates. La valeur doit être supérieure ou égale à 1. Si une valeur inférieure à 1 est définie, elle sera ajustée à 1. |
| [getSuffix](#getSuffix--) | Obtient ou définit le suffixe à ajouter au numéro Bates. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Obtient ou définit le nombre de chiffres pour la numérotation Bates. La valeur doit être comprise entre 3 et 15 inclus. Si une valeur inférieure à 3 est définie, elle sera ajustée à 3. Si une valeur supérieure à 15 est définie, elle sera ajustée à 15. La valeur par défaut est 6. |
| [setPrefix](#setPrefix-java.lang.String-) | Obtient ou définit le préfixe à ajouter au numéro Bates. |
| [setStartNumber](#setStartNumber-int-) | Obtient ou définit le numéro de départ pour la numérotation Bates. La valeur doit être supérieure ou égale à 1. Si une valeur inférieure à 1 est définie, elle sera ajustée à 1. |
| [setSuffix](#setSuffix-java.lang.String-) | Obtient ou définit le suffixe à ajouter au numéro Bates. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

Initialise une nouvelle instance de la classe {@link BatesNArtifact}. Ce constructeur est interne et crée une instance d'artifact d'en-tête avec des valeurs par défaut.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Obtient ou définit le nombre de chiffres pour la numérotation Bates. La valeur doit être comprise entre 3 et 15 inclus. Si une valeur inférieure à 3 est définie, elle sera ajustée à 3. Si une valeur supérieure à 15 est définie, elle sera ajustée à 15. La valeur par défaut est 6.

**Returns:**
valeur int

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Obtient ou définit le préfixe à ajouter au numéro Bates.

**Returns:**
valeur String

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Obtient ou définit le numéro de départ pour la numérotation Bates. La valeur doit être supérieure ou égale à 1. Si une valeur inférieure à 1 est définie, elle sera ajustée à 1.

**Returns:**
valeur int

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Obtient ou définit le suffixe à ajouter au numéro Bates.

**Returns:**
valeur String

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Obtient ou définit le nombre de chiffres pour la numérotation Bates. La valeur doit être comprise entre 3 et 15 inclus. Si une valeur inférieure à 3 est définie, elle sera ajustée à 3. Si une valeur supérieure à 15 est définie, elle sera ajustée à 15. La valeur par défaut est 6.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPrefix {#setPrefix-java.lang.String-}
Obtient ou définit le préfixe à ajouter au numéro Bates.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Obtient ou définit le numéro de départ pour la numérotation Bates. La valeur doit être supérieure ou égale à 1. Si une valeur inférieure à 1 est définie, elle sera ajustée à 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setSuffix {#setSuffix-java.lang.String-}
Obtient ou définit le suffixe à ajouter au numéro Bates.
