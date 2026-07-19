---
title: "Класс System::IO::UnmanagedMemoryStream"
linktitle: "UnmanagedMemoryStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::IO::UnmanagedMemoryStream. Предоставляет доступ к неуправляемой памяти. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2800
url: /ru/cpp/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream class


Предоставляет доступ к неуправляемой памяти. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## Методы

| Метод | Описание |
| --- | --- |
| [Flush](./flush/)() override | Ничего не делает. |
| [get_CanRead](./get_canread/)() const override | Определяет, доступен ли поток для чтения. |
| [get_CanSeek](./get_canseek/)() const override | Определяет, поддерживает ли поток перемещение. |
| [get_CanWrite](./get_canwrite/)() const override | Определяет, доступен ли поток для записи. |
| virtual [get_Capacity](./get_capacity/)() const | Возвращает текущую ёмкость базового буфера памяти. |
| [get_Length](./get_length/)() const override | Возвращает длину потока в байтах. |
| [get_Position](./get_position/)() const override | Возвращает текущую позицию потока. |
| [get_PositionPointer](./get_positionpointer/)() | НЕ РЕАЛИЗОВАНО. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Устанавливает позицию потока, представленного текущим объектом. |
| [set_Position](./set_position/)(int64_t) override | Устанавливает позицию потока. |
| [set_PositionPointer](./set_positionpointer/)(uint8_t *) | НЕ РЕАЛИЗОВАНО. |
| [SetLength](./setlength/)(int64_t) override | НЕ РЕАЛИЗОВАНО. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/)(uint8_t *, int64_t) | Создаёт новый экземпляр [UnmanagedMemoryStream](./). |
| [UnmanagedMemoryStream](./unmanagedmemorystream/)(uint8_t *, int64_t, int64_t, FileAccess) | Создаёт новый экземпляр [UnmanagedMemoryStream](./). |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | НЕ РЕАЛИЗОВАНО. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | НЕ РЕАЛИЗОВАНО. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Null](../stream/null/) | Поток без базового хранилища. |
## См. также

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
