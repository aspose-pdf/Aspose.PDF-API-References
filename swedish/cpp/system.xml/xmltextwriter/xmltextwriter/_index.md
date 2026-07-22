---
title: "System::Xml::XmlTextWriter::XmlTextWriter konstruktor"
linktitle: "XmlTextWriter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextWriter::XmlTextWriter konstruktor. Skapar en instans av XmlTextWriter-klassen med den angivna strömmen och kodningen i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Skapar en instans av klassen [XmlTextWriter](../) med den angivna strömmen och kodningen.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| w | const SharedPtr\<IO::Stream\>\& | Strömmen som du vill skriva till. |
| encoding | const SharedPtr\<Text::Encoding\>\& | Kodningen att generera. Om kodningen är **nullptr** skrivs strömmen ut som UTF-8 och kodningsattributet utelämnas från **ProcessingInstruction**. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor


Skapar en instans av klassen [XmlTextWriter](../) med den angivna TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| w | const SharedPtr\<IO::TextWriter\>\& | TextWriter att skriva till. Det antas att TextWriter redan är inställd på rätt kodning. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor


Skapar en instans av klassen [XmlTextWriter](../) med den angivna filen.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const String\& | Filnamnet att skriva till. Om filen finns trunceras den och skrivs över med det nya innehållet. |
| encoding | const SharedPtr\<Text::Encoding\>\& | Kodningen att generera. Om kodningen är **nullptr** skrivs filen ut som UTF-8 och kodningsattributet utelämnas från **ProcessingInstruction**. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
