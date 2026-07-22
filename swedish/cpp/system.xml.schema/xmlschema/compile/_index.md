---
title: "System::Xml::Schema::XmlSchema::Compile‑metod"
linktitle: "Kompilera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchema::Compile‑metod. Kompilerar XML SchemaObject Model (SOM) till schemainformation för validering. Används för att kontrollera den syntaktiska och semantiska strukturen i det programatiskt byggda SOM‑et. Semantisk valideringskontroll utförs under kompilering i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) method


Kompilerar XML [Schema](../../)[Object](../../../system/object/) Model (SOM) till schemainformation för validering. Används för att kontrollera den syntaktiska och semantiska strukturen i det programatiskt byggda SOM‑et. Semantisk valideringskontroll utförs under kompilering.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| validationEventHandler | ValidationEventHandler | Den validerings‑händelsehanteraren som tar emot information om XML [Schema](../../) valideringsfel. |

## Se även

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) method


Kompilerar XML [Schema](../../)[Object](../../../system/object/) Model (SOM) till schemainformation för validering. Används för att kontrollera den syntaktiska och semantiska strukturen i det programatiskt byggda SOM‑et. Semantisk valideringskontroll utförs under kompilering.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| validationEventHandler | ValidationEventHandler | Den validerings‑händelsehanteraren som tar emot information om XML [Schema](../../) valideringsfel. |
| resolver | const SharedPtr\<XmlResolver\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa namnrymder som refereras i **include**‑ och **import**‑element. |

## Se även

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
