---
title: "System::Xml::XPath::XPathNavigator::AppendChild metod"
linktitle: "AppendChild"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::AppendChild metod. Returnerar ett XmlWriter‑objekt som används för att skapa en eller flera nya barnnoder i slutet av listan över barnnoder för den aktuella noden i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() method


Returnerar ett [XmlWriter](../../../system.xml/xmlwriter/)‑objekt som används för att skapa en eller flera nya barnnoder i slutet av listan över barnnoder för den aktuella noden.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```


### ReturnValue

Ett [XmlWriter](../../../system.xml/xmlwriter/)‑objekt som används för att skapa nya barnnoder i slutet av listan över barnnoder för den aktuella noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) method


Skapar en ny barnnod i slutet av listan över barnnoder för den aktuella noden med XML‑innehållet i det angivna [XmlReader](../../../system.xml/xmlreader/)‑objektet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | SharedPtr\<XmlReader\> | Ett [XmlReader](../../../system.xml/xmlreader/)‑objekt positionerat på XML‑data för den nya barnnoden. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) method


Skapar en ny barnnod i slutet av listan över barnnoder för den aktuella noden med noderna i den angivna [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | SharedPtr\<XPathNavigator\> | Ett [XPathNavigator](../)‑objekt positionerat på noden som ska läggas till som den nya barnnoden. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::AppendChild(String) method


Skapar en ny barnnod i slutet av listan med barnnoder för den aktuella noden med den angivna XML-datasträngen.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | String | XML-datasträngen för den nya barnnoden. |

## Se även

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
