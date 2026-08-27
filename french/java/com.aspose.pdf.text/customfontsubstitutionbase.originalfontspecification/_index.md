---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente la spécification de police d'origine. </p> <hr> <p> Fournit des informations liées à la police d'origine telles que , drapeau. Fournit également un drapeau qui aide à vérifier si la substitution se produira."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> Représente la spécification de police originale. </p> <hr> <p> Fournit des informations liées à la police originale telles que , drapeau. Fournit également un drapeau qui aide à vérifier si la substitution aura tout de même lieu avec la police et l'utilisateur peut remplacer la logique de substitution par défaut. </p>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Initialise un nouvel objet OriginalFontSpecification. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Obtient le nom de la police d'origine. |
| [isEmbedded](#isEmbedded--) | Obtient une valeur indiquant si la police est incorporée. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> Obtient une valeur indiquant que la substitution est inévitable. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
Initialise un nouvel objet OriginalFontSpecification.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Obtient le nom de la police d'origine.

**Returns:**
valeur String

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

Obtient une valeur indiquant si la police est incorporée.

**Returns:**
valeur booléenne

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> Obtient une valeur indiquant que la substitution est inévitable. </p>

**Returns:**
boolean value <hr> <p> Retourne true si la substitution a été demandée en raison de l'absence de la police d'origine ou si la police d'origine ne peut pas être utilisée dans le contexte d'une tâche. Si l'utilisateur ignore le drapeau et ne substitue pas la police, la procédure de substitution de police par défaut est exécutée. Mais cela offre à l'utilisateur la possibilité de modifier la procédure de substitution de police standard et de définir une meilleure police pour le système. Retourne false si la police d'origine est présente, valide, mais qu'il est permis à l'utilisateur de la substituer. </p>
