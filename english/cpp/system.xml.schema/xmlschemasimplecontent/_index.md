---
title: System::Xml::Schema::XmlSchemaSimpleContent class
linktitle: XmlSchemaSimpleContent
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSimpleContent class. Represents the simpleContent element from XML Schema as specified by the World Wide Web Consortium (W3C). This class is for simple and complex types with simple content model in C++.'
type: docs
weight: 5900
url: /cpp/system.xml.schema/xmlschemasimplecontent/
---
## XmlSchemaSimpleContent class


Represents the **simpleContent** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is for simple and complex types with simple content model.

```cpp
class XmlSchemaSimpleContent : public System::Xml::Schema::XmlSchemaContentModel
```

## Methods

| Method | Description |
| --- | --- |
| [get_Content](./get_content/)() override | Returns one of the [XmlSchemaSimpleContentRestriction](../xmlschemasimplecontentrestriction/) or [XmlSchemaSimpleContentExtension](../xmlschemasimplecontentextension/). |
| [set_Content](./set_content/)(SharedPtr\<XmlSchemaContent\>) override | Returns one of the [XmlSchemaSimpleContentRestriction](../xmlschemasimplecontentrestriction/) or [XmlSchemaSimpleContentExtension](../xmlschemasimplecontentextension/). |
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
