---
title: "System::Xml::XmlReader::ReadElementContentAs метод"
linktitle: "ReadElementContentAs"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadElementContentAs метод. Считывает содержимое элемента как запрашиваемый тип в C++."
type: docs
weight: 5200
url: /ru/cpp/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Читает содержимое элемента как запрашиваемый тип.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| returnType | const TypeInfo\& | Тип возвращаемого значения. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Объект [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), который используется для разрешения любых префиксов пространств имён, связанных с преобразованием типов. |

### ReturnValue

Содержимое элемента, преобразованное в запрашиваемый типизированный объект.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) method


Проверяет, что указанные локальное имя и URI пространства имён соответствуют текущему элементу, затем читает содержимое элемента как запрашиваемый тип.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| returnType | const TypeInfo\& | Тип возвращаемого значения. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Объект [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), который используется для разрешения любых префиксов пространств имён, связанных с преобразованием типов. |
| localName | String | Локальное имя элемента. |
| namespaceURI | String | URI пространства имен элемента. |

### ReturnValue

Содержимое элемента, преобразованное в запрашиваемый типизированный объект.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
