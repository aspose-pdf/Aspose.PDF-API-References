---
title: System::Xml::Schema::XmlSchemaValidator::ValidateAttribute method
linktitle: ValidateAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaValidator::ValidateAttribute method. Validates the attribute name, namespace URI, and value in the current element context in C++.'
type: docs
weight: 1600
url: /cpp/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Validates the attribute name, namespace URI, and value in the current element context.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | const String\& | The local name of the attribute to validate. |
| namespaceUri | const String\& | The namespace URI of the attribute to validate. |
| attributeValue | const String\& | The value of the attribute to validate. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful validation of the attribute. This parameter can be **nullptr**. |

### ReturnValue

The validated attribute's value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) method


Validates the attribute name, namespace URI, and value in the current element context.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | const String\& | The local name of the attribute to validate. |
| namespaceUri | const String\& | The namespace URI of the attribute to validate. |
| attributeValue | XmlValueGetter | An [XmlValueGetter](../../xmlvaluegetter/) callback used to pass the attribute's value as a type compatible with the XML [Schema](../../) Definition Language (XSD) type of the attribute. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful validation of the attribute. This parameter and can be **nullptr**. |

### ReturnValue

The validated attribute's value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
