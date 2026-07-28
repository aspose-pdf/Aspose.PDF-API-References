---
title: "SoundData"
linktitle: "SoundData"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ljuddata som definierar ljudet som ska spelas när annoteringen aktiveras."
type: docs
weight: 4540
url: /sv/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

Representerar ljuddata som definierar ljudet som ska spelas när annoteringen aktiveras.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBits](#getBits--) | Hämtar antalet bitar per sampelvärde per kanal. |
| [getChannels](#getChannels--) | Hämtar antalet ljudkanaler. |
| [getContents](#getContents--) | Hämtar strömmen av ljudet som ska spelas när annoteringen aktiveras. |
| [getContentsInternal](#getContentsInternal--) | Hämtar strömmen av ljudet som ska spelas när annoteringen aktiveras. |
| [getEncoding](#getEncoding--) | Hämtar kodningsformatet för samplingsdata. |
| [getRate](#getRate--) | Hämtar samplingsfrekvensen, i prover per sekund. |
| [setBits](#setBits-int-) | Ställer in antalet bitar per sampelvärde per kanal. |
| [setChannels](#setChannels-int-) | Ställer in antalet ljudkanaler. |
| [setEncoding](#setEncoding-int-) | Ställer in kodningsformatet för samplingsdata. |
| [setRate](#setRate-int-) | Ställer in samplingsfrekvensen, i prover per sekund. |

### getBits {#getBits--}
```
public int getBits()
```

Hämtar antalet bitar per sampelvärde per kanal.

**Returns:**
int värde antal bitar

### getChannels {#getChannels--}
```
public int getChannels()
```

Hämtar antalet ljudkanaler.

**Returns:**
Antalet ljudkanaler.

### getContents {#getContents--}
```
public InputStream getContents()
```

Hämtar strömmen av ljudet som ska spelas när annoteringen aktiveras.

**Returns:**
InputStream värde

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Hämtar strömmen av ljudet som ska spelas när annoteringen aktiveras.

**Returns:**
Stream värde

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

Hämtar kodningsformatet för samplingsdata.

**Returns:**
SoundEncoding värde @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

Hämtar samplingsfrekvensen, i prover per sekund.

**Returns:**
int‑värde

### setBits {#setBits-int-}
```
public void setBits(int value)
```

Ställer in antalet bitar per sampelvärde per kanal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | antal bitar |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

Ställer in antalet ljudkanaler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Antalet ljudkanaler. |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

Ställer in kodningsformatet för samplingsdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | SoundEncoding värde @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

Ställer in samplingsfrekvensen, i prover per sekund.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
