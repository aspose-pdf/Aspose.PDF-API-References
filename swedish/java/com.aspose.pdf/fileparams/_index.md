---
title: "FileParams"
linktitle: "FileParams"
second_title: "Aspose.PDF för Java API-referens"
description: "Definierar en inbäddad filparameterordbok som ska innehålla ytterligare filspecifik information."
type: docs
weight: 1490
url: /sv/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

Definierar en inbäddad filparameterordbok som ska innehålla ytterligare filspecifik information.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | Konstruktor för FileParams-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCheckSum](#getCheckSum--) | En 16-byte sträng som är kontrollsumman för byte‑sekvensen i den okomprimerade inbäddade filen. Kontrollsumman beräknas genom att tillämpa den standardiserade MD5‑hash‑algoritmen på byte‑sekvensen i den inbäddade filströmmen. |
| [getCreationDate](#getCreationDate--) | Hämta datum och tid då den inbäddade filen skapades. |
| [getModDate](#getModDate--) | Hämta datum och tid då den inbäddade filen senast ändrades. |
| [getSize](#getSize--) | Storleken på den okomprimerade inbäddade filen, i byte. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Ange datum och tid då den inbäddade filen skapades. |
| [setModDate](#setModDate-java.util.Date-) | Ange datum och tid då den inbäddade filen senast ändrades. |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
Konstruktor för FileParams-klassen.

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

En 16-byte sträng som är kontrollsumman för byte‑sekvensen i den okomprimerade inbäddade filen. Kontrollsumman beräknas genom att tillämpa den standardiserade MD5‑hash‑algoritmen på byte‑sekvensen i den inbäddade filströmmen.

**Returns:**
String värde

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Hämta datum och tid då den inbäddade filen skapades.

**Returns:**
Date-objekt

### getModDate {#getModDate--}
```
public Date getModDate()
```

Hämta datum och tid då den inbäddade filen senast ändrades.

**Returns:**
Date-objekt

### getSize {#getSize--}
```
public int getSize()
```

Storleken på den okomprimerade inbäddade filen, i byte.

**Returns:**
int‑värde

### setCreationDate {#setCreationDate-java.util.Date-}
Ange datum och tid då den inbäddade filen skapades.

### setModDate {#setModDate-java.util.Date-}
Ange datum och tid då den inbäddade filen senast ändrades.
