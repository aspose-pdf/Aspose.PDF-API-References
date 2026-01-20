---
title: System::Xml::Schema::XmlSchema::Read method
linktitle: Read
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchema::Read method. Reads an XML Schema from the supplied stream in C++.'
type: docs
weight: 2900
url: /cpp/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) method


Reads an XML [Schema](../../) from the supplied stream.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<IO::Stream\>\& | The supplied data stream. |
| validationEventHandler | ValidationEventHandler | The validation event handler that receives information about XML [Schema](../../) syntax errors. |

### ReturnValue

The [XmlSchema](../) object representing the XML [Schema](../../).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [Stream](../../../system.io/stream/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) method


Reads an XML [Schema](../../) from the supplied [IO::TextReader](../../../system.io/textreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| reader | const SharedPtr\<IO::TextReader\>\& | The [IO::TextReader](../../../system.io/textreader/) containing the XML [Schema](../../) to read. |
| validationEventHandler | ValidationEventHandler | The validation event handler that receives information about the XML [Schema](../../) syntax errors. |

### ReturnValue

The [XmlSchema](../) object representing the XML [Schema](../../).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) method


Reads an XML [Schema](../../) from the supplied [XmlReader](../../../system.xml/xmlreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| reader | const SharedPtr\<XmlReader\>\& | The [XmlReader](../../../system.xml/xmlreader/) containing the XML [Schema](../../) to read. |
| validationEventHandler | ValidationEventHandler | The validation event handler that receives information about the XML [Schema](../../) syntax errors. |

### ReturnValue

The [XmlSchema](../) object representing the XML [Schema](../../).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
