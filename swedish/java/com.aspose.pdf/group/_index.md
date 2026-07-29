---
title: "Group"
linktitle: "Group"
second_title: "Aspose.PDF för Java API-referens"
description: "En gruppattributklass som specificerar attributen för sidans sidgrupp för användning i den transparenta avbildningsmodellen."
type: docs
weight: 1850
url: /sv/java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Group

```
public final class Group extends Object
```

En gruppattributklass som specificerar attributen för sidans sidgrupp för användning i den transparenta avbildningsmodellen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Group](#Group-com.aspose.pdf.Page-) | Konstruktorn. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorSpace](#getColorSpace--) | Hämtar ColorSpace <p> |
| [isKnockout](#isKnockout--) | Endast för intern användning. Om detta flagga är falskt, kompositeras senare objekt inom gruppen med tidigare objekt som de överlappar; om sant, kompositeras de med gruppens initiala bakgrund och skriver över ("knock out") eventuella tidigare överlappande objekt. |
| [isTransparency](#isTransparency--) | för intern användning returnerar endast gruppens transparensflagga. |
| [setColorSpace](#setColorSpace-com.aspose.pdf.ColorSpace-) | Gruppens färgrymd. |
| [setKnockout](#setKnockout-com.aspose.pdf.ExtendedBoolean-) | Om detta flagga är falsk, kompositeras senare objekt inom gruppen med tidigare objekt som de överlappar; om den är sann, kompositeras de med gruppens initiala bakgrund och skriver över (\"knock out\") eventuella tidigare överlappande objekt. |

### Group {#Group-com.aspose.pdf.Page-}
Konstruktorn.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Hämtar ColorSpace <p>

**Returns:**
ColorSpace‑värde. @see ColorSpace

### isKnockout {#isKnockout--}
```
public ExtendedBoolean isKnockout()
```

Endast för intern användning. Om detta flagga är falskt, kompositeras senare objekt inom gruppen med tidigare objekt som de överlappar; om sant, kompositeras de med gruppens initiala bakgrund och skriver över ("knock out") eventuella tidigare överlappande objekt.

**Returns:**
ExtendedBoolean-element @see ExtendedBoolean

### isTransparency {#isTransparency--}
```
public boolean isTransparency()
```

för intern användning returnerar endast gruppens transparensflagga.

**Returns:**
booleskt värde

### setColorSpace {#setColorSpace-com.aspose.pdf.ColorSpace-}
Gruppens färgrymd.

### setKnockout {#setKnockout-com.aspose.pdf.ExtendedBoolean-}
Om detta flagga är falsk, kompositeras senare objekt inom gruppen med tidigare objekt som de överlappar; om den är sann, kompositeras de med gruppens initiala bakgrund och skriver över (\"knock out\") eventuella tidigare överlappande objekt.
