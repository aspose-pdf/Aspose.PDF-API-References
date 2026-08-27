---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir ses nesnesine özgü ek girişleri temsil eder (Bölüm 9.2 PDF1-7)."
type: docs
weight: 4580
url: /tr/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

Bir ses nesnesine özgü ek girişleri temsil eder (Bölüm 9.2 PDF1-7).

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | Kodlama biçimi için varsayılan değer. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | BitsPerchannel parametresi için varsayılan değer. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Channels parametresi için varsayılan değer. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | SamplingRate için varsayılan değer. |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | Yeni ses örnek verisini başlatır. |
| [SoundSampleData](#SoundSampleData-long-int-) | Yeni ses örnek verisini başlatır. |
| [SoundSampleData](#SoundSampleData-long-int-int-) | Yeni ses örnek verisini başlatır. |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | Yeni ses örnek verisini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | Kanal başına örnek değeri başına bit sayısını alır. |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | Kodlama biçimini alır. |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | Ses kanallarının sayısını alır. |
| [getSamplingRate](#getSamplingRate--) | Örnekleme oranını alır. |
| [setBitsPerChannel](#setBitsPerChannel-int-) | Kanal başına örnek değeri başına bit sayısını ayarlar. |
| [setEncodingFormat](#setEncodingFormat-int-) | Kodlama biçimini ayarlar. |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | Ses kanallarının sayısını ayarlar. |
| [setSamplingRate](#setSamplingRate-long-) | Örnekleme oranını ayarlar. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

Kodlama biçimi için varsayılan değer.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

BitsPerchannel parametresi için varsayılan değer.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Channels parametresi için varsayılan değer.

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

SamplingRate için varsayılan değer.

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

Yeni ses örnek verisini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| samplingRate |  | Örnekleme oranı. |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

Yeni ses örnek verisini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| samplingRate |  | Örnekleme oranı. |
| numberOfSoundChannels |  | Ses kanallarının sayısı. |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

Yeni ses örnek verisini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| samplingRate |  | Örnekleme oranı. |
| numberOfSoundChannels |  | Ses kanallarının sayısı. |
| bitsPerChannel |  | Kanal başına örnek değeri için bit sayısı. |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

Yeni ses örnek verisini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| samplingRate |  | Örnekleme oranı. |
| numberOfSoundChannels |  | Ses kanallarının sayısı. |
| bitsPerChannel |  | Kanal başına örnek değeri için bit sayısı. |
| soundSampleDataEncodingFormat |  | Örnek veri için kodlama biçimi. |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

Kanal başına örnek değeri başına bit sayısını alır.

**Returns:**
int değer

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

Kodlama biçimini alır.

**Returns:**
SoundSampleDataEncodingFormat değeri @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

Ses kanallarının sayısını alır.

**Returns:**
int değer

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

Örnekleme oranını alır.

**Returns:**
uzun değer

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

Kanal başına örnek değeri başına bit sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

Kodlama biçimini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | SoundSampleDataEncodingFormat değeri @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

Ses kanallarının sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

Örnekleme oranını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | uzun değer |
