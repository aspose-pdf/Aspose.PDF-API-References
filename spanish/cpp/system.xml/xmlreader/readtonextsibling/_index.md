---
title: "System::Xml::XmlReader::ReadToNextSibling método"
linktitle: "ReadToNextSibling"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlReader::ReadToNextSibling method. Avanza el XmlReader al siguiente elemento hermano con el nombre local y el URI de espacio de nombres especificados en C++."
type: docs
weight: 7300
url: /es/cpp/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String, String) method


Avanza el [XmlReader](../) al siguiente elemento hermano con el nombre local y el URI de espacio de nombres especificados.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del elemento hermano al que desea moverse. |
| namespaceURI | String | El URI de espacio de nombres del elemento hermano al que desea moverse. |

### ReturnValue

**true** if a matching sibling element is found; otherwise, **false**. If a matching sibling element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the parent element.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadToNextSibling(String) method


Avanza el [XmlReader](../) al siguiente elemento hermano con el nombre calificado especificado.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre calificado del elemento hermano al que desea moverse. |

### ReturnValue

**true** if a matching sibling element is found; otherwise **false**. If a matching sibling element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the parent element.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
