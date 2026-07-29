---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe de base des options d'exportation des champs de formulaire."
type: docs
weight: 1310
url: /fr/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

Représente la classe de base des options d'exportation des champs de formulaire.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | Obtient ou définit une valeur indiquant si la valeur du mot de passe doit être exportée. Valeur : {@code true} si la valeur du mot de passe doit être exportée ; sinon, {@code false}. |
| [getFieldSelector](#getFieldSelector--) | Obtient un délégué qui détermine si un champ particulier doit être exporté. Si le délégué est {@code null}, tous les champs sont exportés (comportement par défaut). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | Obtient ou définit une valeur indiquant si la valeur du mot de passe doit être exportée. Valeur : {@code true} si la valeur du mot de passe doit être exportée ; sinon, {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | Définit un délégué qui détermine si un champ particulier doit être exporté. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

Obtient ou définit une valeur indiquant si la valeur du mot de passe doit être exportée. Valeur : {@code true} si la valeur du mot de passe doit être exportée ; sinon, {@code false}.

**Returns:**
valeur booléenne

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

Obtient un délégué qui détermine si un champ particulier doit être exporté. Si le délégué est {@code null}, tous les champs sont exportés (comportement par défaut).

**Returns:**
un délégué qui détermine si un champ particulier doit être exporté.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

Obtient ou définit une valeur indiquant si la valeur du mot de passe doit être exportée. Valeur : {@code true} si la valeur du mot de passe doit être exportée ; sinon, {@code false}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
Définit un délégué qui détermine si un champ particulier doit être exporté.
