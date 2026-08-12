---
title: "Método System::Xml::XmlNodeChangedEventArgs::get_OldValue"
linktitle: "get_OldValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlNodeChangedEventArgs::get_OldValue. Devuelve el valor original del nodo en C++."
type: docs
weight: 700
url: /es/cpp/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue method


Devuelve el valor original del nodo.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### ReturnValue

El valor original del nodo. Este método devuelve **nullptr** si el nodo no es ni un atributo ni un nodo de texto, o si el nodo está siendo insertado. Si se llama en un evento **XmlDocument::NodeChanging**, **get_OldValue** devuelve el valor actual del nodo que será reemplazado si el cambio tiene éxito. Si se llama en un evento **XmlDocument::NodeChanged**, **get_OldValue** devuelve el valor del nodo antes del cambio.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
