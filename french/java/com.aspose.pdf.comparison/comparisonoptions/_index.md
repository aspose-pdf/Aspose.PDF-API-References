---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe d'options de comparaison de documents PDF."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

Représente une classe d'options de comparaison de documents PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | Crée une instance de la classe {@link ComparisonOptions}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | Obtient et définit l'ordre des opérations d'édition. |
| [getExcludeAreas1](#getExcludeAreas1--) | Obtenir et définir les zones exclues. Utilisé pour la première page ou le document dans la méthode de comparaison. Cette option peut être définie avec {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. |
| [getExcludeAreas2](#getExcludeAreas2--) | Obtenir et définir les zones exclues. Utilisé pour la deuxième page ou le document dans la méthode de comparaison. Cette option peut être définie avec {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. |
| [getExtractionArea](#getExtractionArea--) | Obtenir et définir la zone rectangulaire dans laquelle le texte des pages sera comparé. Cette option ne peut pas être définie avec {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) et { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) options. |
| [isExcludeTables](#isExcludeTables--) | Obtenir et définir l'option qui détermine si les tables sont exclues de la comparaison. Cette option ne peut pas être définie conjointement avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. La valeur par défaut est {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | Obtient et définit l'ordre des opérations d'édition. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Obtenir et définir les zones exclues. Utilisé pour la première page ou le document dans la méthode de comparaison. Cette option peut être définie avec {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Obtenir et définir les zones exclues. Utilisé pour la deuxième page ou le document dans la méthode de comparaison. Cette option peut être définie avec {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. |
| [setExcludeTables](#setExcludeTables-boolean-) | Obtenir et définir l'option qui détermine si les tables sont exclues de la comparaison. Cette option ne peut pas être définie conjointement avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. La valeur par défaut est {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | Obtenir et définir la zone rectangulaire dans laquelle le texte des pages sera comparé. Cette option ne peut pas être définie avec {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) et { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) options. |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

Crée une instance de la classe {@link ComparisonOptions}.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

Obtient et définit l'ordre des opérations d'édition.

**Returns:**
Élément EditOperationsOrder

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Obtenir et définir les zones exclues. Utilisé pour la première page ou le document dans la méthode de comparaison. Cette option peut être définie avec {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option.

**Returns:**
tableau d'instances Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Obtenir et définir les zones exclues. Utilisé pour la deuxième page ou le document dans la méthode de comparaison. Cette option peut être définie avec {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option.

**Returns:**
tableau d'instances Rectangle

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

Obtenir et définir la zone rectangulaire dans laquelle le texte des pages sera comparé. Cette option ne peut pas être définie avec {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) et { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) options.

**Returns:**
Instance de Rectangle

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

Obtenir et définir l'option qui détermine si les tables sont exclues de la comparaison. Cette option ne peut pas être définie conjointement avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. La valeur par défaut est {@code false}.

**Returns:**
valeur booléenne

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
Obtient et définit l'ordre des opérations d'édition.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Obtenir et définir les zones exclues. Utilisé pour la première page ou le document dans la méthode de comparaison. Cette option peut être définie avec {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option.

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Obtenir et définir les zones exclues. Utilisé pour la deuxième page ou le document dans la méthode de comparaison. Cette option peut être définie avec {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option.

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Obtenir et définir l'option qui détermine si les tables sont exclues de la comparaison. Cette option ne peut pas être définie conjointement avec {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) option. La valeur par défaut est {@code false}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
Obtenir et définir la zone rectangulaire dans laquelle le texte des pages sera comparé. Cette option ne peut pas être définie avec {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) et { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) options.
