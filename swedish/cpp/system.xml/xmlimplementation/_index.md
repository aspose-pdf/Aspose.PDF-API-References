---
title: "System::Xml::XmlImplementation-klass"
linktitle: "XmlImplementation"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlImplementation-klass. Definierar kontexten för en uppsättning XmlDocument-objekt i C++."
type: docs
weight: 2000
url: /sv/cpp/system.xml/xmlimplementation/
---
## XmlImplementation class


Definierar kontexten för en uppsättning [XmlDocument](../xmldocument/)-objekt.

```cpp
class XmlImplementation : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [CreateDocument](./createdocument/)() | Skapar ett nytt [XmlDocument](../xmldocument/). |
| [HasFeature](./hasfeature/)(const String\&, const String\&) | Testar om Document [Object](../../system/object/) Model (DOM)-implementeringen implementerar en specifik funktion. |
| [XmlImplementation](./xmlimplementation/)() | Initierar en ny instans av klassen [XmlImplementation](./). |
| [XmlImplementation](./xmlimplementation/)(const SharedPtr\<XmlNameTable\>\&) | Initierar en ny instans av klassen [XmlImplementation](./) med den specificerade [XmlNameTable](../xmlnametable/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
