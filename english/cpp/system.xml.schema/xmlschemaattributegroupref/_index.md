---
title: System::Xml::Schema::XmlSchemaAttributeGroupRef class
linktitle: XmlSchemaAttributeGroupRef
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaAttributeGroupRef class. Represents the attributeGroup element with the ref attribute from the XML Schema as specified by the . AttributesGroupRef is the reference for an attributeGroup, name property contains the attribute group being referenced in C++.'
type: docs
weight: 1300
url: /cpp/system.xml.schema/xmlschemaattributegroupref/
---
## XmlSchemaAttributeGroupRef class


Represents the **attributeGroup** element with the **ref** attribute from the XML [Schema](../) as specified by the [World Wide Web Consortium (W3C)](https://go.microsoft.com/fwlink/?LinkId=49454). AttributesGroupRef is the reference for an attributeGroup, name property contains the attribute group being referenced.

```cpp
class XmlSchemaAttributeGroupRef : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methods

| Method | Description |
| --- | --- |
| [get_RefName](./get_refname/)() | Returns the name of the referenced **attributeGroup** element. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Sets the name of the referenced **attributeGroup** element. |
| [XmlSchemaAttributeGroupRef](./xmlschemaattributegroupref/)() | Initializes a new instance of the [XmlSchemaAttributeGroupRef](./) class. |
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
