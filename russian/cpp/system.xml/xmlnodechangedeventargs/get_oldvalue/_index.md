---
title: "System::Xml::XmlNodeChangedEventArgs::get_OldValue метод"
linktitle: "get_OldValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeChangedEventArgs::get_OldValue метод. Возвращает оригинальное значение узла в C++."
type: docs
weight: 700
url: /ru/cpp/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue method


Возвращает исходное значение узла.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### ReturnValue

Исходное значение узла. Этот метод возвращает **nullptr**, если узел не является ни атрибутом, ни текстовым узлом, или если узел вставляется. Если вызвать в событии **XmlDocument::NodeChanging**, **get_OldValue** возвращает текущее значение узла, которое будет заменено, если изменение успешно. Если вызвать в событии **XmlDocument::NodeChanged**, **get_OldValue** возвращает значение узла до изменения.

## См. также

* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
