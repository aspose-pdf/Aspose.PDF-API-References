---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Options d'enregistrement pour l'exportation au format Excel"
type: docs
weight: 1260
url: /fr/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Options d'enregistrement pour l'exportation au format Excel

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat](#getFormat--) | / * / * Obtient ou définit le facteur qui sera appliqué à la taille de police (virtuelle) lors de la conversion en tableau Excel dans / * le moteur hérité. Réduire la valeur facilite la recherche des colonnes et empêche leur fusion pour certains / * documents. La valeur par défaut est 0,9; définir la valeur à zéro permet à l'algorithme de choisir automatiquement l'échelle. / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | Définissez true si vous devez minimiser le nombre de feuilles de calcul dans le classeur résultant. La valeur par défaut est false ; cela signifie que chaque page PDF est enregistrée comme feuille de calcul séparée. |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | Définissez false si vous devez supprimer l'insertion d'une colonne vide en tant que première colonne de la feuille de calcul. La valeur par défaut est true ; cela signifie qu'une colonne vide sera insérée. |
| [isUniformWorksheets](#isUniformWorksheets--) | Définissez true pour utiliser une division uniforme des colonnes dans le document. La valeur par défaut est false ; cela signifie que la division des colonnes sera indépendante pour chaque page. |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | Format de sortie |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | Définissez false si vous devez supprimer l'insertion d'une colonne vide en tant que première colonne de la feuille de calcul. La valeur par défaut est true ; cela signifie qu'une colonne vide sera insérée. |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | Définissez true si vous devez minimiser le nombre de feuilles de calcul dans le classeur résultant. La valeur par défaut est false ; cela signifie que chaque page PDF est enregistrée comme feuille de calcul séparée. |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | Définit le moteur de conversion qui sera utilisé pour la conversion |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

Constructeur

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * Obtient ou définit le facteur qui sera appliqué à la taille de police (virtuelle) lors de la conversion en tableau Excel dans / * le moteur hérité. Réduire la valeur facilite la recherche des colonnes et empêche leur fusion pour certains / * documents. La valeur par défaut est 0,9; définir la valeur à zéro permet à l'algorithme de choisir automatiquement l'échelle. / * / * / *

**Returns:**
valeur double /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

Définissez true si vous devez minimiser le nombre de feuilles de calcul dans le classeur résultant. La valeur par défaut est false ; cela signifie que chaque page PDF est enregistrée comme feuille de calcul séparée.

**Returns:**
valeur booléenne

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

Définissez false si vous devez supprimer l'insertion d'une colonne vide en tant que première colonne de la feuille de calcul. La valeur par défaut est true ; cela signifie qu'une colonne vide sera insérée.

**Returns:**
valeur booléenne

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

Définissez true pour utiliser une division uniforme des colonnes dans le document. La valeur par défaut est false ; cela signifie que la division des colonnes sera indépendante pour chaque page.

**Returns:**
valeur booléenne

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
Format de sortie

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

Définissez false si vous devez supprimer l'insertion d'une colonne vide en tant que première colonne de la feuille de calcul. La valeur par défaut est true ; cela signifie qu'une colonne vide sera insérée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

Définissez true si vous devez minimiser le nombre de feuilles de calcul dans le classeur résultant. La valeur par défaut est false ; cela signifie que chaque page PDF est enregistrée comme feuille de calcul séparée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

Définit le moteur de conversion qui sera utilisé pour la conversion

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |
