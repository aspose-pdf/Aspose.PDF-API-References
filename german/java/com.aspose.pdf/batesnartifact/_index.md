---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse beschreibt das Bates-Nummerierungs-Artefakt."
type: docs
weight: 290
url: /de/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

Klasse beschreibt das Bates-Nummerierungs-Artefakt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | Initialisiert eine neue Instanz der {@link BatesNArtifact} Klasse. Dieser Konstruktor ist intern und erstellt eine Header-Artifact-Instanz mit Standardwerten. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Liest oder setzt die Anzahl der Ziffern für die Bates-Nummerierung. Der Wert muss zwischen 3 und 15 einschließlich liegen. Wird ein Wert kleiner als 3 gesetzt, wird er auf 3 angepasst. Wird ein Wert größer als 15 gesetzt, wird er auf 15 angepasst. Der Standardwert ist 6. |
| [getPrefix](#getPrefix--) | Liest oder setzt das Präfix, das zur Bates-Nummer hinzugefügt wird. |
| [getStartNumber](#getStartNumber--) | Liest oder setzt die Startnummer für die Bates-Nummerierung. Der Wert muss größer oder gleich 1 sein. Wird ein Wert kleiner als 1 gesetzt, wird er auf 1 angepasst. |
| [getSuffix](#getSuffix--) | Liest oder setzt das Suffix, das zur Bates-Nummer hinzugefügt wird. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Liest oder setzt die Anzahl der Ziffern für die Bates-Nummerierung. Der Wert muss zwischen 3 und 15 einschließlich liegen. Wird ein Wert kleiner als 3 gesetzt, wird er auf 3 angepasst. Wird ein Wert größer als 15 gesetzt, wird er auf 15 angepasst. Der Standardwert ist 6. |
| [setPrefix](#setPrefix-java.lang.String-) | Liest oder setzt das Präfix, das zur Bates-Nummer hinzugefügt wird. |
| [setStartNumber](#setStartNumber-int-) | Liest oder setzt die Startnummer für die Bates-Nummerierung. Der Wert muss größer oder gleich 1 sein. Wird ein Wert kleiner als 1 gesetzt, wird er auf 1 angepasst. |
| [setSuffix](#setSuffix-java.lang.String-) | Liest oder setzt das Suffix, das zur Bates-Nummer hinzugefügt wird. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

Initialisiert eine neue Instanz der {@link BatesNArtifact} Klasse. Dieser Konstruktor ist intern und erstellt eine Header-Artifact-Instanz mit Standardwerten.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Liest oder setzt die Anzahl der Ziffern für die Bates-Nummerierung. Der Wert muss zwischen 3 und 15 einschließlich liegen. Wird ein Wert kleiner als 3 gesetzt, wird er auf 3 angepasst. Wird ein Wert größer als 15 gesetzt, wird er auf 15 angepasst. Der Standardwert ist 6.

**Returns:**
int-Wert

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Liest oder setzt das Präfix, das zur Bates-Nummer hinzugefügt wird.

**Returns:**
String Wert

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Liest oder setzt die Startnummer für die Bates-Nummerierung. Der Wert muss größer oder gleich 1 sein. Wird ein Wert kleiner als 1 gesetzt, wird er auf 1 angepasst.

**Returns:**
int-Wert

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Liest oder setzt das Suffix, das zur Bates-Nummer hinzugefügt wird.

**Returns:**
String Wert

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Liest oder setzt die Anzahl der Ziffern für die Bates-Nummerierung. Der Wert muss zwischen 3 und 15 einschließlich liegen. Wird ein Wert kleiner als 3 gesetzt, wird er auf 3 angepasst. Wird ein Wert größer als 15 gesetzt, wird er auf 15 angepasst. Der Standardwert ist 6.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setPrefix {#setPrefix-java.lang.String-}
Liest oder setzt das Präfix, das zur Bates-Nummer hinzugefügt wird.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Liest oder setzt die Startnummer für die Bates-Nummerierung. Der Wert muss größer oder gleich 1 sein. Wird ein Wert kleiner als 1 gesetzt, wird er auf 1 angepasst.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setSuffix {#setSuffix-java.lang.String-}
Liest oder setzt das Suffix, das zur Bates-Nummer hinzugefügt wird.
