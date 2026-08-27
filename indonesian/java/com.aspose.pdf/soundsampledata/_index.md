---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili entri tambahan yang spesifik untuk objek suara (Bagian 9.2 PDF1-7)."
type: docs
weight: 4580
url: /id/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

Mewakili entri tambahan yang spesifik untuk objek suara (Bagian 9.2 PDF1-7).

## Fields

| Field | Deskripsi |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | Nilai default untuk format enkoding. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | Nilai default untuk parameter BitsPerchannel. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Nilai default untuk parameter Channels. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | Nilai default untuk SamplingRate. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | Menginisialisasi data sampel suara baru. |
| [SoundSampleData](#SoundSampleData-long-int-) | Menginisialisasi data sampel suara baru. |
| [SoundSampleData](#SoundSampleData-long-int-int-) | Menginisialisasi data sampel suara baru. |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | Menginisialisasi data sampel suara baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | Mendapatkan jumlah bit per nilai sampel per kanal. |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | Mendapatkan format enkoding. |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | Mendapatkan jumlah saluran suara. |
| [getSamplingRate](#getSamplingRate--) | Mendapatkan laju sampling. |
| [setBitsPerChannel](#setBitsPerChannel-int-) | Mengatur jumlah bit per nilai sampel per kanal. |
| [setEncodingFormat](#setEncodingFormat-int-) | Menetapkan format enkoding. |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | Mengatur jumlah saluran suara. |
| [setSamplingRate](#setSamplingRate-long-) | Menetapkan laju sampling. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

Nilai default untuk format enkoding.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

Nilai default untuk parameter BitsPerchannel.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Nilai default untuk parameter Channels.

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

Nilai default untuk SamplingRate.

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

Menginisialisasi data sampel suara baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| samplingRate |  | Laju sampling. |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

Menginisialisasi data sampel suara baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| samplingRate |  | Laju sampling. |
| numberOfSoundChannels |  | Jumlah saluran suara. |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

Menginisialisasi data sampel suara baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| samplingRate |  | Laju sampling. |
| numberOfSoundChannels |  | Jumlah saluran suara. |
| bitsPerChannel |  | Jumlah bit per nilai sampel per saluran. |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

Menginisialisasi data sampel suara baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| samplingRate |  | Laju sampling. |
| numberOfSoundChannels |  | Jumlah saluran suara. |
| bitsPerChannel |  | Jumlah bit per nilai sampel per saluran. |
| soundSampleDataEncodingFormat |  | Format enkoding untuk data sampel. |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

Mendapatkan jumlah bit per nilai sampel per kanal.

**Returns:**
nilai int

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

Mendapatkan format enkoding.

**Returns:**
nilai SoundSampleDataEncodingFormat @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

Mendapatkan jumlah saluran suara.

**Returns:**
nilai int

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

Mendapatkan laju sampling.

**Returns:**
nilai long

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

Mengatur jumlah bit per nilai sampel per kanal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

Menetapkan format enkoding.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai SoundSampleDataEncodingFormat @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

Mengatur jumlah saluran suara.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

Menetapkan laju sampling.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai long |
