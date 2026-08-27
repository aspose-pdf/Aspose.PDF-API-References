---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe qui décrit l'algorithme d'optimisation de document. Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources()."
type: docs
weight: 40
url: /fr/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

Classe qui décrit l'algorithme d'optimisation de document. Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources().

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [all](#all--) | Crée une stratégie d'optimisation avec toutes les options activées. Veuillez noter que seules les options qui ne modifient aucune fonctionnalité du document sont activées. Par exemple, la compression d'images et le désincorporation des polices ne seront pas activées (et peuvent être incorporées manuellement). |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | Si défini sur {@link}, tous les flux de contenu de page non compressés seront compressés à l'aide du filtre FlateDecode pendant {@code Document#OptimizeResources()}. La valeur par défaut est {@link} pour préserver la compatibilité ascendante. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Ensemble d'options décrivant comment les images du document seront compressées et les paramètres de la compression. |
| [getImageEncoding](#getImageEncoding--) | Encodage d'image qui sera utilisé. |
| [getImageQuality](#getImageQuality--) | Spécifie le niveau de compression d'image lorsque le drapeau CompressIamges est utilisé. |
| [getMaxResoultion](#getMaxResoultion--) | Spécifie la résolution maximale des images. Si une image a une résolution supérieure, elle sera redimensionnée. |
| [isAllowReusePageContent](#isAllowReusePageContent--) | Si vrai, le contenu des pages sera réutilisé lorsque le document est optimisé pour des pages identiques. |
| [isCompressImages](#isCompressImages--) | Si ce drapeau est défini sur true, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality. |
| [isCompressObjects](#isCompressObjects--) | Si ce drapeau est défini sur {@code }, les objets Pdf seront empaquetés dans des Objest Streams et compressés pour réduire la taille du fichier pdf. |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | Si ce drapeau est défini sur true, les flux de ressources seront analysés. Si des flux en double sont trouvés (c.-à-d. si le contenu du flux est identique), alors ces flux seront stockés comme un seul objet. Cela permet de diminuer la taille du document dans certains cas (par exemple, lorsque le même document a été concaténé plusieurs fois). |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | Supprimer les informations privées (informations de morceau de page). |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | Si ce drapeau est défini sur true, tous les objets du document seront vérifiés et les objets inutilisés (c.-à-d. les objets qui n'ont aucune référence) seront supprimés du document. |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | Si ce drapeau est défini sur true, chaque ressource est vérifiée quant à son utilisation. Si une ressource n'est jamais utilisée, alors la ressource est supprimée. Cela peut réduire la taille du document, par exemple lorsque des pages ont été extraites du document. |
| [isResizeImages](#isResizeImages--) | Si ce drapeau est défini sur true et que CompressImages est true, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié. |
| [isSubsetFonts](#isSubsetFonts--) | Les polices seront converties en sous-ensembles si elles sont définies sur true. |
| [isUnembedFonts](#isUnembedFonts--) | Ne pas intégrer les polices si elles sont définies sur true. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Si vrai, le contenu des pages sera réutilisé lorsque le document est optimisé pour des pages identiques. |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | Si défini sur {@link}, tous les flux de contenu de page non compressés seront compressés à l'aide du filtre FlateDecode pendant {@code Document#OptimizeResources()}. La valeur par défaut est {@link} pour préserver la compatibilité ascendante. |
| [setCompressImages](#setCompressImages-boolean-) | Si ce drapeau est défini sur true, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality. |
| [setCompressObjects](#setCompressObjects-boolean-) | Si ce drapeau est défini sur {@code }, les objets Pdf seront empaquetés dans des Objest Streams et compressés pour réduire la taille du fichier pdf. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Ensemble d'options décrivant comment les images du document seront compressées et les paramètres de la compression. |
| [setImageEncoding](#setImageEncoding-int-) | Encodage d'image qui sera utilisé. |
| [setImageQuality](#setImageQuality-int-) | Spécifie le niveau de compression d'image lorsque le drapeau CompressIamges est utilisé. |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | Si ce drapeau est défini sur true, les flux de ressources seront analysés. Si des flux en double sont trouvés (c.-à-d. si le contenu du flux est identique), alors ces flux seront stockés comme un seul objet. Cela permet de diminuer la taille du document dans certains cas (par exemple, lorsque le même document a été concaténé plusieurs fois). |
| [setMaxResoultion](#setMaxResoultion-int-) | Spécifie la résolution maximale des images. Si une image a une résolution supérieure, elle sera redimensionnée. |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | Supprimer les informations privées (informations de morceau de page). |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | Si ce drapeau est défini sur true, tous les objets du document seront vérifiés et les objets inutilisés (c.-à-d. les objets qui n'ont aucune référence) seront supprimés du document. |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | Si ce drapeau est défini sur true, chaque ressource est vérifiée quant à son utilisation. Si une ressource n'est jamais utilisée, alors la ressource est supprimée. Cela peut réduire la taille du document, par exemple lorsque des pages ont été extraites du document. |
| [setResizeImages](#setResizeImages-boolean-) | Si ce drapeau est défini sur true et que CompressImages est true, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Les polices seront converties en sous-ensembles si elles sont définies sur true. |
| [setUnembedFonts](#setUnembedFonts-boolean-) | Ne pas intégrer les polices si elles sont définies sur true. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

Crée une stratégie d'optimisation avec toutes les options activées. Veuillez noter que seules les options qui ne modifient aucune fonctionnalité du document sont activées. Par exemple, la compression d'images et le désincorporation des polices ne seront pas activées (et peuvent être incorporées manuellement).

**Returns:**
Objet OptimizationOptions.

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

Si défini sur {@link}, tous les flux de contenu de page non compressés seront compressés à l'aide du filtre FlateDecode pendant {@code Document#OptimizeResources()}. La valeur par défaut est {@link} pour préserver la compatibilité ascendante.

**Returns:**
valeur booléenne

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Ensemble d'options décrivant comment les images du document seront compressées et les paramètres de la compression.

**Returns:**
Instance ImageCompressionOptions

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

Encodage d'image qui sera utilisé.

**Returns:**
Élément ImageEncoding

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

Spécifie le niveau de compression d'image lorsque le drapeau CompressIamges est utilisé.

**Returns:**
valeur int @deprecated Veuillez utiliser ImageCompressionOptions.ImageQuality à la place.

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

Spécifie la résolution maximale des images. Si une image a une résolution supérieure, elle sera redimensionnée.

**Returns:**
valeur int

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

Si vrai, le contenu des pages sera réutilisé lorsque le document est optimisé pour des pages identiques.

**Returns:**
valeur booléenne

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

Si ce drapeau est défini sur true, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality.

**Returns:**
valeur booléenne @deprecated Veuillez utiliser ImageCompressionOptions.CompressImages à la place.

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

Si ce drapeau est défini sur {@code }, les objets Pdf seront empaquetés dans des Objest Streams et compressés pour réduire la taille du fichier pdf.

**Returns:**
valeur booléenne

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

Si ce drapeau est défini sur true, les flux de ressources seront analysés. Si des flux en double sont trouvés (c.-à-d. si le contenu du flux est identique), alors ces flux seront stockés comme un seul objet. Cela permet de diminuer la taille du document dans certains cas (par exemple, lorsque le même document a été concaténé plusieurs fois).

**Returns:**
valeur booléenne

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

Supprimer les informations privées (informations de morceau de page).

**Returns:**
valeur booléenne

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

Si ce drapeau est défini sur true, tous les objets du document seront vérifiés et les objets inutilisés (c.-à-d. les objets qui n'ont aucune référence) seront supprimés du document.

**Returns:**
valeur booléenne

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

Si ce drapeau est défini sur true, chaque ressource est vérifiée quant à son utilisation. Si une ressource n'est jamais utilisée, alors la ressource est supprimée. Cela peut réduire la taille du document, par exemple lorsque des pages ont été extraites du document.

**Returns:**
valeur booléenne

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

Si ce drapeau est défini sur true et que CompressImages est true, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié.

**Returns:**
valeur booléenne @deprecated Veuillez utiliser ImageCompressionOptions.ResizeImages à la place.

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

Les polices seront converties en sous-ensembles si elles sont définies sur true.

**Returns:**
valeur booléenne

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

Ne pas intégrer les polices si elles sont définies sur true.

**Returns:**
valeur booléenne

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

Si vrai, le contenu des pages sera réutilisé lorsque le document est optimisé pour des pages identiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

Si défini sur {@link}, tous les flux de contenu de page non compressés seront compressés à l'aide du filtre FlateDecode pendant {@code Document#OptimizeResources()}. La valeur par défaut est {@link} pour préserver la compatibilité ascendante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

Si ce drapeau est défini sur true, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne @deprecated Veuillez utiliser ImageCompressionOptions.CompressImages à la place. |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

Si ce drapeau est défini sur {@code }, les objets Pdf seront empaquetés dans des Objest Streams et compressés pour réduire la taille du fichier pdf.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Ensemble d'options décrivant comment les images du document seront compressées et les paramètres de la compression.

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

Encodage d'image qui sera utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

Spécifie le niveau de compression d'image lorsque le drapeau CompressIamges est utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int @deprecated Veuillez utiliser ImageCompressionOptions.ImageQuality à la place. |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

Si ce drapeau est défini sur true, les flux de ressources seront analysés. Si des flux en double sont trouvés (c.-à-d. si le contenu du flux est identique), alors ces flux seront stockés comme un seul objet. Cela permet de diminuer la taille du document dans certains cas (par exemple, lorsque le même document a été concaténé plusieurs fois).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

Spécifie la résolution maximale des images. Si une image a une résolution supérieure, elle sera redimensionnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

Supprimer les informations privées (informations de morceau de page).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

Si ce drapeau est défini sur true, tous les objets du document seront vérifiés et les objets inutilisés (c.-à-d. les objets qui n'ont aucune référence) seront supprimés du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

Si ce drapeau est défini sur true, chaque ressource est vérifiée quant à son utilisation. Si une ressource n'est jamais utilisée, alors la ressource est supprimée. Cela peut réduire la taille du document, par exemple lorsque des pages ont été extraites du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

Si ce drapeau est défini sur true et que CompressImages est true, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne @deprecated Veuillez utiliser ImageCompressionOptions.ResizeImages à la place. |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Les polices seront converties en sous-ensembles si elles sont définies sur true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

Ne pas intégrer les polices si elles sont définies sur true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
