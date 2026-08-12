---
title: "Método System::Xml::XmlNodeChangedEventArgs::get_NewValue"
linktitle: "get_NewValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlNodeChangedEventArgs::get_NewValue. Devuelve el nuevo valor del nodo en C++."
type: docs
weight: 400
url: /es/cpp/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue method


Devuelve el nuevo valor del nodo.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### ReturnValue

El nuevo valor del nodo. Este método devuelve **nullptr** si el nodo no es ni un atributo ni un nodo de texto, o si el nodo está siendo eliminado. Si se llama en un evento **XmlDocument::NodeChanging**, **get_NewValue** devuelve el valor del nodo si el cambio tiene éxito. Si se llama en un evento **XmlDocument::NodeChanged**, **get_NewValue** devuelve el valor actual del nodo.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
