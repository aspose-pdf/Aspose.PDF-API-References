---
title: System::Xml::XmlValidatingReader class
linktitle: XmlValidatingReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlValidatingReader class. Represents a reader that provides document type definition (DTD), XML-Data Reduced (XDR) schema, and XML Schema definition language (XSD) validation in C++.'
type: docs
weight: 4200
url: /cpp/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader class


Represents a reader that provides document type definition (DTD), XML-Data Reduced (XDR) schema, and XML [Schema](../../system.xml.schema/) definition language (XSD) validation.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Changes the [XmlReader::get_ReadState](../xmlreader/get_readstate/) to Closed. |
| [get_AttributeCount](./get_attributecount/)() override | Returns the number of attributes on the current node. |
| [get_BaseURI](./get_baseuri/)() override | Returns the base URI of the current node. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Returns a value indicating whether the [XmlValidatingReader](./) implements the binary content read methods. |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Returns a value indicating whether this reader can parse and resolve entities. |
| [get_Depth](./get_depth/)() override | Returns the depth of the current node in the XML document. |
| [get_Encoding](./get_encoding/)() | Returns the encoding attribute for the document. |
| [get_EntityHandling](./get_entityhandling/)() | Returns a value that specifies how the reader handles entities. |
| [get_EOF](./get_eof/)() override | Returns a value indicating whether the reader is positioned at the end of the stream. |
| [get_HasValue](./get_hasvalue/)() override | Returns a value indicating whether the current node can have a [XmlValidatingReader::get_Value](./get_value/) other than [String::Empty](../../system/string/empty/). |
| [get_IsDefault](./get_isdefault/)() override | Returns a value indicating whether the current node is an attribute that was generated from the default value defined in the document type definition (DTD) or schema. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Returns a value indicating whether the current node is an empty element (for example, **<MyElement/>**). |
| [get_LineNumber](./get_linenumber/)() override | Returns the current line number. |
| [get_LinePosition](./get_lineposition/)() override | Returns the current line position. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the current node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the current node. |
| [get_Namespaces](./get_namespaces/)() | Returns a value indicating whether to do namespace support. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Returns the namespace Uniform Resource Identifier (URI) (as defined in the World Wide [Web](../../system.web/) Consortium (W3C) Namespace specification) of the node on which the reader is positioned. |
| [get_NameTable](./get_nametable/)() override | Returns the [XmlNameTable](../xmlnametable/) associated with this implementation. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_Prefix](./get_prefix/)() override | Returns the namespace prefix associated with the current node. |
| [get_QuoteChar](./get_quotechar/)() override | Returns the quotation mark character used to enclose the value of an attribute node. |
| [get_Reader](./get_reader/)() | Returns the [XmlReader](../xmlreader/) used to construct this [XmlValidatingReader](./). |
| [get_ReadState](./get_readstate/)() override | Returns the state of the reader. |
| [get_Schemas](./get_schemas/)() | Returns a XmlSchemaCollection to use for validation. |
| [get_SchemaType](./get_schematype/)() | Returns a schema type object. |
| [get_ValidationType](./get_validationtype/)() | Returns a value indicating the type of validation to perform. |
| [get_Value](./get_value/)() override | Returns the text value of the current node. |
| [get_XmlLang](./get_xmllang/)() override | Returns the current **xml:lang** scope. |
| [get_XmlSpace](./get_xmlspace/)() override | Returns the current **xml:space** scope. |
| [GetAttribute](./getattribute/)(String) override | Returns the value of the attribute with the specified name. |
| [GetAttribute](./getattribute/)(String, String) override | Returns the value of the attribute with the specified local name and namespace Uniform Resource Identifier (URI). |
| [GetAttribute](./getattribute/)(int32_t) override | Returns the value of the attribute with the specified index. |
| [HasLineInfo](./haslineinfo/)() override | Returns a value indicating whether the class can return line information. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Resolves a namespace prefix in the current element's scope. |
| [MoveToAttribute](./movetoattribute/)(String) override | Moves to the attribute with the specified name. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Moves to the attribute with the specified local name and namespace Uniform Resource Identifier (URI). |
| [MoveToAttribute](./movetoattribute/)(int32_t) override | Moves to the attribute with the specified index. |
| [MoveToElement](./movetoelement/)() override | Moves to the element that contains the current attribute node. |
| [MoveToFirstAttribute](./movetofirstattribute/)() override | Moves to the first attribute. |
| [MoveToNextAttribute](./movetonextattribute/)() override | Moves to the next attribute. |
| [Read](./read/)() override | Reads the next node from the stream. |
| [ReadAttributeValue](./readattributevalue/)() override | Parses the attribute value into one or more **[Text](../../system.text/)**, **EntityReference**, or **EndEntity** nodes. |
| [ReadContentAsBase64](./readcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Reads the content and returns the Base64 decoded binary bytes. |
| [ReadContentAsBinHex](./readcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Reads the content and returns the BinHex decoded binary bytes. |
| [ReadElementContentAsBase64](./readelementcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Reads the element and decodes the Base64 content. |
| [ReadElementContentAsBinHex](./readelementcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Reads the element and decodes the BinHex content. |
| [ReadString](./readstring/)() override | Reads the contents of an element or text node as a string. |
| [ReadTypedValue](./readtypedvalue/)() | Returns the runt-ime type for the specified XML [Schema](../../system.xml.schema/) definition language (XSD) type. |
| [ResolveEntity](./resolveentity/)() override | Resolves the entity reference for **EntityReference** nodes. |
| [set_EntityHandling](./set_entityhandling/)(System::Xml::EntityHandling) | Sets a value that specifies how the reader handles entities. |
| [set_Namespaces](./set_namespaces/)(bool) | Sets a value indicating whether to do namespace support. |
| [set_ValidationType](./set_validationtype/)(System::Xml::ValidationType) | Sets a value indicating the type of validation to perform. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Sets the [XmlResolver](../xmlresolver/) used for resolving external document type definition (DTD) and schema location references. The [XmlResolver](../xmlresolver/) is also used to handle any import or include elements found in XML [Schema](../../system.xml.schema/) definition language (XSD) schemas. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Adds an event handler for receiving information about document type definition (DTD), XML-Data Reduced (XDR) schema, and XML [Schema](../../system.xml.schema/) definition language (XSD) schema validation errors. |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Removes an event handler for receiving information about document type definition (DTD), XML-Data Reduced (XDR) schema, and XML [Schema](../../system.xml.schema/) definition language (XSD) schema validation errors. |
| [XmlValidatingReader](./xmlvalidatingreader/)(const SharedPtr\<XmlReader\>\&) | Initializes a new instance of the [XmlValidatingReader](./) class that validates the content returned from the given [XmlReader](../xmlreader/). |
| [XmlValidatingReader](./xmlvalidatingreader/)(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Initializes a new instance of the [XmlValidatingReader](./) class with the specified values. |
| [XmlValidatingReader](./xmlvalidatingreader/)(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Initializes a new instance of the [XmlValidatingReader](./) class with the specified values. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks


## Deprecated
This class is obsolete. It is recommended to use the XmlReaderSettings class and the XmlReader::Create method to create a validating XML reader. 

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlReader](../xmlreader/)
* Class [IXmlLineInfo](../ixmllineinfo/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
