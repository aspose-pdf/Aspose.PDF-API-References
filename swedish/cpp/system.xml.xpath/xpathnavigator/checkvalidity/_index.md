---
title: "System::Xml::XPath::XPathNavigator::CheckValidity metod"
linktitle: "CheckValidity"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::CheckValidity‑metod. Verifierar att XML‑data i XPathNavigator följer XML‑Schema‑definitionsspråket (XSD)‑schemat som tillhandahålls i C++."
type: docs
weight: 300
url: /sv/cpp/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity method


Verifierar att XML‑data i [XPathNavigator](../) följer XML‑[Schema](../../../system.xml.schema/)‑definitionsspråket (XSD)‑schemat som tillhandahålls.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schemas | SharedPtr\<System::Xml::Schema::XmlSchemaSet\> | XmlSchemaSet‑uppsättningen som innehåller scheman som används för att validera XML‑data som finns i [XPathNavigator](../). |
| validationEventHandler | System::Xml::Schema::ValidationEventHandler | ValidationEventHandler‑en som tar emot information om varningar och fel vid schemavalidering. |

### ReturnValue

**true** if no schema validation errors occurred; otherwise, **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
