---
title: System::Xml namespace
linktitle: System::Xml
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Xml namespace in C++.'
type: docs
weight: 8100
url: /cpp/system.xml/
---



## Classes

| Class | Description |
| --- | --- |
| [IApplicationResourceStreamResolver](./iapplicationresourcestreamresolver/) | Represents an application resource stream resolver. |
| [IHasXmlNode](./ihasxmlnode/) | Enables a class to return an [XmlNode](./xmlnode/) from the current context or position. |
| [IXmlLineInfo](./ixmllineinfo/) | Provides an interface to enable a class to return line and position information. |
| [IXmlNamespaceResolver](./ixmlnamespaceresolver/) | Provides read-only access to a set of prefix and namespace mappings. |
| [NameTable](./nametable/) | Implements a single-threaded [XmlNameTable](./xmlnametable/). |
| [XmlAttribute](./xmlattribute/) | Represents an attribute. Valid and default values for the attribute are defined in a document type definition (DTD) or schema. |
| [XmlAttributeCollection](./xmlattributecollection/) | Represents a collection of attributes that can be accessed by name or index. |
| [XmlCDataSection](./xmlcdatasection/) | Represents a CDATA section. |
| [XmlCharacterData](./xmlcharacterdata/) | Provides text manipulation methods that are used by several classes. |
| [XmlCharType](./xmlchartype/) | For internal purposes. Do not use this class directly. |
| [XmlComment](./xmlcomment/) | Represents the content of an XML comment. |
| [XmlConvert](./xmlconvert/) | Encodes and decodes XML names, and provides methods for converting between runtime types and XML [Schema](../system.xml.schema/) definition language (XSD) types. When converting data types, the values returned are locale-independent. |
| [XmlDeclaration](./xmldeclaration/) | Represents the XML declaration node **<?xml version='1.0'...?>**. |
| [XmlDocument](./xmldocument/) | Represents an XML document. You can use this class to load, validate, edit, add, and position XML in a document. |
| [XmlDocumentFragment](./xmldocumentfragment/) | Represents a lightweight object that is useful for tree insert operations. |
| [XmlDocumentType](./xmldocumenttype/) | Represents the document type declaration. |
| [XmlElement](./xmlelement/) | Represents an element. |
| [XmlEntity](./xmlentity/) | Represents an entity declaration, such as **<!ENTITY... >**. |
| [XmlEntityReference](./xmlentityreference/) | Represents an entity reference node. |
| [XmlImplementation](./xmlimplementation/) | Defines the context for a set of [XmlDocument](./xmldocument/) objects. |
| [XmlLinkedNode](./xmllinkednode/) | Returns the node immediately preceding or following this node. |
| [XmlNamedNodeMap](./xmlnamednodemap/) | Represents a collection of nodes that can be accessed by name or index. |
| [XmlNamespaceManager](./xmlnamespacemanager/) | Resolves, adds, and removes namespaces to a collection and provides scope management for these namespaces. |
| [XmlNameTable](./xmlnametable/) | Table of atomized string objects. |
| [XmlNode](./xmlnode/) | Represents a single node in the XML document. |
| [XmlNodeChangedEventArgs](./xmlnodechangedeventargs/) | Provides data for the **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** and **XmlDocument::NodeRemoving** events. |
| [XmlNodeList](./xmlnodelist/) | Represents an ordered collection of nodes. |
| [XmlNodeReader](./xmlnodereader/) | Represents a reader that provides fast, non-cached forward only access to XML data in an [XmlNode](./xmlnode/). |
| [XmlNotation](./xmlnotation/) | Represents a notation declaration, such as **<!NOTATION... >**. |
| [XmlParserContext](./xmlparsercontext/) | Provides all the context information required by the [XmlReader](./xmlreader/) to parse an XML fragment. |
| [XmlProcessingInstruction](./xmlprocessinginstruction/) | Represents a processing instruction, which XML defines to keep processor-specific information in the text of the document. |
| [XmlQualifiedName](./xmlqualifiedname/) | Represents an XML qualified name. |
| [XmlReader](./xmlreader/) | Represents a reader that provides fast, noncached, forward-only access to XML data. |
| [XmlReaderSettings](./xmlreadersettings/) | Specifies a set of features to support on the [XmlReader](./xmlreader/) object created by the [XmlReader::Create](./xmlreader/create/) method. |
| [XmlResolver](./xmlresolver/) | Resolves external XML resources named by a Uniform Resource Identifier (URI). |
| [XmlSecureResolver](./xmlsecureresolver/) | Helps to secure another implementation of [XmlResolver](./xmlresolver/) by wrapping the [XmlResolver](./xmlresolver/) object and restricting the resources that the underlying [XmlResolver](./xmlresolver/) has access to. |
| [XmlSignificantWhitespace](./xmlsignificantwhitespace/) | Represents white space between markup in a mixed content node or white space within an **xml:space='preserve'** scope. This is also referred to as significant white space. |
| [XmlText](./xmltext/) | Represents the text content of an element or attribute. |
| [XmlTextReader](./xmltextreader/) | Represents a reader that provides fast, non-cached, forward-only access to XML data. |
| [XmlTextWriter](./xmltextwriter/) | Represents a writer that provides a fast, non-cached, forward-only way of generating streams or files containing XML data that conforms to the W3C Extensible Markup Language (XML) 1.0 and the Namespaces in XML recommendations. |
| [XmlUrlResolver](./xmlurlresolver/) | Resolves external XML resources named by a Uniform Resource Identifier (URI). |
| [XmlValidatingReader](./xmlvalidatingreader/) | Represents a reader that provides document type definition (DTD), XML-Data Reduced (XDR) schema, and XML [Schema](../system.xml.schema/) definition language (XSD) validation. |
| [XmlWhitespace](./xmlwhitespace/) | Represents white space in element content. |
| [XmlWriter](./xmlwriter/) | Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data. |
| [XmlWriterSettings](./xmlwritersettings/) | Specifies a set of features to support on the [XmlWriter](./xmlwriter/) object created by the [XmlWriter::Create](./xmlwriter/create/) method. |
## Enums

| Enum | Description |
| --- | --- |
| [ConformanceLevel](./conformancelevel/) | Specifies the amount of input or output checking that [XmlReader](./xmlreader/) and [XmlWriter](./xmlwriter/) objects perform. |
| [DtdProcessing](./dtdprocessing/) | Specifies the options for processing DTDs. The [DtdProcessing](./dtdprocessing/) enumeration is used by the [XmlReaderSettings](./xmlreadersettings/) class. |
| [EntityHandling](./entityhandling/) | Specifies how the [XmlTextReader](./xmltextreader/) or [XmlValidatingReader](./xmlvalidatingreader/) handle entities. |
| [ExceptionType](./exceptiontype/) |  |
| [Formatting](./formatting/) | Specifies formatting options for the [XmlTextWriter](./xmltextwriter/). |
| [NamespaceHandling](./namespacehandling/) | Specifies whether to remove duplicate namespace declarations in the [XmlWriter](./xmlwriter/). |
| [NewLineHandling](./newlinehandling/) | Specifies how to handle line breaks. |
| [ReadState](./readstate/) | Specifies the state of the reader. |
| [TriState](./tristate/) |  |
| [ValidationType](./validationtype/) | Specifies the type of validation to perform. |
| [WhitespaceHandling](./whitespacehandling/) | Specifies how white space is handled. |
| [WriteState](./writestate/) | Specifies the state of the [XmlWriter](./xmlwriter/). |
| [XmlDateTimeSerializationMode](./xmldatetimeserializationmode/) | Specifies how to treat the time value when converting between string and [DateTime](../system/datetime/). |
| [XmlNamespaceScope](./xmlnamespacescope/) | Defines the namespace scope. |
| [XmlNodeChangedAction](./xmlnodechangedaction/) | Specifies the type of node change. |
| [XmlNodeOrder](./xmlnodeorder/) | Describes the document order of a node compared to a second node. |
| [XmlNodeType](./xmlnodetype/) | Specifies the type of node. |
| [XmlOutputMethod](./xmloutputmethod/) | Specifies the method used to serialize the [XmlWriter](./xmlwriter/) output. |
| [XmlSpace](./xmlspace/) | Specifies the current **xml:space** scope. |
| [XmlStandalone](./xmlstandalone/) |  |
| [XmlTokenizedType](./xmltokenizedtype/) | Represents the XML type for the string. This allows the string to be read as a particular XML type, for example a CDATA section type. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [XmlException](./xmlexception/) |  |
| [XmlNodeChangedEventHandler](./xmlnodechangedeventhandler/) | Represents the method that handles **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** and **XmlDocument::NodeRemoving** events. |
## Functions

| Function | Description |
| --- | --- |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
