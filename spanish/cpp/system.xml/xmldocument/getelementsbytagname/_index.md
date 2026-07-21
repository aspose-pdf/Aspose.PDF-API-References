---
title: "Método System::Xml::XmlDocument::GetElementsByTagName"
linktitle: "GetElementsByTagName"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlDocument::GetElementsByTagName. Devuelve un XmlNodeList que contiene una lista de todos los elementos descendientes que coinciden con el XmlDocument::get_LocalName y XmlNode::get_NamespaceURI especificados en C++."
type: docs
weight: 3200
url: /es/cpp/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String, String) method


Devuelve un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con el [XmlDocument::get_LocalName](../get_localname/) y el [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | The LocalName to match. The special value **"*"** matches all tags. |
| namespaceURI | String | NamespaceURI to match. |

### ReturnValue

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. If no nodes match the specified **localName** and **namespaceURI**, the returned collection will be empty.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::GetElementsByTagName(String) method


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified name.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | The qualified name to match. It is matched against the **get_Name** value of the matching node. The special value **"*"** matches all tags. |

### ReturnValue

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. If no nodes match **name**, the returned collection will be empty.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
