---
title: "System::Xml::XPath::XPathNavigator::Evaluate método"
linktitle: "Evaluate"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::Evaluate método. Evalúa el XPathExpression y devuelve el resultado tipado en C++."
type: docs
weight: 1200
url: /es/cpp/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) method


Evalúa el [XPathExpression](../../xpathexpression/) y devuelve el resultado tipado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | Un [XPathExpression](../../xpathexpression/) que puede evaluarse. |

### ReturnValue

El resultado de la expresión ([Boolean](../../../system/boolean/), número, cadena o conjunto de nodos). Esto se corresponde con objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) method


Utiliza el contexto suministrado para evaluar el [XPathExpression](../../xpathexpression/) y devuelve el resultado tipado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | Un [XPathExpression](../../xpathexpression/) que puede evaluarse. |
| context | SharedPtr\<XPathNodeIterator\> | Un [XPathNodeIterator](../../xpathnodeiterator/) que apunta al conjunto de nodos seleccionado sobre el que se realizará la evaluación. |

### ReturnValue

El resultado de la expresión ([Boolean](../../../system/boolean/), número, cadena o conjunto de nodos). Esto se corresponde con objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Evaluate(String) method


Evalúa la expresión [XPath](../../) especificada y devuelve el resultado tipado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | String | Una cadena que representa una expresión [XPath](../../) que puede evaluarse. |

### ReturnValue

El resultado de la expresión ([Boolean](../../../system/boolean/), número, cadena o conjunto de nodos). Esto se corresponde con objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) method


Evalúa la expresión [XPath](../../) especificada y devuelve el resultado tipado, utilizando el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres en la expresión [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | String | Una cadena que representa una expresión [XPath](../../) que puede evaluarse. |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) utilizado para resolver los prefijos de espacio de nombres en la expresión [XPath](../../). |

### ReturnValue

El resultado de la expresión ([Boolean](../../../system/boolean/), número, cadena o conjunto de nodos). Esto se corresponde con objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
