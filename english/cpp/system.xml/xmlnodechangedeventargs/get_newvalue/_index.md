---
title: System::Xml::XmlNodeChangedEventArgs::get_NewValue method
linktitle: get_NewValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeChangedEventArgs::get_NewValue method. Returns the new value of the node in C++.'
type: docs
weight: 400
url: /cpp/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue method


Returns the new value of the node.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### ReturnValue

The new value of the node. This method returns **nullptr** if the node is neither an attribute nor a text node, or if the node is being removed. If called in a **XmlDocument::NodeChanging** event, **get_NewValue** returns the value of the node if the change is successful. If called in a **XmlDocument::NodeChanged** event, **get_NewValue** returns the current value of the node.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
