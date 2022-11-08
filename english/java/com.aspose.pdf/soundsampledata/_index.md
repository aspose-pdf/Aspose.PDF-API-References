---
title: SoundSampleData
second_title: Aspose.PDF for Java API Reference
description: Represents additional entries specific to a sound object Section 9.2 PDF1-7
type: docs
weight: 331
url: /java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object
```
public class SoundSampleData
```

Represents additional entries specific to a sound object (Section 9.2 PDF1-7)
## Constructors

| Constructor | Description |
| --- | --- |
| [SoundSampleData(long samplingRate)](#SoundSampleData-long-) | Initializes new sound sample data. |
| [SoundSampleData(long samplingRate, int numberOfSoundChannels)](#SoundSampleData-long-int-) | Initializes new sound sample data. |
| [SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)](#SoundSampleData-long-int-int-) | Initializes new sound sample data. |
| [SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)](#SoundSampleData-long-int-int-int-) | Initializes new sound sample data. |
## Fields

| Field | Description |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT-ENCODING-FORMAT) | Default value for encoding format. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT-OF-BITS-PER-CHANNEL) | Default value for BitsPerchannel parameter. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT-OF-SOUND-CHANNELS) | Default value for Channels parameter. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT-SAMPLING-RATE) | Default value for SamplingRate. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | Gets the number of bits per sample value per channel. |
| [getClass()](#getClass--) |  |
| [getEncodingFormat_Rename_Namesake()](#getEncodingFormat-Rename-Namesake--) | Gets the encoding format. |
| [getNumberOfSoundChannels()](#getNumberOfSoundChannels--) | Gets the number of sound channels. |
| [getSamplingRate()](#getSamplingRate--) | Gets the sampling rate. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(int value)](#setBitsPerChannel-int-) | Sets the number of bits per sample value per channel. |
| [setEncodingFormat(int value)](#setEncodingFormat-int-) | Sets the encoding format. |
| [setNumberOfSoundChannels(int value)](#setNumberOfSoundChannels-int-) | Sets the number of sound channels. |
| [setSamplingRate(long value)](#setSamplingRate-long-) | Sets the sampling rate. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SoundSampleData(long samplingRate) {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```


Initializes new sound sample data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| samplingRate | long | The sampling rate. |

### SoundSampleData(long samplingRate, int numberOfSoundChannels) {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```


Initializes new sound sample data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| samplingRate | long | The sampling rate. |
| numberOfSoundChannels | int | The number of sound channels. |

### SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel) {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```


Initializes new sound sample data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| samplingRate | long | The sampling rate. |
| numberOfSoundChannels | int | The number of sound channels. |
| bitsPerChannel | int | The number of bits per sample value per channel. |

### SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat) {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```


Initializes new sound sample data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| samplingRate | long | The sampling rate. |
| numberOfSoundChannels | int | The number of sound channels. |
| bitsPerChannel | int | The number of bits per sample value per channel. |
| soundSampleDataEncodingFormat | int | The encoding format for the sample data. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT-ENCODING-FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```


Default value for encoding format.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT-OF-BITS-PER-CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```


Default value for BitsPerchannel parameter.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT-OF-SOUND-CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```


Default value for Channels parameter.

### DEFAULT_SAMPLING_RATE {#DEFAULT-SAMPLING-RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```


Default value for SamplingRate.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitsPerChannel() {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```


Gets the number of bits per sample value per channel.

**Returns:**
int - int value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEncodingFormat_Rename_Namesake() {#getEncodingFormat-Rename-Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```


Gets the encoding format.

**Returns:**
int - SoundSampleDataEncodingFormat value
### getNumberOfSoundChannels() {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```


Gets the number of sound channels.

**Returns:**
int - int value
### getSamplingRate() {#getSamplingRate--}
```
public long getSamplingRate()
```


Gets the sampling rate.

**Returns:**
long - long value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBitsPerChannel(int value) {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```


Sets the number of bits per sample value per channel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setEncodingFormat(int value) {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```


Sets the encoding format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | SoundSampleDataEncodingFormat value |

### setNumberOfSoundChannels(int value) {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```


Sets the number of sound channels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setSamplingRate(long value) {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```


Sets the sampling rate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | long value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

