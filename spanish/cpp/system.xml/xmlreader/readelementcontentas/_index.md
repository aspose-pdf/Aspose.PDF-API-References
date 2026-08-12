---
title: "System::Xml::XmlReader::ReadElementContentAs método"
linktitle: "ReadElementContentAs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlReader::ReadElementContentAs método. Lee el contenido del elemento como el tipo solicitado en C++."
type: docs
weight: 5200
url: /es/cpp/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Lee el contenido del elemento como el tipo solicitado.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const TypeInfo\& | El tipo del valor que se devolverá. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Un objeto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) que se utiliza para resolver cualquier prefijo de espacio de nombres relacionado con la conversión de tipos. |

### ReturnValue

El contenido del elemento convertido al objeto tipado solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) method


Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el contenido del elemento como el tipo solicitado.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const TypeInfo\& | El tipo del valor que se devolverá. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Un objeto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) que se utiliza para resolver cualquier prefijo de espacio de nombres relacionado con la conversión de tipos. |
| localName | String | El nombre local del elemento. |
| namespaceURI | String | El URI del espacio de nombres del elemento. |

### ReturnValue

El contenido del elemento convertido al objeto tipado solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
