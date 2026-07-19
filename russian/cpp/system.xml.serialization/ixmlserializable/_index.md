---
title: "Класс System::Xml::Serialization::IXmlSerializable"
linktitle: "IXmlSerializable"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Serialization::IXmlSerializable. Обеспечивает пользовательское форматирование для XML‑сериализации и десериализации. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml.serialization/ixmlserializable/
---
## IXmlSerializable class


Обеспечивает пользовательское форматирование для XML‑сериализации и десериализации. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class IXmlSerializable : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [GetSchema](./getschema/)() | Объект XmlSchema, описывающий XML‑представление объекта, которое возвращается методом [WriteXml()](./writexml/) и принимается методом [ReadXml()](./readxml/). |
| virtual [ReadXml](./readxml/)(System::SharedPtr\<System::Xml::XmlReader\>) | Десериализует объект из его XML‑представления. |
| virtual [WriteXml](./writexml/)(System::SharedPtr\<System::Xml::XmlWriter\>) | Сериализует текущий объект в XML‑представление. |
| virtual [~IXmlSerializable](./~ixmlserializable/)() | Деструктор. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PDF for C++](../../)
