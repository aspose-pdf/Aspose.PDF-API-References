---
title: "System::Xml::XmlNodeChangedEventArgs::get_NewParent método"
linktitle: "get_NewParent"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNodeChangedEventArgs::get_NewParent método. Devuelve el valor de XmlNode::get_ParentNode después de que la operación se complete en C++."
type: docs
weight: 300
url: /es/cpp/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent method


Devuelve el valor de [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) después de que la operación se complete.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### ReturnValue

El valor de **ParentNode** después de que la operación se complete. Este método devuelve **nullptr** si el nodo está siendo eliminado. Para nodos de atributo, este método devuelve el valor de [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
