---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt zusätzliche Einträge dar, die spezifisch für ein Sound-Objekt sind (Abschnitt 9.2 PDF1-7)"
type: docs
weight: 4580
url: /de/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

Stellt zusätzliche Einträge dar, die spezifisch für ein Sound-Objekt sind (Abschnitt 9.2 PDF1-7)

## Felder

| Feld | Beschreibung |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | Standardwert für das Kodierungsformat. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | Standardwert für den BitsPerchannel-Parameter. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Standardwert für den Channels-Parameter. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | Standardwert für SamplingRate. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | Initialisiert neue SoundSampleData. |
| [SoundSampleData](#SoundSampleData-long-int-) | Initialisiert neue SoundSampleData. |
| [SoundSampleData](#SoundSampleData-long-int-int-) | Initialisiert neue SoundSampleData. |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | Initialisiert neue SoundSampleData. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | Ermittelt die Anzahl der Bits pro Samplewert pro Kanal. |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | Gibt das Kodierungsformat zurück. |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | Ermittelt die Anzahl der Tonkanäle. |
| [getSamplingRate](#getSamplingRate--) | Gibt die Abtastrate zurück. |
| [setBitsPerChannel](#setBitsPerChannel-int-) | Legt die Anzahl der Bits pro Samplewert pro Kanal fest. |
| [setEncodingFormat](#setEncodingFormat-int-) | Setzt das Kodierungsformat. |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | Legt die Anzahl der Tonkanäle fest. |
| [setSamplingRate](#setSamplingRate-long-) | Setzt die Abtastrate. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

Standardwert für das Kodierungsformat.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

Standardwert für den BitsPerchannel-Parameter.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Standardwert für den Channels-Parameter.

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

Standardwert für SamplingRate.

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

Initialisiert neue SoundSampleData.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| samplingRate |  | Die Abtastrate. |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

Initialisiert neue SoundSampleData.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| samplingRate |  | Die Abtastrate. |
| numberOfSoundChannels |  | Die Anzahl der Tonkanäle. |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

Initialisiert neue SoundSampleData.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| samplingRate |  | Die Abtastrate. |
| numberOfSoundChannels |  | Die Anzahl der Tonkanäle. |
| bitsPerChannel |  | Die Anzahl der Bits pro Samplewert pro Kanal. |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

Initialisiert neue SoundSampleData.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| samplingRate |  | Die Abtastrate. |
| numberOfSoundChannels |  | Die Anzahl der Tonkanäle. |
| bitsPerChannel |  | Die Anzahl der Bits pro Samplewert pro Kanal. |
| soundSampleDataEncodingFormat |  | Das Kodierungsformat für die Beispieldaten. |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

Ermittelt die Anzahl der Bits pro Samplewert pro Kanal.

**Returns:**
int-Wert

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

Gibt das Kodierungsformat zurück.

**Returns:**
SoundSampleDataEncodingFormat-Wert @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

Ermittelt die Anzahl der Tonkanäle.

**Returns:**
int-Wert

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

Gibt die Abtastrate zurück.

**Returns:**
Long-Wert

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

Legt die Anzahl der Bits pro Samplewert pro Kanal fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

Setzt das Kodierungsformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | SoundSampleDataEncodingFormat-Wert @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

Legt die Anzahl der Tonkanäle fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

Setzt die Abtastrate.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Long-Wert |
