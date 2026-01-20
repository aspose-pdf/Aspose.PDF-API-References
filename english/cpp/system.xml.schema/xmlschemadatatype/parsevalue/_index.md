---
title: System::Xml::Schema::XmlSchemaDatatype::ParseValue method
linktitle: ParseValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaDatatype::ParseValue method. When overridden in a derived class, validates the string specified against a built-in or user-defined simple type in C++.'
type: docs
weight: 700
url: /cpp/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue method


When overridden in a derived class, validates the **string** specified against a built-in or user-defined simple type.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | String | The **string** to validate against the simple type. |
| nameTable | SharedPtr\<XmlNameTable\> | The [XmlNameTable](../../../system.xml/xmlnametable/) to use for atomization while parsing the **string** if this [XmlSchemaDatatype](../) object represents the **xs:NCName** type. |
| nsmgr | SharedPtr\<IXmlNamespaceResolver\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object to use while parsing the **string** if this [XmlSchemaDatatype](../) object represents the **xs:QName** type. |

### ReturnValue

An [Object](../../../system/object/) that can be cast safely to the type returned by the [XmlSchemaDatatype::get_ValueType](../get_valuetype/) call.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
