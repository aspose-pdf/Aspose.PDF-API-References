---
title: "Класс System::Net::HttpWebResponse"
linktitle: "HttpWebResponse"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::HttpWebResponse класс. Представляет HTTP-ответ веб‑запроса. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() функции. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2100
url: /ru/cpp/system.net/httpwebresponse/
---
## HttpWebResponse class


Представляет HTTP-ответ веб‑запроса. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) функции. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpWebResponse : public System::Net::WebResponse
```

## Методы

| Метод | Описание |
| --- | --- |
| [Close](./close/)() override | Закрывает поток ответа. |
| [get_CharacterSet](./get_characterset/)() | Не реализовано. |
| [get_ContentLength](./get_contentlength/)() override | Информация RTTI. |
| [get_ContentType](./get_contenttype/)() override | Возвращает MIME‑тип ресурса. |
| virtual [get_Cookies](./get_cookies/)() | Возвращает cookies, связанные с веб‑ответом. |
| [get_Headers](./get_headers/)() override | Возвращает коллекцию заголовков, связанных с текущим ответом. |
| virtual [get_Method](./get_method/)() | Возвращает HTTP‑метод. |
| [get_ResponseUri](./get_responseuri/)() override | Возвращает URI ресурса. |
| virtual [get_StatusCode](./get_statuscode/)() | Возвращает HTTP‑код состояния, связанный с веб‑ответом. |
| virtual [get_StatusDescription](./get_statusdescription/)() | Возвращает строковое представление кода состояния. |
| [get_SupportsHeaders](./get_supportsheaders/)() override | Возвращает значение, указывающее, поддерживает ли текущий ответ заголовки. |
| [GetResponseHeader](./getresponseheader/)(String) | Возвращает соответствующее значение для указанного имени заголовка. |
| [GetResponseStream](./getresponsestream/)() override | Возвращает поток ответа. |
| [HttpWebResponse](./httpwebresponse/)(System::SharedPtr\<Http::HttpResponseMessage\>, System::SharedPtr\<Uri\>, System::SharedPtr\<CookieContainer\>) | Создаёт новый экземпляр. |
## См. также

* Class [WebResponse](../webresponse/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
