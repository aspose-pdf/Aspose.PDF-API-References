---
title: "System::Net::HttpWebRequest класс"
linktitle: "HttpWebRequest"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::HttpWebRequest класс. Представляет HTTP веб‑запрос. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2000
url: /ru/cpp/system.net/httpwebrequest/
---
## HttpWebRequest class


Представляет HTTP веб‑запрос. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Методы

| Метод | Описание |
| --- | --- |
| [Abort](./abort/)() override | Прерывает текущий запрос. |
| virtual [AddRange](./addrange/)(int32_t) | Добавляет заголовок '[Range](../../system/range/)' к текущему запросу. |
| virtual [AddRange](./addrange/)(System::String, int32_t, int32_t) | Добавляет заголовок '[Range](../../system/range/)' к текущему запросу. |
| [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) override | Инициирует асинхронную операцию получения потока для записи данных в ресурс. |
| [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) override | Инициирует асинхронный запрос к ресурсу. |
| [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) override | Ожидает завершения указанной асинхронной операции получения потока. |
| [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) override | Ожидает завершения указанного асинхронного запроса к ресурсу. |
| [get_Accept](./get_accept/)() | Получает значение HTTP‑заголовка 'Accept'. |
| virtual [get_AllowAutoRedirect](./get_allowautoredirect/)() | Получает значение, указывающее, должен ли запрос следовать перенаправлениям. |
| virtual [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Получает значение, указывающее, должны ли полученные от ресурса данные буферизоваться. |
| virtual [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Получает значение, указывающее, включена ли буферизация при отправке данных. |
| virtual [get_ClientCertificates](./get_clientcertificates/)() | Получает коллекцию сертификатов, связанных с текущим запросом. |
| [get_ConnectionGroupName](./get_connectiongroupname/)() override | Получает имя группы соединений. |
| [get_ContentLength](./get_contentlength/)() override | Получает количество байтов данных запроса для отправки. |
| [get_ContentType](./get_contenttype/)() override | Получает MIME‑тип запроса. |
| [get_ContinueTimeout](./get_continuetimeout/)() | Получает тайм‑аут ожидания получения кода состояния 100-Continue. |
| virtual [get_CookieContainer](./get_cookiecontainer/)() | Получает контейнер cookie, связанный с текущим веб‑запросом. |
| [get_Credentials](./get_credentials/)() override | Получает информацию об аутентификации, связанную с текущим запросом. |
| virtual [get_HaveResponse](./get_haveresponse/)() | Возвращает значение, указывающее, получен ли ответ. |
| [get_Headers](./get_headers/)() override | Получает коллекцию HTTP‑заголовков. |
| virtual [get_KeepAlive](./get_keepalive/)() | Получает значение, указывающее, должен ли текущий запрос содержать заголовок 'Keep-Alive'. |
| virtual [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Получает максимальное количество разрешённых перенаправлений. |
| [get_Method](./get_method/)() override | Получает HTTP‑метод. |
| [get_PreAuthenticate](./get_preauthenticate/)() override | Получает значение, указывающее, должен ли запрос быть предварительно аутентифицирован. |
| [get_Proxy](./get_proxy/)() override | Получает HTTP‑прокси. |
| virtual [get_Referer](./get_referer/)() | Получает значение заголовка 'Referer'. |
| [get_RequestUri](./get_requesturi/)() override | Возвращает URI запроса. |
| virtual [get_SendChunked](./get_sendchunked/)() | Получает значение, указывающее, должны ли данные отправляться сегментами. |
| [get_ServicePoint](./get_servicepoint/)() | Возвращает объект service point, представляющий сетевое соединение с ресурсом. |
| virtual [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Возвращает значение, указывающее, может ли текущий запрос использовать контейнер cookie. |
| [get_Timeout](./get_timeout/)() override | Получает количество времени в миллисекундах, после которого запрос будет завершён по тайм‑ауту. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Получает значение, указывающее, равен ли параметр 'Credential' параметру 'DefaultCredentials'. |
| virtual [get_UserAgent](./get_useragent/)() | Получает значение заголовка 'User-Agent'. |
| [GetRequestStream](./getrequeststream/)() override | Возвращает поток для записи данных в ресурс. |
| [GetResponse](./getresponse/)() override | Возвращает веб‑ответ, связанный с текущим веб‑запросом. |
| [HttpWebRequest](./httpwebrequest/)(System::SharedPtr\<Uri\>) | Создаёт новый экземпляр. |
| [set_Accept](./set_accept/)(String) | Устанавливает значение HTTP‑заголовка 'Accept'. |
| virtual [set_AllowAutoRedirect](./set_allowautoredirect/)(bool) | Устанавливает значение, указывающее, должен ли запрос следовать перенаправлениям. |
| virtual [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(bool) | Устанавливает значение, указывающее, должны ли полученные от ресурса данные быть буферизованы. |
| virtual [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(bool) | Устанавливает значение, указывающее, включено ли буферизование при отправке данных. |
| virtual [set_ClientCertificates](./set_clientcertificates/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>) | Устанавливает коллекцию сертификатов, связанных с текущим запросом. |
| [set_ConnectionGroupName](./set_connectiongroupname/)(System::String) override | Устанавливает имя группы соединений. |
| [set_ContentLength](./set_contentlength/)(int64_t) override | Устанавливает количество байтов данных запроса для отправки. |
| [set_ContentType](./set_contenttype/)(String) override | Устанавливает MIME‑тип запроса. |
| [set_ContinueTimeout](./set_continuetimeout/)(int32_t) | Устанавливает тайм‑аут ожидания получения кода состояния 100‑Continue. |
| virtual [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Устанавливает контейнер cookie, связанный с текущим веб‑запросом. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) override | Устанавливает информацию аутентификации, связанную с текущим запросом. |
| [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) override | Устанавливает коллекцию HTTP‑заголовков. |
| virtual [set_KeepAlive](./set_keepalive/)(bool) | Устанавливает значение, указывающее, должен ли текущий запрос содержать заголовок 'Keep-Alive'. |
| virtual [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Устанавливает максимальное количество разрешённых перенаправлений. |
| [set_Method](./set_method/)(String) override | Устанавливает HTTP‑метод. |
| [set_PreAuthenticate](./set_preauthenticate/)(bool) override | Устанавливает значение, указывающее, должен ли запрос быть предварительно аутентифицирован. |
| [set_ProtocolVersion](./set_protocolversion/)(System::Version) | Информация RTTI. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) override | Устанавливает HTTP‑прокси. |
| virtual [set_Referer](./set_referer/)(System::String) | Устанавливает значение заголовка 'Referer'. |
| virtual [set_SendChunked](./set_sendchunked/)(bool) | Устанавливает значение, указывающее, должны ли данные отправляться сегментами. |
| [set_Timeout](./set_timeout/)(int) override | Устанавливает количество времени в миллисекундах, после которого запрос будет прерван по тайм‑ауту. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) override | Устанавливает значение, указывающее, равен ли параметр 'Credential' параметру 'DefaultCredentials'. |
| virtual [set_UserAgent](./set_useragent/)(System::String) | Устанавливает значение заголовка 'User-Agent'. |
## См. также

* Class [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
