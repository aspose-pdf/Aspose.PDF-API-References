---
title: System::Xml::Schema::XmlSchemaObject class
linktitle: XmlSchemaObject
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaObject class. Represents the root class for the Xml schema object model hierarchy and serves as a base class for classes such as the XmlSchema class in C++.'
type: docs
weight: 5000
url: /cpp/system.xml.schema/xmlschemaobject/
---
## XmlSchemaObject class


Represents the root class for the [Xml](../../system.xml/) schema object model hierarchy and serves as a base class for classes such as the [XmlSchema](../xmlschema/) class.

```cpp
class XmlSchemaObject : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_LineNumber](./get_linenumber/)() | Returns the line number in the file to which the **schema** element refers. |
| [get_LinePosition](./get_lineposition/)() | Returns the line position in the file to which the **schema** element refers. |
| [get_Namespaces](./get_namespaces/)() | Returns the XmlSerializerNamespaces to use with this schema object. |
| [get_Parent](./get_parent/)() | Returns the parent of this [XmlSchemaObject](./). |
| [get_SourceUri](./get_sourceuri/)() | Returns the source location for the file that loaded the schema. |
| [set_LineNumber](./set_linenumber/)(int32_t) | Sets the line number in the file to which the **schema** element refers. |
| [set_LinePosition](./set_lineposition/)(int32_t) | Sets the line position in the file to which the **schema** element refers. |
| [set_Namespaces](./set_namespaces/)(const SharedPtr\<System::Xml::Serialization::XmlSerializerNamespaces\>\&) | Sets the XmlSerializerNamespaces to use with this schema object. |
| [set_Parent](./set_parent/)(const SharedPtr\<XmlSchemaObject\>\&) | Sets the parent of this [XmlSchemaObject](./). |
| [set_SourceUri](./set_sourceuri/)(const String\&) | Sets the source location for the file that loaded the schema. |
| [XmlSchemaObject](./xmlschemaobject/)() | Initializes a new instance of the [XmlSchemaObject](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
