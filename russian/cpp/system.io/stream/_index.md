---
title: "System::IO::Stream класс"
linktitle: "Stream"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::Stream класс. Базовый класс для различных реализаций потоков. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2100
url: /ru/cpp/system.io/stream/
---
## Stream class


Базовый класс для различных реализаций потоков. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Stream : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) | Инициирует асинхронную операцию чтения. |
| virtual [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) | Инициирует асинхронную операцию записи. |
| virtual [Close](./close/)() | Закрывает поток. |
| [CopyTo](./copyto/)(const SharedPtr\<Stream\>\&) | Копирует байты в указанный поток. |
| [CopyTo](./copyto/)(const SharedPtr\<Stream\>\&, int32_t) | Копирует байты в указанный поток, используя указанный размер буфера. |
| [Dispose](./dispose/)() override | Освобождает все ресурсы, используемые текущим объектом, и закрывает поток. |
| virtual [EndRead](./endread/)(System::SharedPtr\<System::IAsyncResult\>) | Ожидает завершения указанной асинхронной операции чтения. |
| virtual [EndWrite](./endwrite/)(System::SharedPtr\<System::IAsyncResult\>) | Завершает асинхронную операцию записи. Ожидает завершения указанной асинхронной операции записи. |
| virtual [Flush](./flush/)() | Очищает буферы этого потока и записывает все буферизованные данные в базовое хранилище. |
| virtual [FlushAsync](./flushasync/)(const Threading::CancellationToken\&) | Асинхронно очищает все буферы этого потока, заставляя любые буферизованные данные записываться в базовое устройство, и отслеживает запросы на отмену. |
| [FlushAsync](./flushasync/)() | Асинхронно очищает все буферы этого потока, заставляя любые буферизованные данные записываться в базовое устройство, и отслеживает запросы на отмену. |
| virtual [get_CanRead](./get_canread/)() const | Определяет, доступен ли поток для чтения. |
| virtual [get_CanSeek](./get_canseek/)() const | Определяет, поддерживает ли поток перемещение. |
| virtual [get_CanTimeout](./get_cantimeout/)() const | Получает значение, определяющее, может ли текущий поток завершаться по тайм‑ауту. |
| virtual [get_CanWrite](./get_canwrite/)() const | Определяет, доступен ли поток для записи. |
| virtual [get_Length](./get_length/)() const | Возвращает длину потока в байтах. |
| virtual [get_Position](./get_position/)() const | Возвращает текущую позицию потока. |
| virtual [get_ReadTimeout](./get_readtimeout/)() const | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм‑аута. |
| virtual [get_WriteTimeout](./get_writetimeout/)() const | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться записывать до истечения тайм‑аута. |
| virtual [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| virtual [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| [Read](./read/)(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| virtual [Read](./read/)(const System::Span\<uint8_t\>\&) | Читает указанное количество байтов из потока и записывает их в указанный диапазон байтов. |
| virtual [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) | Асинхронно читает последовательность байтов из текущего потока, перемещает позицию в потоке на количество прочитанных байтов и отслеживает запросы на отмену. |
| [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Асинхронно читает последовательность байтов из текущего потока, перемещает позицию в потоке на количество прочитанных байтов и отслеживает запросы на отмену. |
| virtual [ReadByte](./readbyte/)() | Читает один байт из потока и возвращает 32‑битное целочисленное значение, эквивалентное значению прочитанного байта. |
| virtual [Seek](./seek/)(int64_t, SeekOrigin) | Устанавливает позицию потока, представленного текущим объектом. |
| virtual [set_Position](./set_position/)(int64_t) | Устанавливает позицию потока. |
| virtual [set_ReadTimeout](./set_readtimeout/)(int) | Устанавливает значение, определяющее, может ли текущий поток завершаться по тайм‑ауту. |
| virtual [set_WriteTimeout](./set_writetimeout/)(int) | Устанавливает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм‑аута. |
| virtual [SetLength](./setlength/)(int64_t) | Устанавливает длину потока, представленного текущим объектом. |
| virtual [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Записывает указанный поддиапазон байт из указанного массива байтов в поток. |
| virtual [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) | Записывает указанный поддиапазон байт из указанного массива байтов в поток. |
| [Write](./write/)(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) | Записывает указанный поддиапазон байт из указанного массива байтов в поток. |
| virtual [Write](./write/)(const System::ReadOnlySpan\<uint8_t\>\&) | Записывает указанный поддиапазон байтов из указанного диапазона байтов в поток. |
| virtual [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) | Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы на отмену. |
| [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы на отмену. |
| virtual [WriteByte](./writebyte/)(uint8_t) | Записывает указанное беззнаковое 8-битное целое значение в поток. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Null](./null/) | Поток без базового хранилища. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer этого класса. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
