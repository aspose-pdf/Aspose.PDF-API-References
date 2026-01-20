---
title: System::Xml::XmlWriterSettings class
linktitle: XmlWriterSettings
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlWriterSettings class. Specifies a set of features to support on the XmlWriter object created by the XmlWriter::Create method in C++.'
type: docs
weight: 4500
url: /cpp/system.xml/xmlwritersettings/
---
## XmlWriterSettings class


Specifies a set of features to support on the [XmlWriter](../xmlwriter/) object created by the [XmlWriter::Create](../xmlwriter/create/) method.

```cpp
class XmlWriterSettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() | Creates a copy of the [XmlWriterSettings](./) instance. |
| [get_CheckCharacters](./get_checkcharacters/)() | Returns a value that indicates whether the XML writer should check to ensure that all characters in the document conform to the "2.2 Characters" section of the W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| [get_CloseOutput](./get_closeoutput/)() | Returns a value indicating whether the [XmlWriter](../xmlwriter/) should also close the underlying stream or TextWriter when the [XmlWriter::Close](../xmlwriter/close/) method is called. |
| [get_ConformanceLevel](./get_conformancelevel/)() | Returns the level of conformance that the XML writer checks the XML output for. |
| [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Returns a value that indicates whether the [XmlWriter](../xmlwriter/) does not escape URI attributes. |
| [get_Encoding](./get_encoding/)() | Returns the type of text encoding to use. |
| [get_Indent](./get_indent/)() | Returns a value indicating whether to indent elements. |
| [get_IndentChars](./get_indentchars/)() | Returns the character string to use when indenting. This setting is used when the [XmlWriterSettings::set_Indent](./set_indent/) value is set to **true**. |
| [get_NamespaceHandling](./get_namespacehandling/)() | Returns a value that indicates whether the [XmlWriter](../xmlwriter/) should remove duplicate namespace declarations when writing XML content. The default behavior is for the writer to output all namespace declarations that are present in the writer's namespace resolver. |
| [get_NewLineChars](./get_newlinechars/)() | Returns the character string to use for line breaks. |
| [get_NewLineHandling](./get_newlinehandling/)() | Returns a value indicating whether to normalize line breaks in the output. |
| [get_NewLineOnAttributes](./get_newlineonattributes/)() | Returns a value indicating whether to write attributes on a new line. |
| [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Returns a value indicating whether to omit an XML declaration. |
| [get_OutputMethod](./get_outputmethod/)() | Returns the method used to serialize the [XmlWriter](../xmlwriter/) output. |
| [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Returns a value that indicates whether the [XmlWriter](../xmlwriter/) will add closing tags to all unclosed element tags when the [XmlWriter::Close](../xmlwriter/close/) method is called. |
| [Reset](./reset/)() | Resets the members of the settings class to their default values. |
| [set_CheckCharacters](./set_checkcharacters/)(bool) | Sets a value that indicates whether the XML writer should check to ensure that all characters in the document conform to the "2.2 Characters" section of the W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| [set_CloseOutput](./set_closeoutput/)(bool) | Sets a value indicating whether the [XmlWriter](../xmlwriter/) should also close the underlying stream or TextWriter when the [XmlWriter::Close](../xmlwriter/close/) method is called. |
| [set_ConformanceLevel](./set_conformancelevel/)(System::Xml::ConformanceLevel) | Sets the level of conformance that the XML writer checks the XML output for. |
| [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(bool) | Sets a value that indicates whether the [XmlWriter](../xmlwriter/) does not escape URI attributes. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<System::Text::Encoding\>\&) | Sets the type of text encoding to use. |
| [set_Indent](./set_indent/)(bool) | Sets a value indicating whether to indent elements. |
| [set_IndentChars](./set_indentchars/)(const String\&) | Sets the character string to use when indenting. This setting is used when the [XmlWriterSettings::set_Indent](./set_indent/) value is set to **true**. |
| [set_NamespaceHandling](./set_namespacehandling/)(System::Xml::NamespaceHandling) | Sets a value that indicates whether the [XmlWriter](../xmlwriter/) should remove duplicate namespace declarations when writing XML content. The default behavior is for the writer to output all namespace declarations that are present in the writer's namespace resolver. |
| [set_NewLineChars](./set_newlinechars/)(const String\&) | Sets the character string to use for line breaks. |
| [set_NewLineHandling](./set_newlinehandling/)(System::Xml::NewLineHandling) | Sets a value indicating whether to normalize line breaks in the output. |
| [set_NewLineOnAttributes](./set_newlineonattributes/)(bool) | Sets a value indicating whether to write attributes on a new line. |
| [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(bool) | Sets a value indicating whether to omit an XML declaration. |
| [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(bool) | Sets a value that indicates whether the [XmlWriter](../xmlwriter/) will add closing tags to all unclosed element tags when the [XmlWriter::Close](../xmlwriter/close/) method is called. |
| [XmlWriterSettings](./xmlwritersettings/)() | Initializes a new instance of the [XmlWriterSettings](./) class. |
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
