---
title: "System::Xml::XmlWriter::WriteNode metod"
linktitle: "WriteNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlWriter::WriteNode metod. När den åsidosätts i en avledd klass, kopierar den allt från läsaren till skribenten och flyttar läsaren till början av nästa syskon i C++."
type: docs
weight: 2600
url: /sv/cpp/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) method


När den åsidosätts i en avledd klass kopierar den allt från läsaren till skrivaren och flyttar läsaren till början av nästa syskon.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| reader | SharedPtr\<XmlReader\> | Den [XmlReader](../../xmlreader/) att läsa från. |
| defattr | bool | **true** för att kopiera standardattributen från [XmlReader](../../xmlreader/); annars **false**. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) method


Kopierar allt från XPathNavigator-objektet till skrivaren. Positionen för XPathNavigator förblir oförändrad.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| navigator | SharedPtr\<XPath::XPathNavigator\> | Den XPathNavigator att kopiera från. |
| defattr | bool | **true** för att kopiera standardattributen; annars, **false**. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
