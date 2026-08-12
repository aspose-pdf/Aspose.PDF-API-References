---
title: "inStream"
linktitle: "SharedPtr\\<IO::Stream\\>"
second_title: "Aspose.PDF för C++ API-referens"
description: "Strömmen som innehåller XML-dokumentet som ska laddas."
type: docs
weight: 3400
url: /sv/cpp/system.xml/xmldocument/load/
---
## XmlDocument::Load(SharedPtr\<IO::Stream\>) method


Läser in XML-dokumentet från den angivna strömmen.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| txtReader | SharedPtr\<IO::TextReader\> | TextReader‑objektet som används för att mata XML‑data in i dokumentet. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::Load(SharedPtr\<IO::TextReader\>) method


Läser in XML-dokumentet från den angivna TextReader.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Laddar XML-dokumentet från den angivna [XmlReader](../../xmlreader/). | [XmlReader](../../xmlreader/)-objektet som används för att mata XML‑data in i dokumentet. | TextReader som används för att mata XML-data i dokumentet. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::Load(SharedPtr\<XmlReader\>) method


Läser in XML-dokumentet från den angivna [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| reader | SharedPtr\<XmlReader\> | [XmlReader](../../xmlreader/) som används för att mata XML-data i dokumentet. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::Load(String) method


Läser in XML-dokumentet från den angivna URL:en.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | String | URL för filen som innehåller XML-dokumentet som ska läsas in. URL:en kan vara antingen en lokal fil eller en HTTP-URL (en [Web](../../../system.web/) adress). |

## Se även

* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
