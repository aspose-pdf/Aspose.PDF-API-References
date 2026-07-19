---
title: "Класс System::Xml::Serialization::XmlSerializer"
linktitle: "XmlSerializer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Serialization::XmlSerializer. Выполняет сериализацию и десериализацию объектов в XML-документы и из них. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.xml.serialization/xmlserializer/
---
## XmlSerializer class


Выполняет сериализацию и десериализацию объектов в XML-документы и из них. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class XmlSerializer : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [CanDeserialize](./candeserialize/)(System::SharedPtr\<XmlReader\>) | Проверяет, находится ли конкретный читатель в состоянии, позволяющем десериализацию. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::Stream\>) | Десериализует XML-документ в объект. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::TextReader\>) | Десериализует XML-документ в объект. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>) | Десериализует XML-документ в объект. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>, String) | Десериализует XML-документ в объект. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) | Сериализует документ в XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) | Сериализует документ в XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) | Сериализует документ в XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Сериализует документ в XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Сериализует документ в XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Сериализует документ в XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) | Сериализует документ в XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) | Сериализует документ в XML. |
## Поля

| Поле | Описание |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | Кодирует имя пространства имён. |
| static [WsdlNamespace](./wsdlnamespace/) | RTTI. |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | Имя пространства имён типов WSDL. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PDF for C++](../../)
