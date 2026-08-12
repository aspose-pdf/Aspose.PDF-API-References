---
title: "System::Xml::XmlReader::ReadElementString metod"
linktitle: "ReadElementString"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::ReadElementString metod. Läser ett element som bara innehåller text. Det rekommenderas dock att använda XmlReader::ReadElementContentAsString metod istället, eftersom den ger ett mer direkt sätt att hantera denna operation i C++."
type: docs
weight: 6400
url: /sv/cpp/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() method


Läser ett element som bara innehåller text. Det rekommenderas dock att använda [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) metod istället, eftersom den ger ett mer direkt sätt att hantera denna operation.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```


### ReturnValue

Texten som finns i det lästa elementet. En tom sträng om elementet är tomt.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementString(String, String) method


Kontrollerar att värdena [XmlReader::get_LocalName](../get_localname/) och [XmlReader::get_NamespaceURI](../get_namespaceuri/) för det hittade elementet matchar de angivna strängarna innan ett element som bara innehåller text läses. Det rekommenderas dock att använda [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) metod istället, eftersom den ger ett mer direkt sätt att hantera denna operation.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lokalnamn | String | Det lokala namnet att kontrollera. |
| ns | String | Namnområdets URI att kontrollera. |

### ReturnValue

Texten som finns i det lästa elementet. En tom sträng om elementet är tomt.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementString(String) method


Kontrollerar att värdet [XmlReader::get_Name](../get_name/) för det hittade elementet matchar den angivna strängen innan ett element som bara innehåller text läses. Det rekommenderas dock att använda [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) metod istället, eftersom den ger ett mer direkt sätt att hantera denna operation.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Namnet att kontrollera. |

### ReturnValue

Texten som finns i det lästa elementet. En tom sträng om elementet är tomt.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
