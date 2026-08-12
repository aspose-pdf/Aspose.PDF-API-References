---
title: "System::Xml::XmlImplementation::HasFeature metod"
linktitle: "HasFeature"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlImplementation::HasFeature metod. Testar om Document Object Model (DOM)-implementeringen implementerar en specifik funktion i C++."
type: docs
weight: 300
url: /sv/cpp/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature method


Testar om Document [Object](../../../system/object/) Model (DOM)-implementeringen implementerar en specifik funktion.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strFeature | const String\& | Paketnamnet för funktionen som ska testas. Detta namn är inte skiftlägeskänsligt. |
| strVersion | const String\& | Detta är versionsnumret för paketnamnet som ska testas. Om versionen inte är specificerad (**nullptr**), innebär stöd för vilken version som helst av funktionen att metoden returnerar **true**. |

### ReturnValue

**true** if the feature is implemented in the specified version; otherwise, **false**.
## Anmärkningar



Följande tabell visar kombinationerna som får **HasFeature** att returnera **true**. |||
|-|-|
| strFeature | strVersion |
| XML | 1.0 |
| XML | 2.0 |

## Se även

* Class [String](../../../system/string/)
* Class [XmlImplementation](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
