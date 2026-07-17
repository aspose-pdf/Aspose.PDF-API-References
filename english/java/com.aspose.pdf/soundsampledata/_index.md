---
title: SoundSampleData
linktitle: SoundSampleData
second_title: Aspose.PDF for Java API Reference
description: Represents additional entries specific to a sound object (Section 9.2 PDF1-7)
type: docs
weight: 4580
url: /java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

Represents additional entries specific to a sound object (Section 9.2 PDF1-7)

## Fields

| Field | Description |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | Default value for encoding format. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | Default value for BitsPerchannel parameter. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Default value for Channels parameter. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | Default value for SamplingRate. |

## Constructors

| Constructor | Description |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | Initializes new sound sample data. |
| [SoundSampleData](#SoundSampleData-long-int-) | Initializes new sound sample data. |
| [SoundSampleData](#SoundSampleData-long-int-int-) | Initializes new sound sample data. |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | Initializes new sound sample data. |

## Methods

| Method | Description |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | Gets the number of bits per sample value per channel. |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | Gets the encoding format. |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | Gets the number of sound channels. |
| [getSamplingRate](#getSamplingRate--) | Gets the sampling rate. |
| [setBitsPerChannel](#setBitsPerChannel-int-) | Sets the number of bits per sample value per channel. |
| [setEncodingFormat](#setEncodingFormat-int-) | Sets the encoding format. |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | Sets the number of sound channels. |
| [setSamplingRate](#setSamplingRate-long-) | Sets the sampling rate. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

Default value for encoding format.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

Default value for BitsPerchannel parameter.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Default value for Channels parameter.

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

Default value for SamplingRate.

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

Initializes new sound sample data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| samplingRate |  | The sampling rate. |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

Initializes new sound sample data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| samplingRate |  | The sampling rate. |
| numberOfSoundChannels |  | The number of sound channels. |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

Initializes new sound sample data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| samplingRate |  | The sampling rate. |
| numberOfSoundChannels |  | The number of sound channels. |
| bitsPerChannel |  | The number of bits per sample value per channel. |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

Initializes new sound sample data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| samplingRate |  | The sampling rate. |
| numberOfSoundChannels |  | The number of sound channels. |
| bitsPerChannel |  | The number of bits per sample value per channel. |
| soundSampleDataEncodingFormat |  | The encoding format for the sample data. |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

Gets the number of bits per sample value per channel.

**Returns:**
int value

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

Gets the encoding format.

**Returns:**
SoundSampleDataEncodingFormat value @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

Gets the number of sound channels.

**Returns:**
int value

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

Gets the sampling rate.

**Returns:**
long value

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

Sets the number of bits per sample value per channel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

Sets the encoding format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | SoundSampleDataEncodingFormat value @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

Sets the number of sound channels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

Sets the sampling rate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | long value |
