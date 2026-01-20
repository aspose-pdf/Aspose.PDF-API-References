---
title: System::Xml::XmlTextWriter::XmlTextWriter constructor
linktitle: XmlTextWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextWriter::XmlTextWriter constructor. Creates an instance of the XmlTextWriter class using the specified stream and encoding in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Creates an instance of the [XmlTextWriter](../) class using the specified stream and encoding.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| w | const SharedPtr\<IO::Stream\>\& | The stream to which you want to write. |
| encoding | const SharedPtr\<Text::Encoding\>\& | The encoding to generate. If encoding is **nullptr** it writes out the stream as UTF-8 and omits the encoding attribute from the **ProcessingInstruction**. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor


Creates an instance of the [XmlTextWriter](../) class using the specified TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


| Parameter | Type | Description |
| --- | --- | --- |
| w | const SharedPtr\<IO::TextWriter\>\& | The TextWriter to write to. It is assumed that the TextWriter is already set to the correct encoding. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor


Creates an instance of the [XmlTextWriter](../) class using the specified file.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const String\& | The filename to write to. If the file exists, it truncates it and overwrites it with the new content. |
| encoding | const SharedPtr\<Text::Encoding\>\& | The encoding to generate. If encoding is **nullptr** it writes the file out as UTF-8 and omits the encoding attribute from the **ProcessingInstruction**. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
