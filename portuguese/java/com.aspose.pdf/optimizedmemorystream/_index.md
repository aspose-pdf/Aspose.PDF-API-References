---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Referência da API Aspose.PDF para Java"
description: "Define um MemoryStream que pode conter mais capacidade padrão."
type: docs
weight: 3220
url: /pt/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

Define um MemoryStream que pode conter mais capacidade padrão.

## Campos

| Campo | Descrição |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Valor padrão do tamanho do buffer em bytes. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | Inicializa uma nova instância da classe {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | Inicializa uma nova instância da classe {@link OptimizedMemoryStream} com base no array de bytes especificado. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | Inicializa uma nova instância da classe {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | Inicializa uma nova instância da classe {@link OptimizedMemoryStream} com base no array de bytes especificado. |

## Métodos

| Método | Descrição |
| --- | --- |
| [canRead](#canRead--) | Quando sobrescrito em uma classe derivada, obtém um valor que indica se o fluxo atual suporta leitura. |
| [canSeek](#canSeek--) | Quando sobrescrito em uma classe derivada, obtém um valor que indica se o fluxo atual suporta busca. |
| [canWrite](#canWrite--) | Quando sobrescrito em uma classe derivada, obtém um valor que indica se o fluxo atual suporta gravação. |
| [flush](#flush--) | A função sobrescrita. |
| [getBufferSize](#getBufferSize--) | Obtém ou define o tamanho dos buffers subjacentes. Valor: O tamanho dos buffers. |
| [getFreeOnDispose](#getFreeOnDispose--) | Obtém ou define um valor que indica se os buffers subjacentes devem ser liberados ao descartar. |
| [getLength](#getLength--) | Quando sobrescrito em uma classe derivada, obtém o comprimento em bytes do fluxo. |
| [getPosition](#getPosition--) | Quando sobrescrito em uma classe derivada, obtém ou define a posição dentro do fluxo atual. |
| [read](#read-byte:A-int-int-) | Quando sobrescrito em uma classe derivada, lê uma sequência de bytes do fluxo atual e avança a posição no fluxo pelo número de bytes lidos. |
| [readByte](#readByte--) | Lê um byte do fluxo e avança a posição no fluxo em um byte, ou retorna -1 se estiver no final do fluxo. |
| [seek](#seek-long-int-) | Quando sobrescrito em uma classe derivada, define a posição dentro do fluxo atual. |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | Quando sobrescrito em uma classe derivada, define a posição dentro do fluxo atual. |
| [setBufferSize](#setBufferSize-int-) | Obtém ou define o tamanho dos buffers subjacentes. Valor: O tamanho dos buffers. |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | Obtém ou define um valor que indica se os buffers subjacentes devem ser liberados ao descartar. |
| [setLength](#setLength-long-) | Quando sobrescrito em uma classe derivada, define o comprimento do fluxo atual. |
| [setPosition](#setPosition-long-) | Quando sobrescrito em uma classe derivada, obtém ou define a posição dentro do fluxo atual. A posição atual dentro do fluxo. Valor: |
| [toArray](#toArray--) | Converte o fluxo atual em um array de bytes. |
| [write](#write-byte:A-int-int-) | Quando sobrescrito em uma classe derivada, grava uma sequência de bytes no fluxo atual e avança a posição atual neste fluxo pelo número de bytes gravados. |
| [writeByte](#writeByte-byte-) | Grava um byte na posição atual do fluxo e avança a posição no fluxo em um byte. |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | Grava no fluxo especificado. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

Valor padrão do tamanho do buffer em bytes.

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

Inicializa uma nova instância da classe {@link OptimizedMemoryStream}.

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

Inicializa uma nova instância da classe {@link OptimizedMemoryStream} com base no array de bytes especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer |  | O array de bytes sem sinal a partir do qual criar o fluxo atual. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

Inicializa uma nova instância da classe {@link OptimizedMemoryStream}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bufferSize |  | Tamanho dos buffers subjacentes. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

Inicializa uma nova instância da classe {@link OptimizedMemoryStream} com base no array de bytes especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bufferSize |  | Tamanho dos buffers subjacentes. |
| buffer |  | O array de bytes sem sinal a partir do qual criar o fluxo atual. |

### canRead {#canRead--}
```
public boolean canRead()
```

Quando sobrescrito em uma classe derivada, obtém um valor que indica se o fluxo atual suporta leitura.

**Returns:**
true se o fluxo suportar leitura; caso contrário, false. Valor:

### canSeek {#canSeek--}
```
public boolean canSeek()
```

Quando sobrescrito em uma classe derivada, obtém um valor que indica se o fluxo atual suporta busca.

**Returns:**
true se o fluxo suportar busca; caso contrário, false. Valor:

### canWrite {#canWrite--}
```
public boolean canWrite()
```

Quando sobrescrito em uma classe derivada, obtém um valor que indica se o fluxo atual suporta gravação.

**Returns:**
true se o fluxo suportar gravação; caso contrário, false. Valor:

### flush {#flush--}
```
public void flush()
```

A função sobrescrita.

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

Obtém ou define o tamanho dos buffers subjacentes. Valor: O tamanho dos buffers.

**Returns:**
valor int

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

Obtém ou define um valor que indica se os buffers subjacentes devem ser liberados ao descartar.

**Returns:**
valor booleano

### getLength {#getLength--}
```
public long getLength()
```

Quando sobrescrito em uma classe derivada, obtém o comprimento em bytes do fluxo.

**Returns:**
Um valor long que representa o comprimento do fluxo em bytes. Valor:

### getPosition {#getPosition--}
```
public long getPosition()
```

Quando sobrescrito em uma classe derivada, obtém ou define a posição dentro do fluxo atual.

**Returns:**
A posição atual dentro do fluxo. Valor:

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

Quando sobrescrito em uma classe derivada, lê uma sequência de bytes do fluxo atual e avança a posição no fluxo pelo número de bytes lidos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer |  | Um array de bytes. Quando este método retornar, o buffer conterá o array de bytes especificado com os valores |
| offset |  | O deslocamento de byte baseado em zero no qual começar a armazenar os dados lidos do fluxo atual. |
| contagem |  | O número máximo de bytes a ser lido do fluxo atual. |

**Returns:**
O número total de bytes lidos para o buffer. Isso pode ser menor que o número de bytes solicitados se essa quantidade de bytes não estiver disponível no momento, ou zero (0) se o final do fluxo foi alcançado.

### readByte {#readByte--}
```
public int readByte()
```

Lê um byte do fluxo e avança a posição no fluxo em um byte, ou retorna -1 se estiver no final do fluxo.

**Returns:**
byte ou -1 se estiver no final do fluxo.

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

Quando sobrescrito em uma classe derivada, define a posição dentro do fluxo atual.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| offset |  | Um deslocamento de byte relativo ao parâmetro {@code origin}. |
| origin |  | Um valor do tipo {@link SeekOrigin} indicando o ponto de referência usado para obter a nova posição. |

**Returns:**
A nova posição dentro do fluxo atual.

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
Quando sobrescrito em uma classe derivada, define a posição dentro do fluxo atual.

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

Obtém ou define o tamanho dos buffers subjacentes. Valor: O tamanho dos buffers.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

Obtém ou define um valor que indica se os buffers subjacentes devem ser liberados ao descartar.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

Quando sobrescrito em uma classe derivada, define o comprimento do fluxo atual.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | O comprimento desejado do fluxo atual em bytes. |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

Quando sobrescrito em uma classe derivada, obtém ou define a posição dentro do fluxo atual. A posição atual dentro do fluxo. Valor:

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

Converte o fluxo atual em um array de bytes.

**Returns:**
Um array de bytes

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

Quando sobrescrito em uma classe derivada, grava uma sequência de bytes no fluxo atual e avança a posição atual neste fluxo pelo número de bytes gravados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer |  | Um array de bytes. Este método copia {@code count} bytes de {@code buffer} para o fluxo atual. |
| offset |  | O deslocamento de byte baseado em zero em {@code buffer} onde iniciar a cópia de bytes para o fluxo atual. |
| contagem |  | O número de bytes a serem escritos no fluxo atual. |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

Grava um byte na posição atual do fluxo e avança a posição no fluxo em um byte.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | O byte a ser escrito no fluxo. |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
Grava no fluxo especificado.
