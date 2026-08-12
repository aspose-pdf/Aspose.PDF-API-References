---
title: "System::Xml::XmlDocument::CreateXmlDeclaration metod"
linktitle: "CreateXmlDeclaration"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocument::CreateXmlDeclaration metod. Skapar en XmlDeclaration-nod med de angivna värdena i C++."
type: docs
weight: 1600
url: /sv/cpp/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration method


Skapar en [XmlDeclaration](../../xmldeclaration/) nod med de angivna värdena.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| version | const String\& | Versionen måste vara \"1.0\". |
| encoding | const String\& | Värdet för kodningsattributet. Detta är den kodning som används när du sparar [XmlDocument](../) till en fil eller en ström; därför måste den sättas till en sträng som stöds av klassen [Text::Encoding](../../../system.text/encoding/), annars misslyckas \"XmlDocument::Save(String)\". Om detta är **nullptr** eller [String::Empty](../../../system/string/empty/), skriver inte metoden [XmlDocument::Save](../save/) ett kodningsattribut i XML-deklarationen och därför används standardkodningen UTF-8. |
| standalone | const String\& | Värdet måste vara antingen \"yes\" eller \"no\". Om detta är **nullptr** eller [String::Empty](../../../system/string/empty/), skriver inte metoden [XmlDocument::Save](../save/) ett standalone-attribut i XML-deklarationen. |

### ReturnValue

Den nya [XmlDeclaration](../../xmldeclaration/) noden.
## Anmärkningar



Obs: Om [XmlDocument](../) sparas till antingen en TextWriter eller en [XmlTextWriter](../../xmltextwriter/), kastas detta kodningsvärde bort. Istället används kodningen för TextWriter eller [XmlTextWriter](../../xmltextwriter/). Detta säkerställer att den utskrivna XML‑en kan läsas tillbaka med korrekt kodning.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDeclaration](../../xmldeclaration/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
