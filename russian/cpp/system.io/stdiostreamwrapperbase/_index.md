---
title: "System::IO::STDIOStreamWrapperBase класс"
linktitle: "STDIOStreamWrapperBase"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::STDIOStreamWrapperBase класс. Представляет базовый класс для обёрток, похожих на System.IO.Stream. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2000
url: /ru/cpp/system.io/stdiostreamwrapperbase/
---
## STDIOStreamWrapperBase class


Представляет базовый класс для обёрток, похожих на [System.IO.Stream](../stream/). Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T,typename>class STDIOStreamWrapperBase : public System::IO::Stream
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_CanRead](./get_canread/)() const override | Определяет, поддерживает ли поток чтение. |
| [get_CanSeek](./get_canseek/)() const override | Определяет, поддерживает ли поток перемещение. |
| [get_CanWrite](./get_canwrite/)() const override | Определяет, поддерживает ли поток запись. |
| [get_Length](./get_length/)() const override | Возвращает длину потока. |
| [get_Position](./get_position/)() const override | Возвращает текущую позицию потока. |
| [operator=](./operator=/)(const STDIOStreamWrapperBase\&) | Оператор присваивания копированием. Удалён. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Устанавливает позицию потока, представленного текущим объектом. |
| [set_Position](./set_position/)(int64_t) override | Устанавливает позицию потока. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/)(const STDIOStreamWrapperBase\&) | Конструктор копирования. Удалён. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Null](../stream/null/) | Поток без базового хранилища. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) |  |
| [char_type](./char_type/) | Информация RTTI. |
| [int_type](./int_type/) |  |
| [off_type](./off_type/) |  |
| [pos_type](./pos_type/) |  |
| [ThisType](./thistype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [traits_type](./traits_type/) |  |
## См. также

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
