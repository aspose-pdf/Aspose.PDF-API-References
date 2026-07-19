---
title: "System::Net::FileWebRequest класс"
linktitle: "FileWebRequest"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::FileWebRequest класс. Предоставляет реализацию абстрактного класса WebRequest для работы с файловой системой. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1000
url: /ru/cpp/system.net/filewebrequest/
---
## FileWebRequest class


Предоставляет реализацию абстрактного класса [WebRequest](../webrequest/) для работы с файловой системой. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class FileWebRequest : public System::Net::WebRequest
```

## Методы

| Метод | Описание |
| --- | --- |
| [Abort](./abort/)() override | Прерывает текущий запрос. |
| [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) override | Инициирует асинхронную операцию получения потока для записи данных в ресурс. |
| [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) override | Инициирует асинхронный запрос к ресурсу. |
| [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) override | Ожидает завершения указанной асинхронной операции получения потока. |
| [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) override | Ожидает завершения указанного асинхронного запроса к ресурсу. |
| [FileWebRequest](./filewebrequest/)(System::SharedPtr\<Uri\>) | Создаёт новый экземпляр. |
| [get_ContentType](./get_contenttype/)() override | Получает MIME‑тип запроса. |
| [get_Headers](./get_headers/)() override | Получает коллекцию HTTP‑заголовков. |
| [get_Method](./get_method/)() override | Получает HTTP‑метод. |
| [get_RequestUri](./get_requesturi/)() override | Возвращает URI запроса. |
| [GetResponse](./getresponse/)() override | Возвращает веб‑ответ, связанный с текущим веб‑запросом. |
| [set_ContentType](./set_contenttype/)(String) override | Устанавливает MIME‑тип запроса. |
| [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) override | Устанавливает коллекцию HTTP‑заголовков. |
| [set_Method](./set_method/)(String) override | Устанавливает HTTP‑метод. |
| [set_Timeout](./set_timeout/)(int) override | Информация RTTI. |
## См. также

* Class [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
