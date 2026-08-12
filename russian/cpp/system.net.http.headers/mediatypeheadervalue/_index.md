---
title: "System::Net::Http::Headers::MediaTypeHeaderValue class"
linktitle: "MediaTypeHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::MediaTypeHeaderValue class. Представляет MIME‑тип в значении заголовка ''Content-Type''. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1200
url: /ru/cpp/system.net.http.headers/mediatypeheadervalue/
---
## MediaTypeHeaderValue class


Представляет MIME‑тип в значении заголовка 'Content-Type'. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class MediaTypeHeaderValue : public virtual System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_CharSet](./get_charset/)() | Информация RTTI. |
| [get_MediaType](./get_mediatype/)() | Получает значение заголовка media-type. |
| [get_Parameters](./get_parameters/)() | Возвращает параметры значения заголовка media-type. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [GetMediaTypeLength](./getmediatypelength/)(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [MediaTypeHeaderValue](./). |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)() | Создаёт новый экземпляр. |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)(String) | Создаёт новый экземпляр. |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [MediaTypeHeaderValue](./). |
| [set_CharSet](./set_charset/)(String) | Устанавливает набор символов. |
| [set_MediaType](./set_mediatype/)(String) | Устанавливает значение заголовка media-type. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<MediaTypeHeaderValue\>\&) | Пытается преобразовать переданную строку в экземпляр класса [MediaTypeHeaderValue](./). |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
