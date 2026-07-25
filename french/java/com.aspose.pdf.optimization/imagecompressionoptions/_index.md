---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "La classe contient un ensemble d'options pour la compression d'image."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

La classe contient un ensemble d'options pour la compression d'image.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getEncoding](#getEncoding--) | Obtient ou définit l'encodage utilisé pour stocker les images. |
| [getImageQuality](#getImageQuality--) | Spécifie le niveau de compression d'image lorsque le drapeau CompressImages est utilisé. |
| [getMaxResolution](#getMaxResolution--) | Spécifie la résolution maximale des images. Si l'image a une résolution supérieure, elle sera redimensionnée. |
| [getResizeImages](#getResizeImages--) | Si ce drapeau est défini sur true et que CompressImages est true, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié. |
| [getVersion](#getVersion--) | Version de l'algorithme de compression. Les valeurs possibles sont : 1. compression standard, 2. rapide (compression améliorée qui est plus rapide que la standard mais peut ne pas être applicable à toutes les images), 3. mixte (la compression standard est appliquée aux images qui ne peuvent pas être compressées par l'algorithme plus rapide, cela peut offrir la meilleure compression mais est plus lente que l'algorithme \"rapide\". La version \"Fast\" n'est pas applicable au redimensionnement des images (la méthode standard sera utilisée). La valeur par défaut est \"Standard\"). |
| [isCompressImages](#isCompressImages--) | Si ce drapeau est défini sur true, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality. |
| [setCompressImages](#setCompressImages-boolean-) | Si ce drapeau est défini sur true, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality. |
| [setEncoding](#setEncoding-int-) | Obtient ou définit l'encodage utilisé pour stocker les images. |
| [setImageQuality](#setImageQuality-int-) | Spécifie le niveau de compression d'image lorsque le drapeau CompressImages est utilisé. |
| [setMaxResolution](#setMaxResolution-int-) | Spécifie la résolution maximale des images. Si l'image a une résolution supérieure, elle sera redimensionnée. |
| [setResizeImages](#setResizeImages-boolean-) | Si ce drapeau est défini sur true et que CompressImages est true, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié. |
| [setVersion](#setVersion-int-) | Version de l'algorithme de compression. Les valeurs possibles sont : 1. compression standard, 2. rapide (compression améliorée qui est plus rapide que la standard mais peut ne pas être applicable à toutes les images), 3. mixte (la compression standard est appliquée aux images qui ne peuvent pas être compressées par l'algorithme plus rapide, cela peut offrir la meilleure compression mais est plus lente que l'algorithme \"rapide\". La version \"Fast\" n'est pas applicable au redimensionnement des images (la méthode standard sera utilisée). La valeur par défaut est \"Standard\"). |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

Obtient ou définit l'encodage utilisé pour stocker les images.

**Returns:**
Élément ImageEncoding

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

Spécifie le niveau de compression d'image lorsque le drapeau CompressImages est utilisé.

**Returns:**
valeur int

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

Spécifie la résolution maximale des images. Si l'image a une résolution supérieure, elle sera redimensionnée.

**Returns:**
valeur int

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

Si ce drapeau est défini sur true et que CompressImages est true, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié.

**Returns:**
valeur booléenne

### getVersion {#getVersion--}
```
public final int getVersion()
```

Version de l'algorithme de compression. Les valeurs possibles sont : 1. compression standard, 2. rapide (compression améliorée qui est plus rapide que la standard mais peut ne pas être applicable à toutes les images), 3. mixte (la compression standard est appliquée aux images qui ne peuvent pas être compressées par l'algorithme plus rapide, cela peut offrir la meilleure compression mais est plus lente que l'algorithme \"rapide\". La version \"Fast\" n'est pas applicable au redimensionnement des images (la méthode standard sera utilisée). La valeur par défaut est \"Standard\").

**Returns:**
valeur int

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

Si ce drapeau est défini sur true, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality.

**Returns:**
valeur booléenne

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

Si ce drapeau est défini sur true, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

Obtient ou définit l'encodage utilisé pour stocker les images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

Spécifie le niveau de compression d'image lorsque le drapeau CompressImages est utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

Spécifie la résolution maximale des images. Si l'image a une résolution supérieure, elle sera redimensionnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

Si ce drapeau est défini sur true et que CompressImages est true, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

Version de l'algorithme de compression. Les valeurs possibles sont : 1. compression standard, 2. rapide (compression améliorée qui est plus rapide que la standard mais peut ne pas être applicable à toutes les images), 3. mixte (la compression standard est appliquée aux images qui ne peuvent pas être compressées par l'algorithme plus rapide, cela peut offrir la meilleure compression mais est plus lente que l'algorithme \"rapide\". La version \"Fast\" n'est pas applicable au redimensionnement des images (la méthode standard sera utilisée). La valeur par défaut est \"Standard\").

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
