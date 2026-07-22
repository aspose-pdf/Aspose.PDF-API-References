---
title: "System::Xml::XmlNode::Supports metod"
linktitle: "Supports"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNode::Supports metod. Testar om DOM-implementationen implementerar en specifik funktion i C++."
type: docs
weight: 4400
url: /sv/cpp/system.xml/xmlnode/supports/
---
## XmlNode::Supports method


Testar om DOM‑implementeringen implementerar en specifik funktion.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| funktion | String | Paketnamnet för funktionen som ska testas. Detta namn är inte skiftlägeskänsligt. |
| version | String | Versionsnumret för paketnamnet som ska testas. Om versionen inte är specificerad (null) innebär stöd för någon version av funktionen att metoden returnerar true. |

### ReturnValue

**true** if the feature is implemented in the specified version; otherwise, **false**.
## Anmärkningar



Följande tabell beskriver kombinationerna som returnerar **true**. |||
|-|-|
| Funktion | Version |
| XML | 1.0 |
| XML | 2.0 |

## Se även

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
