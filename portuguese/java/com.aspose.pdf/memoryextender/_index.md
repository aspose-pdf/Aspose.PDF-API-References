---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe MemoryExtender. Ao usar arquivos grandes em um sistema com memória heap limitada, pode ser habilitado para usar espaço em disco como memória swap temporária."
type: docs
weight: 3020
url: /pt/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

Representa a classe MemoryExtender. Ao usar arquivos grandes em um sistema com memória heap limitada, pode ser habilitado para usar espaço em disco como memória swap temporária.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | Obter o analisador de cache personalizado. |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | O tempo máximo para renderizar um único elemento usado na conversão de página para imagem. Valor padrão 10000 milissegundos. Usado somente quando isSkipHeavyContentEnabled() == true. |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | Obter o status do campo EnabledMultiPageImageCache. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | Está habilitado para usar OptimizedMemoryStream como armazenamento de memória padrão. Necessário para trabalhar com documentos grandes acima de 2 Gb. O valor padrão é FALSE. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | Está habilitado para usar OptimizedMemoryStream como armazenamento de memória padrão. Necessário para trabalhar com documentos grandes acima de 2 Gb. O valor padrão é FALSE. |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | Está habilitado para pular objetos com alto consumo de memória na renderização quando há falta de memória heap. O valor padrão é FALSE. |
| [isSwapEnabled](#isSwapEnabled--) | Está habilitado para usar espaço em disco como memória swap temporária. O valor padrão é FALSE. |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | Obtém um valor que indica se pastas ausentes devem ser criadas automaticamente. <p>Se definido como {@code true}, os métodos Aspose que salvam por caminho tentarão criar a estrutura de pastas de destino caso ainda não exista. <p>O valor padrão é {@code false}. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Aplicar o novo analisador de cache personalizado. |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | O tempo máximo para renderizar um único elemento usado na conversão de página para imagem. Valor padrão 10000 milissegundos. Usado somente quando isSkipHeavyContentEnabled() == true. |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | Definir o novo status para o campo EnabledMultiPageImageCache. |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | Definir a bandeira para habilitar a omissão de objetos com alto consumo de memória na renderização quando houver falta de memória heap. |
| [setSwapEnabled](#setSwapEnabled-boolean-) | Defina a flag que indica se o espaço em disco está habilitado para uso como memória swap temporária. |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | Define um valor que indica se pastas ausentes devem ser criadas automaticamente. <p>Se definido como {@code true}, os métodos da Aspose que salvam por caminho tentarão criar a estrutura de pastas de destino caso ela ainda não exista. <p>O valor padrão é {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

Obter o analisador de cache personalizado.

**Returns:**
Objeto CallBackPageImage

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

O tempo máximo para renderizar um único elemento usado na conversão de página para imagem. Valor padrão 10000 milissegundos. Usado somente quando isSkipHeavyContentEnabled() == true.

**Returns:**
int value Número de milissegundos

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

Obter o status do campo EnabledMultiPageImageCache.

**Returns:**
valor booleano

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

Está habilitado para usar OptimizedMemoryStream como armazenamento de memória padrão. Necessário para trabalhar com documentos grandes acima de 2 Gb. O valor padrão é FALSE.

**Returns:**
valor booleano

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

Está habilitado para usar OptimizedMemoryStream como armazenamento de memória padrão. Necessário para trabalhar com documentos grandes acima de 2 Gb. O valor padrão é FALSE.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

Está habilitado para pular objetos com alto consumo de memória na renderização quando há falta de memória heap. O valor padrão é FALSE.

**Returns:**
valor booleano

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

Está habilitado para usar espaço em disco como memória swap temporária. O valor padrão é FALSE.

**Returns:**
valor booleano

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

Obtém um valor que indica se pastas ausentes devem ser criadas automaticamente. <p>Se definido como {@code true}, os métodos Aspose que salvam por caminho tentarão criar a estrutura de pastas de destino caso ainda não exista. <p>O valor padrão é {@code false}.

**Returns:**
valor booleano

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
Aplicar o novo analisador de cache personalizado.

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

O tempo máximo para renderizar um único elemento usado na conversão de página para imagem. Valor padrão 10000 milissegundos. Usado somente quando isSkipHeavyContentEnabled() == true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | int value Número de milissegundos |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

Definir o novo status para o campo EnabledMultiPageImageCache.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | valor booleano |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

Definir a bandeira para habilitar a omissão de objetos com alto consumo de memória na renderização quando houver falta de memória heap.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

Defina a flag que indica se o espaço em disco está habilitado para uso como memória swap temporária.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

Define um valor que indica se pastas ausentes devem ser criadas automaticamente. <p>Se definido como {@code true}, os métodos da Aspose que salvam por caminho tentarão criar a estrutura de pastas de destino caso ela ainda não exista. <p>O valor padrão é {@code false}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
