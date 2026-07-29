---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل إدخالات إضافية خاصة بكائن صوت (القسم 9.2 PDF1-7)"
type: docs
weight: 4580
url: /ar/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

يمثل إدخالات إضافية خاصة بكائن صوت (القسم 9.2 PDF1-7)

## الحقول

| حقل | الوصف |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | القيمة الافتراضية لتنسيق الترميز. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | القيمة الافتراضية لمعلمة BitsPerchannel. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | القيمة الافتراضية لمعلمة Channels. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | القيمة الافتراضية لـ SamplingRate. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | يُهيئ بيانات عينة صوتية جديدة. |
| [SoundSampleData](#SoundSampleData-long-int-) | يُهيئ بيانات عينة صوتية جديدة. |
| [SoundSampleData](#SoundSampleData-long-int-int-) | يُهيئ بيانات عينة صوتية جديدة. |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | يُهيئ بيانات عينة صوتية جديدة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | يحصل على عدد البتات لكل عينة لكل قناة. |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | يحصل على تنسيق الترميز. |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | يحصل على عدد قنوات الصوت. |
| [getSamplingRate](#getSamplingRate--) | يحصل على معدل العينة. |
| [setBitsPerChannel](#setBitsPerChannel-int-) | يضبط عدد البتات لكل عينة لكل قناة. |
| [setEncodingFormat](#setEncodingFormat-int-) | يضبط تنسيق الترميز. |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | يضبط عدد قنوات الصوت. |
| [setSamplingRate](#setSamplingRate-long-) | يضبط معدل العينة. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

القيمة الافتراضية لتنسيق الترميز.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

القيمة الافتراضية لمعلمة BitsPerchannel.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

القيمة الافتراضية لمعلمة Channels.

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

القيمة الافتراضية لـ SamplingRate.

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

يُهيئ بيانات عينة صوتية جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| samplingRate |  | معدل العينة. |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

يُهيئ بيانات عينة صوتية جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| samplingRate |  | معدل العينة. |
| numberOfSoundChannels |  | عدد قنوات الصوت. |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

يُهيئ بيانات عينة صوتية جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| samplingRate |  | معدل العينة. |
| numberOfSoundChannels |  | عدد قنوات الصوت. |
| bitsPerChannel |  | عدد البتات لكل قيمة عينة في كل قناة. |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

يُهيئ بيانات عينة صوتية جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| samplingRate |  | معدل العينة. |
| numberOfSoundChannels |  | عدد قنوات الصوت. |
| bitsPerChannel |  | عدد البتات لكل قيمة عينة في كل قناة. |
| soundSampleDataEncodingFormat |  | تنسيق الترميز للبيانات العينية. |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

يحصل على عدد البتات لكل عينة لكل قناة.

**Returns:**
قيمة int

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

يحصل على تنسيق الترميز.

**Returns:**
SoundSampleDataEncodingFormat قيمة @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

يحصل على عدد قنوات الصوت.

**Returns:**
قيمة int

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

يحصل على معدل العينة.

**Returns:**
قيمة طويلة

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

يضبط عدد البتات لكل عينة لكل قناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

يضبط تنسيق الترميز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | SoundSampleDataEncodingFormat قيمة @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

يضبط عدد قنوات الصوت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

يضبط معدل العينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة طويلة |
