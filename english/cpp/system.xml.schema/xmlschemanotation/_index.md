---
title: System::Xml::Schema::XmlSchemaNotation class
linktitle: XmlSchemaNotation
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaNotation class. Represents the notation element from XML Schema as specified by the World Wide Web Consortium (W3C). An XML Schemanotation declaration is a reconstruction of XML 1.0 NOTATION declarations. The purpose of notations is to describe the format of non-XML data within an XML document in C++.'
type: docs
weight: 4800
url: /cpp/system.xml.schema/xmlschemanotation/
---
## XmlSchemaNotation class


Represents the **notation** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). An XML [Schema](../)**notation** declaration is a reconstruction of **XML** 1.0 NOTATION declarations. The purpose of notations is to describe the format of non-XML data within an XML document.

```cpp
class XmlSchemaNotation : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methods

| Method | Description |
| --- | --- |
| [get_Name](./get_name/)() | Returns the name of the notation. |
| [get_Public](./get_public/)() | Returns the **public** identifier. |
| [get_System](./get_system/)() | Returns the **system** identifier. |
| [set_Name](./set_name/)(const String\&) | Sets the name of the notation. |
| [set_Public](./set_public/)(const String\&) | Sets the **public** identifier. |
| [set_System](./set_system/)(const String\&) | Sets the **system** identifier. |
| [XmlSchemaNotation](./xmlschemanotation/)() | Initializes a new instance of the [XmlSchemaNotation](./) class. |
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
