---
title: "System::Xml::Schema::XmlSchemaDatatype::ChangeType metod"
linktitle: "ChangeType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaDatatype::ChangeType metod. Konverterar det angivna värdet, vars typ är en av de giltiga representationerna av XML‑schematypen som representeras av XmlSchemaDatatype, till den körningstidstyp som anges i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) method


Konverterar det angivna värdet, vars typ är en av de giltiga representationerna av XML‑schematypen som representeras av [XmlSchemaDatatype](../), till den specificerade körningstidstypen.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | SharedPtr\<Object\> | Indata‑värdet som ska konverteras till den specificerade typen. |
| targetType | const TypeInfo\& | Måltypen att konvertera ingångsvärdet till. |

### ReturnValue

Det konverterade ingångsvärdet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Konverterar det angivna värdet, vars typ är en av de giltiga representationerna av XML-schematypen som representeras av [XmlSchemaDatatype](../), till den körningstyp som anges med hjälp av [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) om [XmlSchemaDatatype](../) representerar **xs:QName**-typen eller en typ som är härledd från den.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | SharedPtr\<Object\> | Indata‑värdet som ska konverteras till den specificerade typen. |
| targetType | const TypeInfo\& | Måltypen att konvertera ingångsvärdet till. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | En [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) som används för att lösa namnrymdsprefix. Detta är endast användbart om [XmlSchemaDatatype](../) representerar **xs:QName**-typen eller en typ som är härledd från den. |

### ReturnValue

Det konverterade ingångsvärdet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
