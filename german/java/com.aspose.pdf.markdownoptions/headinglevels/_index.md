---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse dar, die mit Überschriftenebenen basierend auf der Schriftgröße arbeitet."
type: docs
weight: 20
url: /de/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

Stellt eine Klasse dar, die mit Überschriftenebenen basierend auf der Schriftgröße arbeitet.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | Erstellt eine neue Instanz der Klasse HeadingLevels. |
| [HeadingLevels](#HeadingLevels-double-) | Erstellt eine neue Instanz der Klasse HeadingLevels. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | Fügt Überschriftenebenen hinzu. |
| [estimateLevel](#estimateLevel-double-) | Schätzt die mögliche Kopfzeilenebene. Wenn fontSize nicht in der Liste der Ebenen gefunden wird, wird die Ebene zurückgegeben, die diesem Schriftgrößenwert am nächsten liegt. Wenn fontSize außerhalb der angegebenen minimalen und maximalen Kopfzeilenebenen liegt, gibt die Methode false zurück. |
| [findLevel](#findLevel-double-int:A-) | Findet die Ebene für die entsprechende Schriftgröße. Sucht nach einer exakten Übereinstimmung. |
| [getAllLevels](#getAllLevels--) | Ruft alle Überschriftenebenen ab. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

Erstellt eine neue Instanz der Klasse HeadingLevels.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

Erstellt eine neue Instanz der Klasse HeadingLevels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schwellenwert |  | Der Schwellenwert zum Vergleichen von Schriftgrößen. Innerhalb des Schwellenwerts sind die Überschriftenebenen gleich. Der Standardwert des Schwellenwerts beträgt 0,01. |

### addLevels {#addLevels-java.lang.Iterable-}
Fügt Überschriftenebenen hinzu.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

Schätzt die mögliche Kopfzeilenebene. Wenn fontSize nicht in der Liste der Ebenen gefunden wird, wird die Ebene zurückgegeben, die diesem Schriftgrößenwert am nächsten liegt. Wenn fontSize außerhalb der angegebenen minimalen und maximalen Kopfzeilenebenen liegt, gibt die Methode false zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontSize |  | Die Schriftgröße. |

**Returns:**
Überschriftenebene.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

Findet die Ebene für die entsprechende Schriftgröße. Sucht nach einer exakten Übereinstimmung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontSize |  | Die Schriftgröße. |
| Ebene |  | Die entsprechende Überschriftenebene für die angegebene Schriftgröße. |

**Returns:**
False, wenn die fontSize nicht im angegebenen Bereich liegt.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

Ruft alle Überschriftenebenen ab.

**Returns:**
IEnumerable von Double
