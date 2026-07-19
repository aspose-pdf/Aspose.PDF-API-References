---
title: "Класс Aspose::Pdf::OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::OptimizedMemoryStream. Определяет MemoryStream, который может содержать большую стандартную ёмкость в C++."
type: docs
weight: 12400
url: /ru/cpp/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class


Определяет MemoryStream, который может содержать большую стандартную ёмкость.

```cpp
class OptimizedMemoryStream : public System::IO::Stream
```

## Методы

| Метод | Описание |
| --- | --- |
| [Flush](./flush/)() override | Переопределённая функция. |
| [get_BufferSize](./get_buffersize/)() const | Возвращает размер базовых буферов. |
| [get_CanRead](./get_canread/)() const override | При переопределении в производном классе возвращает значение, указывающее, поддерживает ли текущий поток чтение. |
| [get_CanSeek](./get_canseek/)() const override | При переопределении в производном классе возвращает значение, указывающее, поддерживает ли текущий поток перемещение. |
| [get_CanWrite](./get_canwrite/)() const override | При переопределении в производном классе возвращает значение, указывающее, поддерживает ли текущий поток запись. |
| [get_FreeOnDispose](./get_freeondispose/)() const | Возвращает значение, указывающее, следует ли освобождать базовые буферы при освобождении. |
| [get_Length](./get_length/)() const override | При переопределении в производном классе возвращает длину потока в байтах. |
| [get_Position](./get_position/)() const override | При переопределении в производном классе получает или задает позицию в текущем потоке. |
| [OptimizedMemoryStream](./optimizedmemorystream/)() | Инициализирует новый экземпляр класса [OptimizedMemoryStream](./) . |
| [OptimizedMemoryStream](./optimizedmemorystream/)(int32_t, const System::ArrayPtr\<uint8_t\>\&) | Инициализирует новый экземпляр класса [OptimizedMemoryStream](./) на основе указанного массива байтов. |
| [OptimizedMemoryStream](./optimizedmemorystream/)(int32_t) | Инициализирует новый экземпляр класса [OptimizedMemoryStream](./) . |
| [OptimizedMemoryStream](./optimizedmemorystream/)(const System::ArrayPtr\<uint8_t\>\&) | Инициализирует новый экземпляр класса [OptimizedMemoryStream](./) на основе указанного массива байтов. |
| [Read](./read/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | При переопределении в производном классе читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| [ReadByte](./readbyte/)() override | Читает байт из потока и перемещает позицию в потоке на один байт, или возвращает -1, если достигнут конец потока. |
| [Seek](./seek/)(int64_t, System::IO::SeekOrigin) override | При переопределении в производном классе устанавливает позицию в текущем потоке. |
| [set_BufferSize](./set_buffersize/)(int32_t) | Устанавливает размер базовых буферов. |
| [set_FreeOnDispose](./set_freeondispose/)(bool) | Устанавливает значение, указывающее, освобождать ли базовые буферы при освобождении ресурсов. |
| [set_Position](./set_position/)(int64_t) override | При переопределении в производном классе получает или задает позицию в текущем потоке. |
| [SetLength](./setlength/)(int64_t) override | При переопределении в производном классе устанавливает длину текущего потока. |
| [ToArray](./toarray/)() | Преобразует текущий поток в массив байтов. |
| [Write](./write/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | При переопределении в производном классе записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| [WriteByte](./writebyte/)(uint8_t) override | Записывает байт в текущую позицию потока и перемещает позицию в потоке на один байт. |
| [WriteTo](./writeto/)(const System::SharedPtr\<System::IO::Stream\>\&) | Записывает в указанный поток. |
## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Значение размера буфера по умолчанию в байтах. |
| static [Null](../../system.io/stream/null/) | Поток без базового хранилища. |
## См. также

* Class [Stream](../../system.io/stream/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
