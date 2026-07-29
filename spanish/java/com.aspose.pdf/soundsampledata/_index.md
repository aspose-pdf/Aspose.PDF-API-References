---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa entradas adicionales específicas de un objeto de sonido (Sección 9.2 PDF1-7)."
type: docs
weight: 4580
url: /es/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

Representa entradas adicionales específicas de un objeto de sonido (Sección 9.2 PDF1-7).

## Campos

| Campo | Descripción |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | Valor predeterminado para el formato de codificación. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | Valor predeterminado para el parámetro BitsPerchannel. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Valor predeterminado para el parámetro Channels. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | Valor predeterminado para SamplingRate. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | Inicializa nuevos datos de muestra de sonido. |
| [SoundSampleData](#SoundSampleData-long-int-) | Inicializa nuevos datos de muestra de sonido. |
| [SoundSampleData](#SoundSampleData-long-int-int-) | Inicializa nuevos datos de muestra de sonido. |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | Inicializa nuevos datos de muestra de sonido. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | Obtiene el número de bits por valor de muestra por canal. |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | Obtiene el formato de codificación. |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | Obtiene el número de canales de sonido. |
| [getSamplingRate](#getSamplingRate--) | Obtiene la tasa de muestreo. |
| [setBitsPerChannel](#setBitsPerChannel-int-) | Establece el número de bits por valor de muestra por canal. |
| [setEncodingFormat](#setEncodingFormat-int-) | Establece el formato de codificación. |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | Establece el número de canales de sonido. |
| [setSamplingRate](#setSamplingRate-long-) | Establece la tasa de muestreo. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

Valor predeterminado para el formato de codificación.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

Valor predeterminado para el parámetro BitsPerchannel.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Valor predeterminado para el parámetro Channels.

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

Valor predeterminado para SamplingRate.

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

Inicializa nuevos datos de muestra de sonido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| samplingRate |  | La tasa de muestreo. |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

Inicializa nuevos datos de muestra de sonido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| samplingRate |  | La tasa de muestreo. |
| numberOfSoundChannels |  | El número de canales de sonido. |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

Inicializa nuevos datos de muestra de sonido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| samplingRate |  | La tasa de muestreo. |
| numberOfSoundChannels |  | El número de canales de sonido. |
| bitsPerChannel |  | El número de bits por valor de muestra por canal. |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

Inicializa nuevos datos de muestra de sonido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| samplingRate |  | La tasa de muestreo. |
| numberOfSoundChannels |  | El número de canales de sonido. |
| bitsPerChannel |  | El número de bits por valor de muestra por canal. |
| soundSampleDataEncodingFormat |  | El formato de codificación para los datos de muestra. |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

Obtiene el número de bits por valor de muestra por canal.

**Returns:**
valor int

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

Obtiene el formato de codificación.

**Returns:**
Valor SoundSampleDataEncodingFormat @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

Obtiene el número de canales de sonido.

**Returns:**
valor int

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

Obtiene la tasa de muestreo.

**Returns:**
valor largo

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

Establece el número de bits por valor de muestra por canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

Establece el formato de codificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor SoundSampleDataEncodingFormat @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

Establece el número de canales de sonido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

Establece la tasa de muestreo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor largo |
