---
title: System::Xml::XmlReader::Create method
linktitle: Create
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::Create method. Creates a new XmlReader instance using the specified stream with default settings in C++.'
type: docs
weight: 7700
url: /cpp/system.xml/xmlreader/create/
---
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) method


Creates a new [XmlReader](../) instance using the specified stream with default settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) method


Creates a new [XmlReader](../) instance with the specified stream and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |
| settings | const SharedPtr\<XmlReaderSettings\>\& | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Creates a new [XmlReader](../) instance using the specified stream, settings, and context information for parsing.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |
| settings | SharedPtr\<XmlReaderSettings\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | The context information required to parse the XML fragment. The context information can include the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang** and **xml:space** scope, base URI, and document type definition. This value can be **nullptr**. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method


Creates a new [XmlReader](../) instance using the specified stream, base URI, and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |
| settings | SharedPtr\<XmlReaderSettings\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| baseUri | const String\& | The base URI for the entity or document being read. This value can be **nullptr**. **[Security](../../../system.security/) Note** The base URI is used to resolve the relative URI of the XML document. Do not use a base URI from an untrusted source. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) method


Creates a new [XmlReader](../) instance by using the specified text reader.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration is not used by the XML reader to decode the data stream. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) method


Creates a new [XmlReader](../) instance by using the specified text reader and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration isn't used by the XML reader to decode the data stream. |
| settings | const SharedPtr\<XmlReaderSettings\>\& | The settings for the new [XmlReader](../). This value can be **nullptr**. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Creates a new [XmlReader](../) instance by using the specified text reader, settings, and context information for parsing.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration isn't used by the XML reader to decode the data stream. |
| settings | SharedPtr\<XmlReaderSettings\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | The context information required to parse the XML fragment. The context information can include the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang** and **xml:space** scope, base URI, and document type definition. This value can be **nullptr**. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method


Creates a new [XmlReader](../) instance by using the specified text reader, settings, and base URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration isn't used by the [XmlReader](../) to decode the data stream. |
| settings | SharedPtr\<XmlReaderSettings\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| baseUri | const String\& | The base URI for the entity or document being read. This value can be **nullptr**. **[Security](../../../system.security/) Note** The base URI is used to resolve the relative URI of the XML document. Do not use a base URI from an untrusted source. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) method


Creates a new [XmlReader](../) instance by using the specified XML reader and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| reader | const SharedPtr\<XmlReader\>\& | The object that you want to use as the underlying XML reader. |
| settings | SharedPtr\<XmlReaderSettings\> | The settings for the new [XmlReader](../) instance. The conformance level of the [XmlReaderSettings](../../xmlreadersettings/) object must either match the conformance level of the underlying reader, or it must be set to [ConformanceLevel::Auto](../../conformancelevel/). |

### ReturnValue

An object that is wrapped around the specified [XmlReader](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&) method


Creates a new [XmlReader](../) instance with specified URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const String\& | The URI for the file that contains the XML data. The [XmlUrlResolver](../../xmlurlresolver/) class is used to convert the path to a canonical data representation. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) method


Creates a new [XmlReader](../) instance by using the specified URI and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const String\& | The URI for the file containing the XML data. The [XmlResolver](../../xmlresolver/) object on the [XmlReaderSettings](../../xmlreadersettings/) object is used to convert the path to a canonical data representation. If XmlReaderSettings::get_XmlResolver value is **nullptr**, a new [XmlUrlResolver](../../xmlurlresolver/) object is used. |
| settings | const SharedPtr\<XmlReaderSettings\>\& | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Creates a new [XmlReader](../) instance by using the specified URI, settings, and context information for parsing.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const String\& | The URI for the file containing the XML data. The [XmlResolver](../../xmlresolver/) object on the [XmlReaderSettings](../../xmlreadersettings/) object is used to convert the path to a canonical data representation. If XmlReaderSettings::get_XmlResolver value is **nullptr**, a new [XmlUrlResolver](../../xmlurlresolver/) object is used. |
| settings | SharedPtr\<XmlReaderSettings\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | The context information required to parse the XML fragment. The context information can include the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang** and **xml:space** scope, base URI, and document type definition. This value can be **nullptr**. |

### ReturnValue

An object that is used to read the XML data in the stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
