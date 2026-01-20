---
title: System::Xml::Schema::XmlSchemaChoice class
linktitle: XmlSchemaChoice
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaChoice class. Represents the choice element (compositor) from the XML Schema as specified by the World Wide Web Consortium (W3C). The choice allows only one of its children to appear in an instance in C++.'
type: docs
weight: 1400
url: /cpp/system.xml.schema/xmlschemachoice/
---
## XmlSchemaChoice class


Represents the **choice** element (compositor) from the XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). The **choice** allows only one of its children to appear in an instance.

```cpp
class XmlSchemaChoice : public System::Xml::Schema::XmlSchemaGroupBase
```

## Methods

| Method | Description |
| --- | --- |
| [get_Items](./get_items/)() override | Returns the collection of the elements contained with the compositor (**choice**): [XmlSchemaElement](../xmlschemaelement/), [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](./), [XmlSchemaSequence](../xmlschemasequence/), or [XmlSchemaAny](../xmlschemaany/). |
| [XmlSchemaChoice](./xmlschemachoice/)() | Initializes a new instance of the [XmlSchemaChoice](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaGroupBase](../xmlschemagroupbase/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
