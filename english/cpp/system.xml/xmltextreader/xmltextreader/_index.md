---
title: System::Xml::XmlTextReader::XmlTextReader constructor
linktitle: XmlTextReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextReader::XmlTextReader constructor. Initializes a new instance of the XmlTextReader class with the specified stream in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified stream.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | The stream containing the XML data to read. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified stream and [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | The stream containing the XML data to read. |
| nt | const SharedPtr\<XmlNameTable\>\& | The [XmlNameTable](../../xmlnametable/) to use. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified stream, [XmlNodeType](../../xmlnodetype/), and [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const SharedPtr\<IO::Stream\>\& | The stream containing the XML fragment to parse. |
| fragType | XmlNodeType | The [XmlNodeType](../../xmlnodetype/) of the XML fragment. This also determines what the fragment can contain. |
| context | const SharedPtr\<XmlParserContext\>\& | The [XmlParserContext](../../xmlparsercontext/) in which the **xmlFragment** is to be parsed. This includes the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang**, and the **xml:space** scope. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | The TextReader containing the XML data to read. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified TextReader and [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | The TextReader containing the XML data to read. |
| nt | const SharedPtr\<XmlNameTable\>\& | The [XmlNameTable](../../xmlnametable/) to use. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified file.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


| Parameter | Type | Description |
| --- | --- | --- |
| url | const String\& | The URL for the file containing the XML data. The [XmlTextReader::get_BaseURI](../get_baseuri/) is set to this value. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified URL and stream.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| url | const String\& | The URL to use for resolving external resources. The [XmlTextReader::get_BaseURI](../get_baseuri/) is set to this value. |
| input | const SharedPtr\<IO::Stream\>\& | The stream containing the XML data to read. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified URL, stream and [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parameter | Type | Description |
| --- | --- | --- |
| url | const String\& | The URL to use for resolving external resources. The [XmlTextReader::get_BaseURI](../get_baseuri/) is set to this value. If **url** is **nullptr**, **BaseURI** is set to [String::Empty](../../../system/string/empty/). |
| input | const SharedPtr\<IO::Stream\>\& | The stream containing the XML data to read. |
| nt | const SharedPtr\<XmlNameTable\>\& | The [XmlNameTable](../../xmlnametable/) to use. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified URL and TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| url | const String\& | The URL to use for resolving external resources. The [XmlTextReader::get_BaseURI](../get_baseuri/) is set to this value. |
| input | const SharedPtr\<IO::TextReader\>\& | The TextReader containing the XML data to read. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified URL, TextReader and [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parameter | Type | Description |
| --- | --- | --- |
| url | const String\& | The URL to use for resolving external resources. The [XmlTextReader::get_BaseURI](../get_baseuri/) is set to this value. If **url** is **nullptr**, **BaseURI** is set to [String::Empty](../../../system/string/empty/). |
| input | const SharedPtr\<IO::TextReader\>\& | The TextReader containing the XML data to read. |
| nt | const SharedPtr\<XmlNameTable\>\& | The [XmlNameTable](../../xmlnametable/) to use. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified file and [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


| Parameter | Type | Description |
| --- | --- | --- |
| url | const String\& | The URL for the file containing the XML data to read. |
| nt | const SharedPtr\<XmlNameTable\>\& | The [XmlNameTable](../../xmlnametable/) to use. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified string, [XmlNodeType](../../xmlnodetype/), and [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const String\& | The string containing the XML fragment to parse. |
| fragType | XmlNodeType | The [XmlNodeType](../../xmlnodetype/) of the XML fragment. This also determines what the fragment string can contain. |
| context | const SharedPtr\<XmlParserContext\>\& | The [XmlParserContext](../../xmlparsercontext/) in which the **xmlFragment** is to be parsed. This includes the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang**, and the **xml:space** scope. |

## See Also

* Class [String](../../../system/string/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
