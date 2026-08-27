---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som beskriver dokumentoptimeringsalgoritmen. En instans av denna klass kan användas som parameter till metoden OptimizeResources()."
type: docs
weight: 40
url: /sv/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

Klass som beskriver dokumentoptimeringsalgoritmen. En instans av denna klass kan användas som parameter till metoden OptimizeResources().

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [all](#all--) | Skapar optimeringsstrategi med alla alternativ aktiverade. Observera att endast alternativ som inte ändrar någon funktionalitet i dokumentet aktiveras. Dvs. bildkomprimering och avbäddning av teckensnitt kommer inte att aktiveras (och kan bäddas in manuellt). |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | Om den sätts till {@link} komprimeras alla okomprimerade sidinnehållsströmmar med FlateDecode-filtret under {@code Document#OptimizeResources()}. Standard är {@link} för att bevara bakåtkompatibilitet. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Uppsättning av alternativ som beskriver hur bilder i dokumentet ska komprimeras och parametrarna för komprimeringen. |
| [getImageEncoding](#getImageEncoding--) | Bildkodning som kommer att användas. |
| [getImageQuality](#getImageQuality--) | Anger komprimeringsnivå för bilder när flaggan CompressIamges används. |
| [getMaxResoultion](#getMaxResoultion--) | Anger maximal upplösning för bilder. Om en bild har högre upplösning skalas den. |
| [isAllowReusePageContent](#isAllowReusePageContent--) | Om true återanvänds sidinnehåll när dokumentet optimeras för identiska sidor. |
| [isCompressImages](#isCompressImages--) | Om detta flagga är satt till true komprimeras bilder i dokumentet. Komprimeringsnivån anges med egenskapen ImageQuality. |
| [isCompressObjects](#isCompressObjects--) | Om detta flagga är satt till {@code } packas PDF-objekt i Objest Streams och komprimeras för att minska PDF-filens storlek. |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | Om detta flagga är satt till true analyseras resurströmmar. Om dubblettströmmar hittas (dvs. om strömmarnas innehåll är lika) lagras dessa strömmar som ett enda objekt. Detta kan minska dokumentets storlek i vissa fall (till exempel när samma dokument har konkatenerats flera gånger). |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | Ta bort privat information (sidstyckeinformation). |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | Om detta flagga är satt till true kontrolleras alla dokumentobjekt och oanvända objekt (dvs. objekt som inte har någon referens) tas bort från dokumentet. |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | Om detta flagga är satt till true kontrolleras varje resurs för dess användning. Om en resurs aldrig används tas den bort. Detta kan minska dokumentets storlek, till exempel när sidor har extraherats från dokumentet. |
| [isResizeImages](#isResizeImages--) | Om detta flagga är satt till true och CompressImages är true kommer bilder att skalas om bildens upplösning är högre än den angivna MaxResolution‑parametern. |
| [isSubsetFonts](#isSubsetFonts--) | Teckensnitt konverteras till delmängder om de är satta till true. |
| [isUnembedFonts](#isUnembedFonts--) | Gör så att teckensnitt inte bäddas in om de är satta till true. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Om true återanvänds sidinnehåll när dokumentet optimeras för identiska sidor. |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | Om den sätts till {@link} komprimeras alla okomprimerade sidinnehållsströmmar med FlateDecode-filtret under {@code Document#OptimizeResources()}. Standard är {@link} för att bevara bakåtkompatibilitet. |
| [setCompressImages](#setCompressImages-boolean-) | Om detta flagga är satt till true komprimeras bilder i dokumentet. Komprimeringsnivån anges med egenskapen ImageQuality. |
| [setCompressObjects](#setCompressObjects-boolean-) | Om detta flagga är satt till {@code } packas PDF-objekt i Objest Streams och komprimeras för att minska PDF-filens storlek. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Uppsättning av alternativ som beskriver hur bilder i dokumentet ska komprimeras och parametrarna för komprimeringen. |
| [setImageEncoding](#setImageEncoding-int-) | Bildkodning som kommer att användas. |
| [setImageQuality](#setImageQuality-int-) | Anger komprimeringsnivå för bilder när flaggan CompressIamges används. |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | Om detta flagga är satt till true analyseras resurströmmar. Om dubblettströmmar hittas (dvs. om strömmarnas innehåll är lika) lagras dessa strömmar som ett enda objekt. Detta kan minska dokumentets storlek i vissa fall (till exempel när samma dokument har konkatenerats flera gånger). |
| [setMaxResoultion](#setMaxResoultion-int-) | Anger maximal upplösning för bilder. Om en bild har högre upplösning skalas den. |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | Ta bort privat information (sidstyckeinformation). |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | Om detta flagga är satt till true kontrolleras alla dokumentobjekt och oanvända objekt (dvs. objekt som inte har någon referens) tas bort från dokumentet. |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | Om detta flagga är satt till true kontrolleras varje resurs för dess användning. Om en resurs aldrig används tas den bort. Detta kan minska dokumentets storlek, till exempel när sidor har extraherats från dokumentet. |
| [setResizeImages](#setResizeImages-boolean-) | Om detta flagga är satt till true och CompressImages är true kommer bilder att skalas om bildens upplösning är högre än den angivna MaxResolution‑parametern. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Teckensnitt konverteras till delmängder om de är satta till true. |
| [setUnembedFonts](#setUnembedFonts-boolean-) | Gör så att teckensnitt inte bäddas in om de är satta till true. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

Skapar optimeringsstrategi med alla alternativ aktiverade. Observera att endast alternativ som inte ändrar någon funktionalitet i dokumentet aktiveras. Dvs. bildkomprimering och avbäddning av teckensnitt kommer inte att aktiveras (och kan bäddas in manuellt).

**Returns:**
OptimizationOptions‑objekt.

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

Om den sätts till {@link} komprimeras alla okomprimerade sidinnehållsströmmar med FlateDecode-filtret under {@code Document#OptimizeResources()}. Standard är {@link} för att bevara bakåtkompatibilitet.

**Returns:**
booleskt värde

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Uppsättning av alternativ som beskriver hur bilder i dokumentet ska komprimeras och parametrarna för komprimeringen.

**Returns:**
ImageCompressionOptions‑instans

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

Bildkodning som kommer att användas.

**Returns:**
ImageEncoding‑element

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

Anger komprimeringsnivå för bilder när flaggan CompressIamges används.

**Returns:**
int‑värde @deprecated Använd ImageCompressionOptions.ImageQuality istället.

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

Anger maximal upplösning för bilder. Om en bild har högre upplösning skalas den.

**Returns:**
int‑värde

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

Om true återanvänds sidinnehåll när dokumentet optimeras för identiska sidor.

**Returns:**
booleskt värde

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

Om detta flagga är satt till true komprimeras bilder i dokumentet. Komprimeringsnivån anges med egenskapen ImageQuality.

**Returns:**
booleskt värde @deprecated Använd ImageCompressionOptions.CompressImages istället.

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

Om detta flagga är satt till {@code } packas PDF-objekt i Objest Streams och komprimeras för att minska PDF-filens storlek.

**Returns:**
booleskt värde

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

Om detta flagga är satt till true analyseras resurströmmar. Om dubblettströmmar hittas (dvs. om strömmarnas innehåll är lika) lagras dessa strömmar som ett enda objekt. Detta kan minska dokumentets storlek i vissa fall (till exempel när samma dokument har konkatenerats flera gånger).

**Returns:**
booleskt värde

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

Ta bort privat information (sidstyckeinformation).

**Returns:**
booleskt värde

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

Om detta flagga är satt till true kontrolleras alla dokumentobjekt och oanvända objekt (dvs. objekt som inte har någon referens) tas bort från dokumentet.

**Returns:**
booleskt värde

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

Om detta flagga är satt till true kontrolleras varje resurs för dess användning. Om en resurs aldrig används tas den bort. Detta kan minska dokumentets storlek, till exempel när sidor har extraherats från dokumentet.

**Returns:**
booleskt värde

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

Om detta flagga är satt till true och CompressImages är true kommer bilder att skalas om bildens upplösning är högre än den angivna MaxResolution‑parametern.

**Returns:**
booleskt värde @deprecated Använd ImageCompressionOptions.ResizeImages istället.

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

Teckensnitt konverteras till delmängder om de är satta till true.

**Returns:**
booleskt värde

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

Gör så att teckensnitt inte bäddas in om de är satta till true.

**Returns:**
booleskt värde

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

Om true återanvänds sidinnehåll när dokumentet optimeras för identiska sidor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

Om den sätts till {@link} komprimeras alla okomprimerade sidinnehållsströmmar med FlateDecode-filtret under {@code Document#OptimizeResources()}. Standard är {@link} för att bevara bakåtkompatibilitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

Om detta flagga är satt till true komprimeras bilder i dokumentet. Komprimeringsnivån anges med egenskapen ImageQuality.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde @deprecated Använd ImageCompressionOptions.CompressImages istället. |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

Om detta flagga är satt till {@code } packas PDF-objekt i Objest Streams och komprimeras för att minska PDF-filens storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Uppsättning av alternativ som beskriver hur bilder i dokumentet ska komprimeras och parametrarna för komprimeringen.

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

Bildkodning som kommer att användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ImageEncoding‑element |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

Anger komprimeringsnivå för bilder när flaggan CompressIamges används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde @deprecated Använd ImageCompressionOptions.ImageQuality istället. |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

Om detta flagga är satt till true analyseras resurströmmar. Om dubblettströmmar hittas (dvs. om strömmarnas innehåll är lika) lagras dessa strömmar som ett enda objekt. Detta kan minska dokumentets storlek i vissa fall (till exempel när samma dokument har konkatenerats flera gånger).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

Anger maximal upplösning för bilder. Om en bild har högre upplösning skalas den.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

Ta bort privat information (sidstyckeinformation).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

Om detta flagga är satt till true kontrolleras alla dokumentobjekt och oanvända objekt (dvs. objekt som inte har någon referens) tas bort från dokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

Om detta flagga är satt till true kontrolleras varje resurs för dess användning. Om en resurs aldrig används tas den bort. Detta kan minska dokumentets storlek, till exempel när sidor har extraherats från dokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

Om detta flagga är satt till true och CompressImages är true kommer bilder att skalas om bildens upplösning är högre än den angivna MaxResolution‑parametern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde @deprecated Använd ImageCompressionOptions.ResizeImages istället. |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Teckensnitt konverteras till delmängder om de är satta till true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

Gör så att teckensnitt inte bäddas in om de är satta till true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
