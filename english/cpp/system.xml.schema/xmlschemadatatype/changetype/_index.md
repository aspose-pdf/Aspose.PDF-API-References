---
title: System::Xml::Schema::XmlSchemaDatatype::ChangeType method
linktitle: ChangeType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaDatatype::ChangeType method. Converts the value specified, whose type is one of the valid representations of the XML schema type represented by the XmlSchemaDatatype, to the run-time type specified in C++.'
type: docs
weight: 100
url: /cpp/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) method


Converts the value specified, whose type is one of the valid representations of the XML schema type represented by the [XmlSchemaDatatype](../), to the run-time type specified.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | SharedPtr\<Object\> | The input value to convert to the specified type. |
| targetType | const TypeInfo\& | The target type to convert the input value to. |

### ReturnValue

The converted input value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Converts the value specified, whose type is one of the valid representations of the XML schema type represented by the [XmlSchemaDatatype](../), to the run-time type specified using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) if the [XmlSchemaDatatype](../) represents the **xs:QName** type or a type derived from it.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | SharedPtr\<Object\> | The input value to convert to the specified type. |
| targetType | const TypeInfo\& | The target type to convert the input value to. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | An [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) used for resolving namespace prefixes. This is only of use if the [XmlSchemaDatatype](../) represents the **xs:QName** type or a type derived from it. |

### ReturnValue

The converted input value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
