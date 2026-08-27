---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar MemoryExtender-klassen. Genom att använda stora filer på ett system med begränsat heap-minne kan den aktiveras för att använda diskutrymme som temporärt swap-minne."
type: docs
weight: 3020
url: /sv/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

Representerar MemoryExtender-klassen. Genom att använda stora filer på ett system med begränsat heap-minne kan den aktiveras för att använda diskutrymme som temporärt swap-minne.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | Hämta den anpassade cache‑analysatorn. |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | Den maximala tiden för rendering av ett enskilt element som används vid konvertering från sida till bild. Standardvärde 10000 millisekunder. Används endast när isSkipHeavyContentEnabled() == true |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | Hämta statusen för fältet EnabledMultiPageImageCache |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | Är aktiverat för att använda OptimizedMemoryStream som standardminneslagring. Krävs för arbete med stora dokument över 2 Gb. Standardvärde är FALSE |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | Är aktiverat för att använda OptimizedMemoryStream som standardminneslagring. Krävs för arbete med stora dokument över 2 Gb. Standardvärde är FALSE |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | Är aktiverat för att hoppa över objekt med hög minnesförbrukning vid rendering när heapminnet är otillräckligt. Standardvärde är FALSE |
| [isSwapEnabled](#isSwapEnabled--) | Är aktiverat för att använda diskutrymme som temporärt swap‑minne. Standardvärde är FALSE |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | Hämtar ett värde som indikerar om saknade mappar ska skapas automatiskt. <p>Om den sätts till {@code true} kommer Aspose‑metoder som sparar efter sökväg att försöka skapa målmapparna om de ännu inte finns. <p>Standardvärdet är {@code false}. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Tillämpar den nya anpassade cache‑analysatorn. |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | Den maximala tiden för rendering av ett enskilt element som används vid konvertering från sida till bild. Standardvärde 10000 millisekunder Används endast när isSkipHeavyContentEnabled() == true |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | Ställ in den nya statusen för fältet EnabledMultiPageImageCache |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | Ställ in flaggan för att möjliggöra att hoppa över objekt med hög minnesförbrukning vid rendering när heapminnet är otillräckligt. |
| [setSwapEnabled](#setSwapEnabled-boolean-) | Ställ in flaggan för om diskutrymme är aktiverat för att användas som temporärt swap‑minne. |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | Ställer in ett värde som indikerar om saknade mappar ska skapas automatiskt. <p>Om den sätts till {@code true} kommer Aspose‑metoder som sparar efter sökväg att försöka skapa målmapparna om de ännu inte finns. <p>Standardvärdet är {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

Hämta den anpassade cache‑analysatorn.

**Returns:**
CallBackPageImage‑objekt

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

Den maximala tiden för rendering av ett enskilt element som används vid konvertering från sida till bild. Standardvärde 10000 millisekunder. Används endast när isSkipHeavyContentEnabled() == true

**Returns:**
int‑värde Antal millisekunder

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

Hämta statusen för fältet EnabledMultiPageImageCache

**Returns:**
booleskt värde

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

Är aktiverat för att använda OptimizedMemoryStream som standardminneslagring. Krävs för arbete med stora dokument över 2 Gb. Standardvärde är FALSE

**Returns:**
booleskt värde

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

Är aktiverat för att använda OptimizedMemoryStream som standardminneslagring. Krävs för arbete med stora dokument över 2 Gb. Standardvärde är FALSE

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

Är aktiverat för att hoppa över objekt med hög minnesförbrukning vid rendering när heapminnet är otillräckligt. Standardvärde är FALSE

**Returns:**
booleskt värde

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

Är aktiverat för att använda diskutrymme som temporärt swap‑minne. Standardvärde är FALSE

**Returns:**
booleskt värde

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

Hämtar ett värde som indikerar om saknade mappar ska skapas automatiskt. <p>Om den sätts till {@code true} kommer Aspose‑metoder som sparar efter sökväg att försöka skapa målmapparna om de ännu inte finns. <p>Standardvärdet är {@code false}.

**Returns:**
booleskt värde

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
Tillämpar den nya anpassade cache‑analysatorn.

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

Den maximala tiden för rendering av ett enskilt element som används vid konvertering från sida till bild. Standardvärde 10000 millisekunder Används endast när isSkipHeavyContentEnabled() == true

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde Antal millisekunder |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

Ställ in den nya statusen för fältet EnabledMultiPageImageCache

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | booleskt värde |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

Ställ in flaggan för att möjliggöra att hoppa över objekt med hög minnesförbrukning vid rendering när heapminnet är otillräckligt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

Ställ in flaggan för om diskutrymme är aktiverat för att användas som temporärt swap‑minne.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

Ställer in ett värde som indikerar om saknade mappar ska skapas automatiskt. <p>Om den sätts till {@code true} kommer Aspose‑metoder som sparar efter sökväg att försöka skapa målmapparna om de ännu inte finns. <p>Standardvärdet är {@code false}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
