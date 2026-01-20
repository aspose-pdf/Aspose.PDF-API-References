---
title: System::Xml::XmlWriter::Create method
linktitle: Create
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlWriter::Create method. Creates a new XmlWriter instance using the specified stream in C++.'
type: docs
weight: 3700
url: /cpp/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) method


Creates a new [XmlWriter](../) instance using the specified stream.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| output | const SharedPtr\<IO::Stream\>\& | The stream to which you want to write. The [XmlWriter](../) writes XML 1.0 text syntax and appends it to the specified stream. |

### ReturnValue

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) method


Creates a new [XmlWriter](../) instance using the stream and [XmlWriterSettings](../../xmlwritersettings/) object.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| output | const SharedPtr\<IO::Stream\>\& | The stream to which you want to write. The [XmlWriter](../) writes XML 1.0 text syntax and appends it to the specified stream. |
| settings | SharedPtr\<XmlWriterSettings\> | The [XmlWriterSettings](../../xmlwritersettings/) object used to configure the new [XmlWriter](../) instance. If this is **nullptr**, a [XmlWriterSettings](../../xmlwritersettings/) with default settings is used. If the [XmlWriter](../) is being used with the XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) method, you should use the XslCompiledTransform::get_OutputSettings value to obtain an [XmlWriterSettings](../../xmlwritersettings/) object with the correct settings. This ensures that the created [XmlWriter](../) object has the correct output settings. |

### ReturnValue

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) method


Creates a new [XmlWriter](../) instance using the specified TextWriter.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| output | const SharedPtr\<IO::TextWriter\>\& | The TextWriter to which you want to write. The [XmlWriter](../) writes XML 1.0 text syntax and appends it to the specified TextWriter. |

### ReturnValue

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) method


Creates a new [XmlWriter](../) instance using the TextWriter and [XmlWriterSettings](../../xmlwritersettings/) objects.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| output | const SharedPtr\<IO::TextWriter\>\& | The TextWriter to which you want to write. The [XmlWriter](../) writes XML 1.0 text syntax and appends it to the specified TextWriter. |
| settings | SharedPtr\<XmlWriterSettings\> | The [XmlWriterSettings](../../xmlwritersettings/) object used to configure the new [XmlWriter](../) instance. If this is **nullptr**, a [XmlWriterSettings](../../xmlwritersettings/) with default settings is used. If the [XmlWriter](../) is being used with the XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) method, you should use the XslCompiledTransform::get_OutputSettings value to obtain an [XmlWriterSettings](../../xmlwritersettings/) object with the correct settings. This ensures that the created [XmlWriter](../) object has the correct output settings. |

### ReturnValue

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) method


Creates a new [XmlWriter](../) instance using the specified [Text::StringBuilder](../../../system.text/stringbuilder/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| output | const SharedPtr\<Text::StringBuilder\>\& | The [Text::StringBuilder](../../../system.text/stringbuilder/) to which to write to. Content written by the [XmlWriter](../) is appended to the [Text::StringBuilder](../../../system.text/stringbuilder/). |

### ReturnValue

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) method


Creates a new [XmlWriter](../) instance using the [Text::StringBuilder](../../../system.text/stringbuilder/) and [XmlWriterSettings](../../xmlwritersettings/) objects.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| output | const SharedPtr\<Text::StringBuilder\>\& | The [Text::StringBuilder](../../../system.text/stringbuilder/) to which to write to. Content written by the [XmlWriter](../) is appended to the [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | SharedPtr\<XmlWriterSettings\> | The [XmlWriterSettings](../../xmlwritersettings/) object used to configure the new [XmlWriter](../) instance. If this is **nullptr**, a [XmlWriterSettings](../../xmlwritersettings/) with default settings is used. If the [XmlWriter](../) is being used with the XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) method, you should use the XslCompiledTransform::get_OutputSettings value to obtain an [XmlWriterSettings](../../xmlwritersettings/) object with the correct settings. This ensures that the created [XmlWriter](../) object has the correct output settings. |

### ReturnValue

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) method


Creates a new [XmlWriter](../) instance using the specified [XmlWriter](../) object.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| output | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../) object that you want to use as the underlying writer. |

### ReturnValue

An [XmlWriter](../) object that is wrapped around the specified [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) method


Creates a new [XmlWriter](../) instance using the specified [XmlWriter](../) and [XmlWriterSettings](../../xmlwritersettings/) objects.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| output | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../) object that you want to use as the underlying writer. |
| settings | SharedPtr\<XmlWriterSettings\> | The [XmlWriterSettings](../../xmlwritersettings/) object used to configure the new [XmlWriter](../) instance. If this is **nullptr**, a [XmlWriterSettings](../../xmlwritersettings/) with default settings is used. If the [XmlWriter](../) is being used with the XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) method, you should use the XslCompiledTransform::get_OutputSettings value to obtain an [XmlWriterSettings](../../xmlwritersettings/) object with the correct settings. This ensures that the created [XmlWriter](../) object has the correct output settings. |

### ReturnValue

An [XmlWriter](../) object that is wrapped around the specified [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const String\&) method


Creates a new [XmlWriter](../) instance using the specified filename.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const String\& | The file to which you want to write. The [XmlWriter](../) creates a file at the specified path and writes to it in XML 1.0 text syntax. The **outputFileName** must be a file system path. |

### ReturnValue

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) method


Creates a new [XmlWriter](../) instance using the filename and [XmlWriterSettings](../../xmlwritersettings/) object.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const String\& | The file to which you want to write. The [XmlWriter](../) creates a file at the specified path and writes to it in XML 1.0 text syntax. The **outputFileName** must be a file system path. |
| settings | SharedPtr\<XmlWriterSettings\> | The [XmlWriterSettings](../../xmlwritersettings/) object used to configure the new [XmlWriter](../) instance. If this is **nullptr**, a [XmlWriterSettings](../../xmlwritersettings/) with default settings is used. If the [XmlWriter](../) is being used with the XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) method, you should use the XslCompiledTransform::get_OutputSettings value to obtain an [XmlWriterSettings](../../xmlwritersettings/) object with the correct settings. This ensures that the created [XmlWriter](../) object has the correct output settings. |

### ReturnValue

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
