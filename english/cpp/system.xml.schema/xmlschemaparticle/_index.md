---
title: System::Xml::Schema::XmlSchemaParticle class
linktitle: XmlSchemaParticle
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaParticle class. A base class for that is the base class for all particle types (e.g. XmlSchemaAny) in C++.'
type: docs
weight: 5400
url: /cpp/system.xml.schema/xmlschemaparticle/
---
## XmlSchemaParticle class


A base class for that is the base class for all particle types (e.g. [XmlSchemaAny](../xmlschemaany/)).

```cpp
class XmlSchemaParticle : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methods

| Method | Description |
| --- | --- |
| [get_MaxOccurs](./get_maxoccurs/)() | Returns the maximum number of times the particle can occur. |
| [get_MaxOccursString](./get_maxoccursstring/)() | Returns the number as a string value. Maximum number of times the particle can occur. |
| [get_MinOccurs](./get_minoccurs/)() | Returns the minimum number of times the particle can occur. |
| [get_MinOccursString](./get_minoccursstring/)() | Returns the number as a string value. The minimum number of times the particle can occur. |
| [set_MaxOccurs](./set_maxoccurs/)(Decimal) | Sets the maximum number of times the particle can occur. |
| [set_MaxOccursString](./set_maxoccursstring/)(const String\&) | Sets the number as a string value. Maximum number of times the particle can occur. |
| [set_MinOccurs](./set_minoccurs/)(Decimal) | Sets the minimum number of times the particle can occur. |
| [set_MinOccursString](./set_minoccursstring/)(const String\&) | Sets the number as a string value. The minimum number of times the particle can occur. |
| [XmlSchemaParticle](./xmlschemaparticle/)() | Initializes a new instance of the [XmlSchemaParticle](./) class. |
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
