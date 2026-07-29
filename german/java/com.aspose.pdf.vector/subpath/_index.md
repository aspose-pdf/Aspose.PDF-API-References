---
title: "SubPath"
linktitle: "SubPath"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Vektorgrafik-Objekt auf der Seite dar. Grundsätzlich werden Vektorgrafik-Objekte durch zwei Gruppen von SubPaths repräsentiert. Eine davon wird durch eine Menge von Linien und dargestellt."
type: docs
weight: 60
url: /de/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

Stellt ein Vektorgrafik‑Objekt auf der Seite dar. Grundsätzlich werden Vektorgrafik‑Objekte durch zwei Gruppen von SubPaths repräsentiert. Eine davon wird durch eine Menge von Linien und Kurven dargestellt. Die anderen werden als Rechtecke präsentiert und können manchmal verwechselt werden. In der Regel ist es ein rechteckiger Bereich, der eine Farbe hat, aber sehr häufig wird dieses Rechteck am Anfang der Seite platziert und definiert den gesamten Seitenbereich in Weiß. So erhalten Sie den SubPath, aber visuell sehen Sie nur den Text auf der Seite.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRectangle](#getRectangle--) | Liefert das begrenzende Rechteck des GraphicElement. |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Liefert das begrenzende Rechteck des GraphicElement.

**Returns:**
Rechteck-Instanz
