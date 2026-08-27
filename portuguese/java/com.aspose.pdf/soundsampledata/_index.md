---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa entradas adicionais específicas a um objeto de som (Seção 9.2 PDF1-7)."
type: docs
weight: 4580
url: /pt/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

Representa entradas adicionais específicas a um objeto de som (Seção 9.2 PDF1-7).

## Campos

| Campo | Descrição |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | Valor padrão para o formato de codificação. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | Valor padrão para o parâmetro BitsPerchannel. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Valor padrão para o parâmetro Channels. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | Valor padrão para SamplingRate. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | Inicializa novos dados de amostra de som. |
| [SoundSampleData](#SoundSampleData-long-int-) | Inicializa novos dados de amostra de som. |
| [SoundSampleData](#SoundSampleData-long-int-int-) | Inicializa novos dados de amostra de som. |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | Inicializa novos dados de amostra de som. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | Obtém o número de bits por valor de amostra por canal. |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | Obtém o formato de codificação. |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | Obtém o número de canais de áudio. |
| [getSamplingRate](#getSamplingRate--) | Obtém a taxa de amostragem. |
| [setBitsPerChannel](#setBitsPerChannel-int-) | Define o número de bits por valor de amostra por canal. |
| [setEncodingFormat](#setEncodingFormat-int-) | Define o formato de codificação. |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | Define o número de canais de áudio. |
| [setSamplingRate](#setSamplingRate-long-) | Define a taxa de amostragem. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

Valor padrão para o formato de codificação.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

Valor padrão para o parâmetro BitsPerchannel.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Valor padrão para o parâmetro Channels.

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

Valor padrão para SamplingRate.

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

Inicializa novos dados de amostra de som.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| samplingRate |  | A taxa de amostragem. |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

Inicializa novos dados de amostra de som.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| samplingRate |  | A taxa de amostragem. |
| numberOfSoundChannels |  | O número de canais de áudio. |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

Inicializa novos dados de amostra de som.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| samplingRate |  | A taxa de amostragem. |
| numberOfSoundChannels |  | O número de canais de áudio. |
| bitsPerChannel |  | O número de bits por valor de amostra por canal. |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

Inicializa novos dados de amostra de som.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| samplingRate |  | A taxa de amostragem. |
| numberOfSoundChannels |  | O número de canais de áudio. |
| bitsPerChannel |  | O número de bits por valor de amostra por canal. |
| soundSampleDataEncodingFormat |  | O formato de codificação para os dados de amostra. |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

Obtém o número de bits por valor de amostra por canal.

**Returns:**
valor int

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

Obtém o formato de codificação.

**Returns:**
SoundSampleDataEncodingFormat valor @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

Obtém o número de canais de áudio.

**Returns:**
valor int

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

Obtém a taxa de amostragem.

**Returns:**
valor longo

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

Define o número de bits por valor de amostra por canal.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

Define o formato de codificação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | SoundSampleDataEncodingFormat valor @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

Define o número de canais de áudio.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

Define a taxa de amostragem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor longo |
