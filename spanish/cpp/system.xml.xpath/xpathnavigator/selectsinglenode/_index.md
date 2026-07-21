---
title: "System::Xml::XPath::XPathNavigator::SelectSingleNode método"
linktitle: "SelectSingleNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::SelectSingleNode método. Selecciona un solo nodo en el XPathNavigator usando el objeto XPathExpression especificado en C++."
type: docs
weight: 7500
url: /es/cpp/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) method


Selecciona un solo nodo en el [XPathNavigator](../) usando el objeto [XPathExpression](../../xpathexpression/) especificado.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expression | SharedPtr\<XPathExpression\> | Un objeto [XPathExpression](../../xpathexpression/) que contiene la consulta [XPath](../../) compilada. |

### ReturnValue

Un objeto [XPathNavigator](../) que contiene el primer nodo coincidente para la consulta [XPath](../../) especificada; de lo contrario **nullptr** si no hay resultados de la consulta.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectSingleNode(String) method


Selecciona un solo nodo en el [XPathNavigator](../) usando la consulta [XPath](../../) especificada.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | String | Una [String](../../../system/string/) que representa una expresión [XPath](../../). |

### ReturnValue

Un objeto [XPathNavigator](../) que contiene el primer nodo coincidente para la consulta [XPath](../../) especificada; de lo contrario, **nullptr** si no hay resultados de la consulta.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) method


Selecciona un solo nodo en el objeto [XPathNavigator](../) usando la consulta [XPath](../../) especificada con el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) indicado para resolver los prefijos de espacio de nombres.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | String | Una [String](../../../system/string/) que representa una expresión [XPath](../../). |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver los prefijos de espacio de nombres en la consulta [XPath](../../). |

### ReturnValue

Un objeto [XPathNavigator](../) que contiene el primer nodo coincidente para la consulta [XPath](../../) especificada; de lo contrario **nullptr** si no hay resultados de la consulta.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
