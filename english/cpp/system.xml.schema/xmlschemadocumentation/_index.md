---
title: System::Xml::Schema::XmlSchemaDocumentation class
linktitle: XmlSchemaDocumentation
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaDocumentation class. Represents the documentation element from XML Schema as specified by the World Wide Web Consortium (W3C). This class specifies information to be read or used by humans within an annotation in C++.'
type: docs
weight: 2500
url: /cpp/system.xml.schema/xmlschemadocumentation/
---
## XmlSchemaDocumentation class


Represents the **documentation** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class specifies information to be read or used by humans within an **annotation**.

```cpp
class XmlSchemaDocumentation : public System::Xml::Schema::XmlSchemaObject
```

## Methods

| Method | Description |
| --- | --- |
| [get_Language](./get_language/)() | Returns the **xml:lang** attribute. This serves as an indicator of the language used in the contents. |
| [get_Markup](./get_markup/)() | Returns an array of [XmlNode](../../system.xml/xmlnode/) objects that represents the documentation child nodes. |
| [get_Source](./get_source/)() | Returns the Uniform Resource Identifier (URI) source of the information. |
| [set_Language](./set_language/)(const String\&) | Sets the **xml:lang** attribute. This serves as an indicator of the language used in the contents. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | Sets an array of [XmlNode](../../system.xml/xmlnode/) objects that represents the documentation child nodes. |
| [set_Source](./set_source/)(const String\&) | Sets the Uniform Resource Identifier (URI) source of the information. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
