---
title: "System::IO::StringWriter класс"
linktitle: "StringWriter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::StringWriter класс. Реализует TextWriter, который записывает информацию в строку. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2500
url: /ru/cpp/system.io/stringwriter/
---
## StringWriter class


Реализует [TextWriter](../textwriter/), который записывает информацию в строку. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Encoding](./get_encoding/)() override | Возвращает текущую используемую кодировку. |
| virtual [GetStringBuilder](./getstringbuilder/)() | Возвращает текущий используемый StringBuilder. |
| [StringWriter](./stringwriter/)(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) | Создаёт новый экземпляр [StringWriter](./), используя указанный StringBuilder и [IFormatProvider](../../system/iformatprovider/). |
| [StringWriter](./stringwriter/)(const System::SharedPtr\<Text::StringBuilder\>\&) | Создаёт новый экземпляр [StringWriter](./), используя указанный StringBuilder и [IFormatProvider](../../system/iformatprovider/) из текущей культуры. |
| [StringWriter](./stringwriter/)(const IFormatProviderPtr\&) | Создаёт новый экземпляр [StringWriter](./), используя указанный [IFormatProvider](../../system/iformatprovider/). |
| [StringWriter](./stringwriter/)() | Создаёт новый экземпляр [StringWriter](./), используя [IFormatProvider](../../system/iformatprovider/) из текущей культуры. |
| [ToString](./tostring/)() const override | Возвращает базовую строку. |
| [Write](./write/)(char_t) override | Записывает указанный символ в поток. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Записывает указанный поддиапазон символов из указанного массива символов в поток. |
| [Write](./write/)(const String\&) override | Записывает указанную строку в поток. |
## См. также

* Class [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
