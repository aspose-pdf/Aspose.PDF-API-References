---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Eine Rendition-Aktion, die die Wiedergabe von Multimedia-Inhalten steuert."
type: docs
weight: 4180
url: /de/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

Eine Rendition-Aktion, die die Wiedergabe von Multimedia-Inhalten steuert.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Erstellt die Rendition-Aktion. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getJavaScript](#getJavaScript--) | Liest oder setzt den mit der Aktion verknüpften JavaScript-Code. |
| [getRendition](#getRendition--) | Liest oder setzt die mit der Aktion verbundene Rendition. |
| [getRenditionOperation](#getRenditionOperation--) | Der Vorgang, der ausgeführt werden soll, wenn die Aktion ausgelöst wird. |
| [setJavaScript](#setJavaScript-java.lang.String-) | Liest oder setzt den mit der Aktion verknüpften JavaScript-Code. |
| [setRenditionOperation](#setRenditionOperation-int-) | Der Vorgang, der ausgeführt werden soll, wenn die Aktion ausgelöst wird. |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
Erstellt die Rendition-Aktion.

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

Liest oder setzt den mit der Aktion verknüpften JavaScript-Code.

**Returns:**
String Wert

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

Liest oder setzt die mit der Aktion verbundene Rendition.

**Returns:**
Rendition-Instanz

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

Der Vorgang, der ausgeführt werden soll, wenn die Aktion ausgelöst wird.

**Returns:**
RenditionOperation-Element

### setJavaScript {#setJavaScript-java.lang.String-}
Liest oder setzt den mit der Aktion verknüpften JavaScript-Code.

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

Der Vorgang, der ausgeführt werden soll, wenn die Aktion ausgelöst wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | RenditionOperation-Element |
