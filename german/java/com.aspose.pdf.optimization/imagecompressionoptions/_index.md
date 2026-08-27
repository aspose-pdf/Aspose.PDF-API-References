---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse enthält festgelegte Optionen für die Bildkompression."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

Klasse enthält festgelegte Optionen für die Bildkompression.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEncoding](#getEncoding--) | Ruft die Kodierung ab oder legt sie fest, die zum Speichern von Bildern verwendet wird. |
| [getImageQuality](#getImageQuality--) | Gibt das Komprimierungsniveau für Bilder an, wenn das CompressImages-Flag verwendet wird. |
| [getMaxResolution](#getMaxResolution--) | Gibt die maximale Auflösung von Bildern an. Hat ein Bild eine höhere Auflösung, wird es skaliert. |
| [getResizeImages](#getResizeImages--) | Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden Bilder verkleinert, wenn die Bildauflösung größer als der angegebene MaxResolution-Parameter ist. |
| [getVersion](#getVersion--) | Version des Komprimierungsalgorithmus. Mögliche Werte sind: 1. Standardkomprimierung, 2. Schnell (verbesserte Komprimierung, die schneller ist als die Standardkomprimierung, aber möglicherweise nicht für alle Bilder anwendbar ist), 3. Gemischt (Standardkomprimierung wird auf Bilder angewendet, die nicht mit dem schnelleren Algorithmus komprimiert werden können; dies kann die beste Komprimierung ergeben, ist jedoch langsamer als der \"Fast\"-Algorithmus. Version \"Fast\" ist nicht für die Größenanpassung von Bildern anwendbar (standardmäßige Methode wird verwendet). Standard ist \"Standard\"). |
| [isCompressImages](#isCompressImages--) | Wenn dieses Flag auf true gesetzt ist, werden Bilder im Dokument komprimiert. Das Komprimierungsniveau wird über die ImageQuality-Eigenschaft angegeben. |
| [setCompressImages](#setCompressImages-boolean-) | Wenn dieses Flag auf true gesetzt ist, werden Bilder im Dokument komprimiert. Das Komprimierungsniveau wird über die ImageQuality-Eigenschaft angegeben. |
| [setEncoding](#setEncoding-int-) | Ruft die Kodierung ab oder legt sie fest, die zum Speichern von Bildern verwendet wird. |
| [setImageQuality](#setImageQuality-int-) | Gibt das Komprimierungsniveau für Bilder an, wenn das CompressImages-Flag verwendet wird. |
| [setMaxResolution](#setMaxResolution-int-) | Gibt die maximale Auflösung von Bildern an. Hat ein Bild eine höhere Auflösung, wird es skaliert. |
| [setResizeImages](#setResizeImages-boolean-) | Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden Bilder verkleinert, wenn die Bildauflösung größer als der angegebene MaxResolution-Parameter ist. |
| [setVersion](#setVersion-int-) | Version des Komprimierungsalgorithmus. Mögliche Werte sind: 1. Standardkomprimierung, 2. Schnell (verbesserte Komprimierung, die schneller ist als die Standardkomprimierung, aber möglicherweise nicht für alle Bilder anwendbar ist), 3. Gemischt (Standardkomprimierung wird auf Bilder angewendet, die nicht mit dem schnelleren Algorithmus komprimiert werden können; dies kann die beste Komprimierung ergeben, ist jedoch langsamer als der \"Fast\"-Algorithmus. Version \"Fast\" ist nicht für die Größenanpassung von Bildern anwendbar (standardmäßige Methode wird verwendet). Standard ist \"Standard\"). |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

Ruft die Kodierung ab oder legt sie fest, die zum Speichern von Bildern verwendet wird.

**Returns:**
ImageEncoding-Element

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

Gibt das Komprimierungsniveau für Bilder an, wenn das CompressImages-Flag verwendet wird.

**Returns:**
int-Wert

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

Gibt die maximale Auflösung von Bildern an. Hat ein Bild eine höhere Auflösung, wird es skaliert.

**Returns:**
int-Wert

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden Bilder verkleinert, wenn die Bildauflösung größer als der angegebene MaxResolution-Parameter ist.

**Returns:**
boolescher Wert

### getVersion {#getVersion--}
```
public final int getVersion()
```

Version des Komprimierungsalgorithmus. Mögliche Werte sind: 1. Standardkomprimierung, 2. Schnell (verbesserte Komprimierung, die schneller ist als die Standardkomprimierung, aber möglicherweise nicht für alle Bilder anwendbar ist), 3. Gemischt (Standardkomprimierung wird auf Bilder angewendet, die nicht mit dem schnelleren Algorithmus komprimiert werden können; dies kann die beste Komprimierung ergeben, ist jedoch langsamer als der \"Fast\"-Algorithmus. Version \"Fast\" ist nicht für die Größenanpassung von Bildern anwendbar (standardmäßige Methode wird verwendet). Standard ist \"Standard\").

**Returns:**
int-Wert

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

Wenn dieses Flag auf true gesetzt ist, werden Bilder im Dokument komprimiert. Das Komprimierungsniveau wird über die ImageQuality-Eigenschaft angegeben.

**Returns:**
boolescher Wert

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

Wenn dieses Flag auf true gesetzt ist, werden Bilder im Dokument komprimiert. Das Komprimierungsniveau wird über die ImageQuality-Eigenschaft angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

Ruft die Kodierung ab oder legt sie fest, die zum Speichern von Bildern verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ImageEncoding-Element |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

Gibt das Komprimierungsniveau für Bilder an, wenn das CompressImages-Flag verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

Gibt die maximale Auflösung von Bildern an. Hat ein Bild eine höhere Auflösung, wird es skaliert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden Bilder verkleinert, wenn die Bildauflösung größer als der angegebene MaxResolution-Parameter ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

Version des Komprimierungsalgorithmus. Mögliche Werte sind: 1. Standardkomprimierung, 2. Schnell (verbesserte Komprimierung, die schneller ist als die Standardkomprimierung, aber möglicherweise nicht für alle Bilder anwendbar ist), 3. Gemischt (Standardkomprimierung wird auf Bilder angewendet, die nicht mit dem schnelleren Algorithmus komprimiert werden können; dies kann die beste Komprimierung ergeben, ist jedoch langsamer als der \"Fast\"-Algorithmus. Version \"Fast\" ist nicht für die Größenanpassung von Bildern anwendbar (standardmäßige Methode wird verwendet). Standard ist \"Standard\").

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
