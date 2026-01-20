---
title: System::Xml::Schema::XmlSchemaSequence class
linktitle: XmlSchemaSequence
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSequence class. Represents the sequence element (compositor) from the XML Schema as specified by the World Wide Web Consortium (W3C). The sequence requires the elements in the group to appear in the specified sequence within the containing element in C++.'
type: docs
weight: 5700
url: /cpp/system.xml.schema/xmlschemasequence/
---
## XmlSchemaSequence class


Represents the **sequence** element (compositor) from the XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). The **sequence** requires the elements in the group to appear in the specified sequence within the containing element.

```cpp
class XmlSchemaSequence : public System::Xml::Schema::XmlSchemaGroupBase
```

## Methods

| Method | Description |
| --- | --- |
| [get_Items](./get_items/)() override | The elements contained within the compositor. Collection of [XmlSchemaElement](../xmlschemaelement/), [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaSequence](./), or [XmlSchemaAny](../xmlschemaany/). |
| [XmlSchemaSequence](./xmlschemasequence/)() | Initializes a new instance of the [XmlSchemaSequence](./) class. |
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
