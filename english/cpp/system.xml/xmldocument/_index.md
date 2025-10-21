---
title: System::Xml::XmlDocument class
linktitle: XmlDocument
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDocument class. Represents an XML document. You can use this class to load, validate, edit, add, and position XML in a document in C++.'
type: docs
weight: 1400
url: /cpp/system.xml/xmldocument/
---
## XmlDocument class


Represents an XML document. You can use this class to load, validate, edit, add, and position XML in a document.

```cpp
class XmlDocument : public System::Xml::XmlNode
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| [CreateAttribute](./createattribute/)(const String\&) | Creates an [XmlAttribute](../xmlattribute/) with the specified name. |
| [CreateAttribute](./createattribute/)(const String\&, const String\&) | Creates an [XmlAttribute](../xmlattribute/) with the specified qualified name and [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateAttribute](./createattribute/)(const String\&, const String\&, const String\&) | Creates an [XmlAttribute](../xmlattribute/) with the specified [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_LocalName](./get_localname/), and [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateCDataSection](./createcdatasection/)(const String\&) | Creates an [XmlCDataSection](../xmlcdatasection/) containing the specified data. |
| virtual [CreateComment](./createcomment/)(const String\&) | Creates an [XmlComment](../xmlcomment/) containing the specified data. |
| virtual [CreateDocumentFragment](./createdocumentfragment/)() | Creates an [XmlDocumentFragment](../xmldocumentfragment/). |
| virtual [CreateDocumentType](./createdocumenttype/)(const String\&, const String\&, const String\&, const String\&) | Returns a new [XmlDocumentType](../xmldocumenttype/) object. |
| [CreateElement](./createelement/)(const String\&) | Creates an element with the specified name. |
| [CreateElement](./createelement/)(const String\&, const String\&) | Creates an [XmlElement](../xmlelement/) with the qualified name and [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateElement](./createelement/)(const String\&, const String\&, const String\&) | Creates an element with the specified [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_LocalName](./get_localname/), and [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateEntityReference](./createentityreference/)(const String\&) | Creates an [XmlEntityReference](../xmlentityreference/) with the specified name. |
| [CreateNavigator](./createnavigator/)() override | Creates a new XPathNavigator object for navigating this document. |
| virtual [CreateNode](./createnode/)(XmlNodeType, const String\&, const String\&, const String\&) | Creates a [XmlNode](../xmlnode/) with the specified [XmlNodeType](../xmlnodetype/), [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_Name](./get_name/), and [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateNode](./createnode/)(const String\&, const String\&, const String\&) | Creates an [XmlNode](../xmlnode/) with the specified node type, [XmlDocument::get_Name](./get_name/), and [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateNode](./createnode/)(XmlNodeType, const String\&, const String\&) | Creates an [XmlNode](../xmlnode/) with the specified [XmlNodeType](../xmlnodetype/), [XmlDocument::get_Name](./get_name/), and [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateProcessingInstruction](./createprocessinginstruction/)(const String\&, const String\&) | Creates an [XmlProcessingInstruction](../xmlprocessinginstruction/) with the specified name and data. |
| virtual [CreateSignificantWhitespace](./createsignificantwhitespace/)(const String\&) | Creates an [XmlSignificantWhitespace](../xmlsignificantwhitespace/) node. |
| virtual [CreateTextNode](./createtextnode/)(const String\&) | Creates an [XmlText](../xmltext/) with the specified text. |
| virtual [CreateWhitespace](./createwhitespace/)(const String\&) | Creates an [XmlWhitespace](../xmlwhitespace/) node. |
| virtual [CreateXmlDeclaration](./createxmldeclaration/)(const String\&, const String\&, const String\&) | Creates an [XmlDeclaration](../xmldeclaration/) node with the specified values. |
| [get_BaseURI](./get_baseuri/)() override | Returns the base URI of the current node. |
| [get_DocumentElement](./get_documentelement/)() | Returns the root [XmlElement](../xmlelement/) for the document. |
| virtual [get_DocumentType](./get_documenttype/)() | Returns the node containing the DOCTYPE declaration. |
| [get_Implementation](./get_implementation/)() | Returns the [XmlImplementation](../xmlimplementation/) object for the current document. |
| [get_InnerXml](./get_innerxml/)() override | Returns the markup representing the children of the current node. |
| [get_IsReadOnly](./get_isreadonly/)() override | Returns a value indicating whether the current node is read-only. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the node. |
| [get_NameTable](./get_nametable/)() | Returns the [XmlNameTable](../xmlnametable/) associated with this implementation. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Returns the [XmlDocument](./) to which the current node belongs. |
| [get_PreserveWhitespace](./get_preservewhitespace/)() | Returns a value indicating whether to preserve white space in element content. |
| [get_SchemaInfo](./get_schemainfo/)() override | Returns the Post-Schema-Validation-Infoset (PSVI) of the node. |
| [get_Schemas](./get_schemas/)() | Returns the XmlSchemaSet object associated with this [XmlDocument](./). |
| virtual [GetElementById](./getelementbyid/)(String) | Returns the [XmlElement](../xmlelement/) with the specified ID. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String) | Returns an [XmlNodeList](../xmlnodelist/) containing a list of all descendant elements that match the specified name. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String, String) | Returns an [XmlNodeList](../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlDocument::get_LocalName](./get_localname/) and [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [ImportNode](./importnode/)(SharedPtr\<XmlNode\>, bool) | Imports a node from another document to the current document. |
| virtual [Load](./load/)(String) | Loads the XML document from the specified URL. |
| virtual [Load](./load/)(SharedPtr\<IO::Stream\>) | Loads the XML document from the specified stream. |
| virtual [Load](./load/)(SharedPtr\<IO::TextReader\>) | Loads the XML document from the specified TextReader. |
| virtual [Load](./load/)(SharedPtr\<XmlReader\>) | Loads the XML document from the specified [XmlReader](../xmlreader/). |
| virtual [LoadXml](./loadxml/)(String) | Loads the XML document from the specified string. |
| virtual [ReadNode](./readnode/)(SharedPtr\<XmlReader\>) | Creates an [XmlNode](../xmlnode/) object based on the information in the [XmlReader](../xmlreader/). The reader must be positioned on a node or attribute. |
| virtual [Save](./save/)(String) | Saves the XML document to the specified file. If the specified file exists, this method overwrites it. |
| virtual [Save](./save/)(SharedPtr\<IO::Stream\>) | Saves the XML document to the specified stream. |
| virtual [Save](./save/)(SharedPtr\<IO::TextWriter\>) | Saves the XML document to the specified TextWriter. |
| virtual [Save](./save/)(SharedPtr\<XmlWriter\>) | Saves the XML document to the specified [XmlWriter](../xmlwriter/). |
| [set_InnerText](./set_innertext/)(String) override | Throws an InvalidOperationException in all cases. |
| [set_InnerXml](./set_innerxml/)(String) override | Sets the markup representing the children of the current node. |
| [set_PreserveWhitespace](./set_preservewhitespace/)(bool) | Sets a value indicating whether to preserve white space in element content. |
| [set_Schemas](./set_schemas/)(const SharedPtr\<Schema::XmlSchemaSet\>\&) | Sets the XmlSchemaSet object associated with this [XmlDocument](./). |
| virtual [set_XmlResolver](./set_xmlresolver/)(SharedPtr\<System::Xml::XmlResolver\>) | Sets the [XmlResolver](../xmlresolver/) to use for resolving external resources. |
| [Validate](./validate/)(Schema::ValidationEventHandler) | Validates the [XmlDocument](./) against the XML [Schema](../../system.xml.schema/) Definition Language (XSD) schemas contained in the [XmlDocument::get_Schemas](./get_schemas/) list. |
| [Validate](./validate/)(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) | Validates the [XmlNode](../xmlnode/) object specified against the XML [Schema](../../system.xml.schema/) Definition Language (XSD) schemas in the [XmlDocument::get_Schemas](./get_schemas/) list. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves all the children of the [XmlDocument](./) node to the specified [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Saves the [XmlDocument](./) node to the specified [XmlWriter](../xmlwriter/). |
| [XmlDocument](./xmldocument/)() | Initializes a new instance of the [XmlDocument](./) class. |
| [XmlDocument](./xmldocument/)(const SharedPtr\<XmlNameTable\>\&) | Initializes a new instance of the [XmlDocument](./) class with the specified [XmlNameTable](../xmlnametable/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
