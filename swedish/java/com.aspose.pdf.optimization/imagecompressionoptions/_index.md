---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen innehåller en uppsättning alternativ för bildkomprimering."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

Klassen innehåller en uppsättning alternativ för bildkomprimering.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEncoding](#getEncoding--) | Hämtar eller anger kodning som används för att lagra bilder. |
| [getImageQuality](#getImageQuality--) | Anger komprimeringsnivå för bilder när flaggan CompressImages används. |
| [getMaxResolution](#getMaxResolution--) | Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas. |
| [getResizeImages](#getResizeImages--) | Om denna flagga är satt till true och CompressImages är true kommer bilder att skalas om bildens upplösning är större än den angivna MaxResolution‑parametern. |
| [getVersion](#getVersion--) | Version av komprimeringsalgoritmen. Möjliga värden är: 1. standardkomprimering, 2. fast (förbättrad komprimering som är snabbare än standard men kanske inte gäller för alla bilder), 3. blandad (standardkomprimering tillämpas på bilder som inte kan komprimeras med den snabbare algoritmen, detta kan ge bästa komprimering men är långsammare än \"fast\" algoritmen. Version \"Fast\" är inte tillämplig för att skala bilder (standardmetoden kommer att användas). Standard är \"Standard\"). |
| [isCompressImages](#isCompressImages--) | Om denna flagga är satt till true kommer bilder att komprimeras i dokumentet. Komprimeringsnivå anges med egenskapen ImageQuality. |
| [setCompressImages](#setCompressImages-boolean-) | Om denna flagga är satt till true kommer bilder att komprimeras i dokumentet. Komprimeringsnivå anges med egenskapen ImageQuality. |
| [setEncoding](#setEncoding-int-) | Hämtar eller anger kodning som används för att lagra bilder. |
| [setImageQuality](#setImageQuality-int-) | Anger komprimeringsnivå för bilder när flaggan CompressImages används. |
| [setMaxResolution](#setMaxResolution-int-) | Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas. |
| [setResizeImages](#setResizeImages-boolean-) | Om denna flagga är satt till true och CompressImages är true kommer bilder att skalas om bildens upplösning är större än den angivna MaxResolution‑parametern. |
| [setVersion](#setVersion-int-) | Version av komprimeringsalgoritmen. Möjliga värden är: 1. standardkomprimering, 2. fast (förbättrad komprimering som är snabbare än standard men kanske inte gäller för alla bilder), 3. blandad (standardkomprimering tillämpas på bilder som inte kan komprimeras med den snabbare algoritmen, detta kan ge bästa komprimering men är långsammare än \"fast\" algoritmen. Version \"Fast\" är inte tillämplig för att skala bilder (standardmetoden kommer att användas). Standard är \"Standard\"). |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

Hämtar eller anger kodning som används för att lagra bilder.

**Returns:**
ImageEncoding‑element

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

Anger komprimeringsnivå för bilder när flaggan CompressImages används.

**Returns:**
int‑värde

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas.

**Returns:**
int‑värde

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

Om denna flagga är satt till true och CompressImages är true kommer bilder att skalas om bildens upplösning är större än den angivna MaxResolution‑parametern.

**Returns:**
booleskt värde

### getVersion {#getVersion--}
```
public final int getVersion()
```

Version av komprimeringsalgoritmen. Möjliga värden är: 1. standardkomprimering, 2. fast (förbättrad komprimering som är snabbare än standard men kanske inte gäller för alla bilder), 3. blandad (standardkomprimering tillämpas på bilder som inte kan komprimeras med den snabbare algoritmen, detta kan ge bästa komprimering men är långsammare än \"fast\" algoritmen. Version \"Fast\" är inte tillämplig för att skala bilder (standardmetoden kommer att användas). Standard är \"Standard\").

**Returns:**
int‑värde

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

Om denna flagga är satt till true kommer bilder att komprimeras i dokumentet. Komprimeringsnivå anges med egenskapen ImageQuality.

**Returns:**
booleskt värde

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

Om denna flagga är satt till true kommer bilder att komprimeras i dokumentet. Komprimeringsnivå anges med egenskapen ImageQuality.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

Hämtar eller anger kodning som används för att lagra bilder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ImageEncoding‑element |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

Anger komprimeringsnivå för bilder när flaggan CompressImages används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

Om denna flagga är satt till true och CompressImages är true kommer bilder att skalas om bildens upplösning är större än den angivna MaxResolution‑parametern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

Version av komprimeringsalgoritmen. Möjliga värden är: 1. standardkomprimering, 2. fast (förbättrad komprimering som är snabbare än standard men kanske inte gäller för alla bilder), 3. blandad (standardkomprimering tillämpas på bilder som inte kan komprimeras med den snabbare algoritmen, detta kan ge bästa komprimering men är långsammare än \"fast\" algoritmen. Version \"Fast\" är inte tillämplig för att skala bilder (standardmetoden kommer att användas). Standard är \"Standard\").

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
