---
title: "System::Xml::XmlNodeChangedEventArgs::get_OldParent metod"
linktitle: "get_OldParent"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeChangedEventArgs::get_OldParent metod. Returnerar värdet av XmlNode::get_ParentNode innan operationen påbörjades i C++."
type: docs
weight: 600
url: /sv/cpp/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent method


Returnerar värdet av [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) innan operationen påbörjades.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### ReturnValue

Värdet av **ParentNode** innan operationen påbörjades. Denna metod returnerar **nullptr** om noden inte hade någon förälder. För attributnoder returnerar denna metod värdet från [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
