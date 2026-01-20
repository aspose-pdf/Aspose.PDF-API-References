---
title: System::Xml::XmlWriter class
linktitle: XmlWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlWriter class. Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data in C++.'
type: docs
weight: 4400
url: /cpp/system.xml/xmlwriter/
---
## XmlWriter class


Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.

```cpp
class XmlWriter : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Close](./close/)() | When overridden in a derived class, closes this stream and the underlying stream. |
| static [Create](./create/)(const String\&) | Creates a new [XmlWriter](./) instance using the specified filename. |
| static [Create](./create/)(const String\&, SharedPtr\<XmlWriterSettings\>) | Creates a new [XmlWriter](./) instance using the filename and [XmlWriterSettings](../xmlwritersettings/) object. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&) | Creates a new [XmlWriter](./) instance using the specified stream. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) | Creates a new [XmlWriter](./) instance using the stream and [XmlWriterSettings](../xmlwritersettings/) object. |
| static [Create](./create/)(const SharedPtr\<IO::TextWriter\>\&) | Creates a new [XmlWriter](./) instance using the specified TextWriter. |
| static [Create](./create/)(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) | Creates a new [XmlWriter](./) instance using the TextWriter and [XmlWriterSettings](../xmlwritersettings/) objects. |
| static [Create](./create/)(const SharedPtr\<Text::StringBuilder\>\&) | Creates a new [XmlWriter](./) instance using the specified [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [Create](./create/)(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) | Creates a new [XmlWriter](./) instance using the [Text::StringBuilder](../../system.text/stringbuilder/) and [XmlWriterSettings](../xmlwritersettings/) objects. |
| static [Create](./create/)(const SharedPtr\<XmlWriter\>\&) | Creates a new [XmlWriter](./) instance using the specified [XmlWriter](./) object. |
| static [Create](./create/)(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) | Creates a new [XmlWriter](./) instance using the specified [XmlWriter](./) and [XmlWriterSettings](../xmlwritersettings/) objects. |
| [Dispose](./dispose/)() override | Releases all resources used by the current instance of the [XmlWriter](./) class. |
| virtual [Flush](./flush/)() | When overridden in a derived class, flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream. |
| virtual [get_Settings](./get_settings/)() | Returns the [XmlWriterSettings](../xmlwritersettings/) object used to create this [XmlWriter](./) instance. |
| virtual [get_WriteState](./get_writestate/)() | When overridden in a derived class, gets the state of the writer. |
| virtual [get_XmlLang](./get_xmllang/)() | When overridden in a derived class, gets the current **xml:lang** scope. |
| virtual [get_XmlSpace](./get_xmlspace/)() | When overridden in a derived class, gets an [XmlSpace](../xmlspace/) representing the current **xml:space** scope. |
| virtual [LookupPrefix](./lookupprefix/)(String) | When overridden in a derived class, returns the closest prefix defined in the current namespace scope for the namespace URI. |
| virtual [WriteAttributes](./writeattributes/)(SharedPtr\<XmlReader\>, bool) | When overridden in a derived class, writes out all the attributes found at the current position in the [XmlReader](../xmlreader/). |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&, const String\&) | When overridden in a derived class, writes an attribute with the specified local name, namespace URI, and value. |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&) | When overridden in a derived class, writes out the attribute with the specified local name and value. |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&, const String\&, const String\&) | When overridden in a derived class, writes out the attribute with the specified prefix, local name, namespace URI, and value. |
| virtual [WriteBase64](./writebase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | When overridden in a derived class, encodes the specified binary bytes as Base64 and writes out the resulting text. |
| virtual [WriteBinHex](./writebinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | When overridden in a derived class, encodes the specified binary bytes as **BinHex** and writes out the resulting text. |
| virtual [WriteCData](./writecdata/)(String) | When overridden in a derived class, writes out a **...** block containing the specified text. |
| virtual [WriteCharEntity](./writecharentity/)(char16_t) | When overridden in a derived class, forces the generation of a character entity for the specified Unicode character value. |
| virtual [WriteChars](./writechars/)(ArrayPtr\<char16_t\>, int32_t, int32_t) | When overridden in a derived class, writes text one buffer at a time. |
| virtual [WriteComment](./writecomment/)(String) | When overridden in a derived class, writes out a comment **** containing the specified text. |
| virtual [WriteDocType](./writedoctype/)(const String\&, const String\&, const String\&, const String\&) | When overridden in a derived class, writes the DOCTYPE declaration with the specified name and optional attributes. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&) | Writes an element with the specified local name and value. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&, const String\&) | Writes an element with the specified local name, namespace URI, and value. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&, const String\&, const String\&) | Writes an element with the specified prefix, local name, namespace URI, and value. |
| virtual [WriteEndAttribute](./writeendattribute/)() | When overridden in a derived class, closes the previous XmlWriter::WriteStartAttribute(String,String) call. |
| virtual [WriteEndDocument](./writeenddocument/)() | When overridden in a derived class, closes any open elements or attributes and puts the writer back in the Start state. |
| virtual [WriteEndElement](./writeendelement/)() | When overridden in a derived class, closes one element and pops the corresponding namespace scope. |
| virtual [WriteEntityRef](./writeentityref/)(const String\&) | When overridden in a derived class, writes out an entity reference as **&name**;. |
| virtual [WriteFullEndElement](./writefullendelement/)() | When overridden in a derived class, closes one element and pops the corresponding namespace scope. |
| virtual [WriteName](./writename/)(const String\&) | When overridden in a derived class, writes out the specified name, ensuring it is a valid name according to the W3C XML 1.0 recommendation ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual [WriteNmToken](./writenmtoken/)(const String\&) | When overridden in a derived class, writes out the specified name, ensuring it is a valid NmToken according to the W3C XML 1.0 recommendation ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual [WriteNode](./writenode/)(SharedPtr\<XmlReader\>, bool) | When overridden in a derived class, copies everything from the reader to the writer and moves the reader to the start of the next sibling. |
| virtual [WriteNode](./writenode/)(SharedPtr\<XPath::XPathNavigator\>, bool) | Copies everything from the XPathNavigator object to the writer. The position of the XPathNavigator remains unchanged. |
| virtual [WriteProcessingInstruction](./writeprocessinginstruction/)(String, String) | When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: **<?name text?>**. |
| virtual [WriteQualifiedName](./writequalifiedname/)(const String\&, const String\&) | When overridden in a derived class, writes out the namespace-qualified name. This method looks up the prefix that is in scope for the given namespace. |
| virtual [WriteRaw](./writeraw/)(ArrayPtr\<char16_t\>, int32_t, int32_t) | When overridden in a derived class, writes raw markup manually from a character buffer. |
| virtual [WriteRaw](./writeraw/)(const String\&) | When overridden in a derived class, writes raw markup manually from a string. |
| [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&) | Writes the start of an attribute with the specified local name and namespace URI. |
| virtual [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&, const String\&) | When overridden in a derived class, writes the start of an attribute with the specified prefix, local name, and namespace URI. |
| [WriteStartAttribute](./writestartattribute/)(const String\&) | Writes the start of an attribute with the specified local name. |
| virtual [WriteStartDocument](./writestartdocument/)() | When overridden in a derived class, writes the XML declaration with the version "1.0". |
| virtual [WriteStartDocument](./writestartdocument/)(bool) | When overridden in a derived class, writes the XML declaration with the version "1.0" and the standalone attribute. |
| [WriteStartElement](./writestartelement/)(const String\&, const String\&) | When overridden in a derived class, writes the specified start tag and associates it with the given namespace. |
| virtual [WriteStartElement](./writestartelement/)(const String\&, const String\&, const String\&) | When overridden in a derived class, writes the specified start tag and associates it with the given namespace and prefix. |
| [WriteStartElement](./writestartelement/)(const String\&) | When overridden in a derived class, writes out a start tag with the specified local name. |
| virtual [WriteString](./writestring/)(const String\&) | When overridden in a derived class, writes the given text content. |
| virtual [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | When overridden in a derived class, generates and writes the surrogate character entity for the surrogate character pair. |
| virtual [WriteValue](./writevalue/)(SharedPtr\<Object\>) | Writes the object value. |
| virtual [WriteValue](./writevalue/)(const String\&) | Writes a [String](../../system/string/) value. |
| virtual [WriteValue](./writevalue/)(bool) | Writes a [Boolean](../../system/boolean/) value. |
| virtual [WriteValue](./writevalue/)(DateTime) | Writes a [DateTime](../../system/datetime/) value. |
| virtual [WriteValue](./writevalue/)(DateTimeOffset) | Writes a [DateTimeOffset](../../system/datetimeoffset/) value. |
| virtual [WriteValue](./writevalue/)(double) | Writes a [Double](../../system/double/) value. |
| virtual [WriteValue](./writevalue/)(float) | Writes a single-precision floating-point number. |
| virtual [WriteValue](./writevalue/)(Decimal) | Writes a [Decimal](../../system/decimal/) value. |
| virtual [WriteValue](./writevalue/)(int32_t) | Writes a [Int32](../../system/int32/) value. |
| virtual [WriteValue](./writevalue/)(int64_t) | Writes a [Int64](../../system/int64/) value. |
| virtual [WriteWhitespace](./writewhitespace/)(String) | When overridden in a derived class, writes out the given white space. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
