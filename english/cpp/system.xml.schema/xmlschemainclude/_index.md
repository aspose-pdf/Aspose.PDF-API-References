---
title: System::Xml::Schema::XmlSchemaInclude class
linktitle: XmlSchemaInclude
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaInclude class. Represents the include element from XML Schema as specified by the World Wide Web Consortium (W3C). This class is used to include declarations and definitions from an external schema. The included declarations and definitions are then available for processing in the containing schema in C++.'
type: docs
weight: 3600
url: /cpp/system.xml.schema/xmlschemainclude/
---
## XmlSchemaInclude class


Represents the **include** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is used to include declarations and definitions from an external schema. The included declarations and definitions are then available for processing in the containing schema.

```cpp
class XmlSchemaInclude : public System::Xml::Schema::XmlSchemaExternal
```

## Methods

| Method | Description |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Returns the **annotation** value. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Sets the **annotation** value. |
| [XmlSchemaInclude](./xmlschemainclude/)() | Initializes a new instance of the [XmlSchemaInclude](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaExternal](../xmlschemaexternal/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
