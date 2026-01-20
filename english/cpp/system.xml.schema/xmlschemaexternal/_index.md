---
title: System::Xml::Schema::XmlSchemaExternal class
linktitle: XmlSchemaExternal
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaExternal class. Provides information about the included schema in C++.'
type: docs
weight: 2800
url: /cpp/system.xml.schema/xmlschemaexternal/
---
## XmlSchemaExternal class


Provides information about the included schema.

```cpp
class XmlSchemaExternal : public System::Xml::Schema::XmlSchemaObject
```

## Methods

| Method | Description |
| --- | --- |
| [get_Id](./get_id/)() | Returns the string id. |
| [get_Schema](./get_schema/)() | Returns the [XmlSchema](../xmlschema/) for the referenced schema. |
| [get_SchemaLocation](./get_schemalocation/)() | Returns the Uniform Resource Identifier (URI) location for the schema, which tells the schema processor where the schema physically resides. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Returns the qualified attributes, which do not belong to the schema target namespace. |
| [set_Id](./set_id/)(const String\&) | Sets the string id. |
| [set_Schema](./set_schema/)(const SharedPtr\<XmlSchema\>\&) | Sets the [XmlSchema](../xmlschema/) for the referenced schema. |
| [set_SchemaLocation](./set_schemalocation/)(const String\&) | Sets the Uniform Resource Identifier (URI) location for the schema, which tells the schema processor where the schema physically resides. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Sets the qualified attributes, which do not belong to the schema target namespace. |
| [XmlSchemaExternal](./xmlschemaexternal/)() | Initializes a new instance of the [XmlSchemaExternal](./) class. |
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
