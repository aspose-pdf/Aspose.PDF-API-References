---
title: "Método System::Xml::XmlWriter::WriteNode"
linktitle: "WriteNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlWriter::WriteNode. Cuando se sobrescribe en una clase derivada, copia todo del lector al escritor y mueve el lector al inicio del siguiente hermano en C++."
type: docs
weight: 2600
url: /es/cpp/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) method


Cuando se sobrescribe en una clase derivada, copia todo del lector al escritor y mueve el lector al inicio del siguiente hermano.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | SharedPtr\<XmlReader\> | El [XmlReader](../../xmlreader/) del que leer. |
| defattr | bool | **true** para copiar los atributos predeterminados del [XmlReader](../../xmlreader/); de lo contrario, **false**. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) method


Copia todo del objeto XPathNavigator al escritor. La posición del XPathNavigator permanece sin cambios.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| navegador | SharedPtr\<XPath::XPathNavigator\> | El XPathNavigator del cual copiar. |
| defattr | bool | **true** para copiar los atributos predeterminados; de lo contrario, **false**. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
