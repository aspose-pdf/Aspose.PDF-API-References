---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente l'emplacement dans le document PDF où l'erreur d'extraction de texte est apparue."
type: docs
weight: 5050
url: /fr/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

Représente l'emplacement dans le document PDF où l'erreur d'extraction de texte est apparue.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | Clé (nom) de l'objet PDF Font utilisé pour afficher l'opérateur qui provoque l'erreur d'extraction de texte. |
| [getFormKey](#getFormKey--) | Clé (nom) du PDF Form XObject dans lequel l'erreur d'extraction de texte du flux de contenu a été localisée. Non vide si ObjectType == 'xForm'. |
| [getObjectType](#getObjectType--) | Type de l'objet PDF (Page ou xForm) dans lequel l'erreur d'extraction de texte du flux de contenu a été localisée. |
| [getOperatorIndex](#getOperatorIndex--) | Index de l'opérateur d'affichage du texte dans le flux de contenu (collection d'opérateurs) qui provoque l'erreur d'extraction de texte. |
| [getOperatorString](#getOperatorString--) | Opérateur d'affichage du texte qui provoque l'erreur d'extraction de texte. |
| [getPageNumber](#getPageNumber--) | Numéro de la page du document où l'erreur d'extraction de texte a été localisée. |
| [getPath](#getPath--) | Emplacement du document PDF où l'erreur d'extraction de texte est apparue. |
| [getTextStartPoint](#getTextStartPoint--) | Clé (nom) de l'objet PDF Font utilisé pour afficher l'opérateur qui provoque l'erreur d'extraction de texte. |
| [toString](#toString--) | Renvoie la représentation sous forme de chaîne. |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

Clé (nom) de l'objet PDF Font utilisé pour afficher l'opérateur qui provoque l'erreur d'extraction de texte.

**Returns:**
valeur String

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

Clé (nom) du PDF Form XObject dans lequel l'erreur d'extraction de texte du flux de contenu a été localisée. Non vide si ObjectType == 'xForm'.

**Returns:**
valeur String

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

Type de l'objet PDF (Page ou xForm) dans lequel l'erreur d'extraction de texte du flux de contenu a été localisée.

**Returns:**
valeur String

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

Index de l'opérateur d'affichage du texte dans le flux de contenu (collection d'opérateurs) qui provoque l'erreur d'extraction de texte.

**Returns:**
valeur int

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

Opérateur d'affichage du texte qui provoque l'erreur d'extraction de texte.

**Returns:**
valeur String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Numéro de la page du document où l'erreur d'extraction de texte a été localisée.

**Returns:**
valeur int

### getPath {#getPath--}
```
public String getPath()
```

Emplacement du document PDF où l'erreur d'extraction de texte est apparue.

**Returns:**
valeur String

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

Clé (nom) de l'objet PDF Font utilisé pour afficher l'opérateur qui provoque l'erreur d'extraction de texte.

**Returns:**
Instance de Point

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation sous forme de chaîne.

**Returns:**
Représentation sous forme de chaîne.
