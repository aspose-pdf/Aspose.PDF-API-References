---
title: "System::Web::Services::Protocols::SoapHeader class"
linktitle: "SoapHeader"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Web::Services::Protocols::SoapHeader class. Представляет содержимое SOAP‑заголовка. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.web.services.protocols/soapheader/
---
## SoapHeader class


Представляет содержимое SOAP‑заголовка. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SoapHeader : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Actor](./get_actor/)() | Получает URI получателя SOAP‑заголовка, когда используется версия SOAP 1.1. |
| [get_DidUnderstand](./get_didunderstand/)() | Получает значение, указывающее, правильно ли обработан SOAP‑заголовок. |
| [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | Получает значение атрибута 'mustUnderstand', когда используется версия SOAP 1.1. |
| [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | Получает значение атрибута 'mustUnderstand', когда используется версия SOAP 1.2. |
| [get_EncodedRelay](./get_encodedrelay/)() | Получает строковое представление значения атрибута 'relay'. |
| [get_MustUnderstand](./get_mustunderstand/)() | Получает значение, указывающее, должен ли быть понят SOAP‑заголовок. |
| [get_Relay](./get_relay/)() | Получает значение атрибута 'relay'. |
| [get_Role](./get_role/)() | Получает URI получателя SOAP‑заголовка, когда используется версия SOAP 1.2. |
| [set_Actor](./set_actor/)(String) | Устанавливает URI получателя SOAP‑заголовка, когда используется версия SOAP 1.1. |
| [set_DidUnderstand](./set_didunderstand/)(bool) | Устанавливает значение, указывающее, правильно ли обработан SOAP‑заголовок. |
| [set_EncodedMustUnderstand](./set_encodedmustunderstand/)(String) | Устанавливает значение атрибута 'mustUnderstand' при использовании версии SOAP 1.1. |
| [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)(String) | Устанавливает значение атрибута 'mustUnderstand' при использовании версии SOAP 1.2. |
| [set_EncodedRelay](./set_encodedrelay/)(String) | Устанавливает строковое представление значения атрибута 'relay'. |
| [set_MustUnderstand](./set_mustunderstand/)(bool) | Устанавливает значение, указывающее, должен ли заголовок SOAP быть понятен. |
| [set_Relay](./set_relay/)(bool) | Устанавливает значение атрибута 'relay'. |
| [set_Role](./set_role/)(String) | Устанавливает URI получателя заголовка SOAP при использовании версии SOAP 1.2. |
| [SoapHeader](./soapheader/)(System::SharedPtr\<Xml::XmlElement\>) | Создаёт новый экземпляр. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
