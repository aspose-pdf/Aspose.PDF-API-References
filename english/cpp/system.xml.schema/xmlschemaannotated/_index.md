---
title: System::Xml::Schema::XmlSchemaAnnotated class
linktitle: XmlSchemaAnnotated
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaAnnotated class. The base class for any element that can contain annotation elements in C++.'
type: docs
weight: 600
url: /cpp/system.xml.schema/xmlschemaannotated/
---
## XmlSchemaAnnotated class


The base class for any element that can contain annotation elements.

```cpp
class XmlSchemaAnnotated : public System::Xml::Schema::XmlSchemaObject
```

## Methods

| Method | Description |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Returns the **annotation** property. |
| [get_Id](./get_id/)() | Returns the string id. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Returns the qualified attributes that do not belong to the current schema's target namespace. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Sets the **annotation** property. |
| [set_Id](./set_id/)(const String\&) | Sets the string id. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Sets the qualified attributes that do not belong to the current schema's target namespace. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
