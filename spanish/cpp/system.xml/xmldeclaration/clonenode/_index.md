---
title: "System::Xml::XmlDeclaration::CloneNode method"
linktitle: "CloneNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlDeclaration::CloneNode method. Crea una copia de este nodo en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode method


Crea un duplicado de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | bool | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo en sí. Debido a que los nodos [XmlDeclaration](../) no tienen hijos, el nodo clonado siempre incluye el valor de datos, sin importar la configuración del parámetro. |

### ReturnValue

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
