---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de rendu"
type: docs
weight: 4150
url: /fr/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

Représente les options de rendu

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | Initialise une nouvelle instance de l'objet {@code RenderingOptions}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. L'algorithme de substitution de police suit ces étapes : 1. Si l'utilisateur définit explicitement la propriété DefaultFontName, vérifier si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, rechercher les polices ajoutées via le {@code FontRepository.Sources}. 3. Analyser le texte pour identifier son alphabet ou son script et suggérer des noms de police en conséquence. Tenter de localiser et d'utiliser ces polices depuis le système. 4. En dernier recours, rechercher dans le système toute police capable d'afficher les caractères requis. |
| [getBarcodeOptimization](#getBarcodeOptimization--) | Obtient le mode d'optimisation du code‑barres. |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | Indique que toutes les polices seront converties en versions TTF Unicode. Cela est utile pour des raisons de compatibilité et pour optimiser l'utilisation des polices, car chaque nouvelle police TTF ne contiendra pas tous les symboles de la police source, mais uniquement les symboles utilisés dans le texte. |
| [getDefaultFontName](#getDefaultFontName--) | Obtient/definit le nom par défaut de la police utilisée pour remplacer les polices manquantes. |
| [getHeightExtraUnits](#getHeightExtraUnits--) | Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Obtient ou définit l’indication selon laquelle les erreurs liées à l’absence de police seront ignorées. true - signifie que les erreurs d’absence de police seront ignorées. Les segments de texte faisant référence à des ressources incorrectes seront sautés lors du traitement. false par défaut |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | Obtient ou définit le mode haute qualité pour l'interpolation. |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | Nombre maximal de polices dans le cache de polices. La valeur par défaut est 10. |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | Nombre maximal de symboles dans le cache de symboles. La valeur par défaut est 100. |
| [getOptimizeDimensions](#getOptimizeDimensions--) | Obtient ou définit le mode d'optimisation des dimensions. |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | Obtient ou définit une valeur utilisée pour mettre à l'échelle toutes les images de la page afin d'ajuster la largeur de la page. |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | Obtient un mode où les polices système sont rendues nativement. |
| [getUseFontHinting](#getUseFontHinting--) | L'utilisation de ce drapeau active le mécanisme d'optimisation des polices. L'optimisation des polices consiste à utiliser des instructions mathématiques pour ajuster l'affichage d'une police vectorielle. Dans certains cas, activer ce drapeau peut résoudre des problèmes de lisibilité du texte. À l'heure actuelle, l'utilisation de ce drapeau ne peut avoir d'effet que pour les polices TTF, si ces polices sont utilisées dans le document source. |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | Obtient un drapeau qui détermine si le nouveau moteur d'imagerie est utilisé ou non. |
| [getWidthExtraUnits](#getWidthExtraUnits--) | Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle. |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | Obtient une valeur utilisée pour ignorer les erreurs lors du traitement du fichier PDF. |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. L'algorithme de substitution de police suit ces étapes : 1. Si l'utilisateur définit explicitement la propriété DefaultFontName, vérifier si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, rechercher les polices ajoutées via le {@code FontRepository.Sources}. 3. Analyser le texte pour identifier son alphabet ou son script et suggérer des noms de police en conséquence. Tenter de localiser et d'utiliser ces polices depuis le système. 4. En dernier recours, rechercher dans le système toute police capable d'afficher les caractères requis. |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | Définit le mode d'optimisation du code-barres. |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | Indique que toutes les polices seront converties en versions TTF Unicode. Cela est utile pour des raisons de compatibilité et pour optimiser l'utilisation des polices, car chaque nouvelle police TTF ne contiendra pas tous les symboles de la police source, mais uniquement les symboles utilisés dans le texte. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Obtient/definit le nom par défaut de la police utilisée pour remplacer les polices manquantes. |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Obtient ou définit l’indication selon laquelle les erreurs liées à l’absence de police seront ignorées. true - signifie que les erreurs d’absence de police seront ignorées. Les segments de texte faisant référence à des ressources incorrectes seront sautés lors du traitement. false par défaut |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | Obtient ou définit le mode haute qualité pour l'interpolation. |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | Nombre maximal de polices dans le cache de polices. La valeur par défaut est 10. |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | Nombre maximal de symboles dans le cache de symboles. La valeur par défaut est 100. |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | Obtient ou définit le mode d'optimisation des dimensions. |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | Obtient ou définit une valeur utilisée pour mettre à l'échelle toutes les images de la page afin d'ajuster la largeur de la page. |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | Définit un mode où les polices système sont rendues nativement. |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | Définit une valeur utilisée pour ignorer les erreurs lors du traitement du fichier PDF. |
| [setUseFontHinting](#setUseFontHinting-boolean-) | L'utilisation de ce drapeau active le mécanisme d'optimisation des polices. L'optimisation des polices consiste à utiliser des instructions mathématiques pour ajuster l'affichage d'une police vectorielle. Dans certains cas, activer ce drapeau peut résoudre des problèmes de lisibilité du texte. À l'heure actuelle, l'utilisation de ce drapeau ne peut avoir d'effet que pour les polices TTF, si ces polices sont utilisées dans le document source. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Définit un drapeau qui détermine si le nouveau moteur d'imagerie est utilisé ou non. |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle. |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

Initialise une nouvelle instance de l'objet {@code RenderingOptions}.

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. L'algorithme de substitution de police suit ces étapes : 1. Si l'utilisateur définit explicitement la propriété DefaultFontName, vérifier si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, rechercher les polices ajoutées via le {@code FontRepository.Sources}. 3. Analyser le texte pour identifier son alphabet ou son script et suggérer des noms de police en conséquence. Tenter de localiser et d'utiliser ces polices depuis le système. 4. En dernier recours, rechercher dans le système toute police capable d'afficher les caractères requis.

**Returns:**
valeur booléenne

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

Obtient le mode d'optimisation du code‑barres.

**Returns:**
valeur booléenne

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

Indique que toutes les polices seront converties en versions TTF Unicode. Cela est utile pour des raisons de compatibilité et pour optimiser l'utilisation des polices, car chaque nouvelle police TTF ne contiendra pas tous les symboles de la police source, mais uniquement les symboles utilisés dans le texte.

**Returns:**
valeur booléenne

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

Obtient/definit le nom par défaut de la police utilisée pour remplacer les polices manquantes.

**Returns:**
valeur String

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle.

**Returns:**
Valeur flottante

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Obtient ou définit l’indication selon laquelle les erreurs liées à l’absence de police seront ignorées. true - signifie que les erreurs d’absence de police seront ignorées. Les segments de texte faisant référence à des ressources incorrectes seront sautés lors du traitement. false par défaut

**Returns:**
valeur booléenne

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

Obtient ou définit le mode haute qualité pour l'interpolation.

**Returns:**
valeur booléenne

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

Nombre maximal de polices dans le cache de polices. La valeur par défaut est 10.

**Returns:**
valeur int

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

Nombre maximal de symboles dans le cache de symboles. La valeur par défaut est 100.

**Returns:**
valeur int

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

Obtient ou définit le mode d'optimisation des dimensions.

**Returns:**
valeur booléenne

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

Obtient ou définit une valeur utilisée pour mettre à l'échelle toutes les images de la page afin d'ajuster la largeur de la page.

**Returns:**
valeur booléenne @deprecated ScaleImagesToFitPageWidth est obsolète.

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

Obtient un mode où les polices système sont rendues nativement.

**Returns:**
valeur booléenne

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

L'utilisation de ce drapeau active le mécanisme d'optimisation des polices. L'optimisation des polices consiste à utiliser des instructions mathématiques pour ajuster l'affichage d'une police vectorielle. Dans certains cas, activer ce drapeau peut résoudre des problèmes de lisibilité du texte. À l'heure actuelle, l'utilisation de ce drapeau ne peut avoir d'effet que pour les polices TTF, si ces polices sont utilisées dans le document source.

**Returns:**
valeur booléenne

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

Obtient un drapeau qui détermine si le nouveau moteur d'imagerie est utilisé ou non.

**Returns:**
valeur booléenne @deprecated UseNewImagingEngine est obsolète

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle.

**Returns:**
Valeur flottante

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

Obtient une valeur utilisée pour ignorer les erreurs lors du traitement du fichier PDF.

**Returns:**
valeur booléenne

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. L'algorithme de substitution de police suit ces étapes : 1. Si l'utilisateur définit explicitement la propriété DefaultFontName, vérifier si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, rechercher les polices ajoutées via le {@code FontRepository.Sources}. 3. Analyser le texte pour identifier son alphabet ou son script et suggérer des noms de police en conséquence. Tenter de localiser et d'utiliser ces polices depuis le système. 4. En dernier recours, rechercher dans le système toute police capable d'afficher les caractères requis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

Définit le mode d'optimisation du code-barres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

Indique que toutes les polices seront converties en versions TTF Unicode. Cela est utile pour des raisons de compatibilité et pour optimiser l'utilisation des polices, car chaque nouvelle police TTF ne contiendra pas tous les symboles de la police source, mais uniquement les symboles utilisés dans le texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Obtient/definit le nom par défaut de la police utilisée pour remplacer les polices manquantes.

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Obtient ou définit l’indication selon laquelle les erreurs liées à l’absence de police seront ignorées. true - signifie que les erreurs d’absence de police seront ignorées. Les segments de texte faisant référence à des ressources incorrectes seront sautés lors du traitement. false par défaut

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

Obtient ou définit le mode haute qualité pour l'interpolation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

Nombre maximal de polices dans le cache de polices. La valeur par défaut est 10.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

Nombre maximal de symboles dans le cache de symboles. La valeur par défaut est 100.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

Obtient ou définit le mode d'optimisation des dimensions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

Obtient ou définit une valeur utilisée pour mettre à l'échelle toutes les images de la page afin d'ajuster la largeur de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne @deprecated ScaleImagesToFitPageWidth est obsolète. |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

Définit un mode où les polices système sont rendues nativement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

Définit une valeur utilisée pour ignorer les erreurs lors du traitement du fichier PDF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

L'utilisation de ce drapeau active le mécanisme d'optimisation des polices. L'optimisation des polices consiste à utiliser des instructions mathématiques pour ajuster l'affichage d'une police vectorielle. Dans certains cas, activer ce drapeau peut résoudre des problèmes de lisibilité du texte. À l'heure actuelle, l'utilisation de ce drapeau ne peut avoir d'effet que pour les polices TTF, si ces polices sont utilisées dans le document source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

Définit un drapeau qui détermine si le nouveau moteur d'imagerie est utilisé ou non.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne @deprecated UseNewImagingEngine est obsolète |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |
