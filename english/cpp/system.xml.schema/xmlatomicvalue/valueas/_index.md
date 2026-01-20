---
title: System::Xml::Schema::XmlAtomicValue::ValueAs method
linktitle: ValueAs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlAtomicValue::ValueAs method. Returns the validated XML element or attribute''s value as the type specified using the IXmlNamespaceResolver object specified to resolve namespace prefixes in C++.'
type: docs
weight: 1300
url: /cpp/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs method


Returns the validated XML element or attribute's value as the type specified using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | const TypeInfo\& | The type to return the validated XML element or attribute's value as. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes. |

### ReturnValue

The value of the validated XML element or attribute as the type requested.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlAtomicValue](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
