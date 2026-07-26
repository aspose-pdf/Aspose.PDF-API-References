---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Repräsentiert die Klasse MemoryExtender. Bei Verwendung großer Dateien auf einem System mit begrenztem Heap-Speicher kann sie aktiviert werden, um Festplattenspeicher als temporären Auslagerungsspeicher zu nutzen."
type: docs
weight: 3020
url: /de/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

Repräsentiert die Klasse MemoryExtender. Bei Verwendung großer Dateien auf einem System mit begrenztem Heap-Speicher kann sie aktiviert werden, um Festplattenspeicher als temporären Auslagerungsspeicher zu nutzen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | Den benutzerdefinierten Cache-Analysator abrufen. |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | Die maximale Zeit für das Rendern eines einzelnen Elements, das bei der Seiten-zu-Bild-Konvertierung verwendet wird. Standardwert 10000 Millisekunden. Wird nur verwendet, wenn isSkipHeavyContentEnabled() == true. |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | Den Status des Feldes EnabledMultiPageImageCache abrufen. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | Ist aktiviert, OptimizedMemoryStream als Standardspeicher zu verwenden. Erforderlich für die Arbeit mit großen Dokumenten über 2 GB. Standardwert ist FALSE. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | Ist aktiviert, OptimizedMemoryStream als Standardspeicher zu verwenden. Erforderlich für die Arbeit mit großen Dokumenten über 2 GB. Standardwert ist FALSE. |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | Ist aktiviert, Objekte mit hohem Speicherverbrauch beim Rendern bei fehlendem Heap-Speicher zu überspringen. Standardwert ist FALSE. |
| [isSwapEnabled](#isSwapEnabled--) | Ist aktiviert, Festplattenspeicher als temporären Auslagerungsspeicher zu verwenden. Standardwert ist FALSE. |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | Gibt einen Wert zurück, der angibt, ob fehlende Ordner automatisch erstellt werden sollen. <p>Wenn auf {@code true} gesetzt, versuchen Aspose-Methoden, die nach Pfad speichern, die Zielordnerstruktur zu erstellen, falls sie noch nicht existiert. <p>Der Standardwert ist {@code false}. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Den neuen benutzerdefinierten Cache-Analysator anwenden. |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | Die maximale Zeit für das Rendern eines einzelnen Elements, das bei der Seiten-zu-Bild-Konvertierung verwendet wird. Standardwert 10000 Millisekunden. Wird nur verwendet, wenn isSkipHeavyContentEnabled() == true. |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | Den neuen Status für das Feld EnabledMultiPageImageCache festlegen. |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | Flag setzen, um das Überspringen von Objekten mit hohem Speicherverbrauch beim Rendern bei fehlendem Heap-Speicher zu aktivieren. |
| [setSwapEnabled](#setSwapEnabled-boolean-) | Flag setzen, ob Festplattenspeicher als temporärer Auslagerungsspeicher verwendet werden soll. |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | Setzt einen Wert, der angibt, ob fehlende Ordner automatisch erstellt werden sollen. <p>Wenn auf {@code true} gesetzt, versuchen Aspose-Methoden, die nach Pfad speichern, die Zielordnerstruktur zu erstellen, falls sie noch nicht existiert. <p>Der Standardwert ist {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

Den benutzerdefinierten Cache-Analysator abrufen.

**Returns:**
CallBackPageImage-Objekt

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

Die maximale Zeit für das Rendern eines einzelnen Elements, das bei der Seiten-zu-Bild-Konvertierung verwendet wird. Standardwert 10000 Millisekunden. Wird nur verwendet, wenn isSkipHeavyContentEnabled() == true.

**Returns:**
int-Wert Anzahl der Millisekunden

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

Den Status des Feldes EnabledMultiPageImageCache abrufen.

**Returns:**
boolescher Wert

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

Ist aktiviert, OptimizedMemoryStream als Standardspeicher zu verwenden. Erforderlich für die Arbeit mit großen Dokumenten über 2 GB. Standardwert ist FALSE.

**Returns:**
boolescher Wert

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

Ist aktiviert, OptimizedMemoryStream als Standardspeicher zu verwenden. Erforderlich für die Arbeit mit großen Dokumenten über 2 GB. Standardwert ist FALSE.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

Ist aktiviert, Objekte mit hohem Speicherverbrauch beim Rendern bei fehlendem Heap-Speicher zu überspringen. Standardwert ist FALSE.

**Returns:**
boolescher Wert

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

Ist aktiviert, Festplattenspeicher als temporären Auslagerungsspeicher zu verwenden. Standardwert ist FALSE.

**Returns:**
boolescher Wert

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

Gibt einen Wert zurück, der angibt, ob fehlende Ordner automatisch erstellt werden sollen. <p>Wenn auf {@code true} gesetzt, versuchen Aspose-Methoden, die nach Pfad speichern, die Zielordnerstruktur zu erstellen, falls sie noch nicht existiert. <p>Der Standardwert ist {@code false}.

**Returns:**
boolescher Wert

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
Den neuen benutzerdefinierten Cache-Analysator anwenden.

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

Die maximale Zeit für das Rendern eines einzelnen Elements, das bei der Seiten-zu-Bild-Konvertierung verwendet wird. Standardwert 10000 Millisekunden. Wird nur verwendet, wenn isSkipHeavyContentEnabled() == true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert Anzahl der Millisekunden |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

Den neuen Status für das Feld EnabledMultiPageImageCache festlegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | boolescher Wert |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

Flag setzen, um das Überspringen von Objekten mit hohem Speicherverbrauch beim Rendern bei fehlendem Heap-Speicher zu aktivieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

Flag setzen, ob Festplattenspeicher als temporärer Auslagerungsspeicher verwendet werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

Setzt einen Wert, der angibt, ob fehlende Ordner automatisch erstellt werden sollen. <p>Wenn auf {@code true} gesetzt, versuchen Aspose-Methoden, die nach Pfad speichern, die Zielordnerstruktur zu erstellen, falls sie noch nicht existiert. <p>Der Standardwert ist {@code false}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
