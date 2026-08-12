---
title: "System::Xml::XPath::XPathItem::ValueAs método"
linktitle: "ValueAs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathItem::ValueAs método. Devuelve el valor del elemento como el tipo especificado en C++."
type: docs
weight: 1100
url: /es/cpp/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) method


Devuelve el valor del elemento como el tipo especificado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const TypeInfo\& | El tipo al que devolver el valor del elemento. |

### ReturnValue

El valor del elemento como el tipo solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XPathItem](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Cuando se sobrescribe en una clase derivada, devuelve el valor del elemento como el tipo especificado usando el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const TypeInfo\& | El tipo al que devolver el valor del elemento. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefijos de espacio de nombres. |

### ReturnValue

El valor del elemento como el tipo solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathItem](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
