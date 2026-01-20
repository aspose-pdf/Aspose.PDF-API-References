---
title: System::Xml::Schema::XmlSchemaIdentityConstraint class
linktitle: XmlSchemaIdentityConstraint
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaIdentityConstraint class. Class for the identity constraints: key, keyref, and unique elements in C++.'
type: docs
weight: 3400
url: /cpp/system.xml.schema/xmlschemaidentityconstraint/
---
## XmlSchemaIdentityConstraint class


Class for the identity constraints: **key**, **keyref**, and **unique** elements.

```cpp
class XmlSchemaIdentityConstraint : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methods

| Method | Description |
| --- | --- |
| [get_Fields](./get_fields/)() | Returns the collection of fields that apply as children for the XML Path Language ([XPath](../../system.xml.xpath/)) expression selector. |
| [get_Name](./get_name/)() | Returns the name of the identity constraint. |
| [get_QualifiedName](./get_qualifiedname/)() | Returns the qualified name of the identity constraint, which holds the post-compilation interpretation of the **QualifiedName** value. |
| [get_Selector](./get_selector/)() | Returns the [XPath](../../system.xml.xpath/) expression **selector** element. |
| [set_Name](./set_name/)(const String\&) | Sets the name of the identity constraint. |
| [set_Selector](./set_selector/)(const SharedPtr\<XmlSchemaXPath\>\&) | Sets the [XPath](../../system.xml.xpath/) expression **selector** element. |
| [XmlSchemaIdentityConstraint](./xmlschemaidentityconstraint/)() | Initializes a new instance of the [XmlSchemaIdentityConstraint](./) class. |
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
