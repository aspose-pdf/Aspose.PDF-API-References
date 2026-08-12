---
title: "System::Xml::Schema::XmlSchemaValidator::ValidateEndElement metod"
linktitle: "ValidateEndElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaValidator::ValidateEndElement metod. Verifierar om elementets textinnehåll är giltigt enligt dess datatyp för element med enkelt innehåll, och verifierar om innehållet i det aktuella elementet är komplett för element med komplext innehåll i C++."
type: docs
weight: 1800
url: /sv/cpp/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) method


Verifierar om elementets textinnehåll är giltigt enligt dess datatyp för element med enkelt innehåll, och verifierar om innehållet i det aktuella elementet är komplett för element med komplext innehåll.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Ett [XmlSchemaInfo](../../xmlschemainfo/)-objekt vars egenskaper sätts vid lyckad validering av elementet. Denna parameter kan vara **nullptr**. |

### ReturnValue

Det analyserade, typade textvärdet för elementet om elementet har enkelt innehåll.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method


Verifierar om det angivna elementets textinnehåll är giltigt enligt dess datatyp.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Ett [XmlSchemaInfo](../../xmlschemainfo/)-objekt vars egenskaper sätts vid lyckad validering av elementets textinnehåll. Denna parameter kan vara **nullptr**. |
| typedValue | const SharedPtr\<Object\>\& | Det typade textinnehållet i elementet. |

### ReturnValue

Det analyserade, typade enkla innehållet i elementet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
