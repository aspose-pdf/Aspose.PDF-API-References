---
title: "SoundData"
linktitle: "SoundData"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Sounddaten dar, die den abzuspielenden Ton definieren, wenn die Annotation aktiviert wird."
type: docs
weight: 4540
url: /de/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

Stellt Sounddaten dar, die den abzuspielenden Ton definieren, wenn die Annotation aktiviert wird.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBits](#getBits--) | Ermittelt die Anzahl der Bits pro Samplewert pro Kanal. |
| [getChannels](#getChannels--) | Ermittelt die Anzahl der Tonkanäle. |
| [getContents](#getContents--) | Ermittelt den Stream des abzuspielenden Sounds, wenn die Anmerkung aktiviert wird. |
| [getContentsInternal](#getContentsInternal--) | Ermittelt den Stream des abzuspielenden Sounds, wenn die Anmerkung aktiviert wird. |
| [getEncoding](#getEncoding--) | Ermittelt das Kodierungsformat für die Sample-Daten. |
| [getRate](#getRate--) | Ermittelt die Abtastrate in Samples pro Sekunde. |
| [setBits](#setBits-int-) | Legt die Anzahl der Bits pro Samplewert pro Kanal fest. |
| [setChannels](#setChannels-int-) | Legt die Anzahl der Tonkanäle fest. |
| [setEncoding](#setEncoding-int-) | Legt das Kodierungsformat für die Sample-Daten fest. |
| [setRate](#setRate-int-) | Legt die Abtastrate in Samples pro Sekunde fest. |

### getBits {#getBits--}
```
public int getBits()
```

Ermittelt die Anzahl der Bits pro Samplewert pro Kanal.

**Returns:**
int-Wert Anzahl der Bits

### getChannels {#getChannels--}
```
public int getChannels()
```

Ermittelt die Anzahl der Tonkanäle.

**Returns:**
Die Anzahl der Tonkanäle.

### getContents {#getContents--}
```
public InputStream getContents()
```

Ermittelt den Stream des abzuspielenden Sounds, wenn die Anmerkung aktiviert wird.

**Returns:**
InputStream-Wert

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Ermittelt den Stream des abzuspielenden Sounds, wenn die Anmerkung aktiviert wird.

**Returns:**
Stream-Wert

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

Ermittelt das Kodierungsformat für die Sample-Daten.

**Returns:**
SoundEncoding-Wert @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

Ermittelt die Abtastrate in Samples pro Sekunde.

**Returns:**
int-Wert

### setBits {#setBits-int-}
```
public void setBits(int value)
```

Legt die Anzahl der Bits pro Samplewert pro Kanal fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Anzahl der Bits |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

Legt die Anzahl der Tonkanäle fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Die Anzahl der Tonkanäle. |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

Legt das Kodierungsformat für die Sample-Daten fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | SoundEncoding-Wert @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

Legt die Abtastrate in Samples pro Sekunde fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
