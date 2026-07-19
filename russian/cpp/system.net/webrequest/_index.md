---
title: "System::Net::WebRequest class"
linktitle: "WebRequest"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::WebRequest class. Представляет веб‑запрос. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3800
url: /ru/cpp/system.net/webrequest/
---
## WebRequest class


Представляет веб‑запрос. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class WebRequest : public virtual System::Object
```

## Nested classes

* Class [HttpRequestCreator](./httprequestcreator/)
* Class [WebRequestPrefixElement](./webrequestprefixelement/)
## Методы

| Метод | Описание |
| --- | --- |
| virtual [Abort](./abort/)() | Прерывает текущий запрос. |
| virtual [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию получения потока для записи данных в ресурс. |
| virtual [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронный запрос к ресурсу. |
| static [Create](./create/)(String) | Создаёт новый экземпляр класса [WebRequest](./), используя указанный URI. |
| static [Create](./create/)(System::SharedPtr\<Uri\>) | Создаёт новый экземпляр класса [WebRequest](./), используя указанный URI. |
| static [CreateDefault](./createdefault/)(System::SharedPtr\<Uri\>) | Создает потомка [WebRequest](./) для указанной схемы URI. |
| static [CreateHttp](./createhttp/)(String) | Создаёт новый экземпляр класса [WebRequest](./), используя указанный URI. |
| static [CreateHttp](./createhttp/)(System::SharedPtr\<Uri\>) | Создаёт новый экземпляр класса [WebRequest](./), используя указанный URI. |
| virtual [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции получения потока. |
| virtual [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанного асинхронного запроса к ресурсу. |
| virtual [get_CachePolicy](./get_cachepolicy/)() | Получает политику кэширования. |
| virtual [get_ConnectionGroupName](./get_connectiongroupname/)() | Получает имя группы соединений. |
| virtual [get_ContentLength](./get_contentlength/)() | Получает количество байтов данных запроса для отправки. |
| virtual [get_ContentType](./get_contenttype/)() | Получает MIME‑тип запроса. |
| virtual [get_Credentials](./get_credentials/)() | Получает информацию об аутентификации, связанную с текущим запросом. |
| static [get_DefaultWebProxy](./get_defaultwebproxy/)() | Получает глобальный HTTP‑прокси. |
| virtual [get_Headers](./get_headers/)() | Получает коллекцию HTTP‑заголовков. |
| virtual [get_Method](./get_method/)() | Получает HTTP‑метод. |
| virtual [get_PreAuthenticate](./get_preauthenticate/)() | Получает значение, указывающее, должен ли запрос быть предварительно аутентифицирован. |
| static [get_PrefixList](./get_prefixlist/)() | Получает список префиксов. |
| virtual [get_Proxy](./get_proxy/)() | Получает HTTP‑прокси. |
| virtual [get_RequestUri](./get_requesturi/)() | Возвращает URI запроса. |
| virtual [get_Timeout](./get_timeout/)() | Получает количество времени в миллисекундах, после которого запрос будет завершён по тайм‑ауту. |
| virtual [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Получает значение, указывающее, равен ли параметр 'Credential' параметру 'DefaultCredentials'. |
| virtual [GetRequestStream](./getrequeststream/)() | Возвращает поток для записи данных в ресурс. |
| virtual [GetResponse](./getresponse/)() | Возвращает веб‑ответ, связанный с текущим веб‑запросом. |
| static [RegisterPrefix](./registerprefix/)(String, System::SharedPtr\<IWebRequestCreate\>) | Регистрирует потомка [WebRequest](./) для указанного URI. |
| virtual [set_CachePolicy](./set_cachepolicy/)(System::SharedPtr\<System::Net::Cache::RequestCachePolicy\>) | Устанавливает политику кэширования. |
| virtual [set_ConnectionGroupName](./set_connectiongroupname/)(System::String) | Устанавливает имя группы соединений. |
| virtual [set_ContentLength](./set_contentlength/)(int64_t) | Устанавливает количество байтов данных запроса для отправки. |
| virtual [set_ContentType](./set_contenttype/)(String) | Устанавливает MIME‑тип запроса. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Устанавливает информацию аутентификации, связанную с текущим запросом. |
| static [set_DefaultWebProxy](./set_defaultwebproxy/)(System::SharedPtr\<IWebProxy\>) | Устанавливает глобальный HTTP‑прокси. |
| virtual [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) | Устанавливает коллекцию HTTP‑заголовков. |
| virtual [set_Method](./set_method/)(String) | Устанавливает HTTP‑метод. |
| virtual [set_PreAuthenticate](./set_preauthenticate/)(bool) | Устанавливает значение, указывающее, должен ли запрос быть предварительно аутентифицирован. |
| static [set_PrefixList](./set_prefixlist/)(System::SharedPtr\<Collections::Generic::List\<System::SharedPtr\<WebRequest::WebRequestPrefixElement\>\>\>) | Устанавливает список префиксов. |
| virtual [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) | Устанавливает HTTP‑прокси. |
| virtual [set_Timeout](./set_timeout/)(int32_t) | Устанавливает количество времени в миллисекундах, после которого запрос будет прерван по тайм‑ауту. |
| virtual [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Устанавливает значение, указывающее, равен ли параметр 'Credential' параметру 'DefaultCredentials'. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
