---
title: "System::Xml::XmlNodeChangedEventArgs::get_OldParent method"
linktitle: "get_OldParent"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeChangedEventArgs::get_OldParent method. Возвращает значение XmlNode::get_ParentNode до начала операции в C++."
type: docs
weight: 600
url: /ru/cpp/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent method


Возвращает значение [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) до начала операции.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### ReturnValue

Значение **ParentNode** до начала операции. Этот метод возвращает **nullptr**, если у узла не было родителя. Для узлов‑атрибутов этот метод возвращает значение [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
