---
title: "System::Web::Services::Protocols::SoapClientMessage class"
linktitle: "SoapClientMessage"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Web::Services::Protocols::SoapClientMessage class. Представляет данные в отправленном SOAP‑запросе или полученном SOAP‑ответе. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.web.services.protocols/soapclientmessage/
---
## SoapClientMessage class


Представляет данные в отправленном SOAP‑запросе или полученном SOAP‑ответе. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SoapClientMessage : public System::Web::Services::Protocols::SoapMessage
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Action](./get_action/)() override | Возвращает значение атрибута 'SOAPAction'. |
| [get_Client](./get_client/)() | Возвращает экземпляр класса прокси клиента. |
| virtual [get_OneWay](./get_oneway/)() | Возвращает значение, указывающее, не ждёт ли клиент завершения обработки метода сервером. |
| [get_SoapVersion](./get_soapversion/)() override | Возвращает используемую версию SOAP. |
| [get_Url](./get_url/)() override | Возвращает URL XML [Web](../../system.web/) сервиса. |
| [SoapClientMessage](./soapclientmessage/)(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Создаёт новый экземпляр. |
## См. также

* Class [SoapMessage](../soapmessage/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
