---
title: "SoundSampleData"
linktitle: "SoundSampleData"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente des entrées supplémentaires spécifiques à un objet sonore (Section 9.2 PDF1-7)."
type: docs
weight: 4580
url: /fr/java/com.aspose.pdf/soundsampledata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundSampleData

```
public class SoundSampleData extends Object
```

Représente des entrées supplémentaires spécifiques à un objet sonore (Section 9.2 PDF1-7).

## Champs

| Champ | Description |
| --- | --- |
| [DEFAULT_ENCODING_FORMAT](#DEFAULT_ENCODING_FORMAT) | Valeur par défaut pour le format d'encodage. |
| [DEFAULT_OF_BITS_PER_CHANNEL](#DEFAULT_OF_BITS_PER_CHANNEL) | Valeur par défaut pour le paramètre BitsPerchannel. |
| [DEFAULT_OF_SOUND_CHANNELS](#DEFAULT_OF_SOUND_CHANNELS) | Valeur par défaut pour le paramètre Channels. |
| [DEFAULT_SAMPLING_RATE](#DEFAULT_SAMPLING_RATE) | Valeur par défaut pour SamplingRate. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SoundSampleData](#SoundSampleData-long-) | Initialise de nouvelles données d'échantillon sonore. |
| [SoundSampleData](#SoundSampleData-long-int-) | Initialise de nouvelles données d'échantillon sonore. |
| [SoundSampleData](#SoundSampleData-long-int-int-) | Initialise de nouvelles données d'échantillon sonore. |
| [SoundSampleData](#SoundSampleData-long-int-int-int-) | Initialise de nouvelles données d'échantillon sonore. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitsPerChannel](#getBitsPerChannel--) | Obtient le nombre de bits par valeur d'échantillon par canal. |
| [getEncodingFormat_Rename_Namesake](#getEncodingFormat_Rename_Namesake--) | Obtient le format d'encodage. |
| [getNumberOfSoundChannels](#getNumberOfSoundChannels--) | Obtient le nombre de canaux audio. |
| [getSamplingRate](#getSamplingRate--) | Obtient le taux d'échantillonnage. |
| [setBitsPerChannel](#setBitsPerChannel-int-) | Définit le nombre de bits par valeur d'échantillon par canal. |
| [setEncodingFormat](#setEncodingFormat-int-) | Définit le format d'encodage. |
| [setNumberOfSoundChannels](#setNumberOfSoundChannels-int-) | Définit le nombre de canaux audio. |
| [setSamplingRate](#setSamplingRate-long-) | Définit le taux d'échantillonnage. |

### DEFAULT_ENCODING_FORMAT {#DEFAULT_ENCODING_FORMAT}
```
public static final int DEFAULT_ENCODING_FORMAT
```

Valeur par défaut pour le format d'encodage.

### DEFAULT_OF_BITS_PER_CHANNEL {#DEFAULT_OF_BITS_PER_CHANNEL}
```
public static final int DEFAULT_OF_BITS_PER_CHANNEL
```

Valeur par défaut pour le paramètre BitsPerchannel.

### DEFAULT_OF_SOUND_CHANNELS {#DEFAULT_OF_SOUND_CHANNELS}
```
public static final int DEFAULT_OF_SOUND_CHANNELS
```

Valeur par défaut pour le paramètre Channels.

### DEFAULT_SAMPLING_RATE {#DEFAULT_SAMPLING_RATE}
```
public static final long DEFAULT_SAMPLING_RATE
```

Valeur par défaut pour SamplingRate.

### SoundSampleData {#SoundSampleData-long-}
```
public SoundSampleData(long samplingRate)
```

Initialise de nouvelles données d'échantillon sonore.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| samplingRate |  | Le taux d'échantillonnage. |

### SoundSampleData {#SoundSampleData-long-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels)
```

Initialise de nouvelles données d'échantillon sonore.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| samplingRate |  | Le taux d'échantillonnage. |
| numberOfSoundChannels |  | Le nombre de canaux audio. |

### SoundSampleData {#SoundSampleData-long-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel)
```

Initialise de nouvelles données d'échantillon sonore.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| samplingRate |  | Le taux d'échantillonnage. |
| numberOfSoundChannels |  | Le nombre de canaux audio. |
| bitsPerChannel |  | Le nombre de bits par valeur d'échantillon par canal. |

### SoundSampleData {#SoundSampleData-long-int-int-int-}
```
public SoundSampleData(long samplingRate, int numberOfSoundChannels, int bitsPerChannel, int soundSampleDataEncodingFormat)
```

Initialise de nouvelles données d'échantillon sonore.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| samplingRate |  | Le taux d'échantillonnage. |
| numberOfSoundChannels |  | Le nombre de canaux audio. |
| bitsPerChannel |  | Le nombre de bits par valeur d'échantillon par canal. |
| soundSampleDataEncodingFormat |  | Le format d'encodage des données d'échantillon. |

### getBitsPerChannel {#getBitsPerChannel--}
```
public int getBitsPerChannel()
```

Obtient le nombre de bits par valeur d'échantillon par canal.

**Returns:**
valeur int

### getEncodingFormat_Rename_Namesake {#getEncodingFormat_Rename_Namesake--}
```
public int getEncodingFormat_Rename_Namesake()
```

Obtient le format d'encodage.

**Returns:**
Valeur SoundSampleDataEncodingFormat @see SoundSampleDataEncodingFormat

### getNumberOfSoundChannels {#getNumberOfSoundChannels--}
```
public int getNumberOfSoundChannels()
```

Obtient le nombre de canaux audio.

**Returns:**
valeur int

### getSamplingRate {#getSamplingRate--}
```
public long getSamplingRate()
```

Obtient le taux d'échantillonnage.

**Returns:**
valeur longue

### setBitsPerChannel {#setBitsPerChannel-int-}
```
public void setBitsPerChannel(int value)
```

Définit le nombre de bits par valeur d'échantillon par canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setEncodingFormat {#setEncodingFormat-int-}
```
public void setEncodingFormat(int value)
```

Définit le format d'encodage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur SoundSampleDataEncodingFormat @see SoundSampleDataEncodingFormat |

### setNumberOfSoundChannels {#setNumberOfSoundChannels-int-}
```
public void setNumberOfSoundChannels(int value)
```

Définit le nombre de canaux audio.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setSamplingRate {#setSamplingRate-long-}
```
public void setSamplingRate(long value)
```

Définit le taux d'échantillonnage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur longue |
