---
title: "System::Net::Http::Headers::NameValueWithParametersHeaderValue class"
linktitle: "NameValueWithParametersHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::NameValueWithParametersHeaderValue class. Представляет пару ключ/значение с параметрами для использования в заголовках. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1500
url: /ru/cpp/system.net.http.headers/namevaluewithparametersheadervalue/
---
## NameValueWithParametersHeaderValue class


Представляет пару ключ/значение с параметрами для использования в заголовках. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class NameValueWithParametersHeaderValue : public System::Net::Http::Headers::NameValueHeaderValue
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_Parameters](./get_parameters/)() | Информация RTTI. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [GetNameValueWithParametersLength](./getnamevaluewithparameterslength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [NameValueWithParametersHeaderValue](./). |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)(String) | Создаёт новый экземпляр. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)(String, String) | Создаёт новый экземпляр. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)() | Создаёт новый экземпляр. |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [NameValueWithParametersHeaderValue](./). |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<NameValueWithParametersHeaderValue\>\&) | Пытается преобразовать переданную строку в экземпляр класса [NameValueWithParametersHeaderValue](./). |
## См. также

* Class [NameValueHeaderValue](../namevalueheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
