---
title: System::Xml::Schema::XmlSchemaComplexContent class
linktitle: XmlSchemaComplexContent
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaComplexContent class. Represents the complexContent element from XML Schema as specified by the World Wide Web Consortium (W3C). This class represents the complex content model for complex types. It contains extensions or restrictions on a complex type that has either only elements or mixed content in C++.'
type: docs
weight: 1800
url: /cpp/system.xml.schema/xmlschemacomplexcontent/
---
## XmlSchemaComplexContent class


Represents the **complexContent** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class represents the complex content model for complex types. It contains extensions or restrictions on a complex type that has either only elements or mixed content.

```cpp
class XmlSchemaComplexContent : public System::Xml::Schema::XmlSchemaContentModel
```

## Methods

| Method | Description |
| --- | --- |
| [get_Content](./get_content/)() override | Returns the content. |
| [get_IsMixed](./get_ismixed/)() | Returns information that determines if the type has a mixed content model. |
| [set_Content](./set_content/)(SharedPtr\<XmlSchemaContent\>) override | Sets the content. |
| [set_IsMixed](./set_ismixed/)(bool) | Sets information that determines if the type has a mixed content model. |
| [XmlSchemaComplexContent](./xmlschemacomplexcontent/)() | Initializes a new instance of the [XmlSchemaComplexContent](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaContentModel](../xmlschemacontentmodel/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
