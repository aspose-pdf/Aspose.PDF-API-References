---
title: "System::Web::Services::Protocols::SoapMessage класс"
linktitle: "SoapMessage"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Web::Services::Protocols::SoapMessage класс. Представляет SOAP‑сообщение. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1000
url: /ru/cpp/system.web.services.protocols/soapmessage/
---
## SoapMessage class


Представляет SOAP‑сообщение. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SoapMessage : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [CollectHeaders](./collectheaders/)(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) | Устанавливает внутреннюю коллекцию SOAP‑заголовков. |
| [FindHeader](./findheader/)(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) | Найдите сопоставление заголовка по указанному типу заголовка. |
| virtual [get_Action](./get_action/)() | Возвращает значение атрибута 'SOAPAction'. |
| [get_ContentEncoding](./get_contentencoding/)() | Получает значение заголовка 'Content-Encoding'. |
| [get_ContentType](./get_contenttype/)() | Получает значение заголовка 'Content-Type'. |
| [get_Exception](./get_exception/)() | Получает исключение, которое выбрасывается методом XML [Web](../../system.web/) сервиса. |
| [get_Headers](./get_headers/)() | Возвращает коллекцию SOAP‑заголовков. |
| [get_InParameters](./get_inparameters/)() | Получает параметры, передаваемые в метод XML [Web](../../system.web/) сервиса. |
| [get_IsSoap12](./get_issoap12/)() | Возвращает значение, указывающее, используется ли версия SOAP 1.2. |
| [get_OutParameters](./get_outparameters/)() | Получает выходные параметры, передаваемые в метод XML [Web](../../system.web/) сервиса. |
| virtual [get_SoapVersion](./get_soapversion/)() | Возвращает используемую версию SOAP. |
| [get_Stage](./get_stage/)() | Получает стадию обработки SOAP‑сообщения. |
| [get_Stream](./get_stream/)() | Получает поток, содержащий данные SOAP‑сообщения. |
| virtual [get_Url](./get_url/)() | Возвращает URL XML [Web](../../system.web/) сервиса. |
| [GetInParameterValue](./getinparametervalue/)(int32_t) | Получает значение входного параметра по указанному индексу. |
| [GetOutParameterValue](./getoutparametervalue/)(int32_t) | Получает значение выходного параметра по указанному индексу. |
| [GetReturnValue](./getreturnvalue/)() | Получает возвращаемое значение метода XML [Web](../../system.web/) сервиса. |
| [set_ContentEncoding](./set_contentencoding/)(String) | Устанавливает значение заголовка 'Content-Encoding'. |
| [set_ContentType](./set_contenttype/)(String) | Устанавливает значение заголовка 'Content-Type'. |
| [set_InParameters](./set_inparameters/)(System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Устанавливает параметры, передаваемые в метод XML [Web](../../system.web/) сервиса. |
| [set_InternalStream](./set_internalstream/)(System::SharedPtr\<System::IO::Stream\>) | Устанавливает поток, содержащий данные SOAP‑сообщения. |
| [set_OutParameters](./set_outparameters/)(System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Устанавливает выходные параметры, передаваемые в метод XML [Web](../../system.web/) сервиса. |
| [SetException](./setexception/)(SoapException) | Устанавливает исключение, выбрасываемое методом XML [Web](../../system.web/) сервиса. |
| [SetHeaders](./setheaders/)(System::SharedPtr\<SoapHeaderCollection\>) | Устанавливает коллекцию заголовков SOAP. |
| [SetStage](./setstage/)(SoapMessageStage) | Устанавливает этап обработки SOAP‑сообщения. |
| [SetStream](./setstream/)(System::SharedPtr\<System::IO::Stream\>) | Устанавливает поток, содержащий данные SOAP‑сообщения. |
| [SoapMessage](./soapmessage/)() | Создаёт новый экземпляр. |
| [UpdateHeaderValues](./updateheadervalues/)(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>) | Обновляет внутреннюю коллекцию заголовков SOAP. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
