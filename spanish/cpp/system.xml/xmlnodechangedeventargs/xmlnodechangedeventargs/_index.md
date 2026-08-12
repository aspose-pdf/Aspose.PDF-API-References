---
title: "Constructor System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs"
linktitle: "XmlNodeChangedEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs. Inicializa una nueva instancia de la clase XmlNodeChangedEventArgs en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs constructor


Inicializa una nueva instancia de la clase [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | const SharedPtr\<XmlNode\>\& | El [XmlNode](../../xmlnode/) que generó el evento. |
| oldParent | const SharedPtr\<XmlNode\>\& | El antiguo nodo padre [XmlNode](../../xmlnode/) del [XmlNode](../../xmlnode/) que generó el evento. |
| newParent | const SharedPtr\<XmlNode\>\& | El nuevo nodo padre [XmlNode](../../xmlnode/) del [XmlNode](../../xmlnode/) que generó el evento. |
| oldValue | const String\& | El valor antiguo del [XmlNode](../../xmlnode/) que generó el evento. |
| newValue | const String\& | El valor nuevo del [XmlNode](../../xmlnode/) que generó el evento. |
| action | XmlNodeChangedAction | El [XmlNodeChangedAction](../../xmlnodechangedaction/). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
