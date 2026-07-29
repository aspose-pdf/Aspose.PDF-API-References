---
title: "HtmlSaveOptions.CssSavingInfo"
linktitle: "HtmlSaveOptions.CssSavingInfo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe représente un ensemble de données liées à l'enregistrement personnalisé de CSS pendant la conversion de PDF au format HTML"
type: docs
weight: 2010
url: /fr/java/com.aspose.pdf/htmlsaveoptions.csssavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.CssSavingInfo

```
public static class HtmlSaveOptions.CssSavingInfo extends Object
```

Cette classe représente un ensemble de données liées à l'enregistrement personnalisé de CSS pendant la conversion de PDF au format HTML

## Méthodes

| Méthode | Description |
| --- | --- |
| [getContentStream](#getContentStream--) | Défini par le convertisseur. Représente le contenu binaire du CSS enregistré |
| [getCssNumber](#getCssNumber--) | Défini par le convertisseur. Lors de la conversion, plusieurs fichiers CSS sont créés. Cette propriété indique l'ordre du fichier CSS enregistré pendant la conversion. Elle peut être utilisée dans la logique du code personnalisé pour décider comment traiter ou où enregistrer le contenu CSS |
| [getSupposedURL](#getSupposedURL--) | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer le contenu. |
| [setContentStream](#setContentStream-java.io.InputStream-) | Défini par le convertisseur. Représente le contenu binaire du CSS enregistré |
| [setCssNumber](#setCssNumber-int-) | Défini par le convertisseur. Lors de la conversion, plusieurs fichiers CSS sont créés. Cette propriété indique l'ordre du fichier CSS enregistré pendant la conversion. Elle peut être utilisée dans la logique du code personnalisé pour décider comment traiter ou où enregistrer le contenu CSS |
| [setSupposedURL](#setSupposedURL-java.lang.String-) | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer le contenu. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Défini par le convertisseur. Représente le contenu binaire du CSS enregistré

**Returns:**
Instance InputStream

### getCssNumber {#getCssNumber--}
```
public int getCssNumber()
```

Défini par le convertisseur. Lors de la conversion, plusieurs fichiers CSS sont créés. Cette propriété indique l'ordre du fichier CSS enregistré pendant la conversion. Elle peut être utilisée dans la logique du code personnalisé pour décider comment traiter ou où enregistrer le contenu CSS

**Returns:**
valeur int

### getSupposedURL {#getSupposedURL--}
```
public String getSupposedURL()
```

Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer le contenu.

**Returns:**
valeur String

### setContentStream {#setContentStream-java.io.InputStream-}
Défini par le convertisseur. Représente le contenu binaire du CSS enregistré

### setCssNumber {#setCssNumber-int-}
```
public void setCssNumber(int cssNumber)
```

Défini par le convertisseur. Lors de la conversion, plusieurs fichiers CSS sont créés. Cette propriété indique l'ordre du fichier CSS enregistré pendant la conversion. Elle peut être utilisée dans la logique du code personnalisé pour décider comment traiter ou où enregistrer le contenu CSS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cssNumber |  | valeur int |

### setSupposedURL {#setSupposedURL-java.lang.String-}
Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer le contenu.
