---
title: "System::IO::BasicSTDOStreamWrapper класс"
linktitle: "BasicSTDOStreamWrapper"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BasicSTDOStreamWrapper класс. Представляет обёртку, похожую на System.IO.Stream, для std::basic_ostream и его производных объектов. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper class


Представляет [System.IO.Stream](../stream/)-like обёртку для std::basic_ostream и его производных объектов. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Методы

| Метод | Описание |
| --- | --- |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) | Создаёт новый экземпляр [BasicSTDOStreamWrapper](./). |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const BasicSTDOStreamWrapper\&) | Конструктор копирования. Удалён. |
| [Flush](./flush/)() override | Очищает буферы этого потока и записывает все буферизованные данные в базовое хранилище. |
| [operator=](./operator=/)(const BasicSTDOStreamWrapper\&) | Оператор присваивания копированием. Удалён. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Если режим обёртки бинарный, читает указанное количество байтов из потока, иначе читает указанное количество символов и преобразует их в тип uint8_t. Записывает результат чтения в указанный массив байтов. Не поддерживается! |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| [ReadByte](./readbyte/)() override | Если режим обёртки бинарный, читает один байт из последнего хранилища декодированных символов, иначе читает один символ из потока и преобразует его в тип uint8_t. Не поддерживается! |
| [SetLength](./setlength/)(int64_t) override | Устанавливает длину потока, представленного текущим объектом. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Если режим обёртки бинарный, записывает в поток указанный поддиапазон байтов из указанного массива байтов, иначе преобразует указанный поддиапазон байтов из указанного массива байтов в тип [char_type](./char_type/) и затем записывает результат в поток. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Записывает указанный поддиапазон байт из указанного массива байтов в поток. |
| [WriteByte](./writebyte/)(uint8_t) override | Если режим обёртки бинарный, записывает в поток указанное беззнаковое 8‑битное целочисленное значение, иначе преобразует его в тип [char_type](./char_type/) и затем записывает результат в поток. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Null](../stream/null/) | Поток без базового хранилища. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) |  |
| [char_type](./char_type/) | Информация RTTI. |
| [ThisType](./thistype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [traits_type](./traits_type/) |  |
## См. также

* Class [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
