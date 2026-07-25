---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe d'options pour comparer des documents avec une sortie côte à côte."
type: docs
weight: 60
url: /fr/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

Représente une classe d'options pour comparer des documents avec une sortie côte à côte.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | Crée une instance de la classe {@link SideBySideComparisonOptions}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | Obtient et définit la propriété qui détermine si des marqueurs de modification supplémentaires sont affichés. Si elle est définie, elle affiche les marques de modification qui ne sont pas sur la page actuelle mais présentes sur une autre page. Si la modification se situe entre des mots, la marque peut ne pas être positionnée exactement par rapport au caractère d'espace. La valeur par défaut est {@code false}. |
| [getComparisonArea1](#getComparisonArea1--) | Obtient et définit la zone de comparaison. Utilisée pour la première page ou le premier document dans la méthode de comparaison. Cette option ne peut pas être définie en même temps que les options {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) et {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [getComparisonArea2](#getComparisonArea2--) | Obtient et définit la zone de comparaison. Utilisée pour la deuxième page ou le deuxième document dans la méthode de comparaison. Cette option ne peut pas être définie en même temps que les options {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) et {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [getComparisonMode](#getComparisonMode--) | Obtient et définit un mode de comparaison. La valeur par défaut est {@link ComparisonMode#IgnoreSpaces}. |
| [getDeleteColor](#getDeleteColor--) | Obtient la couleur utilisée pour marquer le contenu supprimé lors d'une comparaison côte à côte. Cette propriété définit la représentation visuelle des suppressions dans le résultat de la comparaison. |
| [getExcludeAreas1](#getExcludeAreas1--) | Obtenez et définissez les zones d'exclusion. Utilisé pour la première page ou le premier document dans la méthode de comparaison. Cette option peut être définie en même temps que {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie en même temps que l'option {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [getExcludeAreas2](#getExcludeAreas2--) | Obtenez et définissez les zones d'exclusion. Utilisé pour la deuxième page ou le deuxième document dans la méthode de comparaison. Cette option peut être définie en même temps que {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie en même temps que l'option {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [getExcludeTables](#getExcludeTables--) | Obtenez et définissez l'option qui détermine si les tables sont exclues de la comparaison. Cette option ne peut pas être définie en même temps que {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) et {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). La valeur par défaut est {@code false}. |
| [getInsertColor](#getInsertColor--) | Obtient la couleur utilisée pour marquer le contenu inséré lors d'une comparaison côte à côte. Cette propriété définit la représentation visuelle de l'insertion dans le résultat de la comparaison. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | Obtient et définit la propriété qui détermine si des marqueurs de modification supplémentaires sont affichés. Si elle est définie, elle affiche les marques de modification qui ne sont pas sur la page actuelle mais présentes sur une autre page. Si la modification se situe entre des mots, la marque peut ne pas être positionnée exactement par rapport au caractère d'espace. La valeur par défaut est {@code false}. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | Obtient et définit la zone de comparaison. Utilisée pour la première page ou le premier document dans la méthode de comparaison. Cette option ne peut pas être définie en même temps que les options {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) et {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | Obtient et définit la zone de comparaison. Utilisée pour la deuxième page ou le deuxième document dans la méthode de comparaison. Cette option ne peut pas être définie en même temps que les options {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) et {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [setComparisonMode](#setComparisonMode-int-) | Obtient et définit un mode de comparaison. La valeur par défaut est {@link ComparisonMode#IgnoreSpaces}. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | Définit la couleur utilisée pour marquer le contenu supprimé lors d'une comparaison côte à côte. Cette propriété définit la représentation visuelle des suppressions dans le résultat de la comparaison. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Obtenez et définissez les zones d'exclusion. Utilisé pour la première page ou le premier document dans la méthode de comparaison. Cette option peut être définie en même temps que {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie en même temps que l'option {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Obtenez et définissez les zones d'exclusion. Utilisé pour la deuxième page ou le deuxième document dans la méthode de comparaison. Cette option peut être définie en même temps que {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie en même temps que l'option {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [setExcludeTables](#setExcludeTables-boolean-) | Obtenez et définissez l'option qui détermine si les tables sont exclues de la comparaison. Cette option ne peut pas être définie en même temps que {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) et {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). La valeur par défaut est {@code false}. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | Définit la couleur utilisée pour marquer le contenu inséré lors d'une comparaison côte à côte. Cette propriété définit la représentation visuelle de l'insertion dans le résultat de la comparaison. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

Crée une instance de la classe {@link SideBySideComparisonOptions}.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

Obtient et définit la propriété qui détermine si des marqueurs de modification supplémentaires sont affichés. Si elle est définie, elle affiche les marques de modification qui ne sont pas sur la page actuelle mais présentes sur une autre page. Si la modification se situe entre des mots, la marque peut ne pas être positionnée exactement par rapport au caractère d'espace. La valeur par défaut est {@code false}.

**Returns:**
valeur booléenne

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

Obtient et définit la zone de comparaison. Utilisée pour la première page ou le premier document dans la méthode de comparaison. Cette option ne peut pas être définie en même temps que les options {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) et {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

**Returns:**
Instance de Rectangle

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

Obtient et définit la zone de comparaison. Utilisée pour la deuxième page ou le deuxième document dans la méthode de comparaison. Cette option ne peut pas être définie en même temps que les options {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) et {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

**Returns:**
Instance de Rectangle

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

Obtient et définit un mode de comparaison. La valeur par défaut est {@link ComparisonMode#IgnoreSpaces}.

**Returns:**
Élément ComparisonMode

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

Obtient la couleur utilisée pour marquer le contenu supprimé lors d'une comparaison côte à côte. Cette propriété définit la représentation visuelle des suppressions dans le résultat de la comparaison.

**Returns:**
la couleur utilisée pour marquer le contenu supprimé lors d'une comparaison côte à côte.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Obtenez et définissez les zones d'exclusion. Utilisé pour la première page ou le premier document dans la méthode de comparaison. Cette option peut être définie en même temps que {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie en même temps que l'option {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

**Returns:**
tableau d'instances Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Obtenez et définissez les zones d'exclusion. Utilisé pour la deuxième page ou le deuxième document dans la méthode de comparaison. Cette option peut être définie en même temps que {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie en même temps que l'option {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

**Returns:**
tableau d'instances Rectangle

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

Obtenez et définissez l'option qui détermine si les tables sont exclues de la comparaison. Cette option ne peut pas être définie en même temps que {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) et {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). La valeur par défaut est {@code false}.

**Returns:**
valeur booléenne

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

Obtient la couleur utilisée pour marquer le contenu inséré lors d'une comparaison côte à côte. Cette propriété définit la représentation visuelle de l'insertion dans le résultat de la comparaison.

**Returns:**
la couleur utilisée pour marquer le contenu inséré lors d'une comparaison côte à côte.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

Obtient et définit la propriété qui détermine si des marqueurs de modification supplémentaires sont affichés. Si elle est définie, elle affiche les marques de modification qui ne sont pas sur la page actuelle mais présentes sur une autre page. Si la modification se situe entre des mots, la marque peut ne pas être positionnée exactement par rapport au caractère d'espace. La valeur par défaut est {@code false}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
Obtient et définit la zone de comparaison. Utilisée pour la première page ou le premier document dans la méthode de comparaison. Cette option ne peut pas être définie en même temps que les options {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) et {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
Obtient et définit la zone de comparaison. Utilisée pour la deuxième page ou le deuxième document dans la méthode de comparaison. Cette option ne peut pas être définie en même temps que les options {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) et {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

Obtient et définit un mode de comparaison. La valeur par défaut est {@link ComparisonMode#IgnoreSpaces}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ComparisonMode |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
Définit la couleur utilisée pour marquer le contenu supprimé lors d'une comparaison côte à côte. Cette propriété définit la représentation visuelle des suppressions dans le résultat de la comparaison.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Obtenez et définissez les zones d'exclusion. Utilisé pour la première page ou le premier document dans la méthode de comparaison. Cette option peut être définie en même temps que {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie en même temps que l'option {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Obtenez et définissez les zones d'exclusion. Utilisé pour la deuxième page ou le deuxième document dans la méthode de comparaison. Cette option peut être définie en même temps que {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Cette option ne peut pas être définie en même temps que l'option {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Obtenez et définissez l'option qui détermine si les tables sont exclues de la comparaison. Cette option ne peut pas être définie en même temps que {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) et {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). La valeur par défaut est {@code false}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
Définit la couleur utilisée pour marquer le contenu inséré lors d'une comparaison côte à côte. Cette propriété définit la représentation visuelle de l'insertion dans le résultat de la comparaison.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
