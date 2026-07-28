---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen beskriver Bates-numreringsartefakt."
type: docs
weight: 290
url: /sv/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

Klassen beskriver Bates-numreringsartefakt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | Initierar en ny instans av klassen {@link BatesNArtifact}. Denna konstruktor är intern och skapar ett rubrik‑artifact‑objekt med standardvärden. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Hämtar eller anger antalet siffror för Bates‑numrering. Värdet måste vara mellan 3 och 15 inklusive. Om ett värde mindre än 3 anges, justeras det till 3. Om ett värde större än 15 anges, justeras det till 15. Standardvärdet är 6. |
| [getPrefix](#getPrefix--) | Hämtar eller anger prefixet som ska läggas till Bates-numret. |
| [getStartNumber](#getStartNumber--) | Hämtar eller anger startnumret för Bates-numrering. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1. |
| [getSuffix](#getSuffix--) | Hämtar eller anger suffixet som ska läggas till Bates-numret. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Hämtar eller anger antalet siffror för Bates‑numrering. Värdet måste vara mellan 3 och 15 inklusive. Om ett värde mindre än 3 anges, justeras det till 3. Om ett värde större än 15 anges, justeras det till 15. Standardvärdet är 6. |
| [setPrefix](#setPrefix-java.lang.String-) | Hämtar eller anger prefixet som ska läggas till Bates-numret. |
| [setStartNumber](#setStartNumber-int-) | Hämtar eller anger startnumret för Bates-numrering. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1. |
| [setSuffix](#setSuffix-java.lang.String-) | Hämtar eller anger suffixet som ska läggas till Bates-numret. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

Initierar en ny instans av klassen {@link BatesNArtifact}. Denna konstruktor är intern och skapar ett rubrik‑artifact‑objekt med standardvärden.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Hämtar eller anger antalet siffror för Bates‑numrering. Värdet måste vara mellan 3 och 15 inklusive. Om ett värde mindre än 3 anges, justeras det till 3. Om ett värde större än 15 anges, justeras det till 15. Standardvärdet är 6.

**Returns:**
int‑värde

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Hämtar eller anger prefixet som ska läggas till Bates-numret.

**Returns:**
String värde

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Hämtar eller anger startnumret för Bates-numrering. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1.

**Returns:**
int‑värde

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Hämtar eller anger suffixet som ska läggas till Bates-numret.

**Returns:**
String värde

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Hämtar eller anger antalet siffror för Bates‑numrering. Värdet måste vara mellan 3 och 15 inklusive. Om ett värde mindre än 3 anges, justeras det till 3. Om ett värde större än 15 anges, justeras det till 15. Standardvärdet är 6.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPrefix {#setPrefix-java.lang.String-}
Hämtar eller anger prefixet som ska läggas till Bates-numret.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Hämtar eller anger startnumret för Bates-numrering. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setSuffix {#setSuffix-java.lang.String-}
Hämtar eller anger suffixet som ska läggas till Bates-numret.
