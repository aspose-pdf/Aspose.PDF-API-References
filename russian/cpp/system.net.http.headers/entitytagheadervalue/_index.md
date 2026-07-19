---
title: "System::Net::Http::Headers::EntityTagHeaderValue класс"
linktitle: "EntityTagHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::EntityTagHeaderValue класс. Представляет значение заголовка ''Entity-Tag''. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 500
url: /ru/cpp/system.net.http.headers/entitytagheadervalue/
---
## EntityTagHeaderValue class


Представляет значение заголовка 'Entity-Tag'. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class EntityTagHeaderValue : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [EntityTagHeaderValue](./entitytagheadervalue/)(String) | Создаёт новый экземпляр. |
| [EntityTagHeaderValue](./entitytagheadervalue/)(String, bool) | Создаёт новый экземпляр. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static [get_Any](./get_any/)() | Получает значение заголовка 'ETag'. |
| [get_IsWeak](./get_isweak/)() | Получает значение, указывающее, является ли текущий экземпляр слабым валидатором. |
| [get_Tag](./get_tag/)() | Информация RTTI. |
| static [GetEntityTagLength](./getentitytaglength/)(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [EntityTagHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [EntityTagHeaderValue](./). |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<EntityTagHeaderValue\>\&) | Пытается преобразовать переданную строку в экземпляр класса [EntityTagHeaderValue](./). |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
