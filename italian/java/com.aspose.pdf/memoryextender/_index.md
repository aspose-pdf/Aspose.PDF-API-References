---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe MemoryExtender. Utilizzando file di grandi dimensioni su un sistema con memoria heap limitata, può essere abilitata a usare lo spazio su disco come memoria di swap temporanea."
type: docs
weight: 3020
url: /it/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

Rappresenta la classe MemoryExtender. Utilizzando file di grandi dimensioni su un sistema con memoria heap limitata, può essere abilitata a usare lo spazio su disco come memoria di swap temporanea.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | Ottieni l'analizzatore di cache personalizzato. |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | Il tempo massimo per il rendering di un singolo elemento utilizzato nella conversione di pagina in immagine. Valore predefinito 10000 millisecondi. Usato solo quando isSkipHeavyContentEnabled() == true. |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | Ottieni lo stato del campo EnabledMultiPageImageCache. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | È abilitato a utilizzare OptimizedMemoryStream come archiviazione di memoria predefinita. Necessario per lavorare con documenti di grandi dimensioni superiori a 2 Gb. Il valore predefinito è FALSE. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | È abilitato a utilizzare OptimizedMemoryStream come archiviazione di memoria predefinita. Necessario per lavorare con documenti di grandi dimensioni superiori a 2 Gb. Il valore predefinito è FALSE. |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | È abilitato a ignorare gli oggetti con alto consumo di memoria durante il rendering in caso di mancanza di heap. Il valore predefinito è FALSE. |
| [isSwapEnabled](#isSwapEnabled--) | È abilitato a utilizzare lo spazio su disco come memoria di swap temporanea. Il valore predefinito è FALSE. |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | Restituisce un valore che indica se le cartelle mancanti devono essere create automaticamente. <p>Se impostato su {@code true}, i metodi Aspose che salvano per percorso tenteranno di creare la struttura di cartelle di destinazione se non esiste già. <p>Il valore predefinito è {@code false}. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Applica il nuovo analizzatore di cache personalizzato. |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | Il tempo massimo per il rendering di un singolo elemento utilizzato nella conversione di pagina in immagine. Valore predefinito 10000 millisecondi. Usato solo quando isSkipHeavyContentEnabled() == true. |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | Imposta il nuovo stato per il campo EnabledMultiPageImageCache. |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | Imposta il flag per abilitare l'ignorare gli oggetti con alto consumo di memoria durante il rendering in caso di mancanza di heap. |
| [setSwapEnabled](#setSwapEnabled-boolean-) | Imposta il flag per indicare se lo spazio su disco è abilitato per l'uso come memoria di swap temporanea. |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | Imposta un valore che indica se le cartelle mancanti devono essere create automaticamente. <p>Se impostato su {@code true}, i metodi Aspose che salvano per percorso tenteranno di creare la struttura della cartella di destinazione se non esiste già. <p>Il valore predefinito è {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

Ottieni l'analizzatore di cache personalizzato.

**Returns:**
Oggetto CallBackPageImage

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

Il tempo massimo per il rendering di un singolo elemento utilizzato nella conversione di pagina in immagine. Valore predefinito 10000 millisecondi. Usato solo quando isSkipHeavyContentEnabled() == true.

**Returns:**
int value Numero di millisecondi

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

Ottieni lo stato del campo EnabledMultiPageImageCache.

**Returns:**
valore booleano

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

È abilitato a utilizzare OptimizedMemoryStream come archiviazione di memoria predefinita. Necessario per lavorare con documenti di grandi dimensioni superiori a 2 Gb. Il valore predefinito è FALSE.

**Returns:**
valore booleano

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

È abilitato a utilizzare OptimizedMemoryStream come archiviazione di memoria predefinita. Necessario per lavorare con documenti di grandi dimensioni superiori a 2 Gb. Il valore predefinito è FALSE.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

È abilitato a ignorare gli oggetti con alto consumo di memoria durante il rendering in caso di mancanza di heap. Il valore predefinito è FALSE.

**Returns:**
valore booleano

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

È abilitato a utilizzare lo spazio su disco come memoria di swap temporanea. Il valore predefinito è FALSE.

**Returns:**
valore booleano

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

Restituisce un valore che indica se le cartelle mancanti devono essere create automaticamente. <p>Se impostato su {@code true}, i metodi Aspose che salvano per percorso tenteranno di creare la struttura di cartelle di destinazione se non esiste già. <p>Il valore predefinito è {@code false}.

**Returns:**
valore booleano

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
Applica il nuovo analizzatore di cache personalizzato.

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

Il tempo massimo per il rendering di un singolo elemento utilizzato nella conversione di pagina in immagine. Valore predefinito 10000 millisecondi. Usato solo quando isSkipHeavyContentEnabled() == true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | int value Numero di millisecondi |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

Imposta il nuovo stato per il campo EnabledMultiPageImageCache.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | valore booleano |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

Imposta il flag per abilitare l'ignorare gli oggetti con alto consumo di memoria durante il rendering in caso di mancanza di heap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

Imposta il flag per indicare se lo spazio su disco è abilitato per l'uso come memoria di swap temporanea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

Imposta un valore che indica se le cartelle mancanti devono essere create automaticamente. <p>Se impostato su {@code true}, i metodi Aspose che salvano per percorso tenteranno di creare la struttura della cartella di destinazione se non esiste già. <p>Il valore predefinito è {@code false}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
