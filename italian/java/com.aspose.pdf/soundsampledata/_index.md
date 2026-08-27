---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta voci aggiuntive specifiche per un oggetto audio (Sezione 9.2 PDF1-7)"
type: docs
weight: 4580
url: /it/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

Rappresenta voci aggiuntive specifiche per un oggetto audio (Sezione 9.2 PDF1-7)

## Campi

| Campo | Descrizione |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | Valore predefinito per il formato di codifica. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | Valore predefinito per il parametro BitsPerchannel. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Valore predefinito per il parametro Channels. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | Valore predefinito per SamplingRate. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | Inizializza nuovi dati del campione audio. |
| [SoundSampleData](#SoundSampleData-long-int-) | Inizializza nuovi dati del campione audio. |
| [SoundSampleData](#SoundSampleData-long-int-int-) | Inizializza nuovi dati del campione audio. |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | Inizializza nuovi dati del campione audio. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | Ottiene il numero di bit per valore di campione per canale. |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | Restituisce il formato di codifica. |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | Ottiene il numero di canali audio. |
| [getSamplingRate](#getSamplingRate--) | Restituisce il tasso di campionamento. |
| [setBitsPerChannel](#setBitsPerChannel-int-) | Imposta il numero di bit per valore di campione per canale. |
| [setEncodingFormat](#setEncodingFormat-int-) | Imposta il formato di codifica. |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | Imposta il numero di canali audio. |
| [setSamplingRate](#setSamplingRate-long-) | Imposta il tasso di campionamento. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

Valore predefinito per il formato di codifica.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

Valore predefinito per il parametro BitsPerchannel.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Valore predefinito per il parametro Channels.

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

Valore predefinito per SamplingRate.

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

Inizializza nuovi dati del campione audio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| samplingRate |  | Il tasso di campionamento. |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

Inizializza nuovi dati del campione audio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| samplingRate |  | Il tasso di campionamento. |
| numberOfSoundChannels |  | Il numero di canali audio. |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

Inizializza nuovi dati del campione audio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| samplingRate |  | Il tasso di campionamento. |
| numberOfSoundChannels |  | Il numero di canali audio. |
| bitsPerChannel |  | Il numero di bit per valore del campione per canale. |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

Inizializza nuovi dati del campione audio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| samplingRate |  | Il tasso di campionamento. |
| numberOfSoundChannels |  | Il numero di canali audio. |
| bitsPerChannel |  | Il numero di bit per valore del campione per canale. |
| soundSampleDataEncodingFormat |  | Il formato di codifica per i dati di esempio. |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

Ottiene il numero di bit per valore di campione per canale.

**Returns:**
valore int

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

Restituisce il formato di codifica.

**Returns:**
Valore SoundSampleDataEncodingFormat @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

Ottiene il numero di canali audio.

**Returns:**
valore int

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

Restituisce il tasso di campionamento.

**Returns:**
valore long

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

Imposta il numero di bit per valore di campione per canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

Imposta il formato di codifica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore SoundSampleDataEncodingFormat @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

Imposta il numero di canali audio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

Imposta il tasso di campionamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore long |
