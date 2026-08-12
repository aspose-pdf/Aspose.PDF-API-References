---
title: "System::Xml::XmlNodeChangedEventArgs::get_NewParent method"
linktitle: "get_NewParent"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeChangedEventArgs::get_NewParent method. Возвращает значение XmlNode::get_ParentNode после завершения операции в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent method


Возвращает значение [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) после завершения операции.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### ReturnValue

Значение **ParentNode** после завершения операции. Этот метод возвращает **nullptr**, если узел удаляется. Для узлов‑атрибутов этот метод возвращает значение [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
