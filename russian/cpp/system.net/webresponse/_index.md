---
title: "Класс System::Net::WebResponse"
linktitle: "WebResponse"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::WebResponse. Представляет веб‑ответ. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 4000
url: /ru/cpp/system.net/webresponse/
---
## WebResponse class


Представляет веб‑ответ. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class WebResponse : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Close](./close/)() | Закрывает поток ответа. |
| [Dispose](./dispose/)() override | Ничего не делает. |
| virtual [get_ContentLength](./get_contentlength/)() | Информация RTTI. |
| virtual [get_ContentType](./get_contenttype/)() | Возвращает MIME‑тип ресурса. |
| virtual [get_Headers](./get_headers/)() | Возвращает коллекцию заголовков, связанных с текущим ответом. |
| virtual [get_ResponseUri](./get_responseuri/)() | Возвращает URI ресурса. |
| virtual [get_SupportsHeaders](./get_supportsheaders/)() | Возвращает значение, указывающее, поддерживает ли текущий ответ заголовки. |
| virtual [GetResponseStream](./getresponsestream/)() | Возвращает поток ответа. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
