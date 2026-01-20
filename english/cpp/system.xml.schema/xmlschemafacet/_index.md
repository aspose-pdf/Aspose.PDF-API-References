---
title: System::Xml::Schema::XmlSchemaFacet class
linktitle: XmlSchemaFacet
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaFacet class. A base class for all facets that are used when simple types are derived by restriction in C++.'
type: docs
weight: 2900
url: /cpp/system.xml.schema/xmlschemafacet/
---
## XmlSchemaFacet class


A base class for all facets that are used when simple types are derived by restriction.

```cpp
class XmlSchemaFacet : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_IsFixed](./get_isfixed/)() | Returns information that indicates that this facet is fixed. |
| [get_Value](./get_value/)() | Returns the **value** attribute of the facet. |
| virtual [set_IsFixed](./set_isfixed/)(bool) | Sets information that indicates that this facet is fixed. |
| [set_Value](./set_value/)(const String\&) | Sets the **value** attribute of the facet. |
| [XmlSchemaFacet](./xmlschemafacet/)() | Initializes a new instance of the [XmlSchemaFacet](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
