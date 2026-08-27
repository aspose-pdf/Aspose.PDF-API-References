---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Absorber-Objekt für Grafikelemente dar. Führt eine Grafiksuche durch und bietet Zugriff auf die Suchergebnisse über {@code GraphicsAbsorber.Elements}({@link."
type: docs
weight: 30
url: /de/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

Stellt ein Absorber‑Objekt für Grafikelemente bereit. Führt eine Grafiksuche durch und bietet Zugriff auf die Suchergebnisse über die {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements})‑Sammlung.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [dispose](#dispose--) | Gibt alle von der {@link GraphicsAbsorber} Klasse verwendeten Ressourcen frei. |
| [getElements](#getElements--) | Ruft die Sammlung von Suchvorkommen ab, die mit {@link GraphicElement} Objekten dargestellt werden. |
| [resumeUpdate](#resumeUpdate--) | Setzt das Update fürPage#getContents und alle @link XForm#getContents fort. Wurde zur Leistungssteigerung durchgeführt, siehe auch. |
| [suppressUpdate](#suppressUpdate--) | Unterdrückt das Update für Page#getContents und alle @link XForm#getContents. Wurde zur Leistungssteigerung durchgeführt, siehe auch. |
| [visit](#visit-com.aspose.pdf.Page-) | Führt die Suche auf der angegebenen Seite aus. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

Gibt alle von der {@link GraphicsAbsorber} Klasse verwendeten Ressourcen frei.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Ruft die Sammlung von Suchvorkommen ab, die mit {@link GraphicElement} Objekten dargestellt werden.

**Returns:**
GraphicElementCollection-Instanz

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Setzt das Update fürPage#getContents und alle @link XForm#getContents fort. Wurde zur Leistungssteigerung durchgeführt, siehe auch.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Unterdrückt das Update für Page#getContents und alle @link XForm#getContents. Wurde zur Leistungssteigerung durchgeführt, siehe auch.

### visit {#visit-com.aspose.pdf.Page-}
Führt die Suche auf der angegebenen Seite aus.
