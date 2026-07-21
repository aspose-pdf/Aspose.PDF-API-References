---
title: "System::Xml::XmlDocumentType::CloneNode method"
linktitle: "CloneNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlDocumentType::CloneNode method. Crea un duplicado de este nodo en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode method


Crea un duplicado de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| profundo | bool | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo en sí. Para nodos de tipo DocumentType, el nodo clonado siempre incluye el subárbol, independientemente de la configuración del parámetro. |

### ReturnValue

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocumentType](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
