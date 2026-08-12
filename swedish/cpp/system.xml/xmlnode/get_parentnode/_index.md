---
title: "System::Xml::XmlNode::get_ParentNode metod"
linktitle: "get_ParentNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNode::get_ParentNode metod. Returnerar föräldern till denna nod (för noder som kan ha föräldrar) i C++."
type: docs
weight: 2100
url: /sv/cpp/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode method


Returnerar föräldern till denna nod (för noder som kan ha föräldrar).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### ReturnValue

Den [XmlNode](../) som är föräldern till den aktuella noden.
## Anmärkningar



Om en nod precis har skapats och ännu inte har lagts till i trädet, eller om den har tagits bort från trädet, är föräldern **nullptr**. För alla andra noder beror det returnerade värdet på [XmlNode::get_NodeType](../get_nodetype/) för noden. Följande tabell beskriver de möjliga returvärdena för **get_NodeType**‑metoden. |||
|-|-|
| NodeType | Returvärde för ParentNode |
| Attribut, Dokument, Dokumentfragment, Entitet, Notation | Returnerar **nullptr**; dessa noder har inga föräldrar. |
| CDATA | Returnerar elementet eller entitetsreferensen som innehåller CDATA-sektionen. |
| Comment | Returnerar elementet, entitetsreferensen, dokumenttypen eller dokumentet som innehåller kommentaren. |
| DocumentType | Returnerar dokumentnoden. |
| Element | Returnerar föräldranoden för elementet. Om elementet är rotknoden i trädet är föräldern dokumentnoden. |
| EntityReference | Returnerar elementet, attributet eller enhetreferensen som innehåller enhetreferensen. |
| ProcessingInstruction | Returnerar dokumentet, elementet, dokumenttypen eller enhetreferensen som innehåller bearbetningsinstruktionen. |
| Text | Returnerar förälderelementet, attributet eller enhetreferensen som innehåller textnoden. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
