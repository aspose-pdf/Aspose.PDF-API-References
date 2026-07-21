---
title: "System::Xml::XmlElement::CloneNode método"
linktitle: "CloneNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlElement::CloneNode method. Crea una copia de este nodo en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode method


Crea un duplicado de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | bool | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo mismo (y sus atributos si el nodo es un [XmlElement](../)). |

### ReturnValue

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
