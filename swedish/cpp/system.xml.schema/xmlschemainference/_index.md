---
title: "System::Xml::Schema::XmlSchemaInference-klass"
linktitle: "XmlSchemaInference"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaInference-klass. Härleder ett XML Schema Definition Language (XSD)-schema från ett XML-dokument. XmlSchemaInference-klassen kan inte ärvas i C++."
type: docs
weight: 3700
url: /sv/cpp/system.xml.schema/xmlschemainference/
---
## XmlSchemaInference class


Härleder ett XML [Schema](../) Definition Language (XSD)-schema från ett XML-dokument. Klassen [XmlSchemaInference](./) kan inte ärvas.

```cpp
class XmlSchemaInference : public System::Object
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [InferenceOption](./inferenceoption/) | Påverkar förekomst- och typinformation som härleds av klassen [XmlSchemaInference](./) för element och attribut i ett XML-dokument. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Occurrence](./get_occurrence/)() | Returnerar värdet [XmlSchemaInference::InferenceOption](./inferenceoption/) som påverkar schemats förekomstdeklarationer härledda från XML-dokumentet. |
| [get_TypeInference](./get_typeinference/)() | Returnerar värdet [XmlSchemaInference::InferenceOption](./inferenceoption/) som påverkar typer härledda från XML-dokumentet. |
| [InferSchema](./inferschema/)(const SharedPtr\<XmlReader\>\&) | Härleder ett XML [Schema](../) Definition Language (XSD)-schema från XML-dokumentet som finns i det angivna [XmlReader](../../system.xml/xmlreader/)-objektet. |
| [InferSchema](./inferschema/)(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) | Härleder ett XML [Schema](../) Definition Language (XSD)-schema från XML-dokumentet som finns i det angivna [XmlReader](../../system.xml/xmlreader/)-objektet, och förfinar det härledda schemat med ett befintligt schema i det angivna [XmlSchemaSet](../xmlschemaset/)-objektet med samma mål-namnutrymme. |
| [set_Occurrence](./set_occurrence/)(XmlSchemaInference::InferenceOption) | Ställer in värdet [XmlSchemaInference::InferenceOption](./inferenceoption/) som påverkar schemats förekomstdeklarationer härledda från XML-dokumentet. |
| [set_TypeInference](./set_typeinference/)(XmlSchemaInference::InferenceOption) | Ställer in värdet [XmlSchemaInference::InferenceOption](./inferenceoption/) som påverkar typer härledda från XML-dokumentet. |
| [XmlSchemaInference](./xmlschemainference/)() | Initierar en ny instans av klassen [XmlSchemaInference](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
