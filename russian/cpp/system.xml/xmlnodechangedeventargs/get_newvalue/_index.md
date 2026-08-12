---
title: "System::Xml::XmlNodeChangedEventArgs::get_NewValue метод"
linktitle: "get_NewValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeChangedEventArgs::get_NewValue метод. Возвращает новое значение узла в C++."
type: docs
weight: 400
url: /ru/cpp/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue method


Возвращает новое значение узла.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### ReturnValue

Новое значение узла. Этот метод возвращает **nullptr**, если узел не является ни атрибутом, ни текстовым узлом, или если узел удаляется. Если вызвать в событии **XmlDocument::NodeChanging**, **get_NewValue** возвращает значение узла, если изменение успешно. Если вызвать в событии **XmlDocument::NodeChanged**, **get_NewValue** возвращает текущее значение узла.

## См. также

* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
