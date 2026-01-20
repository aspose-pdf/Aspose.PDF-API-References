---
title: System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator constructor
linktitle: XmlSchemaValidator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator constructor. Initializes a new instance of the XmlSchemaValidator class in C++.'
type: docs
weight: 100
url: /cpp/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator constructor


Initializes a new instance of the [XmlSchemaValidator](../) class.

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


| Parameter | Type | Description |
| --- | --- | --- |
| nameTable | const SharedPtr\<XmlNameTable\>\& | An [XmlNameTable](../../../system.xml/xmlnametable/) object containing element and attribute names as atomized strings. |
| schemas | const SharedPtr\<XmlSchemaSet\>\& | An [XmlSchemaSet](../../xmlschemaset/) object containing the XML [Schema](../../) Definition Language (XSD) schemas used for validation. |
| namespaceResolver | const SharedPtr\<IXmlNamespaceResolver\>\& | An [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used for resolving namespaces encountered during validation. |
| validationFlags | XmlSchemaValidationFlags | An [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) value specifying schema validation options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
