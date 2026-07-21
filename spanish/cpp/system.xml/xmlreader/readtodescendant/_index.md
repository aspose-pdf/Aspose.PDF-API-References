---
title: "Método System::Xml::XmlReader::ReadToDescendant"
linktitle: "ReadToDescendant"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlReader::ReadToDescendant. Avanza el XmlReader al siguiente elemento descendiente con el nombre local y el URI de espacio de nombres especificados en C++."
type: docs
weight: 7100
url: /es/cpp/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String, String) method


Avanza el [XmlReader](../) al siguiente elemento descendiente con el nombre local y el URI de espacio de nombres especificados.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del elemento al que desea moverse. |
| namespaceURI | String | El URI de espacio de nombres del elemento al que desea moverse. |

### ReturnValue

**true** if a matching descendant element is found; otherwise **false**. If a matching child element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the element. If the [XmlReader](../) is not positioned on an element when [XmlReader::ReadToDescendant(String,String)](./) was called, this method returns **false** and the position of the [XmlReader](../) is not changed.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadToDescendant(String) method


Avanza el [XmlReader](../) al siguiente elemento descendiente con el nombre calificado especificado.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre calificado del elemento al que desea moverse. |

### ReturnValue

**true** if a matching descendant element is found; otherwise **false**. If a matching child element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the element. If the [XmlReader](../) is not positioned on an element when [XmlReader::ReadToDescendant(String)](./) was called, this method returns **false** and the position of the [XmlReader](../) is not changed.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
