---
title: "System::Xml::XmlReader::ReadToFollowing metod"
linktitle: "ReadToFollowing"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::ReadToFollowing metod. Läser tills ett element med det angivna lokala namnet och namnrymds-URI-en hittas i C++."
type: docs
weight: 7200
url: /sv/cpp/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String, String) method


Läser tills ett element med det angivna lokala namnet och namnrymds-URI:n hittas.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det lokala namnet på elementet. |
| namespaceURI | String | Namnrymdens URI för elementet. |

### ReturnValue

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadToFollowing(String) method


Läser tills ett element med det angivna kvalificerade namnet hittas.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på elementet. |

### ReturnValue

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
