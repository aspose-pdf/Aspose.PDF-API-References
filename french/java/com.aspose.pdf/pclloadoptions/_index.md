---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de chargement (import) d'un fichier PCL dans un document pdf."
type: docs
weight: 3530
url: /fr/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

Représente les options de chargement (import) d'un fichier PCL dans un document pdf.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | Crée l'objet {@code PclLoadOptions}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [getConversionEngine](#getConversionEngine--) | Définit le moteur de conversion qui sera utilisé pour la conversion |
| [getExceptions](#getExceptions--) | Liste des erreurs de conversion. |
| [isSupressErrors](#isSupressErrors--) | Obtient ou définit la valeur booléenne qui indique si les erreurs de conversion PCL doivent être supprimées. |
| [setBatchSize](#setBatchSize-int-) | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [setConversionEngine](#setConversionEngine-int-) | Définit le moteur de conversion qui sera utilisé pour la conversion |
| [setSupressErrors](#setSupressErrors-boolean-) | Obtient ou définit la valeur booléenne qui indique si les erreurs de conversion PCL doivent être supprimées. |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

Crée l'objet {@code PclLoadOptions}.

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination.

**Returns:**
valeur int

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Définit le moteur de conversion qui sera utilisé pour la conversion

**Returns:**
Élément ConversionEngines @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

Liste des erreurs de conversion.

**Returns:**
Liste des Exceptions

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

Obtient ou définit la valeur booléenne qui indique si les erreurs de conversion PCL doivent être supprimées.

**Returns:**
valeur booléenne

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Définit le moteur de conversion qui sera utilisé pour la conversion

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| conversionEngine |  | Élément ConversionEngines @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

Obtient ou définit la valeur booléenne qui indique si les erreurs de conversion PCL doivent être supprimées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| supressErrors |  | valeur booléenne |
