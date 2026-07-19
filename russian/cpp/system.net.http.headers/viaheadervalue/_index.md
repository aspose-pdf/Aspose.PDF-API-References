---
title: "System::Net::Http::Headers::ViaHeaderValue класс"
linktitle: "ViaHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::ViaHeaderValue класс. Представляет значение заголовка ''Via''. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2600
url: /ru/cpp/system.net.http.headers/viaheadervalue/
---
## ViaHeaderValue class


Представляет значение заголовка 'Via'. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ViaHeaderValue : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_Comment](./get_comment/)() | Возвращает комментарий из значения заголовка 'Via'. |
| [get_ProtocolName](./get_protocolname/)() | Информация RTTI. |
| [get_ProtocolVersion](./get_protocolversion/)() | Возвращает версию протокола из значения заголовка 'Via'. |
| [get_ReceivedBy](./get_receivedby/)() | Возвращает хост и порт, через которые был получен запрос или ответ. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [GetViaLength](./getvialength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [ViaHeaderValue](./). |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [ViaHeaderValue](./). |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ViaHeaderValue\>\&) | Пытается преобразовать переданную строку в экземпляр класса [ViaHeaderValue](./). |
| [ViaHeaderValue](./viaheadervalue/)(String, String) | Создаёт новый экземпляр. |
| [ViaHeaderValue](./viaheadervalue/)(String, String, String) | Создаёт новый экземпляр. |
| [ViaHeaderValue](./viaheadervalue/)(String, String, String, String) | Создаёт новый экземпляр. |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
