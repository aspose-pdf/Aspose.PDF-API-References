---
title: "XfaParserOptions"
linktitle: "XfaParserOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "klass för att hantera relaterad datakapsling"
type: docs
weight: 5560
url: /sv/java/com.aspose.pdf/xfaparseroptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfaParserOptions

```
public class XfaParserOptions extends Object
```

klass för att hantera relaterad datakapsling

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XfaParserOptions](#XfaParserOptions-java.awt.geom.Dimension2D-) | Initierar en ny instans av klassen {@code XfaParserOptions}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBasePath](#getBasePath--) | Hämtar eller anger basvägen. Värde: Basvägen. |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Om detta egenskap är sann kommer ytterligare röda rektanglar att ritas för obligatoriska Xfa \"excluded groups\". Denna egenskap introducerades eftersom avsaknad av analogier för exkluderade grupper under konvertering av Xfa-representationen av formulär till standard. Den är falsk som standard. |
| [getPageSize](#getPageSize--) | Hämtar eller anger sidans storlek. Värde: Sidans storlek. |
| [getSigned](#getSigned--) | Om denna egenskap är sann kommer dokumentet att konverteras med användning av xfa-formulärströmmen (om den finns). Om den är falsk kommer xfa-formulärströmmen att ignoreras. Denna egenskap introducerades eftersom det inte är tydligt hur man beräknar kontrollsumman som används för att kontrollera signaturen. |
| [setBasePath](#setBasePath-java.net.URI-) | Hämtar eller anger basvägen. Värde: Basvägen. |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Om detta egenskap är sann kommer ytterligare röda rektanglar att ritas för obligatoriska Xfa \"excluded groups\". Denna egenskap introducerades eftersom avsaknad av analogier för exkluderade grupper under konvertering av Xfa-representationen av formulär till standard. Den är falsk som standard. |
| [setPageSize](#setPageSize-java.awt.geom.Dimension2D-) | Hämtar eller anger sidans storlek. Värde: Sidans storlek. |
| [setSigned](#setSigned-boolean-) | Om denna egenskap är sann kommer dokumentet att konverteras med användning av xfa-formulärströmmen (om den finns). Om den är falsk kommer xfa-formulärströmmen att ignoreras. Denna egenskap introducerades eftersom det inte är tydligt hur man beräknar kontrollsumman som används för att kontrollera signaturen. |

### XfaParserOptions {#XfaParserOptions-java.awt.geom.Dimension2D-}
Initierar en ny instans av klassen {@code XfaParserOptions}.

### getBasePath {#getBasePath--}
```
public URI getBasePath()
```

Hämtar eller anger basvägen. Värde: Basvägen.

**Returns:**
URI-objekt

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Om detta egenskap är sann kommer ytterligare röda rektanglar att ritas för obligatoriska Xfa \"excluded groups\". Denna egenskap introducerades eftersom avsaknad av analogier för exkluderade grupper under konvertering av Xfa-representationen av formulär till standard. Den är falsk som standard.

**Returns:**
booleskt värde

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Hämtar eller anger sidans storlek. Värde: Sidans storlek.

**Returns:**
Dimension2D‑objekt

### getSigned {#getSigned--}
```
public boolean getSigned()
```

Om denna egenskap är sann kommer dokumentet att konverteras med användning av xfa-formulärströmmen (om den finns). Om den är falsk kommer xfa-formulärströmmen att ignoreras. Denna egenskap introducerades eftersom det inte är tydligt hur man beräknar kontrollsumman som används för att kontrollera signaturen.

**Returns:**
booleskt värde

### setBasePath {#setBasePath-java.net.URI-}
Hämtar eller anger basvägen. Värde: Basvägen.

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Om detta egenskap är sann kommer ytterligare röda rektanglar att ritas för obligatoriska Xfa \"excluded groups\". Denna egenskap introducerades eftersom avsaknad av analogier för exkluderade grupper under konvertering av Xfa-representationen av formulär till standard. Den är falsk som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setPageSize {#setPageSize-java.awt.geom.Dimension2D-}
Hämtar eller anger sidans storlek. Värde: Sidans storlek.

### setSigned {#setSigned-boolean-}
```
public void setSigned(boolean value)
```

Om denna egenskap är sann kommer dokumentet att konverteras med användning av xfa-formulärströmmen (om den finns). Om den är falsk kommer xfa-formulärströmmen att ignoreras. Denna egenskap introducerades eftersom det inte är tydligt hur man beräknar kontrollsumman som används för att kontrollera signaturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
