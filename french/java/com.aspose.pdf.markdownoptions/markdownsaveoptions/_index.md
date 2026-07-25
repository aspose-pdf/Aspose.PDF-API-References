---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe d'option d'enregistrement du document au format markdown."
type: docs
weight: 60
url: /fr/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Représente la classe d'option d'enregistrement du document au format markdown.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | Crée une option d'instance pour enregistrer un document au format markdown. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | Obtenir ou définir une zone rectangulaire pour extraire le contenu en markdown. |
| [getEmphasisStyle](#getEmphasisStyle--) | Obtient ou définit le style d'emphase pour le document généré. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | Obtient et définit une propriété indiquant si les graphiques vectoriels doivent être extraits. |
| [getHeadingLevels](#getHeadingLevels--) | Définit les niveaux de titres attendus à utiliser dans la stratégie de reconnaissance des en-têtes par taille de police. Si la valeur de cette propriété est définie, alors la stratégie de reconnaissance des en-têtes {@link HeadingRecognitionStrategy#Heuristic} sera sélectionnée lorsqu'on définit les stratégies {@link HeadingRecognitionStrategy#Auto}, même si le document contient des signets. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Obtient ou définit la stratégie de reconnaissance des titres. |
| [getHeadingStyle](#getHeadingStyle--) | Obtient ou définit le style de titre pour le document généré. |
| [getLineBreakStyle](#getLineBreakStyle--) | Obtient ou définit le style de saut de ligne pour le document généré. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | Obtient et définit le nom du répertoire où enregistrer les ressources du document telles que les images. Si la valeur n'est pas spécifiée, les images seront écrites dans le même répertoire que le fichier markdown lui‑même. Ce n'est pas un chemin, c'est seulement un nom ! Ce répertoire sera créé automatiquement dans le répertoire contenant le fichier markdown enregistré. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | Obtient et définit le nom du répertoire où enregistrer les ressources du document telles que les images. Ce répertoire sera créé automatiquement dans le répertoire contenant le fichier markdown enregistré. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | Obtient et définit l'autorisation de convertir les indices et exposants. Cette valeur est vraie par défaut. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | Obtient et définit l'autorisation d'utiliser une balise img pour insérer des images à gauche et à droite du texte. Dans ce cas, dans le visualiseur markdown, le texte s'enroulera autour de l'image. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | Obtenir ou définir une zone rectangulaire pour extraire le contenu en markdown. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | Obtient ou définit le style d'emphase pour le document généré. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | Obtient et définit une propriété indiquant si les graphiques vectoriels doivent être extraits. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Définit les niveaux de titres attendus à utiliser dans la stratégie de reconnaissance des en-têtes par taille de police. Si la valeur de cette propriété est définie, alors la stratégie de reconnaissance des en-têtes {@link HeadingRecognitionStrategy#Heuristic} sera sélectionnée lorsqu'on définit les stratégies {@link HeadingRecognitionStrategy#Auto}, même si le document contient des signets. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Obtient ou définit la stratégie de reconnaissance des titres. |
| [setHeadingStyle](#setHeadingStyle-int-) | Obtient ou définit le style de titre pour le document généré. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | Obtient ou définit le style de saut de ligne pour le document généré. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | Obtient et définit le nom du répertoire où enregistrer les ressources du document telles que les images. Si la valeur n'est pas spécifiée, les images seront écrites dans le même répertoire que le fichier markdown lui‑même. Ce n'est pas un chemin, c'est seulement un nom ! Ce répertoire sera créé automatiquement dans le répertoire contenant le fichier markdown enregistré. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | Obtient et définit le nom du répertoire où enregistrer les ressources du document telles que les images. Ce répertoire sera créé automatiquement dans le répertoire contenant le fichier markdown enregistré. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | Obtient et définit l'autorisation de convertir les indices et exposants. Cette valeur est vraie par défaut. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | Obtient et définit l'autorisation d'utiliser une balise img pour insérer des images à gauche et à droite du texte. Dans ce cas, dans le visualiseur markdown, le texte s'enroulera autour de l'image. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Crée une option d'instance pour enregistrer un document au format markdown.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

Obtenir ou définir une zone rectangulaire pour extraire le contenu en markdown.

**Returns:**
Instance de Rectangle

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

Obtient ou définit le style d'emphase pour le document généré.

**Returns:**
Élément EmphasisStyle

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

Obtient et définit une propriété indiquant si les graphiques vectoriels doivent être extraits.

**Returns:**
valeur booléenne

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Définit les niveaux de titres attendus à utiliser dans la stratégie de reconnaissance des en-têtes par taille de police. Si la valeur de cette propriété est définie, alors la stratégie de reconnaissance des en-têtes {@link HeadingRecognitionStrategy#Heuristic} sera sélectionnée lorsqu'on définit les stratégies {@link HeadingRecognitionStrategy#Auto}, même si le document contient des signets.

**Returns:**
Instance de HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Obtient ou définit la stratégie de reconnaissance des titres.

**Returns:**
Élément HeadingRecognitionStrategy

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

Obtient ou définit le style de titre pour le document généré.

**Returns:**
Élément HeadingStyle

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

Obtient ou définit le style de saut de ligne pour le document généré.

**Returns:**
Élément LineBreakStyle

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

Obtient et définit le nom du répertoire où enregistrer les ressources du document telles que les images. Si la valeur n'est pas spécifiée, les images seront écrites dans le même répertoire que le fichier markdown lui‑même. Ce n'est pas un chemin, c'est seulement un nom ! Ce répertoire sera créé automatiquement dans le répertoire contenant le fichier markdown enregistré.

**Returns:**
valeur String

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

Obtient et définit le nom du répertoire où enregistrer les ressources du document telles que les images. Ce répertoire sera créé automatiquement dans le répertoire contenant le fichier markdown enregistré.

**Returns:**
valeur String

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

Obtient et définit l'autorisation de convertir les indices et exposants. Cette valeur est vraie par défaut.

**Returns:**
valeur booléenne

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

Obtient et définit l'autorisation d'utiliser une balise img pour insérer des images à gauche et à droite du texte. Dans ce cas, dans le visualiseur markdown, le texte s'enroulera autour de l'image.

**Returns:**
valeur booléenne

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
Obtenir ou définir une zone rectangulaire pour extraire le contenu en markdown.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

Obtient ou définit le style d'emphase pour le document généré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément EmphasisStyle |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

Obtient et définit une propriété indiquant si les graphiques vectoriels doivent être extraits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Définit les niveaux de titres attendus à utiliser dans la stratégie de reconnaissance des en-têtes par taille de police. Si la valeur de cette propriété est définie, alors la stratégie de reconnaissance des en-têtes {@link HeadingRecognitionStrategy#Heuristic} sera sélectionnée lorsqu'on définit les stratégies {@link HeadingRecognitionStrategy#Auto}, même si le document contient des signets.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Obtient ou définit la stratégie de reconnaissance des titres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément HeadingRecognitionStrategy |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

Obtient ou définit le style de titre pour le document généré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément HeadingStyle |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

Obtient ou définit le style de saut de ligne pour le document généré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément LineBreakStyle |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
Obtient et définit le nom du répertoire où enregistrer les ressources du document telles que les images. Si la valeur n'est pas spécifiée, les images seront écrites dans le même répertoire que le fichier markdown lui‑même. Ce n'est pas un chemin, c'est seulement un nom ! Ce répertoire sera créé automatiquement dans le répertoire contenant le fichier markdown enregistré.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
Obtient et définit le nom du répertoire où enregistrer les ressources du document telles que les images. Ce répertoire sera créé automatiquement dans le répertoire contenant le fichier markdown enregistré.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

Obtient et définit l'autorisation de convertir les indices et exposants. Cette valeur est vraie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

Obtient et définit l'autorisation d'utiliser une balise img pour insérer des images à gauche et à droite du texte. Dans ce cas, dans le visualiseur markdown, le texte s'enroulera autour de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
