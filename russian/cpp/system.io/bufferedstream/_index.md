---
title: "Класс System::IO::BufferedStream"
linktitle: "BufferedStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::IO::BufferedStream. Добавляет слой буферизации поверх другого потока. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1000
url: /ru/cpp/system.io/bufferedstream/
---
## BufferedStream class


Добавляет слой буферизации поверх другого потока. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class BufferedStream : public System::IO::Stream
```

## Методы

| Метод | Описание |
| --- | --- |
| [BufferedStream](./bufferedstream/)(const SharedPtr\<Stream\>\&) | Создаёт объект [BufferedStream](./), который оборачивает указанный поток и использует буфер длиной 4096 байт. |
| [BufferedStream](./bufferedstream/)(const SharedPtr\<Stream\>\&, int) | Создаёт объект [BufferedStream](./), который оборачивает указанный поток и использует буфер указанного размера. |
| [Flush](./flush/)() override | Записывает содержимое буфера в базовый поток. |
| [get_CanRead](./get_canread/)() const override | Определяет, доступен ли поток для чтения. |
| [get_CanSeek](./get_canseek/)() const override | Определяет, поддерживает ли поток перемещение. |
| [get_CanWrite](./get_canwrite/)() const override | Определяет, доступен ли поток для записи. |
| [get_Length](./get_length/)() const override | Возвращает длину потока. |
| [get_Position](./get_position/)() const override | Возвращает текущую позицию потока. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Читает указанное количество байтов из базового потока и записывает их в указанный массив байтов. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Читает указанное количество байтов из базового потока и записывает их в указанный массив байтов. |
| [ReadByte](./readbyte/)() override | Читает один байт из базового потока и возвращает 32‑битное целочисленное значение, эквивалентное значению прочитанного байта. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Устанавливает позицию потока, представленного текущим объектом. |
| [set_Position](./set_position/)(int64_t) override | Сбрасывает буфер в базовый поток, а затем устанавливает позицию потока. |
| [SetLength](./setlength/)(int64_t) override | Устанавливает длину потока, представленного текущим объектом. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Записывает указанный поддиапазон байтов из указанного массива байтов в базовый поток. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Записывает указанный поддиапазон байтов из указанного массива байтов в базовый поток. |
| [WriteByte](./writebyte/)(uint8_t) override | Записывает указанное беззнаковое 8‑битное целочисленное значение в базовый поток. |
| virtual [~BufferedStream](./~bufferedstream/)() | Деструктор. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Null](../stream/null/) | Поток без базового хранилища. |
## См. также

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
