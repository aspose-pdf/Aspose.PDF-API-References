---
title: "System::Net::Http::Headers::StringWithQualityHeaderValue класс"
linktitle: "StringWithQualityHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::StringWithQualityHeaderValue класс. Представляет значение с дополнительным качеством строкового заголовка. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2300
url: /ru/cpp/system.net.http.headers/stringwithqualityheadervalue/
---
## StringWithQualityHeaderValue class


Представляет значение с дополнительным качеством строкового заголовка. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class StringWithQualityHeaderValue : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_Quality](./get_quality/)() | Возвращает качество. |
| [get_Value](./get_value/)() | Информация RTTI. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [GetStringWithQualityLength](./getstringwithqualitylength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [StringWithQualityHeaderValue](./). |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [StringWithQualityHeaderValue](./). |
| [StringWithQualityHeaderValue](./stringwithqualityheadervalue/)(String) | Создаёт новый экземпляр. |
| [StringWithQualityHeaderValue](./stringwithqualityheadervalue/)(String, double) | Создаёт новый экземпляр. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<StringWithQualityHeaderValue\>\&) | Пытается преобразовать переданную строку в экземпляр класса [StringWithQualityHeaderValue](./). |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
