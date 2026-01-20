---
title: System::Xml::Schema::XmlSchemaAnnotation class
linktitle: XmlSchemaAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaAnnotation class. Represents the World Wide Web Consortium (W3C) annotation element in C++.'
type: docs
weight: 700
url: /cpp/system.xml.schema/xmlschemaannotation/
---
## XmlSchemaAnnotation class


Represents the World Wide [Web](../../system.web/) Consortium (W3C) **annotation** element.

```cpp
class XmlSchemaAnnotation : public System::Xml::Schema::XmlSchemaObject
```

## Methods

| Method | Description |
| --- | --- |
| [get_Id](./get_id/)() | Returns the string id. |
| [get_Items](./get_items/)() | Returns the **Items** collection that is used to store the **appinfo** and **documentation** child elements. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Returns the qualified attributes that do not belong to the schema's target namespace. |
| [set_Id](./set_id/)(const String\&) | Sets the string id. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Sets the qualified attributes that do not belong to the schema's target namespace. |
| [XmlSchemaAnnotation](./xmlschemaannotation/)() | Initializes a new instance of the [XmlSchemaAnnotation](./) class. |
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
