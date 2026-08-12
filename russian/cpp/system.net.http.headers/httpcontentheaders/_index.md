---
title: "Класс System::Net::Http::Headers::HttpContentHeaders"
linktitle: "HttpContentHeaders"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::HttpContentHeaders класс. Представляет коллекцию заголовков ''Content''. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.net.http.headers/httpcontentheaders/
---
## HttpContentHeaders class


Представляет коллекцию заголовков 'Content'. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpContentHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Методы

| Метод | Описание |
| --- | --- |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Добавляет известные заголовки в указанную коллекцию. |
| [get_Allow](./get_allow/)() | Информация RTTI. |
| [get_ContentDisposition](./get_contentdisposition/)() | Получает значение заголовка 'Content-Disposition'. |
| [get_ContentEncoding](./get_contentencoding/)() | Получает значение заголовка 'Content-Encoding'. |
| [get_ContentLanguage](./get_contentlanguage/)() | Получает значение заголовка 'Content-Language'. |
| [get_ContentLength](./get_contentlength/)() | Получает значение заголовка 'Content-Length'. |
| [get_ContentLocation](./get_contentlocation/)() | Получает значение заголовка 'Content-Location'. |
| [get_ContentMD5](./get_contentmd5/)() | Получает значение заголовка 'Content-MD5'. |
| [get_ContentRange](./get_contentrange/)() | Получает значение заголовка 'Content-Range'. |
| [get_ContentType](./get_contenttype/)() | Получает значение заголовка 'Content-Type'. |
| [get_Expires](./get_expires/)() | Получает значение заголовка 'Expires'. |
| [get_LastModified](./get_lastmodified/)() | Получает значение заголовка 'Last-Modified'. |
| [HttpContentHeaders](./httpcontentheaders/)(HeaderFunc\<Nullable\<int64_t\>\>) | Создаёт новый экземпляр. |
| [set_ContentDisposition](./set_contentdisposition/)(System::SharedPtr\<ContentDispositionHeaderValue\>) | Устанавливает значение заголовка 'Content-Disposition'. |
| [set_ContentLength](./set_contentlength/)(Nullable\<int64_t\>) | Устанавливает значение заголовка 'Content-Length'. |
| [set_ContentLocation](./set_contentlocation/)(System::SharedPtr\<Uri\>) | Устанавливает значение заголовка 'Content-Location'. |
| [set_ContentMD5](./set_contentmd5/)(System::ArrayPtr\<uint8_t\>) | Устанавливает значение заголовка 'Content-MD5'. |
| [set_ContentRange](./set_contentrange/)(System::SharedPtr\<ContentRangeHeaderValue\>) | Устанавливает значение заголовка 'Content-Range'. |
| [set_ContentType](./set_contenttype/)(System::SharedPtr\<MediaTypeHeaderValue\>) | Устанавливает значение заголовка 'Content-Type'. |
| [set_Expires](./set_expires/)(Nullable\<DateTimeOffset\>) | Устанавливает значение заголовка 'Expires'. |
| [set_LastModified](./set_lastmodified/)(Nullable\<DateTimeOffset\>) | Устанавливает значение заголовка 'Last-Modified'. |
## См. также

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
