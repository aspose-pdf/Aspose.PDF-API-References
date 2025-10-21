---
title: System::Xml::XmlTextWriter class
linktitle: XmlTextWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextWriter class. Represents a writer that provides a fast, non-cached, forward-only way of generating streams or files containing XML data that conforms to the W3C Extensible Markup Language (XML) 1.0 and the Namespaces in XML recommendations in C++.'
type: docs
weight: 4000
url: /cpp/system.xml/xmltextwriter/
---
## XmlTextWriter class


Represents a writer that provides a fast, non-cached, forward-only way of generating streams or files containing XML data that conforms to the W3C Extensible Markup Language (XML) 1.0 and the Namespaces in XML recommendations.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Closes this stream and the underlying stream. |
| [Flush](./flush/)() override | Flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream. |
| [get_BaseStream](./get_basestream/)() | Returns the underlying stream object. |
| [get_Formatting](./get_formatting/)() | Indicates how the output is formatted. |
| [get_Indentation](./get_indentation/)() | Returns how many IndentChars to write for each level in the hierarchy when [XmlTextWriter::set_Formatting](./set_formatting/) is set to [Formatting::Indented](../formatting/). |
| [get_IndentChar](./get_indentchar/)() | Returns which character to use for indenting when [XmlTextWriter::set_Formatting](./set_formatting/) is set to [Formatting::Indented](../formatting/). |
| [get_Namespaces](./get_namespaces/)() | Returns a value indicating whether to do namespace support. |
| [get_QuoteChar](./get_quotechar/)() | Returns which character to use to quote attribute values. |
| [get_WriteState](./get_writestate/)() override | Returns the state of the writer. |
| [get_XmlLang](./get_xmllang/)() override | Returns the current **xml:lang** scope. |
| [get_XmlSpace](./get_xmlspace/)() override | Returns an [XmlSpace](../xmlspace/) representing the current **xml:space** scope. |
| [LookupPrefix](./lookupprefix/)(String) override | Returns the closest prefix defined in the current namespace scope for the namespace URI. |
| [set_Formatting](./set_formatting/)(System::Xml::Formatting) | Indicates how the output is formatted. |
| [set_Indentation](./set_indentation/)(int32_t) | Sets how many IndentChars to write for each level in the hierarchy when [XmlTextWriter::set_Formatting](./set_formatting/) is set to [Formatting::Indented](../formatting/). |
| [set_IndentChar](./set_indentchar/)(char16_t) | Sets which character to use for indenting when [XmlTextWriter::set_Formatting](./set_formatting/) is set to [Formatting::Indented](../formatting/). |
| [set_Namespaces](./set_namespaces/)(bool) | Sets a value indicating whether to do namespace support. |
| [set_QuoteChar](./set_quotechar/)(char16_t) | Sets which character to use to quote attribute values. |
| [WriteBase64](./writebase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Encodes the specified binary bytes as base64 and writes out the resulting text. |
| [WriteBinHex](./writebinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Encodes the specified binary bytes as binhex and writes out the resulting text. |
| [WriteCData](./writecdata/)(String) override | Writes out a **...** block containing the specified text. |
| [WriteCharEntity](./writecharentity/)(char16_t) override | Forces the generation of a character entity for the specified Unicode character value. |
| [WriteChars](./writechars/)(ArrayPtr\<char16_t\>, int32_t, int32_t) override | Writes text one buffer at a time. |
| [WriteComment](./writecomment/)(String) override | Writes out a comment **** containing the specified text. |
| [WriteDocType](./writedoctype/)(const String\&, const String\&, const String\&, const String\&) override | Writes the DOCTYPE declaration with the specified name and optional attributes. |
| [WriteEndAttribute](./writeendattribute/)() override | Closes the previous [XmlTextWriter::WriteStartAttribute](./writestartattribute/) call. |
| [WriteEndDocument](./writeenddocument/)() override | Closes any open elements or attributes and puts the writer back in the Start state. |
| [WriteEndElement](./writeendelement/)() override | Closes one element and pops the corresponding namespace scope. |
| [WriteEntityRef](./writeentityref/)(const String\&) override | Writes out an entity reference as **&name**;. |
| [WriteFullEndElement](./writefullendelement/)() override | Closes one element and pops the corresponding namespace scope. |
| [WriteName](./writename/)(const String\&) override | Writes out the specified name, ensuring it is a valid name according to the [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| [WriteNmToken](./writenmtoken/)(const String\&) override | Writes out the specified name, ensuring it is a valid **NmToken** according to the [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| [WriteProcessingInstruction](./writeprocessinginstruction/)(String, String) override | Writes out a processing instruction with a space between the name and text as follows: **<?name text?>**. |
| [WriteQualifiedName](./writequalifiedname/)(const String\&, const String\&) override | Writes out the namespace-qualified name. This method looks up the prefix that is in scope for the given namespace. |
| [WriteRaw](./writeraw/)(ArrayPtr\<char16_t\>, int32_t, int32_t) override | Writes raw markup manually from a character buffer. |
| [WriteRaw](./writeraw/)(const String\&) override | Writes raw markup manually from a string. |
| [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&, const String\&) override | Writes the start of an attribute. |
| [WriteStartDocument](./writestartdocument/)() override | Writes the XML declaration with the version "1.0". |
| [WriteStartDocument](./writestartdocument/)(bool) override | Writes the XML declaration with the version "1.0" and the standalone attribute. |
| [WriteStartElement](./writestartelement/)(const String\&, const String\&, const String\&) override | Writes the specified start tag and associates it with the given namespace and prefix. |
| [WriteString](./writestring/)(const String\&) override | Writes the given text content. |
| [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Generates and writes the surrogate character entity for the surrogate character pair. |
| [WriteWhitespace](./writewhitespace/)(String) override | Writes out the given white space. |
| [XmlTextWriter](./xmltextwriter/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) | Creates an instance of the [XmlTextWriter](./) class using the specified stream and encoding. |
| [XmlTextWriter](./xmltextwriter/)(const String\&, const SharedPtr\<Text::Encoding\>\&) | Creates an instance of the [XmlTextWriter](./) class using the specified file. |
| [XmlTextWriter](./xmltextwriter/)(const SharedPtr\<IO::TextWriter\>\&) | Creates an instance of the [XmlTextWriter](./) class using the specified TextWriter. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



It is recommended to use the [XmlWriter](../xmlwriter/) class instead. 

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlWriter](../xmlwriter/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
