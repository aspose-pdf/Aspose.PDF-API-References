---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Define un MemoryStream que puede contener una mayor capacidad estándar"
type: docs
weight: 3220
url: /es/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

Define un MemoryStream que puede contener una mayor capacidad estándar

## Campos

| Campo | Descripción |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Valor predeterminado del tamaño del búfer en bytes. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | Inicializa una nueva instancia de la clase {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | Inicializa una nueva instancia de la clase {@link OptimizedMemoryStream} basada en la matriz de bytes especificada. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | Inicializa una nueva instancia de la clase {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | Inicializa una nueva instancia de la clase {@link OptimizedMemoryStream} basada en la matriz de bytes especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [canRead](#canRead--) | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el flujo actual admite lectura. |
| [canSeek](#canSeek--) | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el flujo actual admite búsqueda. |
| [canWrite](#canWrite--) | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el flujo actual admite escritura. |
| [flush](#flush--) | La función sobrescrita. |
| [getBufferSize](#getBufferSize--) | Obtiene o establece el tamaño de los búferes subyacentes. Valor: El tamaño de los búferes. |
| [getFreeOnDispose](#getFreeOnDispose--) | Obtiene o establece un valor que indica si se deben liberar los búferes subyacentes al desechar. |
| [getLength](#getLength--) | Cuando se sobrescribe en una clase derivada, obtiene la longitud en bytes del flujo. |
| [getPosition](#getPosition--) | Cuando se sobrescribe en una clase derivada, obtiene o establece la posición dentro del flujo actual. |
| [read](#read-byte:A-int-int-) | Cuando se sobrescribe en una clase derivada, lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos. |
| [readByte](#readByte--) | Lee un byte del flujo y avanza la posición dentro del flujo en un byte, o devuelve -1 si está al final del flujo. |
| [seek](#seek-long-int-) | Cuando se sobrescribe en una clase derivada, establece la posición dentro del flujo actual. |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | Cuando se sobrescribe en una clase derivada, establece la posición dentro del flujo actual. |
| [setBufferSize](#setBufferSize-int-) | Obtiene o establece el tamaño de los búferes subyacentes. Valor: El tamaño de los búferes. |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | Obtiene o establece un valor que indica si se deben liberar los búferes subyacentes al desechar. |
| [setLength](#setLength-long-) | Cuando se sobrescribe en una clase derivada, establece la longitud del flujo actual. |
| [setPosition](#setPosition-long-) | Cuando se sobrescribe en una clase derivada, obtiene o establece la posición dentro del flujo actual. La posición actual dentro del flujo. Valor: |
| [toArray](#toArray--) | Convierte el flujo actual en una matriz de bytes. |
| [write](#write-byte:A-int-int-) | Cuando se sobrescribe en una clase derivada, escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos. |
| [writeByte](#writeByte-byte-) | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte. |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | Escribe en el flujo especificado. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

Valor predeterminado del tamaño del búfer en bytes.

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

Inicializa una nueva instancia de la clase {@link OptimizedMemoryStream}.

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

Inicializa una nueva instancia de la clase {@link OptimizedMemoryStream} basada en la matriz de bytes especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer |  | La matriz de bytes sin signo a partir de la cual crear el flujo actual. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

Inicializa una nueva instancia de la clase {@link OptimizedMemoryStream}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bufferSize |  | Tamaño de los búferes subyacentes. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

Inicializa una nueva instancia de la clase {@link OptimizedMemoryStream} basada en la matriz de bytes especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bufferSize |  | Tamaño de los búferes subyacentes. |
| búfer |  | La matriz de bytes sin signo a partir de la cual crear el flujo actual. |

### canRead {#canRead--}
```
public boolean canRead()
```

Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el flujo actual admite lectura.

**Returns:**
true si el flujo admite lectura; de lo contrario, false. Valor:

### canSeek {#canSeek--}
```
public boolean canSeek()
```

Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el flujo actual admite búsqueda.

**Returns:**
true si el flujo admite búsqueda; de lo contrario, false. Valor:

### canWrite {#canWrite--}
```
public boolean canWrite()
```

Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el flujo actual admite escritura.

**Returns:**
true si el flujo admite escritura; de lo contrario, false. Valor:

### flush {#flush--}
```
public void flush()
```

La función sobrescrita.

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

Obtiene o establece el tamaño de los búferes subyacentes. Valor: El tamaño de los búferes.

**Returns:**
valor int

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

Obtiene o establece un valor que indica si se deben liberar los búferes subyacentes al desechar.

**Returns:**
valor booleano

### getLength {#getLength--}
```
public long getLength()
```

Cuando se sobrescribe en una clase derivada, obtiene la longitud en bytes del flujo.

**Returns:**
Un valor long que representa la longitud del flujo en bytes. Valor:

### getPosition {#getPosition--}
```
public long getPosition()
```

Cuando se sobrescribe en una clase derivada, obtiene o establece la posición dentro del flujo actual.

**Returns:**
La posición actual dentro del flujo. Valor:

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

Cuando se sobrescribe en una clase derivada, lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer |  | Una matriz de bytes. Cuando este método devuelve, el búfer contiene la matriz de bytes especificada con los valores |
| offset |  | El desplazamiento de byte basado en cero en el que comenzar a almacenar los datos leídos del flujo actual. |
| conteo |  | El número máximo de bytes que se leerán del flujo actual. |

**Returns:**
El número total de bytes leídos en el búfer. Esto puede ser menor que el número de bytes solicitados si esa cantidad de bytes no está disponible actualmente, o cero (0) si se ha alcanzado el final del flujo.

### readByte {#readByte--}
```
public int readByte()
```

Lee un byte del flujo y avanza la posición dentro del flujo en un byte, o devuelve -1 si está al final del flujo.

**Returns:**
byte o -1 si está al final del flujo.

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

Cuando se sobrescribe en una clase derivada, establece la posición dentro del flujo actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offset |  | Un desplazamiento de bytes relativo al parámetro {@code origin}. |
| origin |  | Un valor del tipo {@link SeekOrigin} que indica el punto de referencia utilizado para obtener la nueva posición. |

**Returns:**
La nueva posición dentro del flujo actual.

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
Cuando se sobrescribe en una clase derivada, establece la posición dentro del flujo actual.

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

Obtiene o establece el tamaño de los búferes subyacentes. Valor: El tamaño de los búferes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

Obtiene o establece un valor que indica si se deben liberar los búferes subyacentes al desechar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

Cuando se sobrescribe en una clase derivada, establece la longitud del flujo actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | La longitud deseada del flujo actual en bytes. |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

Cuando se sobrescribe en una clase derivada, obtiene o establece la posición dentro del flujo actual. La posición actual dentro del flujo. Valor:

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

Convierte el flujo actual en una matriz de bytes.

**Returns:**
Una matriz de bytes

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

Cuando se sobrescribe en una clase derivada, escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer |  | Una matriz de bytes. Este método copia {@code count} bytes desde {@code buffer} al flujo actual. |
| offset |  | El desplazamiento de bytes basado en cero en {@code buffer} donde comenzar a copiar bytes al flujo actual. |
| conteo |  | El número de bytes que se escribirán en el flujo actual. |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | El byte que se escribirá en el flujo. |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
Escribe en el flujo especificado.
