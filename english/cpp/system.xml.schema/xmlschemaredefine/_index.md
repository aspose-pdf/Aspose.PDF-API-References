---
title: System::Xml::Schema::XmlSchemaRedefine class
linktitle: XmlSchemaRedefine
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaRedefine class. Represents the redefine element from XML Schema as specified by the World Wide Web Consortium (W3C). This class can be used to allow simple and complex types, groups and attribute groups from external schema files to be redefined in the current schema. This class can also be used to provide versioning for the schema elements in C++.'
type: docs
weight: 5600
url: /cpp/system.xml.schema/xmlschemaredefine/
---
## XmlSchemaRedefine class


Represents the **redefine** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class can be used to allow simple and complex types, groups and attribute groups from external schema files to be redefined in the current schema. This class can also be used to provide versioning for the schema elements.

```cpp
class XmlSchemaRedefine : public System::Xml::Schema::XmlSchemaExternal
```

## Methods

| Method | Description |
| --- | --- |
| [get_AttributeGroups](./get_attributegroups/)() | Returns the [XmlSchemaObjectTable](../xmlschemaobjecttable/) , for all attributes in the schema, which holds the post-compilation interpretation of the **AttributeGroups** value. |
| [get_Groups](./get_groups/)() | Returns the [XmlSchemaObjectTable](../xmlschemaobjecttable/), for all groups in the schema, which holds the post-compilation interpretation of the **Groups** value. |
| [get_Items](./get_items/)() | Returns the collection of the following classes: [XmlSchemaAnnotation](../xmlschemaannotation/), [XmlSchemaAttributeGroup](../xmlschemaattributegroup/), [XmlSchemaComplexType](../xmlschemacomplextype/), [XmlSchemaSimpleType](../xmlschemasimpletype/), and [XmlSchemaGroup](../xmlschemagroup/). |
| [get_SchemaTypes](./get_schematypes/)() | Returns the [XmlSchemaObjectTable](../xmlschemaobjecttable/), for all simple and complex types in the schema, which holds the post-compilation interpretation of the **SchemaTypes** value. |
| [XmlSchemaRedefine](./xmlschemaredefine/)() | Initializes a new instance of the [XmlSchemaRedefine](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaExternal](../xmlschemaexternal/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
