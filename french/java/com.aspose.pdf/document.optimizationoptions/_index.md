---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe qui décrit l'algorithme d'optimisation du document. Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources(). @deprecated Cette classe est obsolète. Veuillez."
type: docs
weight: 1110
url: /fr/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

Classe décrivant l'algorithme d'optimisation de document. Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources(). @deprecated Cette classe est obsolète. Veuillez utiliser com.aspose.pdf.optimization.OptimizationOptions à la place.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | Obsolète. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [all](#all--) | Crée une stratégie d'optimisation avec toutes les options activées. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | Spécifie la dimension maximale de l'image. Si la largeur ou la hauteur de l'image existante est supérieure à cette valeur, la taille de l'image sera réduite proportionnellement. |
| [getResolution](#getResolution--) | Spécifie le nouveau dpi de l'image lorsque le drapeau CompressIamges est utilisé. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | Spécifie la dimension maximale de l'image. Si la largeur ou la hauteur de l'image existante est supérieure à cette valeur, la taille de l'image sera réduite proportionnellement. |
| [setResolution](#setResolution-int-) | Spécifie le nouveau dpi de l'image lorsque le drapeau CompressIamges est utilisé. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

Obsolète.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

Crée une stratégie d'optimisation avec toutes les options activées.

**Returns:**
Objet OptimizationOptions.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

Spécifie la dimension maximale de l'image. Si la largeur ou la hauteur de l'image existante est supérieure à cette valeur, la taille de l'image sera réduite proportionnellement.

**Returns:**
dimension maximale de l'image

### getResolution {#getResolution--}
```
public int getResolution()
```

Spécifie le nouveau dpi de l'image lorsque le drapeau CompressIamges est utilisé.

**Returns:**
résolution de l'image

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

Spécifie la dimension maximale de l'image. Si la largeur ou la hauteur de l'image existante est supérieure à cette valeur, la taille de l'image sera réduite proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dimension |  | dimension maximale de l'image |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

Spécifie le nouveau dpi de l'image lorsque le drapeau CompressIamges est utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpi |  | résolution de l'image |
