---
title: "Resurser"
linktitle: "Resurser"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar sidresurser."
type: docs
weight: 4220
url: /sv/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

Klass som representerar sidresurser.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | Rensar cachad data, frigör minne osv. |
| [getExtGStates](#getExtGStates--) | Hämtar alla ExGStates från resurser. |
| [getFonts](#getFonts--) | Hämtar {@code Fonts} resurssamling |
| [getFonts](#getFonts-boolean-) | Returnerar fonts-samling. Om resurserna inte innehåller fonts‑posten kommer den att skapas beroende på flaggan CreateIfAbsent. |
| [getForms](#getForms--) | Hämtar {@code Forms} formulärsamling |
| [getImages](#getImages--) | Hämtar {@code Images} bildsamling |
| [getResourceDictionary](#getResourceDictionary--) | Internt fält |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | Hämtar resurser för |
| [isCommonResource](#isCommonResource--) | Sant om dessa resurser är gemensamma, d.v.s. delas mellan flera sidor (placerade i sidornas ordbok eller i varje sida som objektreferens). Manipulation med gemensamma resurser måste utföras mycket försiktigt, exempelvis kan borttagning av ett objekt från gemensamma resurser på en sida orsaka fel på andra sidor om det borttagna objektet användes på andra sidor. |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | Endast för internt bruk! |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Rensar cachad data, frigör minne osv.

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

Hämtar alla ExGStates från resurser.

**Returns:**
Returnerar en ordbok med ExGStates namnnycklar.

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

Hämtar {@code Fonts} resurssamling

**Returns:**
FontCollection-objekt

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

Returnerar fonts-samling. Om resurserna inte innehåller fonts‑posten kommer den att skapas beroende på flaggan CreateIfAbsent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createIfAbsent |  | Om denna flagga är sann så kommer fonts att skapas om detta post saknas. |

**Returns:**
Fonts-samling.

### getForms {#getForms--}
```
public XFormCollection getForms()
```

Hämtar {@code Forms} formulärsamling

**Returns:**
XFormCollection-objekt

### getImages {#getImages--}
```
public XImageCollection getImages()
```

Hämtar {@code Images} bildsamling

**Returns:**
XImageCollection-objekt

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

Internt fält

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
Hämtar resurser för

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

Sant om dessa resurser är gemensamma, d.v.s. delas mellan flera sidor (placerade i sidornas ordbok eller i varje sida som objektreferens). Manipulation med gemensamma resurser måste utföras mycket försiktigt, exempelvis kan borttagning av ett objekt från gemensamma resurser på en sida orsaka fel på andra sidor om det borttagna objektet användes på andra sidor.

**Returns:**
booleskt värde

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
Endast för internt bruk!
