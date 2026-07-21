---
title: "System::Xml::XmlWhitespace::CloneNode método"
linktitle: "CloneNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlWhitespace::CloneNode método. Crea un duplicado de este nodo en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode method


Crea un duplicado de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| profundo | bool | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo en sí. Para los nodos de espacio en blanco, el nodo clonado siempre incluye el valor de datos, sin importar la configuración del parámetro. |

### ReturnValue

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
