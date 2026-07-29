---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den Dokumentoptimierungsalgorithmus beschreibt. Eine Instanz dieser Klasse kann als Parameter der Methode OptimizeResources() verwendet werden."
type: docs
weight: 40
url: /de/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

Klasse, die den Dokumentoptimierungsalgorithmus beschreibt. Eine Instanz dieser Klasse kann als Parameter der Methode OptimizeResources() verwendet werden.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [all](#all--) | Erstellt eine Optimierungsstrategie mit allen aktivierten Optionen. Bitte beachten Sie, dass nur Optionen aktiviert werden, die die Funktionalität des Dokuments nicht verändern. d. h. Bildkomprimierung und das Entfernen von Schriftart-Einbettungen werden nicht aktiviert (und können manuell eingebettet werden). |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | Wenn auf {@link} gesetzt, werden alle unkomprimierten Seiteninhalts-Streams mithilfe des FlateDecode-Filters während {@code Document#OptimizeResources()} komprimiert. Standard ist {@link}, um die Abwärtskompatibilität zu erhalten. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Menge von Optionen, die beschreiben, ob Bilder im Dokument komprimiert werden und die Parameter der Kompression. |
| [getImageEncoding](#getImageEncoding--) | Bildkodierung, die verwendet wird. |
| [getImageQuality](#getImageQuality--) | Gibt das Komprimierungsniveau für Bilder an, wenn das Flag CompressIamges verwendet wird. |
| [getMaxResoultion](#getMaxResoultion--) | Gibt die maximale Auflösung von Bildern an. Hat ein Bild eine höhere Auflösung, wird es skaliert. |
| [isAllowReusePageContent](#isAllowReusePageContent--) | Wenn true, werden Seiteninhalte wiederverwendet, wenn das Dokument für gleiche Seiten optimiert wird. |
| [isCompressImages](#isCompressImages--) | Wenn dieses Flag auf true gesetzt ist, werden Bilder im Dokument komprimiert. Das Komprimierungsniveau wird über die Eigenschaft ImageQuality angegeben. |
| [isCompressObjects](#isCompressObjects--) | Wenn dieses Flag auf {@code } gesetzt ist, werden PDF-Objekte in Objest Streams gepackt und komprimiert, um die PDF-Dateigröße zu reduzieren. |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | Wenn dieses Flag auf true gesetzt ist, werden Ressourcen-Streams analysiert. Werden doppelte Streams gefunden (d. h. wenn der Stream-Inhalt gleich ist), werden diese Streams als ein Objekt gespeichert. Dies ermöglicht in manchen Fällen eine Verringerung der Dokumentgröße (z. B. wenn dasselbe Dokument mehrfach zusammengefügt wurde). |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | Private Informationen entfernen (Seitenstück-Info). |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | Wenn dieses Flag auf true gesetzt ist, werden alle Dokumentobjekte überprüft und ungenutzte Objekte (d. h. Objekte, die keine Referenz haben) aus dem Dokument entfernt. |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | Wenn dieses Flag auf true gesetzt ist, wird jede Ressource auf ihre Verwendung geprüft. Wird eine Ressource nie verwendet, wird sie entfernt. Dies kann die Dokumentgröße verringern, zum Beispiel wenn Seiten aus dem Dokument extrahiert wurden. |
| [isResizeImages](#isResizeImages--) | Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden Bilder verkleinert, wenn die Bildauflösung größer ist als der angegebene MaxResolution-Parameter. |
| [isSubsetFonts](#isSubsetFonts--) | Schriftarten werden in Teilmengen konvertiert, wenn das Flag auf true gesetzt ist. |
| [isUnembedFonts](#isUnembedFonts--) | Schriftarten nicht einbetten, wenn das Flag auf true gesetzt ist. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Wenn true, werden Seiteninhalte wiederverwendet, wenn das Dokument für gleiche Seiten optimiert wird. |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | Wenn auf {@link} gesetzt, werden alle unkomprimierten Seiteninhalts-Streams mithilfe des FlateDecode-Filters während {@code Document#OptimizeResources()} komprimiert. Standard ist {@link}, um die Abwärtskompatibilität zu erhalten. |
| [setCompressImages](#setCompressImages-boolean-) | Wenn dieses Flag auf true gesetzt ist, werden Bilder im Dokument komprimiert. Das Komprimierungsniveau wird über die Eigenschaft ImageQuality angegeben. |
| [setCompressObjects](#setCompressObjects-boolean-) | Wenn dieses Flag auf {@code } gesetzt ist, werden PDF-Objekte in Objest Streams gepackt und komprimiert, um die PDF-Dateigröße zu reduzieren. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Menge von Optionen, die beschreiben, ob Bilder im Dokument komprimiert werden und die Parameter der Kompression. |
| [setImageEncoding](#setImageEncoding-int-) | Bildkodierung, die verwendet wird. |
| [setImageQuality](#setImageQuality-int-) | Gibt das Komprimierungsniveau für Bilder an, wenn das Flag CompressIamges verwendet wird. |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | Wenn dieses Flag auf true gesetzt ist, werden Ressourcen-Streams analysiert. Werden doppelte Streams gefunden (d. h. wenn der Stream-Inhalt gleich ist), werden diese Streams als ein Objekt gespeichert. Dies ermöglicht in manchen Fällen eine Verringerung der Dokumentgröße (z. B. wenn dasselbe Dokument mehrfach zusammengefügt wurde). |
| [setMaxResoultion](#setMaxResoultion-int-) | Gibt die maximale Auflösung von Bildern an. Hat ein Bild eine höhere Auflösung, wird es skaliert. |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | Private Informationen entfernen (Seitenstück-Info). |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | Wenn dieses Flag auf true gesetzt ist, werden alle Dokumentobjekte überprüft und ungenutzte Objekte (d. h. Objekte, die keine Referenz haben) aus dem Dokument entfernt. |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | Wenn dieses Flag auf true gesetzt ist, wird jede Ressource auf ihre Verwendung geprüft. Wird eine Ressource nie verwendet, wird sie entfernt. Dies kann die Dokumentgröße verringern, zum Beispiel wenn Seiten aus dem Dokument extrahiert wurden. |
| [setResizeImages](#setResizeImages-boolean-) | Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden Bilder verkleinert, wenn die Bildauflösung größer ist als der angegebene MaxResolution-Parameter. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Schriftarten werden in Teilmengen konvertiert, wenn das Flag auf true gesetzt ist. |
| [setUnembedFonts](#setUnembedFonts-boolean-) | Schriftarten nicht einbetten, wenn das Flag auf true gesetzt ist. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

Erstellt eine Optimierungsstrategie mit allen aktivierten Optionen. Bitte beachten Sie, dass nur Optionen aktiviert werden, die die Funktionalität des Dokuments nicht verändern. d. h. Bildkomprimierung und das Entfernen von Schriftart-Einbettungen werden nicht aktiviert (und können manuell eingebettet werden).

**Returns:**
OptimizationOptions-Objekt.

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

Wenn auf {@link} gesetzt, werden alle unkomprimierten Seiteninhalts-Streams mithilfe des FlateDecode-Filters während {@code Document#OptimizeResources()} komprimiert. Standard ist {@link}, um die Abwärtskompatibilität zu erhalten.

**Returns:**
boolescher Wert

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Menge von Optionen, die beschreiben, ob Bilder im Dokument komprimiert werden und die Parameter der Kompression.

**Returns:**
ImageCompressionOptions-Instanz

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

Bildkodierung, die verwendet wird.

**Returns:**
ImageEncoding-Element

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

Gibt das Komprimierungsniveau für Bilder an, wenn das Flag CompressIamges verwendet wird.

**Returns:**
int value @deprecated Bitte verwenden Sie stattdessen ImageCompressionOptions.ImageQuality.

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

Gibt die maximale Auflösung von Bildern an. Hat ein Bild eine höhere Auflösung, wird es skaliert.

**Returns:**
int-Wert

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

Wenn true, werden Seiteninhalte wiederverwendet, wenn das Dokument für gleiche Seiten optimiert wird.

**Returns:**
boolescher Wert

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

Wenn dieses Flag auf true gesetzt ist, werden Bilder im Dokument komprimiert. Das Komprimierungsniveau wird über die Eigenschaft ImageQuality angegeben.

**Returns:**
boolescher Wert @deprecated Bitte verwenden Sie stattdessen ImageCompressionOptions.CompressImages.

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

Wenn dieses Flag auf {@code } gesetzt ist, werden PDF-Objekte in Objest Streams gepackt und komprimiert, um die PDF-Dateigröße zu reduzieren.

**Returns:**
boolescher Wert

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

Wenn dieses Flag auf true gesetzt ist, werden Ressourcen-Streams analysiert. Werden doppelte Streams gefunden (d. h. wenn der Stream-Inhalt gleich ist), werden diese Streams als ein Objekt gespeichert. Dies ermöglicht in manchen Fällen eine Verringerung der Dokumentgröße (z. B. wenn dasselbe Dokument mehrfach zusammengefügt wurde).

**Returns:**
boolescher Wert

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

Private Informationen entfernen (Seitenstück-Info).

**Returns:**
boolescher Wert

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

Wenn dieses Flag auf true gesetzt ist, werden alle Dokumentobjekte überprüft und ungenutzte Objekte (d. h. Objekte, die keine Referenz haben) aus dem Dokument entfernt.

**Returns:**
boolescher Wert

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

Wenn dieses Flag auf true gesetzt ist, wird jede Ressource auf ihre Verwendung geprüft. Wird eine Ressource nie verwendet, wird sie entfernt. Dies kann die Dokumentgröße verringern, zum Beispiel wenn Seiten aus dem Dokument extrahiert wurden.

**Returns:**
boolescher Wert

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden Bilder verkleinert, wenn die Bildauflösung größer ist als der angegebene MaxResolution-Parameter.

**Returns:**
boolescher Wert @deprecated Bitte verwenden Sie stattdessen ImageCompressionOptions.ResizeImages.

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

Schriftarten werden in Teilmengen konvertiert, wenn das Flag auf true gesetzt ist.

**Returns:**
boolescher Wert

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

Schriftarten nicht einbetten, wenn das Flag auf true gesetzt ist.

**Returns:**
boolescher Wert

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

Wenn true, werden Seiteninhalte wiederverwendet, wenn das Dokument für gleiche Seiten optimiert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

Wenn auf {@link} gesetzt, werden alle unkomprimierten Seiteninhalts-Streams mithilfe des FlateDecode-Filters während {@code Document#OptimizeResources()} komprimiert. Standard ist {@link}, um die Abwärtskompatibilität zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

Wenn dieses Flag auf true gesetzt ist, werden Bilder im Dokument komprimiert. Das Komprimierungsniveau wird über die Eigenschaft ImageQuality angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert @deprecated Bitte verwenden Sie stattdessen ImageCompressionOptions.CompressImages. |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

Wenn dieses Flag auf {@code } gesetzt ist, werden PDF-Objekte in Objest Streams gepackt und komprimiert, um die PDF-Dateigröße zu reduzieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Menge von Optionen, die beschreiben, ob Bilder im Dokument komprimiert werden und die Parameter der Kompression.

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

Bildkodierung, die verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ImageEncoding-Element |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

Gibt das Komprimierungsniveau für Bilder an, wenn das Flag CompressIamges verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int value @deprecated Bitte verwenden Sie stattdessen ImageCompressionOptions.ImageQuality. |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

Wenn dieses Flag auf true gesetzt ist, werden Ressourcen-Streams analysiert. Werden doppelte Streams gefunden (d. h. wenn der Stream-Inhalt gleich ist), werden diese Streams als ein Objekt gespeichert. Dies ermöglicht in manchen Fällen eine Verringerung der Dokumentgröße (z. B. wenn dasselbe Dokument mehrfach zusammengefügt wurde).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

Gibt die maximale Auflösung von Bildern an. Hat ein Bild eine höhere Auflösung, wird es skaliert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

Private Informationen entfernen (Seitenstück-Info).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

Wenn dieses Flag auf true gesetzt ist, werden alle Dokumentobjekte überprüft und ungenutzte Objekte (d. h. Objekte, die keine Referenz haben) aus dem Dokument entfernt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

Wenn dieses Flag auf true gesetzt ist, wird jede Ressource auf ihre Verwendung geprüft. Wird eine Ressource nie verwendet, wird sie entfernt. Dies kann die Dokumentgröße verringern, zum Beispiel wenn Seiten aus dem Dokument extrahiert wurden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden Bilder verkleinert, wenn die Bildauflösung größer ist als der angegebene MaxResolution-Parameter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert @deprecated Bitte verwenden Sie stattdessen ImageCompressionOptions.ResizeImages. |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Schriftarten werden in Teilmengen konvertiert, wenn das Flag auf true gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

Schriftarten nicht einbetten, wenn das Flag auf true gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
