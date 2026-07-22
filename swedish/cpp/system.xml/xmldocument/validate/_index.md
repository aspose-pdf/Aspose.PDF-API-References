---
title: "System::Xml::XmlDocument::Validate metod"
linktitle: "Validera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocument::Validate metod. Validerar XmlDocument mot XML Schema Definition Language (XSD)-scheman som finns i XmlDocument::get_Schemas‑listan i C++."
type: docs
weight: 4300
url: /sv/cpp/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) method


Validerar [XmlDocument](../) mot XML [Schema](../../../system.xml.schema/) Definition Language (XSD)-scheman som finns i listan [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| validationEventHandler | Schema::ValidationEventHandler | Objektet [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) som tar emot information om varningar och fel vid schemavalidering. |

## Se även

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) method


Validerar det angivna [XmlNode](../../xmlnode/)‑objektet mot XML [Schema](../../../system.xml.schema/) Definition Language (XSD)-scheman i listan [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| validationEventHandler | Schema::ValidationEventHandler | Objektet [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) som tar emot information om varningar och fel vid schemavalidering. |
| nodeToValidate | const SharedPtr\<XmlNode\>\& | Det [XmlNode](../../xmlnode/)‑objekt som skapats från ett [XmlDocument](../) för validering. |

## Se även

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
