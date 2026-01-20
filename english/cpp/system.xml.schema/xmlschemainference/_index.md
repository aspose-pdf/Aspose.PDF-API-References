---
title: System::Xml::Schema::XmlSchemaInference class
linktitle: XmlSchemaInference
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaInference class. Infers an XML Schema Definition Language (XSD) schema from an XML document. The XmlSchemaInference class cannot be inherited in C++.'
type: docs
weight: 3700
url: /cpp/system.xml.schema/xmlschemainference/
---
## XmlSchemaInference class


Infers an XML [Schema](../) Definition Language (XSD) schema from an XML document. The [XmlSchemaInference](./) class cannot be inherited.

```cpp
class XmlSchemaInference : public System::Object
```

## Enums

| Enum | Description |
| --- | --- |
| [InferenceOption](./inferenceoption/) | Affects occurrence and type information inferred by the [XmlSchemaInference](./) class for elements and attributes in an XML document. |
## Methods

| Method | Description |
| --- | --- |
| [get_Occurrence](./get_occurrence/)() | Returns the [XmlSchemaInference::InferenceOption](./inferenceoption/) value that affects schema occurrence declarations inferred from the XML document. |
| [get_TypeInference](./get_typeinference/)() | Returns the [XmlSchemaInference::InferenceOption](./inferenceoption/) value that affects types inferred from the XML document. |
| [InferSchema](./inferschema/)(const SharedPtr\<XmlReader\>\&) | Infers an XML [Schema](../) Definition Language (XSD) schema from the XML document contained in the [XmlReader](../../system.xml/xmlreader/) object specified. |
| [InferSchema](./inferschema/)(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) | Infers an XML [Schema](../) Definition Language (XSD) schema from the XML document contained in the [XmlReader](../../system.xml/xmlreader/) object specified, and refines the inferred schema using an existing schema in the [XmlSchemaSet](../xmlschemaset/) object specified with the same target namespace. |
| [set_Occurrence](./set_occurrence/)(XmlSchemaInference::InferenceOption) | Sets the [XmlSchemaInference::InferenceOption](./inferenceoption/) value that affects schema occurrence declarations inferred from the XML document. |
| [set_TypeInference](./set_typeinference/)(XmlSchemaInference::InferenceOption) | Sets the [XmlSchemaInference::InferenceOption](./inferenceoption/) value that affects types inferred from the XML document. |
| [XmlSchemaInference](./xmlschemainference/)() | Initializes a new instance of the [XmlSchemaInference](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
