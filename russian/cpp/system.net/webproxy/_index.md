---
title: "Класс System::Net::WebProxy"
linktitle: "WebProxy"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::WebProxy. Представляет http‑прокси‑сервер. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3700
url: /ru/cpp/system.net/webproxy/
---
## WebProxy class


Представляет http веб‑прокси‑сервер. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class WebProxy : public System::Net::IWebProxy
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Address](./get_address/)() | Получает адрес текущего прокси‑сервера. |
| [get_BypassList](./get_bypasslist/)() | Получает список адресов, которые не используют прокси‑сервер. |
| [get_BypassProxyOnLocal](./get_bypassproxyonlocal/)() | Получает значение, указывающее, должен ли прокси‑сервер использоваться для локальных адресов. |
| virtual [get_Credentials](./get_credentials/)() | Получает учётные данные, которые отправляются прокси‑серверу для аутентификации. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Получает значение, указывающее, должны ли отправляться учётные данные по умолчанию с запросами. |
| static [GetDefaultProxy](./getdefaultproxy/)() | Возвращает прокси, использующий нединамические настройки Internet Explorer. |
| virtual [GetProxy](./getproxy/)(System::SharedPtr\<Uri\>) | Возвращает проксированный URI для веб‑запроса. |
| virtual [IsBypassed](./isbypassed/)(System::SharedPtr\<Uri\>) | Проверяет, не используется ли прокси‑сервер для указанного URI. |
| [set_Address](./set_address/)(System::SharedPtr\<Uri\>) | Устанавливает адрес текущего прокси‑сервера. |
| [set_BypassList](./set_bypasslist/)(System::ArrayPtr\<String\>) | Устанавливает список адресов, которые не используют прокси‑сервер. |
| [set_BypassProxyOnLocal](./set_bypassproxyonlocal/)(bool) | Устанавливает значение, указывающее, должен ли прокси‑сервер использоваться для локальных адресов. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Устанавливает учётные данные, которые отправляются прокси‑серверу для аутентификации. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Устанавливает значение, указывающее, должны ли отправляться учётные данные по умолчанию с запросами. |
| [WebProxy](./webproxy/)() | Создаёт новый экземпляр. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>) | Создаёт новый экземпляр. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool) | Создаёт новый экземпляр. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) | Создаёт новый экземпляр. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) | Создаёт новый экземпляр. |
| [WebProxy](./webproxy/)(String, int32_t) | Создаёт новый экземпляр. |
| [WebProxy](./webproxy/)(String) | Создаёт новый экземпляр. |
| [WebProxy](./webproxy/)(String, bool) | Создаёт новый экземпляр. |
| [WebProxy](./webproxy/)(String, bool, System::ArrayPtr\<String\>) | Создаёт новый экземпляр. |
| [WebProxy](./webproxy/)(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) | Создаёт новый экземпляр. |
## См. также

* Class [IWebProxy](../iwebproxy/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
