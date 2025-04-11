---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.OptimizedMemoryStream. Определяет MemoryStream, который может содержать больше стандартной емкости
type: docs
weight: 7990
url: /ru/net/aspose.pdf/optimizedmemorystream/
---
## Класс OptimizedMemoryStream

Определяет MemoryStream, который может содержать больше стандартной емкости

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
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Получает или задает размер базовых буферов. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | При переопределении в производном классе получает значение, указывающее, поддерживает ли текущий поток чтение. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | При переопределении в производном классе получает значение, указывающее, поддерживает ли текущий поток перемещение. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | При переопределении в производном классе получает значение, указывающее, поддерживает ли текущий поток запись. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Получает или задает значение, указывающее, освобождать ли базовые буферы при освобождении. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | При переопределении в производном классе получает длину в байтах потока. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | При переопределении в производном классе получает или задает позицию в текущем потоке. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | Функция переопределена. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | При переопределении в производном классе считывает последовательность байтов из текущего потока и перемещает позицию в потоке на количество считанных байтов. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Считывает байт из потока и перемещает позицию в потоке на один байт, или возвращает -1, если достигнут конец потока. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | При переопределении в производном классе устанавливает позицию в текущем потоке. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | При переопределении в производном классе устанавливает длину текущего потока. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Преобразует текущий поток в массив байтов. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | При переопределении в производном классе записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Записывает в указанный поток. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Значение размера буфера по умолчанию в байтах. |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)