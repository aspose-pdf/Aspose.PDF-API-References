---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Options d'enregistrement pour l'exportation au format XPS"
type: docs
weight: 5770
url: /fr/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Options d'enregistrement pour l'exportation au format XPS

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [getDefaultFont](#getDefaultFont--) | Obtient/definit le nom de police par défaut. Utilisé si le nom de police intégré n'est pas trouvé dans le système. |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | Indique s'il faut préserver le texte transparent (OCRisé). |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | Obtient/definit le drapeau d'utilisation des polices TrueType incorporées. Éviter l'utilisation des polices TrueType incorporées peut réduire le temps de conversion. |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | Obtient ou définit l'option UseNewImagingEngine. |
| [setBatchSize](#setBatchSize-int-) | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | Obtient/definit le nom de police par défaut. Utilisé si le nom de police intégré n'est pas trouvé dans le système. |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Indique s'il faut préserver le texte transparent (OCRisé). |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | Obtient/definit le drapeau d'utilisation des polices TrueType incorporées. Éviter l'utilisation des polices TrueType incorporées peut réduire le temps de conversion. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Obtient ou définit l'option UseNewImagingEngine. |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

Constructeur

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination.

**Returns:**
valeur int

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

Obtient/definit le nom de police par défaut. Utilisé si le nom de police intégré n'est pas trouvé dans le système.

**Returns:**
valeur String

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

Indique s'il faut préserver le texte transparent (OCRisé).

**Returns:**
valeur booléenne

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

Obtient/definit le drapeau d'utilisation des polices TrueType incorporées. Éviter l'utilisation des polices TrueType incorporées peut réduire le temps de conversion.

**Returns:**
valeur booléenne

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

Obtient ou définit l'option UseNewImagingEngine.

**Returns:**
valeur booléenne @deprecated UseNewImagingEngine est obsolète

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setDefaultFont {#setDefaultFont-java.lang.String-}
Obtient/definit le nom de police par défaut. Utilisé si le nom de police intégré n'est pas trouvé dans le système.

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

Indique s'il faut préserver le texte transparent (OCRisé).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

Obtient/definit le drapeau d'utilisation des polices TrueType incorporées. Éviter l'utilisation des polices TrueType incorporées peut réduire le temps de conversion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

Obtient ou définit l'option UseNewImagingEngine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne @deprecated UseNewImagingEngine est obsolète |
