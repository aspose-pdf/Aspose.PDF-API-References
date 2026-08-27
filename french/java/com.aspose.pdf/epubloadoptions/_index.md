---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Contient les options de chargement/importation d'un fichier EPUB dans un document PDF."
type: docs
weight: 1220
url: /fr/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

Contient les options de chargement/importation d'un fichier EPUB dans un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | Crée les options de chargement par défaut pour convertir un fichier EPUB en document PDF. Taille de page PDF par défaut - A4 300 dpi 2480 × 3508. |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Crée les options de chargement par défaut pour convertir un fichier EPUB en document PDF. Taille de page PDF par défaut - A4 300 dpi 2480 × 3508. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCustomCss](#getCustomCss--) | Obtient ou définit le Css personnalisé à appliquer lors de l'ouverture du document Epub. |
| [getEngineType](#getEngineType--) | Sélectionnez le type de moteur pour la conversion EPUB vers PDF. La valeur par défaut est EngineType.NEW |
| [getMargin](#getMargin--) | Obtient une référence sur l'objet qui représente les informations de marge. |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | Représente le mode d'utilisation de la zone des marges – définit le traitement des instructions (le cas échéant) du CSS du document importé liées à l'utilisation des marges. |
| [getPageSize](#getPageSize--) | Obtient la taille de page de sortie pour l'importation. |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | ATTENTION ! La fonctionnalité est implémentée mais n'est pas encore exposée dans l'API publique en raison d'un problème bloquant dans la couche OSHARED détecté pour le document d'exemple. Représente le mode d'utilisation de la taille de page lors de la conversion. Les formats (comme HTML, EPUB, etc.) ont généralement une mise en page fluide, ce qui permet d'adapter la taille de page requise. Mais parfois le contenu possède des positions horizontales ou une taille spécifiées qui n'autorisent pas de placer le contenu dans la taille de page requise. Dans ce cas, nous pouvons définir ce qui doit être fait (c’est‑à‑dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du document PDF résultant). |
| [setCustomCss](#setCustomCss-java.lang.String-) | Obtient ou définit le Css personnalisé à appliquer lors de l'ouverture du document Epub. |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | Sélectionnez le type de moteur pour la conversion EPUB vers PDF. La valeur par défaut est EngineType.NEW |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Obtient une référence sur l'objet qui représente les informations de marge. |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | Représente le mode d'utilisation de la zone des marges – définit le traitement des instructions (le cas échéant) du CSS du document importé liées à l'utilisation des marges. |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | ATTENTION ! La fonctionnalité est implémentée mais n'est pas encore exposée dans l'API publique en raison d'un problème bloquant dans la couche OSHARED détecté pour le document d'exemple. Représente le mode d'utilisation de la taille de page lors de la conversion. Les formats (comme HTML, EPUB, etc.) ont généralement une mise en page fluide, ce qui permet d'adapter la taille de page requise. Mais parfois le contenu possède des positions horizontales ou une taille spécifiées qui n'autorisent pas de placer le contenu dans la taille de page requise. Dans ce cas, nous pouvons définir ce qui doit être fait (c’est‑à‑dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du document PDF résultant). |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

Crée les options de chargement par défaut pour convertir un fichier EPUB en document PDF. Taille de page PDF par défaut - A4 300 dpi 2480 × 3508.

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
Crée les options de chargement par défaut pour convertir un fichier EPUB en document PDF. Taille de page PDF par défaut - A4 300 dpi 2480 × 3508.

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

Obtient ou définit le Css personnalisé à appliquer lors de l'ouverture du document Epub.

**Returns:**
valeur String

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

Sélectionnez le type de moteur pour la conversion EPUB vers PDF. La valeur par défaut est EngineType.NEW

**Returns:**
Élément EngineType

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtient une référence sur l'objet qui représente les informations de marge.

**Returns:**
Objet MarginInfo

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

Représente le mode d'utilisation de la zone des marges – définit le traitement des instructions (le cas échéant) du CSS du document importé liées à l'utilisation des marges.

**Returns:**
Valeur MarginsAreaUsageModes @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Obtient la taille de page de sortie pour l'importation.

**Returns:**
Objet Dimension2D

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

ATTENTION ! La fonctionnalité est implémentée mais n'est pas encore exposée dans l'API publique en raison d'un problème bloquant dans la couche OSHARED détecté pour le document d'exemple. Représente le mode d'utilisation de la taille de page lors de la conversion. Les formats (comme HTML, EPUB, etc.) ont généralement une mise en page fluide, ce qui permet d'adapter la taille de page requise. Mais parfois le contenu possède des positions horizontales ou une taille spécifiées qui n'autorisent pas de placer le contenu dans la taille de page requise. Dans ce cas, nous pouvons définir ce qui doit être fait (c’est‑à‑dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du document PDF résultant).

**Returns:**
Valeur PageSizeAdjustmentModes @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
Obtient ou définit le Css personnalisé à appliquer lors de l'ouverture du document Epub.

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
Sélectionnez le type de moteur pour la conversion EPUB vers PDF. La valeur par défaut est EngineType.NEW

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Obtient une référence sur l'objet qui représente les informations de marge.

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

Représente le mode d'utilisation de la zone des marges – définit le traitement des instructions (le cas échéant) du CSS du document importé liées à l'utilisation des marges.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| marginsAreaUsageMode |  | Valeur MarginsAreaUsageModes @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

ATTENTION ! La fonctionnalité est implémentée mais n'est pas encore exposée dans l'API publique en raison d'un problème bloquant dans la couche OSHARED détecté pour le document d'exemple. Représente le mode d'utilisation de la taille de page lors de la conversion. Les formats (comme HTML, EPUB, etc.) ont généralement une mise en page fluide, ce qui permet d'adapter la taille de page requise. Mais parfois le contenu possède des positions horizontales ou une taille spécifiées qui n'autorisent pas de placer le contenu dans la taille de page requise. Dans ce cas, nous pouvons définir ce qui doit être fait (c’est‑à‑dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du document PDF résultant).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | Valeur PageSizeAdjustmentModes @see PageSizeAdjustmentModes |
