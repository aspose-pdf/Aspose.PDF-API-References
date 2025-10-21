---
title: System::Xml::XmlValidatingReader::XmlValidatingReader constructor
linktitle: XmlValidatingReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlValidatingReader::XmlValidatingReader constructor. Initializes a new instance of the XmlValidatingReader class with the specified values in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Initializes a new instance of the [XmlValidatingReader](../) class with the specified values.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const SharedPtr\<IO::Stream\>\& | The stream containing the XML fragment to parse. |
| fragType | XmlNodeType | The [XmlNodeType](../../xmlnodetype/) of the XML fragment. This determines what the fragment can contain (see table below). |
| context | const SharedPtr\<XmlParserContext\>\& | The [XmlParserContext](../../xmlparsercontext/) in which the XML fragment is to be parsed. This includes the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, current **xml:lang**, and **xml:space** scope. |
## Remarks



The following table lists valid values for **fragType** and how the reader parses each of the different node types. |||
|-|-|
|XmlNodeType|Fragment May Contain |
|Element|Any valid element content (for example, any combination of elements, comments, processing instructions, cdata, text, and entity references). |
|Attribute|The value of an attribute (the part inside the quotes). |
|Document|The contents of an entire XML document; this enforces document level rules. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor


Initializes a new instance of the [XmlValidatingReader](../) class that validates the content returned from the given [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


| Parameter | Type | Description |
| --- | --- | --- |
| reader | const SharedPtr\<XmlReader\>\& | The [XmlReader](../../xmlreader/) to read from while validating. The current implementation supports only [XmlTextReader](../../xmltextreader/). |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Initializes a new instance of the [XmlValidatingReader](../) class with the specified values.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const String\& | The string containing the XML fragment to parse. |
| fragType | XmlNodeType | The [XmlNodeType](../../xmlnodetype/) of the XML fragment. This also determines what the fragment string can contain (see table below). |
| context | const SharedPtr\<XmlParserContext\>\& | The [XmlParserContext](../../xmlparsercontext/) in which the XML fragment is to be parsed. This includes the [NameTable](../../nametable/) to use, encoding, namespace scope, current **xml:lang**, and **xml:space** scope. |
## Remarks



The following table lists valid values for **fragType** and how the reader parses each of the different node types. |||
|-|-|
|XmlNodeType|Fragment May Contain |
|Element|Any valid element content (for example, any combination of elements, comments, processing instructions, cdata, text, and entity references). |
|Attribute|The value of an attribute (the part inside the quotes). |
|Document|The contents of an entire XML document; this enforces document level rules. |

## See Also

* Class [String](../../../system/string/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
