---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OptimizedMemoryStream. Define um MemoryStream que pode conter mais capacidade padrão
type: docs
weight: 7990
url: /pt/net/aspose.pdf/optimizedmemorystream/
---
## Classe OptimizedMemoryStream

Define um MemoryStream que pode conter mais capacidade padrão

```csharp
public class OptimizedMemoryStream : Stream
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | Inicializa uma nova instância da classe `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | Inicializa uma nova instância da classe `OptimizedMemoryStream` com base no array de bytes especificado. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | Inicializa uma nova instância da classe `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | Inicializa uma nova instância da classe `OptimizedMemoryStream` com base no array de bytes especificado. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Obtém ou define o tamanho dos buffers subjacentes. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | Quando substituído em uma classe derivada, obtém um valor que indica se o fluxo atual suporta leitura. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | Quando substituído em uma classe derivada, obtém um valor que indica se o fluxo atual suporta busca. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | Quando substituído em uma classe derivada, obtém um valor que indica se o fluxo atual suporta gravação. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Obtém ou define um valor que indica se deve liberar os buffers subjacentes ao descartar. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | Quando substituído em uma classe derivada, obtém o comprimento em bytes do fluxo. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | Quando substituído em uma classe derivada, obtém ou define a posição dentro do fluxo atual. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | A função substituída. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | Quando substituído em uma classe derivada, lê uma sequência de bytes do fluxo atual e avança a posição dentro do fluxo pelo número de bytes lidos. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Lê um byte do fluxo e avança a posição dentro do fluxo em um byte, ou retorna -1 se estiver no final do fluxo. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | Quando substituído em uma classe derivada, define a posição dentro do fluxo atual. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | Quando substituído em uma classe derivada, define o comprimento do fluxo atual. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Converte o fluxo atual em um array de bytes. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | Quando substituído em uma classe derivada, grava uma sequência de bytes no fluxo atual e avança a posição atual dentro deste fluxo pelo número de bytes gravados. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Grava um byte na posição atual do fluxo e avança a posição dentro do fluxo em um byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Grava no fluxo especificado. |

## Campos

| Nome | Descrição |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Valor padrão do tamanho do buffer em bytes. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)