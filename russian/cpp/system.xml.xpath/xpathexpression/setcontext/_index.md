---
title: "Метод System::Xml::XPath::XPathExpression::SetContext"
linktitle: "SetContext"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathExpression::SetContext. При переопределении в производном классе указывает объект IXmlNamespaceResolver, используемый для разрешения пространств имён в C++."
type: docs
weight: 500
url: /ru/cpp/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) method


При переопределении в производном классе указывает объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) для разрешения пространств имён.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | Объект, реализующий интерфейс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) для разрешения пространств имён. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) method


При переопределении в производном классе указывает объект [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) для разрешения пространств имён.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| nsManager | SharedPtr\<XmlNamespaceManager\> | Объект [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) для разрешения пространств имён. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
