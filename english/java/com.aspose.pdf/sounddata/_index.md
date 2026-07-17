---
title: SoundData
linktitle: SoundData
second_title: Aspose.PDF for Java API Reference
description: Represents a sound data defining the sound to be played when the annotation is activated.
type: docs
weight: 4540
url: /java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

Represents a sound data defining the sound to be played when the annotation is activated.

## Methods

| Method | Description |
| --- | --- |
| [getBits](#getBits--) | Gets the number of bits per sample value per channel. |
| [getChannels](#getChannels--) | Gets the number of sound channels. |
| [getContents](#getContents--) | Gets stream of the sound to be played when the annotation is activated. |
| [getContentsInternal](#getContentsInternal--) | Gets stream of the sound to be played when the annotation is activated. |
| [getEncoding](#getEncoding--) | Gets the encoding format for the sample data. |
| [getRate](#getRate--) | Gets the sampling rate, in samples per second. |
| [setBits](#setBits-int-) | Sets the number of bits per sample value per channel. |
| [setChannels](#setChannels-int-) | Sets the number of sound channels. |
| [setEncoding](#setEncoding-int-) | Sets the encoding format for the sample data. |
| [setRate](#setRate-int-) | Sets the sampling rate, in samples per second. |

### getBits {#getBits--}
```
public int getBits()
```

Gets the number of bits per sample value per channel.

**Returns:**
int value number of bits

### getChannels {#getChannels--}
```
public int getChannels()
```

Gets the number of sound channels.

**Returns:**
The number of sound channels.

### getContents {#getContents--}
```
public InputStream getContents()
```

Gets stream of the sound to be played when the annotation is activated.

**Returns:**
InputStream value

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Gets stream of the sound to be played when the annotation is activated.

**Returns:**
Stream value

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

Gets the encoding format for the sample data.

**Returns:**
SoundEncoding value @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

Gets the sampling rate, in samples per second.

**Returns:**
int value

### setBits {#setBits-int-}
```
public void setBits(int value)
```

Sets the number of bits per sample value per channel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | number of bits |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

Sets the number of sound channels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | The number of sound channels. |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

Sets the encoding format for the sample data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | SoundEncoding value @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

Sets the sampling rate, in samples per second.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
