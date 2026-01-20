---
title: System::Xml::Schema::XmlSchemaGroup class
linktitle: XmlSchemaGroup
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaGroup class. Represents the group element from XML Schema as specified by the World Wide Web Consortium (W3C). This class defines groups at the schema level that are referenced from the complex types. It groups a set of element declarations so that they can be incorporated as a group into complex type definitions in C++.'
type: docs
weight: 3100
url: /cpp/system.xml.schema/xmlschemagroup/
---
## XmlSchemaGroup class


Represents the **group** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class defines groups at the **schema** level that are referenced from the complex types. It groups a set of element declarations so that they can be incorporated as a group into complex type definitions.

```cpp
class XmlSchemaGroup : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methods

| Method | Description |
| --- | --- |
| [get_Name](./get_name/)() | Returns the name of the schema group. |
| [get_Particle](./get_particle/)() | Returns one of the [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), or [XmlSchemaSequence](../xmlschemasequence/) classes. |
| [get_QualifiedName](./get_qualifiedname/)() | Returns the qualified name of the schema group. |
| [set_Name](./set_name/)(const String\&) | Sets the name of the schema group. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaGroupBase\>\&) | Sets one of the [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), or [XmlSchemaSequence](../xmlschemasequence/) classes. |
| [XmlSchemaGroup](./xmlschemagroup/)() | Initializes a new instance of the [XmlSchemaGroup](./) class. |
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
