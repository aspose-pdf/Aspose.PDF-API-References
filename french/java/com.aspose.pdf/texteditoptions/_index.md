---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Décrit les options des opérations d'édition de texte."
type: docs
weight: 4970
url: /fr/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

Décrit les options des opérations d'édition de texte.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | Initialise une nouvelle instance de l'objet {@code TextEditOptions} avec les options par défaut. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * Initialise une nouvelle instance de l'objet {@code TextEditOptions} pour le mode de réarrangement de texte spécifié. / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | Initialise une nouvelle instance de l'objet {@code TextEditOptions} avec les options par défaut. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Initialise une nouvelle instance de l'objet {@code TextEditOptions} avec les options par défaut. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Initialise une nouvelle instance de l'objet {@code TextEditOptions} avec les options par défaut. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | Initialise une nouvelle instance de l'objet {@code TextEditOptions} avec les options par défaut. NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | Obtient la valeur qui autorise l'utilisation de la transformation linguistique lors de l'ajout ou de la modification du texte. true - la transformation linguistique sera appliquée si nécessaire (valeur par défaut). false - la transformation linguistique NE sera PAS appliquée. |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | Obtient le mode de traitement du chemin de découpe du texte modifié. |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | Obtient le mode qui définit le comportement pour les scénarios de remplacement de polices. |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | Obtient le mode qui définit le comportement pour les scénarios de transformation linguistique. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Obtient le mode qui définit le comportement dans le cas où les polices ne contiennent pas les caractères demandés. |
| [getReplacementFont](#getReplacementFont--) | Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> Obtient ou définit la valeur qui autorise la recherche de soulignement de texte sur la page du document source. <p> (Obsolète) Veuillez utiliser TextSearchOptions.SearchForTextRelatedGraphics à la place. </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | Définit la valeur qui autorise l'utilisation de la transformation linguistique lors de l'ajout ou de la modification du texte. true - la transformation linguistique sera appliquée si nécessaire (valeur par défaut). false - la transformation linguistique NE sera PAS appliquée. |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | Obtient le mode de traitement du chemin de découpe du texte modifié. |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | Définit le mode qui définit le comportement pour les scénarios de remplacement de polices. |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Définit le mode qui définit le comportement pour les scénarios de transformation linguistique. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Définit le mode qui définit le comportement dans le cas où les polices ne contiennent pas les caractères demandés. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> Obtient ou définit la valeur qui autorise la recherche de soulignement de texte sur la page du document source. <p> (Obsolète) Veuillez utiliser TextSearchOptions.SearchForTextRelatedGraphics à la place. </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

Initialise une nouvelle instance de l'objet {@code TextEditOptions} avec les options par défaut. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * Initialise une nouvelle instance de l'objet {@code TextEditOptions} pour le mode de réarrangement de texte spécifié. / * / *

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
Initialise une nouvelle instance de l'objet {@code TextEditOptions} avec les options par défaut. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Initialise une nouvelle instance de l'objet {@code TextEditOptions} avec les options par défaut. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Initialise une nouvelle instance de l'objet {@code TextEditOptions} avec les options par défaut. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
Initialise une nouvelle instance de l'objet {@code TextEditOptions} avec les options par défaut. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

Obtient la valeur qui autorise l'utilisation de la transformation linguistique lors de l'ajout ou de la modification du texte. true - la transformation linguistique sera appliquée si nécessaire (valeur par défaut). false - la transformation linguistique NE sera PAS appliquée.

**Returns:**
valeur booléenne

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

Obtient le mode de traitement du chemin de découpe du texte modifié.

**Returns:**
Élément ClippingPathsProcessingMode

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

Obtient le mode qui définit le comportement pour les scénarios de remplacement de polices.

**Returns:**
Valeur FontReplace @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

Obtient le mode qui définit le comportement pour les scénarios de transformation linguistique.

**Returns:**
Valeur LanguageTransformation @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

Obtient le mode qui définit le comportement dans le cas où les polices ne contiennent pas les caractères demandés.

**Returns:**
Valeur NoCharacterAction @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis

**Returns:**
Instance Font

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> Obtient ou définit la valeur qui autorise la recherche de soulignement de texte sur la page du document source. <p> (Obsolète) Veuillez utiliser TextSearchOptions.SearchForTextRelatedGraphics à la place. </p>

**Returns:**
valeur booléenne

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

Définit la valeur qui autorise l'utilisation de la transformation linguistique lors de l'ajout ou de la modification du texte. true - la transformation linguistique sera appliquée si nécessaire (valeur par défaut). false - la transformation linguistique NE sera PAS appliquée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
Obtient le mode de traitement du chemin de découpe du texte modifié.

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
Définit le mode qui définit le comportement pour les scénarios de remplacement de polices.

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Définit le mode qui définit le comportement pour les scénarios de transformation linguistique.

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Définit le mode qui définit le comportement dans le cas où les polices ne contiennent pas les caractères demandés.

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> Obtient ou définit la valeur qui autorise la recherche de soulignement de texte sur la page du document source. <p> (Obsolète) Veuillez utiliser TextSearchOptions.SearchForTextRelatedGraphics à la place. </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
