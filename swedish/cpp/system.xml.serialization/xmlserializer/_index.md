---
title: "System::Xml::Serialization::XmlSerializer klass"
linktitle: "XmlSerializer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Serialization::XmlSerializer klass. Utför serialisering och deserialisering av objekt till och från XML‑dokument. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.xml.serialization/xmlserializer/
---
## XmlSerializer class


Utför serialisering och deserialisering av objekt till och från XML‑dokument. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class XmlSerializer : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [CanDeserialize](./candeserialize/)(System::SharedPtr\<XmlReader\>) | Kontrollerar om en specifik läsare är i ett deserialiserbart tillstånd. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::Stream\>) | Deserialiserar XML‑dokument till ett objekt. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::TextReader\>) | Deserialiserar XML‑dokument till ett objekt. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>) | Deserialiserar XML‑dokument till ett objekt. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>, String) | Deserialiserar XML‑dokument till ett objekt. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) | Serialiserar dokument till XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) | Serialiserar dokument till XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) | Serialiserar dokument till XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serialiserar dokument till XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serialiserar dokument till XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serialiserar dokument till XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) | Serialiserar dokument till XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) | Serialiserar dokument till XML. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | Kodning av namnrymdens namn. |
| static [WsdlNamespace](./wsdlnamespace/) | RTTI. |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | WSDL-typer namnrymdens namn. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PDF for C++](../../)
