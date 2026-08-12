---
title: "System::Xml::XPath::XPathNavigator::ValueAs método"
linktitle: "ValueAs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::ValueAs método. Devuelve el valor del nodo actual como el Tipo especificado, usando el objeto IXmlNamespaceResolver especificado para resolver los prefijos de espacio de nombres en C++."
type: docs
weight: 8100
url: /es/cpp/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs method


Devuelve el valor del nodo actual como el Tipo especificado, usando el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const TypeInfo\& | El Tipo al que devolver el valor del nodo actual. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefijos de espacio de nombres. |

### ReturnValue

El valor del nodo actual como el Tipo solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
