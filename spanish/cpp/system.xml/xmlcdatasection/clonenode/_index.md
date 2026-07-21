---
title: "System::Xml::XmlCDataSection::CloneNode método"
linktitle: "CloneNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlCDataSection::CloneNode método. Crea una copia de este nodo en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode method


Crea un duplicado de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| profundo | bool | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo en sí. Dado que los nodos CDATA no tienen hijos, independientemente de la configuración del parámetro, el nodo clonado siempre incluirá el contenido de datos. |

### ReturnValue

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlCDataSection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
