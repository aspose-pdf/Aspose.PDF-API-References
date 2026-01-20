---
title: System::Xml::Schema::XmlSchemaKeyref class
linktitle: XmlSchemaKeyref
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaKeyref class. This class represents the keyref element from XMLSchema as specified by the World Wide Web Consortium (W3C) in C++.'
type: docs
weight: 4000
url: /cpp/system.xml.schema/xmlschemakeyref/
---
## XmlSchemaKeyref class


This class represents the **keyref** element from XMLSchema as specified by the World Wide [Web](../../system.web/) Consortium (W3C).

```cpp
class XmlSchemaKeyref : public System::Xml::Schema::XmlSchemaIdentityConstraint
```

## Methods

| Method | Description |
| --- | --- |
| [get_Refer](./get_refer/)() | Returns the name of the key that this constraint refers to in another simple or complex type. |
| [set_Refer](./set_refer/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of the key that this constraint refers to in another simple or complex type. |
| [XmlSchemaKeyref](./xmlschemakeyref/)() | Initializes a new instance of the [XmlSchemaKeyref](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
