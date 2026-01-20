---
title: System::Xml::Schema::XmlSchemaGroupRef class
linktitle: XmlSchemaGroupRef
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaGroupRef class. Represents the group element with ref attribute from the XML Schema as specified by the World Wide Web Consortium (W3C). This class is used within complex types that reference a group defined at the schema level in C++.'
type: docs
weight: 3300
url: /cpp/system.xml.schema/xmlschemagroupref/
---
## XmlSchemaGroupRef class


Represents the **group** element with **ref** attribute from the XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is used within complex types that reference a **group** defined at the **schema** level.

```cpp
class XmlSchemaGroupRef : public System::Xml::Schema::XmlSchemaParticle
```

## Methods

| Method | Description |
| --- | --- |
| [get_Particle](./get_particle/)() | Returns one of the [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), or [XmlSchemaSequence](../xmlschemasequence/) classes, which holds the post-compilation interpretation of the **Particle** value. |
| [get_RefName](./get_refname/)() | Returns the name of a group defined in this schema (or another schema indicated by the specified namespace). |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of a group defined in this schema (or another schema indicated by the specified namespace). |
| [XmlSchemaGroupRef](./xmlschemagroupref/)() | Initializes a new instance of the [XmlSchemaGroupRef](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
