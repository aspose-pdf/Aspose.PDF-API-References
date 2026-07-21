---
title: "System::Xml::XmlEntityReference::CloneNode método"
linktitle: "CloneNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlEntityReference::CloneNode método. Crea un duplicado de este nodo en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode method


Crea un duplicado de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | bool | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo mismo. Para nodos [XmlEntityReference](../), este método siempre devuelve un nodo de referencia de entidad sin hijos. El texto de reemplazo se establece cuando el nodo se inserta en un padre. |

### ReturnValue

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntityReference](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
