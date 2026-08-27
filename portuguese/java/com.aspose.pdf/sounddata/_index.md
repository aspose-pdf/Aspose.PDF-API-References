---
title: "SoundData"
linktitle: "SoundData"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa dados de som que definem o áudio a ser reproduzido quando a anotação é ativada."
type: docs
weight: 4540
url: /pt/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

Representa dados de som que definem o áudio a ser reproduzido quando a anotação é ativada.

## Métodos

| Método | Descrição |
| --- | --- |
| [getBits](#getBits--) | Obtém o número de bits por valor de amostra por canal. |
| [getChannels](#getChannels--) | Obtém o número de canais de áudio. |
| [getContents](#getContents--) | Obtém o fluxo de áudio a ser reproduzido quando a anotação é ativada. |
| [getContentsInternal](#getContentsInternal--) | Obtém o fluxo de áudio a ser reproduzido quando a anotação é ativada. |
| [getEncoding](#getEncoding--) | Obtém o formato de codificação dos dados de amostra. |
| [getRate](#getRate--) | Obtém a taxa de amostragem, em amostras por segundo. |
| [setBits](#setBits-int-) | Define o número de bits por valor de amostra por canal. |
| [setChannels](#setChannels-int-) | Define o número de canais de áudio. |
| [setEncoding](#setEncoding-int-) | Define o formato de codificação dos dados de amostra. |
| [setRate](#setRate-int-) | Define a taxa de amostragem, em amostras por segundo. |

### getBits {#getBits--}
```
public int getBits()
```

Obtém o número de bits por valor de amostra por canal.

**Returns:**
int valor número de bits

### getChannels {#getChannels--}
```
public int getChannels()
```

Obtém o número de canais de áudio.

**Returns:**
O número de canais de áudio.

### getContents {#getContents--}
```
public InputStream getContents()
```

Obtém o fluxo de áudio a ser reproduzido quando a anotação é ativada.

**Returns:**
valor InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Obtém o fluxo de áudio a ser reproduzido quando a anotação é ativada.

**Returns:**
valor Stream

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

Obtém o formato de codificação dos dados de amostra.

**Returns:**
valor SoundEncoding @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

Obtém a taxa de amostragem, em amostras por segundo.

**Returns:**
valor int

### setBits {#setBits-int-}
```
public void setBits(int value)
```

Define o número de bits por valor de amostra por canal.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | número de bits |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

Define o número de canais de áudio.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | O número de canais de áudio. |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

Define o formato de codificação dos dados de amostra.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor SoundEncoding @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

Define a taxa de amostragem, em amostras por segundo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
