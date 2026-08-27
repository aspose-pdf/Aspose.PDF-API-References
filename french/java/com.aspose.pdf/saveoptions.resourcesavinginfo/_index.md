---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe représente un ensemble de données liées à l'enregistrement de fichiers de ressources externes qui se produit lors de la conversion de PDF vers un autre format (par ex. HTML)."
type: docs
weight: 4440
url: /fr/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

Cette classe représente un ensemble de données liées à l'enregistrement de fichiers de ressources externes qui se produit lors de la conversion de PDF vers un autre format (par ex. HTML).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getContentStream](#getContentStream--) | Défini par le convertisseur. Représente le contenu binaire du fichier enregistré. |
| [getResourceType](#getResourceType--) | Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment le traiter ou où enregistrer ce fichier. |
| [getSupposedFileName](#getSupposedFileName--) | Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment le traiter ou où enregistrer ce fichier. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour certaines raisons, le fichier proposé doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même de manière standard pour le convertisseur. Ainsi, le fait de le définir sur true signifie que le code personnalisé n’a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑même (dans les deux sens – pour l’enregistrement quelque part et pour le nommage dans le fichier de référence). |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour certaines raisons, le fichier proposé doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même de manière standard pour le convertisseur. Ainsi, le fait de le définir sur true signifie que le code personnalisé n’a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑même (dans les deux sens – pour l’enregistrement quelque part et pour le nommage dans le fichier de référence). |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

Défini par le convertisseur. Représente le contenu binaire du fichier enregistré.

**Returns:**
tableau d'octets

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment le traiter ou où enregistrer ce fichier.

**Returns:**
NodeLevelResourceType élément @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment le traiter ou où enregistrer ce fichier.

**Returns:**
valeur String

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour certaines raisons, le fichier proposé doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même de manière standard pour le convertisseur. Ainsi, le fait de le définir sur true signifie que le code personnalisé n’a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑même (dans les deux sens – pour l’enregistrement quelque part et pour le nommage dans le fichier de référence).

**Returns:**
valeur booléenne

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour certaines raisons, le fichier proposé doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même de manière standard pour le convertisseur. Ainsi, le fait de le définir sur true signifie que le code personnalisé n’a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑même (dans les deux sens – pour l’enregistrement quelque part et pour le nommage dans le fichier de référence).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| customProcessingCancelled |  | valeur booléenne |
