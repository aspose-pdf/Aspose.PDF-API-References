---
title: "System::Xml::XPath::XPathNavigator::Select método"
linktitle: "Seleccionar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::Select método. Selecciona un conjunto de nodos usando la XPathExpression especificada en C++."
type: docs
weight: 7100
url: /es/cpp/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(SharedPtr\<XPathExpression\>) method


Selecciona un conjunto de nodos usando la [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | Un objeto [XPathExpression](../../xpathexpression/) que contiene la consulta [XPath](../../) compilada. |

### ReturnValue

Un [XPathNodeIterator](../../xpathnodeiterator/) que apunta al conjunto de nodos seleccionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Select(String) method


Selecciona un conjunto de nodos, usando la expresión [XPath](../../) especificada.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | String | Una [String](../../../system/string/) que representa una expresión [XPath](../../). |

### ReturnValue

Un [XPathNodeIterator](../../xpathnodeiterator/) que apunta al conjunto de nodos seleccionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) method


Selecciona un conjunto de nodos usando la expresión [XPath](../../) especificada con el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | String | Una [String](../../../system/string/) que representa una expresión [XPath](../../). |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefijos de espacio de nombres. |

### ReturnValue

Un [XPathNodeIterator](../../xpathnodeiterator/) que apunta al conjunto de nodos seleccionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
