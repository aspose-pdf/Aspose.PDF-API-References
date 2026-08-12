---
title: "Класс System::Xml::Schema::XmlSchemaAny"
linktitle: "XmlSchemaAny"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaAny класс. Представляет любой элемент World Wide Web Consortium (W3C) в C++."
type: docs
weight: 800
url: /ru/cpp/system.xml.schema/xmlschemaany/
---
## XmlSchemaAny class


Представляет World Wide [Web](../../system.web/) Consortium (W3C) элемент **any**.

```cpp
class XmlSchemaAny : public System::Xml::Schema::XmlSchemaParticle
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Namespace](./get_namespace/)() | Возвращает пространства имён, содержащие элементы, которые могут быть использованы. |
| [get_ProcessContents](./get_processcontents/)() | Возвращает информацию о том, как приложение или XML‑процессор должен обрабатывать проверку XML‑документов для элементов, указанных элементом **any**. |
| [set_Namespace](./set_namespace/)(const String\&) | Устанавливает пространства имён, содержащие элементы, которые могут быть использованы. |
| [set_ProcessContents](./set_processcontents/)(XmlSchemaContentProcessing) | Устанавливает информацию о том, как приложение или XML‑процессор должен обрабатывать проверку XML‑документов для элементов, указанных элементом **any**. |
| [XmlSchemaAny](./xmlschemaany/)() | Инициализирует новый экземпляр класса [XmlSchemaAny](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
