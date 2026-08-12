---
title: "System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator konstruktor"
linktitle: "XmlSchemaValidator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator konstruktor. Initierar en ny instans av klassen XmlSchemaValidator i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator constructor


Initierar en ny instans av klassen [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nameTable | const SharedPtr\<XmlNameTable\>\& | Ett [XmlNameTable](../../../system.xml/xmlnametable/) objekt som innehåller element- och attributnamn som atomiserade strängar. |
| schemas | const SharedPtr\<XmlSchemaSet\>\& | Ett [XmlSchemaSet](../../xmlschemaset/) objekt som innehåller XML [Schema](../../) Definition Language (XSD)-scheman som används för validering. |
| namespaceResolver | const SharedPtr\<IXmlNamespaceResolver\>\& | Ett [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objekt som används för att lösa namnrymder som påträffas under validering. |
| validationFlags | XmlSchemaValidationFlags | Ett [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) värde som specificerar alternativ för schemavalidering. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
