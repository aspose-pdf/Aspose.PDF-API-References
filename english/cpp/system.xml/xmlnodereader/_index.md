---
title: System::Xml::XmlNodeReader class
linktitle: XmlNodeReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeReader class. Represents a reader that provides fast, non-cached forward only access to XML data in an XmlNode in C++.'
type: docs
weight: 2800
url: /cpp/system.xml/xmlnodereader/
---
## XmlNodeReader class


Represents a reader that provides fast, non-cached forward only access to XML data in an [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Changes the [XmlNodeReader::get_ReadState](./get_readstate/) to [ReadState::Closed](../readstate/). |
| [get_AttributeCount](./get_attributecount/)() override | Returns the number of attributes on the current node. |
| [get_BaseURI](./get_baseuri/)() override | Returns the base URI of the current node. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Returns a value indicating whether the [XmlNodeReader](./) implements the binary content read methods. |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Returns a value indicating whether this reader can parse and resolve entities. |
| [get_Depth](./get_depth/)() override | Returns the depth of the current node in the XML document. |
| [get_EOF](./get_eof/)() override | Returns a value indicating whether the reader is positioned at the end of the stream. |
| [get_HasAttributes](./get_hasattributes/)() override | Returns a value indicating whether the current node has any attributes. |
| [get_HasValue](./get_hasvalue/)() override | Returns a value indicating whether the current node can have a [XmlNodeReader::get_Value](./get_value/) value. |
| [get_IsDefault](./get_isdefault/)() override | Returns a value indicating whether the current node is an attribute that was generated from the default value defined in the document type definition (DTD) or schema. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Returns a value indicating whether the current node is an empty element (for example, **<MyElement/>**). |
| [get_LocalName](./get_localname/)() override | Returns the local name of the current node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the current node. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Returns the namespace URI (as defined in the W3C Namespace specification) of the node on which the reader is positioned. |
| [get_NameTable](./get_nametable/)() override | Returns the [XmlNameTable](../xmlnametable/) associated with this implementation. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_Prefix](./get_prefix/)() override | Returns the namespace prefix associated with the current node. |
| [get_ReadState](./get_readstate/)() override | Returns the state of the reader. |
| [get_SchemaInfo](./get_schemainfo/)() override | Returns the schema information that has been assigned to the current node. |
| [get_Value](./get_value/)() override | Returns the text value of the current node. |
| [get_XmlLang](./get_xmllang/)() override | Returns the current **xml:lang** scope. |
| [get_XmlSpace](./get_xmlspace/)() override | Returns the current **xml:space** scope. |
| [GetAttribute](./getattribute/)(String) override | Returns the value of the attribute with the specified name. |
| [GetAttribute](./getattribute/)(String, String) override | Returns the value of the attribute with the specified local name and namespace URI. |
| [GetAttribute](./getattribute/)(int32_t) override | Returns the value of the attribute with the specified index. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Resolves a namespace prefix in the current element's scope. |
| [MoveToAttribute](./movetoattribute/)(String) override | Moves to the attribute with the specified name. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Moves to the attribute with the specified local name and namespace URI. |
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
| [ResolveEntity](./resolveentity/)() override | Resolves the entity reference for **EntityReference** nodes. |
| [Skip](./skip/)() override | Skips the children of the current node. |
| [XmlNodeReader](./xmlnodereader/)(const SharedPtr\<XmlNode\>\&) | Creates an instance of the [XmlNodeReader](./) class using the specified [XmlNode](../xmlnode/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlReader](../xmlreader/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
