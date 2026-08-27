---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe MemoryExtender. Lors de l’utilisation de gros fichiers sur un système avec une mémoire tampon limitée, elle peut être activée pour utiliser l’espace disque comme mémoire d’échange temporaire."
type: docs
weight: 3020
url: /fr/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

Représente la classe MemoryExtender. Lors de l’utilisation de gros fichiers sur un système avec une mémoire tampon limitée, elle peut être activée pour utiliser l’espace disque comme mémoire d’échange temporaire.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | Obtenir l'analyseur de cache personnalisé. |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | Le temps maximal pour le rendu d'un seul élément utilisé dans la conversion de page en image. Valeur par défaut 10000 millisecondes. Utilisé uniquement lorsque isSkipHeavyContentEnabled() == true. |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | Obtenir le statut du champ EnabledMultiPageImageCache. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | Est activé pour utiliser OptimizedMemoryStream comme stockage mémoire par défaut. Nécessaire pour travailler avec de gros documents de plus de 2 Go. La valeur par défaut est FALSE. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | Est activé pour utiliser OptimizedMemoryStream comme stockage mémoire par défaut. Nécessaire pour travailler avec de gros documents de plus de 2 Go. La valeur par défaut est FALSE. |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | Est activé pour ignorer les objets à forte consommation de mémoire lors du rendu en cas de manque de mémoire du tas. La valeur par défaut est FALSE. |
| [isSwapEnabled](#isSwapEnabled--) | Est activé pour utiliser l'espace disque comme mémoire d'échange temporaire. La valeur par défaut est FALSE. |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | Obtient une valeur indiquant si les dossiers manquants doivent être créés automatiquement. <p>Si défini sur {@code true}, les méthodes Aspose qui enregistrent par chemin tenteront de créer la structure de dossiers cible si elle n'existe pas déjà. <p>La valeur par défaut est {@code false}. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Appliquer le nouvel analyseur de cache personnalisé. |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | Le temps maximal pour le rendu d'un seul élément utilisé dans la conversion de page en image. Valeur par défaut 10000 millisecondes Utilisé uniquement lorsque isSkipHeavyContentEnabled() == true. |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | Définir le nouveau statut du champ EnabledMultiPageImageCache. |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | Définir le drapeau pour activer l'ignorance des objets à forte consommation de mémoire lors du rendu en cas de manque de mémoire du tas. |
| [setSwapEnabled](#setSwapEnabled-boolean-) | Définir le drapeau indiquant si l'espace disque est activé pour être utilisé comme mémoire d'échange temporaire. |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | Définit une valeur indiquant si les dossiers manquants doivent être créés automatiquement. <p>Si la valeur est {@code true}, les méthodes Aspose qui enregistrent par chemin tenteront de créer la structure de dossiers cible si elle n'existe pas déjà. <p>La valeur par défaut est {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

Obtenir l'analyseur de cache personnalisé.

**Returns:**
Objet CallBackPageImage

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

Le temps maximal pour le rendu d'un seul élément utilisé dans la conversion de page en image. Valeur par défaut 10000 millisecondes. Utilisé uniquement lorsque isSkipHeavyContentEnabled() == true.

**Returns:**
int value Nombre de millisecondes

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

Obtenir le statut du champ EnabledMultiPageImageCache.

**Returns:**
valeur booléenne

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

Est activé pour utiliser OptimizedMemoryStream comme stockage mémoire par défaut. Nécessaire pour travailler avec de gros documents de plus de 2 Go. La valeur par défaut est FALSE.

**Returns:**
valeur booléenne

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

Est activé pour utiliser OptimizedMemoryStream comme stockage mémoire par défaut. Nécessaire pour travailler avec de gros documents de plus de 2 Go. La valeur par défaut est FALSE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

Est activé pour ignorer les objets à forte consommation de mémoire lors du rendu en cas de manque de mémoire du tas. La valeur par défaut est FALSE.

**Returns:**
valeur booléenne

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

Est activé pour utiliser l'espace disque comme mémoire d'échange temporaire. La valeur par défaut est FALSE.

**Returns:**
valeur booléenne

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

Obtient une valeur indiquant si les dossiers manquants doivent être créés automatiquement. <p>Si défini sur {@code true}, les méthodes Aspose qui enregistrent par chemin tenteront de créer la structure de dossiers cible si elle n'existe pas déjà. <p>La valeur par défaut est {@code false}.

**Returns:**
valeur booléenne

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
Appliquer le nouvel analyseur de cache personnalisé.

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

Le temps maximal pour le rendu d'un seul élément utilisé dans la conversion de page en image. Valeur par défaut 10000 millisecondes Utilisé uniquement lorsque isSkipHeavyContentEnabled() == true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | int value Nombre de millisecondes |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

Définir le nouveau statut du champ EnabledMultiPageImageCache.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | valeur booléenne |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

Définir le drapeau pour activer l'ignorance des objets à forte consommation de mémoire lors du rendu en cas de manque de mémoire du tas.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

Définir le drapeau indiquant si l'espace disque est activé pour être utilisé comme mémoire d'échange temporaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

Définit une valeur indiquant si les dossiers manquants doivent être créés automatiquement. <p>Si la valeur est {@code true}, les méthodes Aspose qui enregistrent par chemin tenteront de créer la structure de dossiers cible si elle n'existe pas déjà. <p>La valeur par défaut est {@code false}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
