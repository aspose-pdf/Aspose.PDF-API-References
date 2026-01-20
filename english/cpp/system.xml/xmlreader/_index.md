---
title: System::Xml::XmlReader class
linktitle: XmlReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader class. Represents a reader that provides fast, noncached, forward-only access to XML data in C++.'
type: docs
weight: 3300
url: /cpp/system.xml/xmlreader/
---
## XmlReader class


Represents a reader that provides fast, noncached, forward-only access to XML data.

```cpp
class XmlReader : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Close](./close/)() | When overridden in a derived class, changes the [XmlReader::get_ReadState](./get_readstate/) to [ReadState::Closed](../readstate/). |
| static [Create](./create/)(const String\&) | Creates a new [XmlReader](./) instance with specified URI. |
| static [Create](./create/)(const String\&, const SharedPtr\<XmlReaderSettings\>\&) | Creates a new [XmlReader](./) instance by using the specified URI and settings. |
| static [Create](./create/)(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) | Creates a new [XmlReader](./) instance by using the specified URI, settings, and context information for parsing. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&) | Creates a new [XmlReader](./) instance using the specified stream with default settings. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) | Creates a new [XmlReader](./) instance with the specified stream and settings. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) | Creates a new [XmlReader](./) instance using the specified stream, base URI, and settings. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) | Creates a new [XmlReader](./) instance using the specified stream, settings, and context information for parsing. |
| static [Create](./create/)(const SharedPtr\<IO::TextReader\>\&) | Creates a new [XmlReader](./) instance by using the specified text reader. |
| static [Create](./create/)(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) | Creates a new [XmlReader](./) instance by using the specified text reader and settings. |
| static [Create](./create/)(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) | Creates a new [XmlReader](./) instance by using the specified text reader, settings, and base URI. |
| static [Create](./create/)(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) | Creates a new [XmlReader](./) instance by using the specified text reader, settings, and context information for parsing. |
| static [Create](./create/)(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) | Creates a new [XmlReader](./) instance by using the specified XML reader and settings. |
| [Dispose](./dispose/)() override | Releases all resources used by the current instance of the [XmlReader](./) class. |
| virtual [get_AttributeCount](./get_attributecount/)() | When overridden in a derived class, gets the number of attributes on the current node. |
| virtual [get_BaseURI](./get_baseuri/)() | When overridden in a derived class, gets the base URI of the current node. |
| virtual [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | Returns a value indicating whether the [XmlReader](./) implements the binary content read methods. |
| virtual [get_CanReadValueChunk](./get_canreadvaluechunk/)() | Returns a value indicating whether the [XmlReader](./) implements the [XmlReader::ReadValueChunk](./readvaluechunk/) method. |
| virtual [get_CanResolveEntity](./get_canresolveentity/)() | Returns a value indicating whether this reader can parse and resolve entities. |
| virtual [get_Depth](./get_depth/)() | When overridden in a derived class, gets the depth of the current node in the XML document. |
| virtual [get_EOF](./get_eof/)() | When overridden in a derived class, gets a value indicating whether the reader is positioned at the end of the stream. |
| virtual [get_HasAttributes](./get_hasattributes/)() | Returns a value indicating whether the current node has any attributes. |
| virtual [get_HasValue](./get_hasvalue/)() | When overridden in a derived class, gets a value indicating whether the current node can have a [XmlReader::get_Value](./get_value/) value. |
| virtual [get_IsDefault](./get_isdefault/)() | When overridden in a derived class, gets a value indicating whether the current node is an attribute that was generated from the default value defined in the DTD or schema. |
| virtual [get_IsEmptyElement](./get_isemptyelement/)() | When overridden in a derived class, gets a value indicating whether the current node is an empty element (for example, **<MyElement/>**). |
| virtual [get_LocalName](./get_localname/)() | When overridden in a derived class, gets the local name of the current node. |
| virtual [get_Name](./get_name/)() | When overridden in a derived class, gets the qualified name of the current node. |
| virtual [get_NamespaceURI](./get_namespaceuri/)() | When overridden in a derived class, gets the namespace URI (as defined in the W3C Namespace specification) of the node on which the reader is positioned. |
| virtual [get_NameTable](./get_nametable/)() | When overridden in a derived class, gets the [XmlNameTable](../xmlnametable/) associated with this implementation. |
| virtual [get_NodeType](./get_nodetype/)() | When overridden in a derived class, gets the type of the current node. |
| virtual [get_Prefix](./get_prefix/)() | When overridden in a derived class, gets the namespace prefix associated with the current node. |
| virtual [get_QuoteChar](./get_quotechar/)() | When overridden in a derived class, gets the quotation mark character used to enclose the value of an attribute node. |
| virtual [get_ReadState](./get_readstate/)() | When overridden in a derived class, gets the state of the reader. |
| virtual [get_SchemaInfo](./get_schemainfo/)() | Returns the schema information that has been assigned to the current node as a result of schema validation. |
| virtual [get_Settings](./get_settings/)() | Returns the [XmlReaderSettings](../xmlreadersettings/) object used to create this [XmlReader](./) instance. |
| virtual [get_Value](./get_value/)() | When overridden in a derived class, gets the text value of the current node. |
| virtual [get_ValueType](./get_valuetype/)() | Returns The type for the current node. |
| virtual [get_XmlLang](./get_xmllang/)() | When overridden in a derived class, gets the current **xml:lang** scope. |
| virtual [get_XmlSpace](./get_xmlspace/)() | When overridden in a derived class, gets the current **xml:space** scope. |
| virtual [GetAttribute](./getattribute/)(String) | When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_Name](./get_name/) value. |
| virtual [GetAttribute](./getattribute/)(String, String) | When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values. |
| virtual [GetAttribute](./getattribute/)(int32_t) | When overridden in a derived class, gets the value of the attribute with the specified index. |
| virtual [idx_get](./idx_get/)(int32_t) | When overridden in a derived class, gets the value of the attribute with the specified index. |
| virtual [idx_get](./idx_get/)(String) | When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_Name](./get_name/) value. |
| virtual [idx_get](./idx_get/)(String, String) | When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values. |
| static [IsName](./isname/)(const String\&) | Returns a value indicating whether the string argument is a valid XML name. |
| static [IsNameToken](./isnametoken/)(const String\&) | Returns a value indicating whether or not the string argument is a valid XML name token. |
| virtual [IsStartElement](./isstartelement/)() | Calls [XmlReader::MoveToContent](./movetocontent/) and tests if the current content node is a start tag or empty element tag. |
| virtual [IsStartElement](./isstartelement/)(String) | Calls [XmlReader::MoveToContent](./movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_Name](./get_name/) value of the element found matches the given argument. |
| virtual [IsStartElement](./isstartelement/)(String, String) | Calls [XmlReader::MoveToContent](./movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values of the element found match the given strings. |
| virtual [LookupNamespace](./lookupnamespace/)(const String\&) | When overridden in a derived class, resolves a namespace prefix in the current element's scope. |
| virtual [MoveToAttribute](./movetoattribute/)(String) | When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_Name](./get_name/) value. |
| virtual [MoveToAttribute](./movetoattribute/)(String, String) | When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values. |
| virtual [MoveToAttribute](./movetoattribute/)(int32_t) | When overridden in a derived class, moves to the attribute with the specified index. |
| virtual [MoveToContent](./movetocontent/)() | Checks whether the current node is a content (non-white space text, **CDATA**, **Element**, **EndElement**, **EntityReference**, or **EndEntity**) node. If the node is not a content node, the reader skips ahead to the next content node or end of file. It skips over nodes of the following type: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, or **SignificantWhitespace**. |
| virtual [MoveToElement](./movetoelement/)() | When overridden in a derived class, moves to the element that contains the current attribute node. |
| virtual [MoveToFirstAttribute](./movetofirstattribute/)() | When overridden in a derived class, moves to the first attribute. |
| virtual [MoveToNextAttribute](./movetonextattribute/)() | When overridden in a derived class, moves to the next attribute. |
| virtual [Read](./read/)() | When overridden in a derived class, reads the next node from the stream. |
| virtual [ReadAttributeValue](./readattributevalue/)() | When overridden in a derived class, parses the attribute value into one or more **[Text](../../system.text/)**, **EntityReference**, or **EndEntity** nodes. |
| virtual [ReadContentAs](./readcontentas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Reads the content as an object of the type specified. |
| virtual [ReadContentAsBase64](./readcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | Reads the content and returns the Base64 decoded binary bytes. |
| virtual [ReadContentAsBinHex](./readcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | Reads the content and returns the **BinHex** decoded binary bytes. |
| virtual [ReadContentAsBoolean](./readcontentasboolean/)() | Reads the text content at the current position as a [Boolean](../../system/boolean/). |
| virtual [ReadContentAsDateTime](./readcontentasdatetime/)() | Reads the text content at the current position as a [DateTime](../../system/datetime/) object. |
| virtual [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | Reads the text content at the current position as a [DateTimeOffset](../../system/datetimeoffset/) object. |
| virtual [ReadContentAsDecimal](./readcontentasdecimal/)() | Reads the text content at the current position as a [Decimal](../../system/decimal/) object. |
| virtual [ReadContentAsDouble](./readcontentasdouble/)() | Reads the text content at the current position as a double-precision floating-point number. |
| virtual [ReadContentAsFloat](./readcontentasfloat/)() | Reads the text content at the current position as a single-precision floating point number. |
| virtual [ReadContentAsInt](./readcontentasint/)() | Reads the text content at the current position as a 32-bit signed integer. |
| virtual [ReadContentAsLong](./readcontentaslong/)() | Reads the text content at the current position as a 64-bit signed integer. |
| virtual [ReadContentAsObject](./readcontentasobject/)() | Reads the text content at the current position as an [Object](../../system/object/). |
| virtual [ReadContentAsString](./readcontentasstring/)() | Reads the text content at the current position as a [String](../../system/string/) object. |
| virtual [ReadElementContentAs](./readelementcontentas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Reads the element content as the requested type. |
| virtual [ReadElementContentAs](./readelementcontentas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) | Checks that the specified local name and namespace URI matches that of the current element, then reads the element content as the requested type. |
| virtual [ReadElementContentAsBase64](./readelementcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | Reads the element and decodes the **Base64** content. |
| virtual [ReadElementContentAsBinHex](./readelementcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | Reads the element and decodes the **BinHex** content. |
| virtual [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | Reads the current element and returns the contents as a [Boolean](../../system/boolean/) object. |
| virtual [ReadElementContentAsBoolean](./readelementcontentasboolean/)(String, String) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [Boolean](../../system/boolean/) object. |
| virtual [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | Reads the current element and returns the contents as a [DateTime](../../system/datetime/) object. |
| virtual [ReadElementContentAsDateTime](./readelementcontentasdatetime/)(String, String) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [DateTime](../../system/datetime/) object. |
| virtual [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | Reads the current element and returns the contents as a [Decimal](../../system/decimal/) object. |
| virtual [ReadElementContentAsDecimal](./readelementcontentasdecimal/)(String, String) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [Decimal](../../system/decimal/) object. |
| virtual [ReadElementContentAsDouble](./readelementcontentasdouble/)() | Reads the current element and returns the contents as a double-precision floating-point number. |
| virtual [ReadElementContentAsDouble](./readelementcontentasdouble/)(String, String) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a double-precision floating-point number. |
| virtual [ReadElementContentAsFloat](./readelementcontentasfloat/)() | Reads the current element and returns the contents as single-precision floating-point number. |
| virtual [ReadElementContentAsFloat](./readelementcontentasfloat/)(String, String) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a single-precision floating-point number. |
| virtual [ReadElementContentAsInt](./readelementcontentasint/)() | Reads the current element and returns the contents as a 32-bit signed integer. |
| virtual [ReadElementContentAsInt](./readelementcontentasint/)(String, String) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a 32-bit signed integer. |
| virtual [ReadElementContentAsLong](./readelementcontentaslong/)() | Reads the current element and returns the contents as a 64-bit signed integer. |
| virtual [ReadElementContentAsLong](./readelementcontentaslong/)(String, String) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a 64-bit signed integer. |
| virtual [ReadElementContentAsObject](./readelementcontentasobject/)() | Reads the current element and returns the contents as an [Object](../../system/object/). |
| virtual [ReadElementContentAsObject](./readelementcontentasobject/)(String, String) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as an [Object](../../system/object/). |
| virtual [ReadElementContentAsString](./readelementcontentasstring/)() | Reads the current element and returns the contents as a [String](../../system/string/) object. |
| virtual [ReadElementContentAsString](./readelementcontentasstring/)(String, String) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [String](../../system/string/) object. |
| virtual [ReadElementString](./readelementstring/)() | Reads a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [ReadElementString](./readelementstring/)(String) | Checks that the [XmlReader::get_Name](./get_name/) value of the element found matches the given string before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [ReadElementString](./readelementstring/)(String, String) | Checks that the [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values of the element found matches the given strings before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [ReadEndElement](./readendelement/)() | Checks that the current content node is an end tag and advances the reader to the next node. |
| virtual [ReadInnerXml](./readinnerxml/)() | When overridden in a derived class, reads all the content, including markup, as a string. |
| virtual [ReadOuterXml](./readouterxml/)() | When overridden in a derived class, reads the content, including markup, representing this node and all its children. |
| virtual [ReadStartElement](./readstartelement/)() | Checks that the current node is an element and advances the reader to the next node. |
| virtual [ReadStartElement](./readstartelement/)(String) | Checks that the current content node is an element with the given [XmlReader::get_Name](./get_name/) value and advances the reader to the next node. |
| virtual [ReadStartElement](./readstartelement/)(String, String) | Checks that the current content node is an element with the given [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values and advances the reader to the next node. |
| virtual [ReadString](./readstring/)() | When overridden in a derived class, reads the contents of an element or text node as a string. However, it is recommended to use the [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [ReadSubtree](./readsubtree/)() | Returns a new [XmlReader](./) instance that can be used to read the current node, and all its descendants. |
| virtual [ReadToDescendant](./readtodescendant/)(String) | Advances the [XmlReader](./) to the next descendant element with the specified qualified name. |
| virtual [ReadToDescendant](./readtodescendant/)(String, String) | Advances the [XmlReader](./) to the next descendant element with the specified local name and namespace URI. |
| virtual [ReadToFollowing](./readtofollowing/)(String) | Reads until an element with the specified qualified name is found. |
| virtual [ReadToFollowing](./readtofollowing/)(String, String) | Reads until an element with the specified local name and namespace URI is found. |
| virtual [ReadToNextSibling](./readtonextsibling/)(String) | Advances the [XmlReader](./) to the next sibling element with the specified qualified name. |
| virtual [ReadToNextSibling](./readtonextsibling/)(String, String) | Advances the [XmlReader](./) to the next sibling element with the specified local name and namespace URI. |
| virtual [ReadValueChunk](./readvaluechunk/)(ArrayPtr\<char16_t\>, int32_t, int32_t) | Reads large streams of text embedded in an XML document. |
| virtual [ResolveEntity](./resolveentity/)() | When overridden in a derived class, resolves the entity reference for **EntityReference** nodes. |
| virtual [Skip](./skip/)() | Skips the children of the current node. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
