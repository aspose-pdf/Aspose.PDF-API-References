---
title: "System::Xml::XPath::XPathNavigator::MoveToFollowing método"
linktitle: "MoveToFollowing"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::MoveToFollowing método. Mueve el XPathNavigator al elemento con el nombre local y el URI de espacio de nombres especificados en orden de documento en C++."
type: docs
weight: 5700
url: /es/cpp/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) method


Mueve el [XPathNavigator](../) al elemento con el nombre local y el URI de espacio de nombres especificados en orden de documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del elemento. |
| namespaceURI | String | El URI del espacio de nombres del elemento. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## Ver también

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) method


Mueve el [XPathNavigator](../) al elemento con el nombre local y el URI de espacio de nombres especificados, hasta el límite especificado, en orden de documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del elemento. |
| namespaceURI | String | El URI del espacio de nombres del elemento. |
| end | SharedPtr\<XPathNavigator\> | El objeto [XPathNavigator](../) posicionado en el límite del elemento que el [XPathNavigator](../) actual no pasará mientras busca el siguiente elemento. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToFollowing(XPathNodeType) method


Mueve el [XPathNavigator](../) al siguiente elemento del [XPathNodeType](../../xpathnodetype/) especificado en orden de documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | XPathNodeType | El [XPathNodeType](../../xpathnodetype/) del elemento. El [XPathNodeType](../../xpathnodetype/) no puede ser [XPathNodeType::Attribute](../../xpathnodetype/) o [XPathNodeType::Namespace](../../xpathnodetype/). |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## Ver también

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) method


Mueve el [XPathNavigator](../) al siguiente elemento del [XPathNodeType](../../xpathnodetype/) especificado, hasta el límite especificado, en orden de documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | XPathNodeType | El [XPathNodeType](../../xpathnodetype/) del elemento. El [XPathNodeType](../../xpathnodetype/) no puede ser [XPathNodeType::Attribute](../../xpathnodetype/) o [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | SharedPtr\<XPathNavigator\> | El objeto [XPathNavigator](../) posicionado en el límite del elemento que el [XPathNavigator](../) actual no pasará mientras busca el siguiente elemento. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## Ver también

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
