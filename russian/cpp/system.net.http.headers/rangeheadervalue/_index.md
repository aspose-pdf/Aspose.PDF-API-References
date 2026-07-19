---
title: "System::Net::Http::Headers::RangeHeaderValue класс"
linktitle: "RangeHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::RangeHeaderValue класс. Представляет значение заголовка ''Range''. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2000
url: /ru/cpp/system.net.http.headers/rangeheadervalue/
---
## RangeHeaderValue class


Представляет значение заголовка '[Range](../../system/range/)' header. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class RangeHeaderValue : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_Ranges](./get_ranges/)() | Возвращает коллекцию диапазонов. |
| [get_Unit](./get_unit/)() | Информация RTTI. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [GetRangeLength](./getrangelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [RangeHeaderValue](./). |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [RangeHeaderValue](./). |
| [RangeHeaderValue](./rangeheadervalue/)() | Создаёт новый экземпляр. |
| [RangeHeaderValue](./rangeheadervalue/)(Nullable\<int64_t\>, Nullable\<int64_t\>) | Создаёт новый экземпляр. |
| [set_Unit](./set_unit/)(String) | Устанавливает единицу. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<RangeHeaderValue\>\&) | Пытается преобразовать переданную строку в экземпляр класса [RangeHeaderValue](./). |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
