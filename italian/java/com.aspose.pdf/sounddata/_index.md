---
title: "SoundData"
linktitle: "SoundData"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta i dati audio che definiscono il suono da riprodurre quando l'annotazione è attivata."
type: docs
weight: 4540
url: /it/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

Rappresenta i dati audio che definiscono il suono da riprodurre quando l'annotazione è attivata.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBits](#getBits--) | Ottiene il numero di bit per valore di campione per canale. |
| [getChannels](#getChannels--) | Ottiene il numero di canali audio. |
| [getContents](#getContents--) | Ottiene lo stream del suono da riprodurre quando l'annotazione è attivata. |
| [getContentsInternal](#getContentsInternal--) | Ottiene lo stream del suono da riprodurre quando l'annotazione è attivata. |
| [getEncoding](#getEncoding--) | Ottiene il formato di codifica per i dati del campione. |
| [getRate](#getRate--) | Ottiene la frequenza di campionamento, in campioni al secondo. |
| [setBits](#setBits-int-) | Imposta il numero di bit per valore di campione per canale. |
| [setChannels](#setChannels-int-) | Imposta il numero di canali audio. |
| [setEncoding](#setEncoding-int-) | Imposta il formato di codifica per i dati del campione. |
| [setRate](#setRate-int-) | Imposta la frequenza di campionamento, in campioni al secondo. |

### getBits {#getBits--}
```
public int getBits()
```

Ottiene il numero di bit per valore di campione per canale.

**Returns:**
int valore numero di bit

### getChannels {#getChannels--}
```
public int getChannels()
```

Ottiene il numero di canali audio.

**Returns:**
Il numero di canali audio.

### getContents {#getContents--}
```
public InputStream getContents()
```

Ottiene lo stream del suono da riprodurre quando l'annotazione è attivata.

**Returns:**
valore InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Ottiene lo stream del suono da riprodurre quando l'annotazione è attivata.

**Returns:**
valore Stream

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

Ottiene il formato di codifica per i dati del campione.

**Returns:**
valore SoundEncoding @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

Ottiene la frequenza di campionamento, in campioni al secondo.

**Returns:**
valore int

### setBits {#setBits-int-}
```
public void setBits(int value)
```

Imposta il numero di bit per valore di campione per canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | numero di bit |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

Imposta il numero di canali audio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Il numero di canali audio. |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

Imposta il formato di codifica per i dati del campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore SoundEncoding @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

Imposta la frequenza di campionamento, in campioni al secondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
