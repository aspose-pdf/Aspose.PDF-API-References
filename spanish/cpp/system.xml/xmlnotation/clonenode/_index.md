---
title: "System::Xml::XmlNotation::CloneNode método"
linktitle: "CloneNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNotation::CloneNode método. Crea un duplicado de este nodo. Los nodos Notation no pueden ser clonados. Llamar a este método sobre un objeto XmlNotation lanza una excepción en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode method


Crea una copia de este nodo. Los nodos de notación no pueden clonarse. Llamar a este método en un objeto [XmlNotation](../) lanza una excepción.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| profundo | bool | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo mismo. |

### ReturnValue

Una copia [XmlNode](../../xmlnode/) del nodo desde el cual se llama al método.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNotation](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
