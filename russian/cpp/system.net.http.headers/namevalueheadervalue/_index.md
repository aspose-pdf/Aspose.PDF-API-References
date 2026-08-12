---
title: "System::Net::Http::Headers::NameValueHeaderValue класс"
linktitle: "NameValueHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::NameValueHeaderValue класс. Представляет пару ключ/значение для использования в заголовках. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() функции. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1400
url: /ru/cpp/system.net.http.headers/namevalueheadervalue/
---
## NameValueHeaderValue class


Представляет пару ключ/значение для использования в заголовках. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class NameValueHeaderValue : public virtual System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static [Find](./find/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, String) | Находит экземпляр класса NameValueHeaderValue в коллекции по указанному имени. |
| [get_Name](./get_name/)() | Возвращает имя текущего экземпляра. |
| [get_Value](./get_value/)() | Получает значение текущего экземпляра. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [GetHashCode](./gethashcode/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) | Возвращает хеш-код всех элементов коллекции. |
| static [GetNameValueLength](./getnamevaluelength/)(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [NameValueHeaderValue](./). |
| static [GetNameValueLength](./getnamevaluelength/)(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [NameValueHeaderValue](./). |
| static [GetNameValueListLength](./getnamevaluelistlength/)(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) | Преобразует переданную строку, начиная с указанного индекса, в коллекцию экземпляров класса NameValueHeaderValue и возвращает длину разобранной подстроки. |
| static [GetValueLength](./getvaluelength/)(String, int32_t) | Возвращает длину значения, начиная с указанного индекса. |
| [NameValueHeaderValue](./namevalueheadervalue/)() | Создаёт новый экземпляр. |
| [NameValueHeaderValue](./namevalueheadervalue/)(String) | Создаёт новый экземпляр. |
| [NameValueHeaderValue](./namevalueheadervalue/)(String, String) | Создаёт новый экземпляр. |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [NameValueHeaderValue](./). |
| [set_Value](./set_value/)(String) | Устанавливает значение текущего экземпляра. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [ToString](./tostring/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) | Возвращает строковое представление коллекции экземпляров класса NameValueHeaderValue. |
| static [ToString](./tostring/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) | Возвращает строковое представление коллекции экземпляров класса NameValueHeaderValue. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<NameValueHeaderValue\>\&) | Пытается преобразовать переданную строку в экземпляр класса [NameValueHeaderValue](./). |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
