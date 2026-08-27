---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de chargement/importation d'un fichier SVG dans un document PDF."
type: docs
weight: 4700
url: /fr/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

Représente les options de chargement/importation d'un fichier SVG dans un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | Crée l'objet {@code SvgLoadOptions}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | Permet de sélectionner le moteur de conversion qui sera utilisé pendant la conversion. Actuellement, le nouveau moteur est en phase de test B, donc cette valeur est définie par défaut sur ConversionEngines.LegacyEngine |
| [getPageInfo](#getPageInfo--) | Obtient les informations de page qui doivent être appliquées lors du chargement du document. |
| [isAdjustPageSize](#isAdjustPageSize--) | Ajuste la taille de la page PDF à la taille du SVG |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | Ajuste la taille de la page PDF à la taille du SVG |
| [setConversionEngine](#setConversionEngine-int-) | Permet de sélectionner le moteur de conversion qui sera utilisé pendant la conversion. Actuellement, le nouveau moteur est en phase de test B, donc cette valeur est définie par défaut sur ConversionEngines.LegacyEngine |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Définit les informations de page qui doivent être appliquées lors du chargement du document. |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

Crée l'objet {@code SvgLoadOptions}.

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Permet de sélectionner le moteur de conversion qui sera utilisé pendant la conversion. Actuellement, le nouveau moteur est en phase de test B, donc cette valeur est définie par défaut sur ConversionEngines.LegacyEngine

**Returns:**
Élément ConversionEngines @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtient les informations de page qui doivent être appliquées lors du chargement du document.

**Returns:**
Objet PageInfo

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

Ajuste la taille de la page PDF à la taille du SVG

**Returns:**
valeur booléenne

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

Ajuste la taille de la page PDF à la taille du SVG

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Permet de sélectionner le moteur de conversion qui sera utilisé pendant la conversion. Actuellement, le nouveau moteur est en phase de test B, donc cette valeur est définie par défaut sur ConversionEngines.LegacyEngine

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| conversionEngine |  | Élément ConversionEngines @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Définit les informations de page qui doivent être appliquées lors du chargement du document.
