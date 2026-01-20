---
title: System::Xml::Schema::XmlSchemaImport class
linktitle: XmlSchemaImport
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaImport class. Represents the import element from XML Schema as specified by the World Wide Web Consortium (W3C). This class is used to import schema components from other schemas in C++.'
type: docs
weight: 3500
url: /cpp/system.xml.schema/xmlschemaimport/
---
## XmlSchemaImport class


Represents the **import** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is used to import schema components from other schemas.

```cpp
class XmlSchemaImport : public System::Xml::Schema::XmlSchemaExternal
```

## Methods

| Method | Description |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Returns the **annotation** value. |
| [get_Namespace](./get_namespace/)() | Returns the target namespace for the imported schema as a Uniform Resource Identifier (URI) reference. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Sets the **annotation** value. |
| [set_Namespace](./set_namespace/)(const String\&) | Sets the target namespace for the imported schema as a Uniform Resource Identifier (URI) reference. |
| [XmlSchemaImport](./xmlschemaimport/)() | Initializes a new instance of the [XmlSchemaImport](./) class. |
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
