---
title: System::Xml::XmlWriter::WriteStartElement method
linktitle: WriteStartElement
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlWriter::WriteStartElement method. When overridden in a derived class, writes out a start tag with the specified local name in C++.'
type: docs
weight: 3200
url: /cpp/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&) method


When overridden in a derived class, writes out a start tag with the specified local name.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | const String\& | The local name of the element. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteStartElement(const String\&, const String\&) method


When overridden in a derived class, writes the specified start tag and associates it with the given namespace.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | const String\& | The local name of the element. |
| ns | const String\& | The namespace URI to associate with the element. If this namespace is already in scope and has an associated prefix, the writer automatically writes that prefix also. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) method


When overridden in a derived class, writes the specified start tag and associates it with the given namespace and prefix.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const String\& | The namespace prefix of the element. |
| localName | const String\& | The local name of the element. |
| ns | const String\& | The namespace URI to associate with the element. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
