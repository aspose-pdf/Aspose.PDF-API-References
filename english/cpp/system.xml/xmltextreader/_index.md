---
title: System::Xml::XmlTextReader class
linktitle: XmlTextReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextReader class. Represents a reader that provides fast, non-cached, forward-only access to XML data in C++.'
type: docs
weight: 3900
url: /cpp/system.xml/xmltextreader/
---
## XmlTextReader class


Represents a reader that provides fast, non-cached, forward-only access to XML data.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Changes the [XmlReader::get_ReadState](../xmlreader/get_readstate/) to **Closed**. |
| [get_AttributeCount](./get_attributecount/)() override | Returns the number of attributes on the current node. |
| [get_BaseURI](./get_baseuri/)() override | Returns the base URI of the current node. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Returns a value indicating whether the [XmlTextReader](./) implements the binary content read methods. |
| [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Returns a value indicating whether the [XmlTextReader](./) implements the [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) method. |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Returns a value indicating whether this reader can parse and resolve entities. |
| [get_Depth](./get_depth/)() override | Returns the depth of the current node in the XML document. |
| [get_DtdProcessing](./get_dtdprocessing/)() | Returns the [DtdProcessing](../dtdprocessing/) enumeration. |
| [get_Encoding](./get_encoding/)() | Returns the encoding of the document. |
| [get_EntityHandling](./get_entityhandling/)() | Returns a value that specifies how the reader handles entities. |
| [get_EOF](./get_eof/)() override | Returns a value indicating whether the reader is positioned at the end of the stream. |
| [get_HasValue](./get_hasvalue/)() override | Returns a value indicating whether the current node can have a [XmlTextReader::get_Value](./get_value/) other than [String::Empty](../../system/string/empty/). |
| [get_IsDefault](./get_isdefault/)() override | Returns a value indicating whether the current node is an attribute that was generated from the default value defined in the DTD or schema. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Returns a value indicating whether the current node is an empty element (for example, **<MyElement/>**). |
| [get_LineNumber](./get_linenumber/)() override | Returns the current line number. |
| [get_LinePosition](./get_lineposition/)() override | Returns the current line position. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the current node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the current node. |
| [get_Namespaces](./get_namespaces/)() | Returns a value indicating whether to do namespace support. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Returns the namespace URI (as defined in the W3C Namespace specification) of the node on which the reader is positioned. |
| [get_NameTable](./get_nametable/)() override | Returns the [XmlNameTable](../xmlnametable/) associated with this implementation. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_Normalization](./get_normalization/)() | Returns a value indicating whether to normalize white space and attribute values. |
| [get_Prefix](./get_prefix/)() override | Returns the namespace prefix associated with the current node. |
| [get_ProhibitDtd](./get_prohibitdtd/)() | Returns a value indicating whether to allow DTD processing. |
| [get_QuoteChar](./get_quotechar/)() override | Returns the quotation mark character used to enclose the value of an attribute node. |
| [get_ReadState](./get_readstate/)() override | Returns the state of the reader. |
| [get_Value](./get_value/)() override | Returns the text value of the current node. |
| [get_WhitespaceHandling](./get_whitespacehandling/)() | Returns a value that specifies how white space is handled. |
| [get_XmlLang](./get_xmllang/)() override | Returns the current **xml:lang** scope. |
| [get_XmlSpace](./get_xmlspace/)() override | Returns the current **xml:space** scope. |
| [GetAttribute](./getattribute/)(String) override | Returns the value of the attribute with the specified name. |
| [GetAttribute](./getattribute/)(String, String) override | Returns the value of the attribute with the specified local name and namespace URI. |
| [GetAttribute](./getattribute/)(int32_t) override | Returns the value of the attribute with the specified index. |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Returns a collection that contains all namespaces currently in-scope. |
| [GetRemainder](./getremainder/)() | Returns the remainder of the buffered XML. |
| [HasLineInfo](./haslineinfo/)() override | Returns a value indicating whether the class can return line information. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Resolves a namespace prefix in the current element's scope. |
| [MoveToAttribute](./movetoattribute/)(String) override | Moves to the attribute with the specified name. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Moves to the attribute with the specified local name and namespace URI. |
| [MoveToAttribute](./movetoattribute/)(int32_t) override | Moves to the attribute with the specified index. |
| [MoveToElement](./movetoelement/)() override | Moves to the element that contains the current attribute node. |
| [MoveToFirstAttribute](./movetofirstattribute/)() override | Moves to the first attribute. |
| [MoveToNextAttribute](./movetonextattribute/)() override | Moves to the next attribute. |
| [Read](./read/)() override | Reads the next node from the stream. |
| [ReadAttributeValue](./readattributevalue/)() override | Parses the attribute value into one or more **[Text](../../system.text/)**, **EntityReference**, or **EndEntity** nodes. |
| [ReadBase64](./readbase64/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Decodes Base64 and returns the decoded binary bytes. |
| [ReadBinHex](./readbinhex/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Decodes **BinHex** and returns the decoded binary bytes. |
| [ReadChars](./readchars/)(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) | Reads the text contents of an element into a character buffer. This method is designed to read large streams of embedded text by calling it successively. |
| [ReadContentAsBase64](./readcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Reads the content and returns the **Base64** decoded binary bytes. |
| [ReadContentAsBinHex](./readcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Reads the content and returns the **BinHex** decoded binary bytes. |
| [ReadElementContentAsBase64](./readelementcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Reads the element and decodes the Base64 content. |
| [ReadElementContentAsBinHex](./readelementcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Reads the element and decodes the **BinHex** content. |
| [ReadString](./readstring/)() override | Reads the contents of an element or a text node as a string. |
| [ResetState](./resetstate/)() | Resets the state of the reader to [ReadState::Initial](../readstate/). |
| [ResolveEntity](./resolveentity/)() override | Resolves the entity reference for **EntityReference** nodes. |
| [set_DtdProcessing](./set_dtdprocessing/)(System::Xml::DtdProcessing) | Sets the [DtdProcessing](../dtdprocessing/) enumeration. |
| [set_EntityHandling](./set_entityhandling/)(System::Xml::EntityHandling) | Sets a value that specifies how the reader handles entities. |
| [set_Namespaces](./set_namespaces/)(bool) | Sets a value indicating whether to do namespace support. |
| [set_Normalization](./set_normalization/)(bool) | Sets a value indicating whether to normalize white space and attribute values. |
| [set_ProhibitDtd](./set_prohibitdtd/)(bool) | Sets a value indicating whether to allow DTD processing. |
| [set_WhitespaceHandling](./set_whitespacehandling/)(System::Xml::WhitespaceHandling) | Sets a value that specifies how white space is handled. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Sets the [XmlResolver](../xmlresolver/) used for resolving DTD references. |
| [Skip](./skip/)() override | Skips the children of the current node. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified stream. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::Stream\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified URL and stream. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified stream and [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified URL, stream and [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::TextReader\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified TextReader. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::TextReader\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified URL and TextReader. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified TextReader and [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified URL, TextReader and [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified stream, [XmlNodeType](../xmlnodetype/), and [XmlParserContext](../xmlparsercontext/). |
| [XmlTextReader](./xmltextreader/)(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified string, [XmlNodeType](../xmlnodetype/), and [XmlParserContext](../xmlparsercontext/). |
| [XmlTextReader](./xmltextreader/)(const String\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified file. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<XmlNameTable\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified file and [XmlNameTable](../xmlnametable/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



It is recommended to use the [XmlReader](../xmlreader/) class instead. 

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlReader](../xmlreader/)
* Class [IXmlLineInfo](../ixmllineinfo/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
