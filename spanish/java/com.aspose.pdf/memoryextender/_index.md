---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la clase MemoryExtender. Al usar archivos grandes en un sistema con memoria heap limitada, se puede habilitar para usar espacio en disco como memoria de intercambio temporal."
type: docs
weight: 3020
url: /es/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

Representa la clase MemoryExtender. Al usar archivos grandes en un sistema con memoria heap limitada, se puede habilitar para usar espacio en disco como memoria de intercambio temporal.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | Obtener el analizador de caché personalizado. |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | El tiempo máximo para renderizar un solo elemento utilizado en la conversión de página a imagen. Valor predeterminado 10000 milisegundos. Se usa solo cuando isSkipHeavyContentEnabled() == true. |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | Obtener el estado del campo EnabledMultiPageImageCache. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | Está habilitado para usar OptimizedMemoryStream como almacenamiento de memoria predeterminado. Requerido para trabajar con documentos grandes de más de 2 Gb. El valor predeterminado es FALSE. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | Está habilitado para usar OptimizedMemoryStream como almacenamiento de memoria predeterminado. Requerido para trabajar con documentos grandes de más de 2 Gb. El valor predeterminado es FALSE. |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | Está habilitado para omitir objetos con alto consumo de memoria al renderizar con falta de memoria heap. El valor predeterminado es FALSE. |
| [isSwapEnabled](#isSwapEnabled--) | Está habilitado para usar espacio en disco como memoria de intercambio temporal. El valor predeterminado es FALSE. |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | Obtiene un valor que indica si las carpetas faltantes deben crearse automáticamente. <p>Si se establece en {@code true}, los métodos de Aspose que guardan por ruta intentarán crear la estructura de carpetas de destino si aún no existe. <p>El valor predeterminado es {@code false}. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Aplicar el nuevo analizador de caché personalizado. |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | El tiempo máximo para renderizar un solo elemento utilizado en la conversión de página a imagen. Valor predeterminado 10000 milisegundos. Se usa solo cuando isSkipHeavyContentEnabled() == true. |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | Establecer el nuevo estado para el campo EnabledMultiPageImageCache. |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | Establecer la bandera para habilitar el omitir objetos con alto consumo de memoria al renderizar con falta de memoria heap. |
| [setSwapEnabled](#setSwapEnabled-boolean-) | Establecer la bandera que indica si el espacio en disco está habilitado para usar como memoria de intercambio temporal. |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | Establece un valor que indica si las carpetas faltantes deben crearse automáticamente. <p>Si se establece en {@code true}, los métodos de Aspose que guardan por ruta intentarán crear la estructura de carpetas de destino si aún no existe. <p>El valor predeterminado es {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

Obtener el analizador de caché personalizado.

**Returns:**
Objeto CallBackPageImage

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

El tiempo máximo para renderizar un solo elemento utilizado en la conversión de página a imagen. Valor predeterminado 10000 milisegundos. Se usa solo cuando isSkipHeavyContentEnabled() == true.

**Returns:**
int value Número de milisegundos

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

Obtener el estado del campo EnabledMultiPageImageCache.

**Returns:**
valor booleano

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

Está habilitado para usar OptimizedMemoryStream como almacenamiento de memoria predeterminado. Requerido para trabajar con documentos grandes de más de 2 Gb. El valor predeterminado es FALSE.

**Returns:**
valor booleano

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

Está habilitado para usar OptimizedMemoryStream como almacenamiento de memoria predeterminado. Requerido para trabajar con documentos grandes de más de 2 Gb. El valor predeterminado es FALSE.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

Está habilitado para omitir objetos con alto consumo de memoria al renderizar con falta de memoria heap. El valor predeterminado es FALSE.

**Returns:**
valor booleano

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

Está habilitado para usar espacio en disco como memoria de intercambio temporal. El valor predeterminado es FALSE.

**Returns:**
valor booleano

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

Obtiene un valor que indica si las carpetas faltantes deben crearse automáticamente. <p>Si se establece en {@code true}, los métodos de Aspose que guardan por ruta intentarán crear la estructura de carpetas de destino si aún no existe. <p>El valor predeterminado es {@code false}.

**Returns:**
valor booleano

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
Aplicar el nuevo analizador de caché personalizado.

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

El tiempo máximo para renderizar un solo elemento utilizado en la conversión de página a imagen. Valor predeterminado 10000 milisegundos. Se usa solo cuando isSkipHeavyContentEnabled() == true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | int value Número de milisegundos |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

Establecer el nuevo estado para el campo EnabledMultiPageImageCache.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | valor booleano |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

Establecer la bandera para habilitar el omitir objetos con alto consumo de memoria al renderizar con falta de memoria heap.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

Establecer la bandera que indica si el espacio en disco está habilitado para usar como memoria de intercambio temporal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

Establece un valor que indica si las carpetas faltantes deben crearse automáticamente. <p>Si se establece en {@code true}, los métodos de Aspose que guardan por ruta intentarán crear la estructura de carpetas de destino si aún no existe. <p>El valor predeterminado es {@code false}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
