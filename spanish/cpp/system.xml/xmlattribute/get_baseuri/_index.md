---
title: "System::Xml::XmlAttribute::get_BaseURI método"
linktitle: "get_BaseURI"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlAttribute::get_BaseURI método. Devuelve el Identificador Uniforme de Recursos (URI) base del nodo en C++."
type: docs
weight: 300
url: /es/cpp/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI method


Devuelve el Identificador Uniforme de Recursos (URI) base del nodo.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### ReturnValue

La ubicación desde la que se cargó el nodo o [String::Empty](../../../system/string/empty/) si el nodo no tiene URI base. Los nodos [Attribute](../../../system/attribute/) tienen el mismo URI base que su elemento propietario. Si un nodo de atributo no tiene un elemento propietario, get_BaseURI devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Class [String](../../../system/string/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
