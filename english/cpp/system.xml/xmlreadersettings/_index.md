---
title: System::Xml::XmlReaderSettings class
linktitle: XmlReaderSettings
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReaderSettings class. Specifies a set of features to support on the XmlReader object created by the XmlReader::Create method in C++.'
type: docs
weight: 3400
url: /cpp/system.xml/xmlreadersettings/
---
## XmlReaderSettings class


Specifies a set of features to support on the [XmlReader](../xmlreader/) object created by the [XmlReader::Create](../xmlreader/create/) method.

```cpp
class XmlReaderSettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [CheckReadOnly](./checkreadonly/)(const String\&) |  |
| [Clone](./clone/)() | Creates a copy of the [XmlReaderSettings](./) instance. |
| [get_CheckCharacters](./get_checkcharacters/)() | Returns a value indicating whether to do character checking. |
| [get_CloseInput](./get_closeinput/)() | Returns a value indicating whether the underlying stream or TextReader should be closed when the reader is closed. |
| [get_ConformanceLevel](./get_conformancelevel/)() | Returns the level of conformance which the [XmlReader](../xmlreader/) will comply. |
| [get_DtdProcessing](./get_dtdprocessing/)() | Returns a value that determines the processing of DTDs. |
| [get_IgnoreComments](./get_ignorecomments/)() | Returns a value indicating whether to ignore comments. |
| [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Returns a value indicating whether to ignore processing instructions. |
| [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Returns a value indicating whether to ignore insignificant white space. |
| [get_LineNumberOffset](./get_linenumberoffset/)() | Returns line number offset of the [XmlReader](../xmlreader/) object. |
| [get_LinePositionOffset](./get_linepositionoffset/)() | Returns line position offset of the [XmlReader](../xmlreader/) object. |
| [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Returns a value indicating the maximum allowable number of characters in a document that result from expanding entities. |
| [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Returns a value indicating the maximum allowable number of characters in an XML document. A zero (0) value means no limits on the size of the XML document. A non-zero value specifies the maximum size, in characters. |
| [get_NameTable](./get_nametable/)() | Returns the [XmlNameTable](../xmlnametable/) used for atomized string comparisons. |
| [get_ProhibitDtd](./get_prohibitdtd/)() | Returns a value indicating whether to prohibit document type definition (DTD) processing. |
| [get_Schemas](./get_schemas/)() | Returns the XmlSchemaSet to use when performing schema validation. |
| [get_ValidationFlags](./get_validationflags/)() | Returns a value indicating the schema validation settings. This setting applies to [XmlReader](../xmlreader/) objects that validate schemas ([XmlReaderSettings::get_ValidationType](./get_validationtype/) value is [ValidationType::Schema](../validationtype/)). |
| [get_ValidationType](./get_validationtype/)() | Returns a value indicating whether the [XmlReader](../xmlreader/) will perform validation or type assignment when reading. |
| [Reset](./reset/)() | Resets the members of the settings class to their default values. |
| [set_CheckCharacters](./set_checkcharacters/)(bool) | Sets a value indicating whether to do character checking. |
| [set_CloseInput](./set_closeinput/)(bool) | Sets a value indicating whether the underlying stream or TextReader should be closed when the reader is closed. |
| [set_ConformanceLevel](./set_conformancelevel/)(System::Xml::ConformanceLevel) | Sets the level of conformance which the [XmlReader](../xmlreader/) will comply. |
| [set_DtdProcessing](./set_dtdprocessing/)(System::Xml::DtdProcessing) | Sets a value that determines the processing of DTDs. |
| [set_IgnoreComments](./set_ignorecomments/)(bool) | Sets a value indicating whether to ignore comments. |
| [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(bool) | Sets a value indicating whether to ignore processing instructions. |
| [set_IgnoreWhitespace](./set_ignorewhitespace/)(bool) | Sets a value indicating whether to ignore insignificant white space. |
| [set_LineNumberOffset](./set_linenumberoffset/)(int32_t) | Sets line number offset of the [XmlReader](../xmlreader/) object. |
| [set_LinePositionOffset](./set_linepositionoffset/)(int32_t) | Sets line position offset of the [XmlReader](../xmlreader/) object. |
| [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(int64_t) | Sets a value indicating the maximum allowable number of characters in a document that result from expanding entities. |
| [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(int64_t) | Sets a value indicating the maximum allowable number of characters in an XML document. A zero (0) value means no limits on the size of the XML document. A non-zero value specifies the maximum size, in characters. |
| [set_NameTable](./set_nametable/)(const SharedPtr\<XmlNameTable\>\&) | Sets the [XmlNameTable](../xmlnametable/) used for atomized string comparisons. |
| [set_ProhibitDtd](./set_prohibitdtd/)(bool) | Sets a value indicating whether to prohibit document type definition (DTD) processing. |
| [set_Schemas](./set_schemas/)(const SharedPtr\<Schema::XmlSchemaSet\>\&) | Sets the XmlSchemaSet to use when performing schema validation. |
| [set_ValidationFlags](./set_validationflags/)(Schema::XmlSchemaValidationFlags) | Sets a value indicating the schema validation settings. This setting applies to [XmlReader](../xmlreader/) objects that validate schemas ([XmlReaderSettings::get_ValidationType](./get_validationtype/) value is [ValidationType::Schema](../validationtype/)). |
| [set_ValidationType](./set_validationtype/)(System::Xml::ValidationType) | Sets a value indicating whether the [XmlReader](../xmlreader/) will perform validation or type assignment when reading. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Sets the [XmlResolver](../xmlresolver/) used to access external documents. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Adds an event handler that occurs when the reader encounters validation errors. |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Removes an event handler that occurs when the reader encounters validation errors. |
| [XmlReaderSettings](./xmlreadersettings/)() | Initializes a new instance of the [XmlReaderSettings](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
