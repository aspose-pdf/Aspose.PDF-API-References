---
title: "SoundData"
linktitle: "SoundData"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa datos de sonido que definen el audio a reproducir cuando se activa la anotación."
type: docs
weight: 4540
url: /es/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

Representa datos de sonido que definen el audio a reproducir cuando se activa la anotación.

## Métodos

| Método | Descripción |
| --- | --- |
| [getBits](#getBits--) | Obtiene el número de bits por valor de muestra por canal. |
| [getChannels](#getChannels--) | Obtiene el número de canales de sonido. |
| [getContents](#getContents--) | Obtiene la secuencia del sonido que se reproducirá cuando se active la anotación. |
| [getContentsInternal](#getContentsInternal--) | Obtiene la secuencia del sonido que se reproducirá cuando se active la anotación. |
| [getEncoding](#getEncoding--) | Obtiene el formato de codificación de los datos de muestra. |
| [getRate](#getRate--) | Obtiene la tasa de muestreo, en muestras por segundo. |
| [setBits](#setBits-int-) | Establece el número de bits por valor de muestra por canal. |
| [setChannels](#setChannels-int-) | Establece el número de canales de sonido. |
| [setEncoding](#setEncoding-int-) | Establece el formato de codificación de los datos de muestra. |
| [setRate](#setRate-int-) | Establece la tasa de muestreo, en muestras por segundo. |

### getBits {#getBits--}
```
public int getBits()
```

Obtiene el número de bits por valor de muestra por canal.

**Returns:**
valor int número de bits

### getChannels {#getChannels--}
```
public int getChannels()
```

Obtiene el número de canales de sonido.

**Returns:**
El número de canales de sonido.

### getContents {#getContents--}
```
public InputStream getContents()
```

Obtiene la secuencia del sonido que se reproducirá cuando se active la anotación.

**Returns:**
valor InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Obtiene la secuencia del sonido que se reproducirá cuando se active la anotación.

**Returns:**
valor Stream

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

Obtiene el formato de codificación de los datos de muestra.

**Returns:**
valor SoundEncoding @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

Obtiene la tasa de muestreo, en muestras por segundo.

**Returns:**
valor int

### setBits {#setBits-int-}
```
public void setBits(int value)
```

Establece el número de bits por valor de muestra por canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | número de bits |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

Establece el número de canales de sonido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | El número de canales de sonido. |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

Establece el formato de codificación de los datos de muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor SoundEncoding @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

Establece la tasa de muestreo, en muestras por segundo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
