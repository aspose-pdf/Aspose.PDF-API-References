---
title: "System::Xml::XmlAttribute::PrependChild método"
linktitle: "PrependChild"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlAttribute::PrependChild método. Añade el nodo especificado al principio de la lista de nodos hijos de este nodo en C++."
type: docs
weight: 1600
url: /es/cpp/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild method


Añade el nodo especificado al comienzo de la lista de nodos hijos de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | El [XmlNode](../../xmlnode/) a añadir. Si es un [XmlDocumentFragment](../../xmldocumentfragment/), todo el contenido del fragmento de documento se mueve a la lista de hijos de este nodo. |

### ReturnValue

El [XmlNode](../../xmlnode/) añadido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
