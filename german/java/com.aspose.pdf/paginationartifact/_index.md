---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine abstrakte Basisklasse für Paginierungsartefakte in einem Dokument dar."
type: docs
weight: 3460
url: /de/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

Stellt eine abstrakte Basisklasse für Paginierungsartefakte in einem Dokument dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEndPage](#getEndPage--) | Liest oder setzt die Endseitennummer für das Artefakt. Der Wert muss größer oder gleich 0 sein. Wenn ein Wert kleiner als 0 gesetzt wird, wird er auf 0 angepasst. Der Standardwert 0 bedeutet, dass keine Endseitenbegrenzungen vorhanden sind. |
| [getStartPage](#getStartPage--) | Liest oder setzt die Startseitennummer für das Artefakt. Der Wert muss größer oder gleich 1 sein. Wenn ein Wert kleiner als 1 gesetzt wird, wird er auf 1 angepasst. |
| [getSubset](#getSubset--) | Liest oder setzt die Teilmenge von Seiten, auf die das Artefakt angewendet wird (z. B. alle Seiten, gerade Seiten, ungerade Seiten). |
| [setEndPage](#setEndPage-int-) | Liest oder setzt die Endseitennummer für das Artefakt. Der Wert muss größer oder gleich 0 sein. Wenn ein Wert kleiner als 0 gesetzt wird, wird er auf 0 angepasst. Der Standardwert 0 bedeutet, dass keine Endseitenbegrenzungen vorhanden sind. |
| [setStartPage](#setStartPage-int-) | Liest oder setzt die Startseitennummer für das Artefakt. Der Wert muss größer oder gleich 1 sein. Wenn ein Wert kleiner als 1 gesetzt wird, wird er auf 1 angepasst. |
| [setSubset](#setSubset-int-) | Liest oder setzt die Teilmenge von Seiten, auf die das Artefakt angewendet wird (z. B. alle Seiten, gerade Seiten, ungerade Seiten). |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

Liest oder setzt die Endseitennummer für das Artefakt. Der Wert muss größer oder gleich 0 sein. Wenn ein Wert kleiner als 0 gesetzt wird, wird er auf 0 angepasst. Der Standardwert 0 bedeutet, dass keine Endseitenbegrenzungen vorhanden sind.

**Returns:**
int-Wert

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

Liest oder setzt die Startseitennummer für das Artefakt. Der Wert muss größer oder gleich 1 sein. Wenn ein Wert kleiner als 1 gesetzt wird, wird er auf 1 angepasst.

**Returns:**
int-Wert

### getSubset {#getSubset--}
```
public final int getSubset()
```

Liest oder setzt die Teilmenge von Seiten, auf die das Artefakt angewendet wird (z. B. alle Seiten, gerade Seiten, ungerade Seiten).

**Returns:**
int-Wert

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

Liest oder setzt die Endseitennummer für das Artefakt. Der Wert muss größer oder gleich 0 sein. Wenn ein Wert kleiner als 0 gesetzt wird, wird er auf 0 angepasst. Der Standardwert 0 bedeutet, dass keine Endseitenbegrenzungen vorhanden sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

Liest oder setzt die Startseitennummer für das Artefakt. Der Wert muss größer oder gleich 1 sein. Wenn ein Wert kleiner als 1 gesetzt wird, wird er auf 1 angepasst.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

Liest oder setzt die Teilmenge von Seiten, auf die das Artefakt angewendet wird (z. B. alle Seiten, gerade Seiten, ungerade Seiten).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
