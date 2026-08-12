---
title: "класс System::IO::FileStream"
linktitle: "FileStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::IO::FileStream. Представляет поток файла, поддерживающий синхронные и асинхронные операции чтения и записи. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1500
url: /ru/cpp/system.io/filestream/
---
## FileStream class


Представляет поток файла, поддерживающий синхронные и асинхронные операции чтения и записи. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class FileStream : public System::IO::Stream
```

## Методы

| Метод | Описание |
| --- | --- |
| [Close](./close/)() override | Закрывает текущий объект [FileStream](./). |
| [FileStream](./filestream/)(const String\&, FileMode) | Создаёт новый экземпляр класса [FileStream](./) и инициализирует его указанными параметрами. |
| [FileStream](./filestream/)(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) | Создаёт новый экземпляр класса [FileStream](./) и инициализирует его указанными параметрами. |
| [FileStream](./filestream/)(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) | Создаёт новый экземпляр класса [FileStream](./) и инициализирует его указанными параметрами. |
| [FileStream](./filestream/)(const FileStream\&) |  |
| [Flush](./flush/)() override | Очищает буферы этого потока и записывает все буферизованные данные в базовый файл. |
| [Flush](./flush/)(bool) | Очищает буферы этого потока и записывает все буферизованные данные в базовый файл. Синоним метода [Flush()](./flush/). |
| [FlushAsync](./flushasync/)(const Threading::CancellationToken\&) override | Асинхронно очищает все буферы этого потока, заставляя любые буферизованные данные записываться в базовое устройство, и отслеживает запросы на отмену. |
| [get_CanRead](./get_canread/)() const override | Определяет, доступен ли поток для чтения. |
| [get_CanSeek](./get_canseek/)() const override | Определяет, поддерживает ли поток перемещение. |
| [get_CanWrite](./get_canwrite/)() const override | Определяет, доступен ли поток для записи. |
| [get_Length](./get_length/)() const override | Возвращает длину потока в байтах. |
| [get_Name](./get_name/)() const | Возвращает имя файла, инкапсулированного текущим объектом [FileStream](./). |
| [get_Position](./get_position/)() const override | Возвращает текущую позицию потока. |
| [operator=](./operator=/)(const FileStream\&) |  |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) override | Асинхронно читает последовательность байтов из текущего потока, перемещает позицию в потоке на количество прочитанных байтов и отслеживает запросы на отмену. |
| [ReadByte](./readbyte/)() override | Читает один байт из потока и возвращает 32‑битное целочисленное значение, эквивалентное значению прочитанного байта. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Устанавливает позицию потока, представленного текущим объектом. |
| [set_Position](./set_position/)(int64_t) override | Очищает поток и затем устанавливает позицию потока. |
| [SetLength](./setlength/)(int64_t) override | Устанавливает длину потока, представленного текущим объектом. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Записывает указанный поддиапазон байт из указанного массива байтов в поток. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Записывает указанный поддиапазон байт из указанного массива байтов в поток. |
| [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) override | Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы на отмену. |
| [WriteByte](./writebyte/)(uint8_t) override | Записывает указанное беззнаковое 8-битное целое значение в поток. |
| [~FileStream](./~filestream/)() | Деструктор. |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | Значение по умолчанию количества байтов, буферизованных во время операций чтения и записи. |
| static [Null](../stream/null/) | Поток без базового хранилища. |
## См. также

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
