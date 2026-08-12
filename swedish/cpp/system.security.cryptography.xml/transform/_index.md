---
title: "System::Security::Cryptography::Xml::Transform klass"
linktitle: "Transform"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::Xml::Transform klass. Tillhandahåller information om hur data transformeras av signatären. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert‑fel. Omge alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system.security.cryptography.xml/transform/
---
## Transform class


Tillhandahåller information om hur data transformeras av signatären. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert‑fel. Omge alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Transform : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Algorithm](./get_algorithm/)() |  |
| [get_Context](./get_context/)() |  |
| virtual [get_InputTypes](./get_inputtypes/)() |  |
| virtual [get_OutputTypes](./get_outputtypes/)() |  |
| [get_PropagatedNamespaces](./get_propagatednamespaces/)() |  |
| virtual [GetDigestedOutput](./getdigestedoutput/)(SharedPtr\<HashAlgorithm\>) |  |
| virtual [GetOutput](./getoutput/)() |  |
| virtual [GetOutput](./getoutput/)(const TypeInfo\&) |  |
| virtual [LoadInnerXml](./loadinnerxml/)(SharedPtr\<System::Xml::XmlNodeList\>) |  |
| virtual [LoadInput](./loadinput/)(SharedPtr\<Object\>) |  |
| [set_Algorithm](./set_algorithm/)(String) |  |
| [set_Context](./set_context/)(SharedPtr\<System::Xml::XmlElement\>) |  |
| [set_Resolver](./set_resolver/)(SharedPtr\<System::Xml::XmlResolver\>) |  |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Xml](../)
* Library [Aspose.PDF for C++](../../)
