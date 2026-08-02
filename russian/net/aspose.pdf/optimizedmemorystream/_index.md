---
title: "Класс OptimizedMemoryStream"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.OptimizedMemoryStream. Определяет MemoryStream, который может содержать большую стандартную ёмкость"
type: docs
weight: 8130
url: /ru/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

Определяет MemoryStream, который может содержать большую стандартную ёмкость.

```csharp
public class OptimizedMemoryStream : Stream
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | Инициализирует новый экземпляр класса `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | Инициализирует новый экземпляр класса `OptimizedMemoryStream` на основе указанного массива байтов. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | Инициализирует новый экземпляр класса `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | Инициализирует новый экземпляр класса `OptimizedMemoryStream` на основе указанного массива байтов. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Получает или задаёт размер базовых буферов. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | При переопределении в производном классе возвращает значение, указывающее, поддерживает ли текущий поток чтение. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | При переопределении в производном классе возвращает значение, указывающее, поддерживает ли текущий поток поиск. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | При переопределении в производном классе возвращает значение, указывающее, поддерживает ли текущий поток запись. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Получает или задаёт значение, указывающее, освобождать ли базовые буферы при освобождении ресурсов. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | При переопределении в производном классе возвращает длину потока в байтах. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | При переопределении в производном классе получает или задаёт позицию в текущем потоке. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | Функция переопределена. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | При переопределении в производном классе читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Читает байт из потока и перемещает позицию в потоке на один байт, или возвращает -1, если достигнут конец потока. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | При переопределении в производном классе задаёт позицию в текущем потоке. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | При переопределении в производном классе задаёт длину текущего потока. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Преобразует текущий поток в массив байтов. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | При переопределении в производном классе записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Записывает байт в текущую позицию потока и перемещает позицию в потоке на один байт. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Записывает в указанный поток. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Значение размера буфера по умолчанию в байтах. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


