---
title: "Класс System::Net::Http::HttpMethod"
linktitle: "HttpMethod"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::Http::HttpMethod. Представляет HTTP‑метод. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 700
url: /ru/cpp/system.net.http/httpmethod/
---
## HttpMethod class


Представляет HTTP‑метод. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpMethod : public System::IEquatable<System::SharedPtr<System::Net::Http::HttpMethod>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<HttpMethod\>) override | Определяет, равны ли текущий и указанный объекты. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static [get_Delete](./get_delete/)() | Возвращает HTTP‑метод 'DELETE'. |
| static [get_Get](./get_get/)() | Возвращает HTTP‑метод 'GET'. |
| static [get_Head](./get_head/)() | Возвращает HTTP‑метод 'HEAD'. |
| [get_Method](./get_method/)() | Возвращает строковое представление HTTP‑метода. |
| static [get_Options](./get_options/)() | Возвращает HTTP‑метод 'OPTIONS'. |
| static [get_Post](./get_post/)() | Возвращает HTTP‑метод 'POST'. |
| static [get_Put](./get_put/)() | Возвращает HTTP‑метод 'PUT'. |
| static [get_Trace](./get_trace/)() | Возвращает HTTP‑метод 'TRACE'. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [HttpMethod](./httpmethod/)(String) | Создаёт новый экземпляр. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
## См. также

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
