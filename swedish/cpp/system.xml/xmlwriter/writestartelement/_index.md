---
title: "System::Xml::XmlWriter::WriteStartElement metod"
linktitle: "WriteStartElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlWriter::WriteStartElement metod. När den åsidosätts i en avledd klass skriver den ut en starttagg med det angivna lokala namnet i C++."
type: docs
weight: 3200
url: /sv/cpp/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&) method


När den åsidosätts i en avledd klass skriver den ut en starttagg med det angivna lokala namnet.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const String\& | Det lokala namnet på elementet. |

## Se även

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteStartElement(const String\&, const String\&) method


När den åsidosätts i en avledd klass skriver den den angivna starttaggen och associerar den med den givna namnrymden.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const String\& | Det lokala namnet på elementet. |
| ns | const String\& | Namnutrymmet URI att associera med elementet. Om detta namnrymd redan är i scope och har ett associerat prefix skriver skribenten automatiskt även det prefixet. |

## Se även

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) method


När den åsidosätts i en avledd klass skriver den den angivna starttaggen och associerar den med den givna namnrymden och prefixet.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const String\& | Namnrymdsprefixet för elementet. |
| localName | const String\& | Det lokala namnet på elementet. |
| ns | const String\& | Namnutrymmet URI att associera med elementet. |

## Se även

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
