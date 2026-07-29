---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "Aspose.PDF för Java API-referens"
description: "En renditionsåtgärd som styr uppspelning av multimedia-innehåll."
type: docs
weight: 4180
url: /sv/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

En renditionsåtgärd som styr uppspelning av multimedia-innehåll.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Skapar rendition‑åtgärden. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getJavaScript](#getJavaScript--) | Hämtar eller anger JavaScript‑kod som är associerad med åtgärden. |
| [getRendition](#getRendition--) | Hämtar eller anger rendition som är associerad med åtgärden. |
| [getRenditionOperation](#getRenditionOperation--) | Operationen som ska utföras när åtgärden utlöses. |
| [setJavaScript](#setJavaScript-java.lang.String-) | Hämtar eller anger JavaScript‑kod som är associerad med åtgärden. |
| [setRenditionOperation](#setRenditionOperation-int-) | Operationen som ska utföras när åtgärden utlöses. |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
Skapar rendition‑åtgärden.

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

Hämtar eller anger JavaScript‑kod som är associerad med åtgärden.

**Returns:**
String värde

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

Hämtar eller anger rendition som är associerad med åtgärden.

**Returns:**
Rendition‑instans

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

Operationen som ska utföras när åtgärden utlöses.

**Returns:**
RenditionOperation‑element

### setJavaScript {#setJavaScript-java.lang.String-}
Hämtar eller anger JavaScript‑kod som är associerad med åtgärden.

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

Operationen som ska utföras när åtgärden utlöses.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | RenditionOperation‑element |
