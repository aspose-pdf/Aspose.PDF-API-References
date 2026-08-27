---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ytterligare poster specifika för ett ljudobjekt (Avsnitt 9.2 PDF1-7)."
type: docs
weight: 4580
url: /sv/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

Representerar ytterligare poster specifika för ett ljudobjekt (Avsnitt 9.2 PDF1-7).

## Fält

| Fält | Beskrivning |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | Standardvärde för kodningsformat. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | Standardvärde för BitsPerchannel‑parameter. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Standardvärde för Channels‑parameter. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | Standardvärde för SamplingRate. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | Initierar ny ljudsamplingsdata. |
| [SoundSampleData](#SoundSampleData-long-int-) | Initierar ny ljudsamplingsdata. |
| [SoundSampleData](#SoundSampleData-long-int-int-) | Initierar ny ljudsamplingsdata. |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | Initierar ny ljudsamplingsdata. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | Hämtar antalet bitar per sampelvärde per kanal. |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | Hämtar kodningsformatet. |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | Hämtar antalet ljudkanaler. |
| [getSamplingRate](#getSamplingRate--) | Hämtar samplingsfrekvensen. |
| [setBitsPerChannel](#setBitsPerChannel-int-) | Ställer in antalet bitar per sampelvärde per kanal. |
| [setEncodingFormat](#setEncodingFormat-int-) | Ställer in kodningsformatet. |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | Ställer in antalet ljudkanaler. |
| [setSamplingRate](#setSamplingRate-long-) | Ställer in samplingsfrekvensen. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

Standardvärde för kodningsformat.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

Standardvärde för BitsPerchannel‑parameter.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Standardvärde för Channels‑parameter.

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

Standardvärde för SamplingRate.

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

Initierar ny ljudsamplingsdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| samplingRate |  | Samplingsfrekvensen. |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

Initierar ny ljudsamplingsdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| samplingRate |  | Samplingsfrekvensen. |
| numberOfSoundChannels |  | Antalet ljudkanaler. |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

Initierar ny ljudsamplingsdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| samplingRate |  | Samplingsfrekvensen. |
| numberOfSoundChannels |  | Antalet ljudkanaler. |
| bitsPerChannel |  | Antalet bitar per samplingsvärde per kanal. |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

Initierar ny ljudsamplingsdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| samplingRate |  | Samplingsfrekvensen. |
| numberOfSoundChannels |  | Antalet ljudkanaler. |
| bitsPerChannel |  | Antalet bitar per samplingsvärde per kanal. |
| soundSampleDataEncodingFormat |  | Kodningsformatet för exempeldata. |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

Hämtar antalet bitar per sampelvärde per kanal.

**Returns:**
int‑värde

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

Hämtar kodningsformatet.

**Returns:**
SoundSampleDataEncodingFormat‑värde @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

Hämtar antalet ljudkanaler.

**Returns:**
int‑värde

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

Hämtar samplingsfrekvensen.

**Returns:**
long värde

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

Ställer in antalet bitar per sampelvärde per kanal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

Ställer in kodningsformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | SoundSampleDataEncodingFormat‑värde @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

Ställer in antalet ljudkanaler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

Ställer in samplingsfrekvensen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | long värde |
