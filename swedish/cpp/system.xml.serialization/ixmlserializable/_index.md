---
title: "System::Xml::Serialization::IXmlSerializable klass"
linktitle: "IXmlSerializable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Serialization::IXmlSerializable klass. Tillhandahåller anpassad formatering för XML-serialisering och deserialisering. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml.serialization/ixmlserializable/
---
## IXmlSerializable class


Tillhandahåller anpassad formatering för XML-serialisering och deserialisering. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class IXmlSerializable : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [GetSchema](./getschema/)() | Ett XmlSchema-objekt som beskriver XML-representationen av objektet som returneras av metoden [WriteXml()](./writexml/) och accepteras av metoden [ReadXml()](./readxml/). |
| virtual [ReadXml](./readxml/)(System::SharedPtr\<System::Xml::XmlReader\>) | Deserialiserar objektet från dess XML-representation. |
| virtual [WriteXml](./writexml/)(System::SharedPtr\<System::Xml::XmlWriter\>) | Serialiserar det aktuella objektet till XML-representation. |
| virtual [~IXmlSerializable](./~ixmlserializable/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PDF for C++](../../)
