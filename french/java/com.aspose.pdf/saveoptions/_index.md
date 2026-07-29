---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le type SaveOptions maintient le niveau d'abstraction sur les options de sauvegarde individuelles."
type: docs
weight: 4370
url: /fr/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

Le type SaveOptions maintient le niveau d'abstraction sur les options de sauvegarde individuelles.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | Format d’enregistrement des données. |
| [getWarningHandler](#getWarningHandler--) | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération d’enregistrement se poursuit, toutefois l’utilisateur peut également renvoyer Abort, auquel cas l’opération d’enregistrement doit s’arrêter. |
| [isCacheGlyphs](#isCacheGlyphs--) | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages APS. Améliore les performances de la conversion PDF vers d’autres formats mais augmente la consommation de mémoire. |
| [isCloseResponse](#isCloseResponse--) | Obtient la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages APS. Améliore les performances de la conversion PDF vers d’autres formats mais augmente la consommation de mémoire. |
| [setCloseResponse](#setCloseResponse-boolean-) | Définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération d’enregistrement se poursuit, toutefois l’utilisateur peut également renvoyer Abort, auquel cas l’opération d’enregistrement doit s’arrêter. |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

Format d’enregistrement des données.

**Returns:**
Valeur SaveFormat @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération d’enregistrement se poursuit, toutefois l’utilisateur peut également renvoyer Abort, auquel cas l’opération d’enregistrement doit s’arrêter.

**Returns:**
Valeur IWarningCallback

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages APS. Améliore les performances de la conversion PDF vers d’autres formats mais augmente la consommation de mémoire.

**Returns:**
valeur booléenne

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

Obtient la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse.

**Returns:**
valeur booléenne

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages APS. Améliore les performances de la conversion PDF vers d’autres formats mais augmente la consommation de mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

Définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération d’enregistrement se poursuit, toutefois l’utilisateur peut également renvoyer Abort, auquel cas l’opération d’enregistrement doit s’arrêter.
