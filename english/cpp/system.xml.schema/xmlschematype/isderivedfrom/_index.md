---
title: System::Xml::Schema::XmlSchemaType::IsDerivedFrom method
linktitle: IsDerivedFrom
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaType::IsDerivedFrom method. Returns a value indicating if the derived schema type specified is derived from the base schema type specified in C++.'
type: docs
weight: 1700
url: /cpp/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom method


Returns a value indicating if the derived schema type specified is derived from the base schema type specified.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


| Parameter | Type | Description |
| --- | --- | --- |
| derivedType | SharedPtr\<XmlSchemaType\> | The derived [XmlSchemaType](../) to test. |
| baseType | const SharedPtr\<XmlSchemaType\>\& | The base [XmlSchemaType](../) to test the derived [XmlSchemaType](../) against. |
| except | XmlSchemaDerivationMethod | One of the [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) values representing a type derivation method to exclude from testing. |

### ReturnValue

**true** if the derived type is derived from the base type; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
