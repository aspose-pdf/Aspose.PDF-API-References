---
title: "Метод System::Xml::Xsl::XslTransform::Load"
linktitle: "Load"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Xsl::XslTransform::Load. Загружает XSLT‑таблицу стилей, содержащуюся в IXPathNavigable, в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


Загружает таблицу стилей XSLT, содержащуюся в IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим XSLT‑таблицу стилей. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Загружает таблицу стилей XSLT, содержащуюся в IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим XSLT‑таблицу стилей. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для загрузки любых таблиц стилей, указанных в элементах **xsl:import** и **xsl:include**. Если это **nullptr**, внешние ресурсы не разрешаются. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) method


Загружает таблицу стилей XSLT, содержащуюся в XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| таблица стилей | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Объект XPathNavigator, содержащий таблицу стилей XSLT. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Загружает таблицу стилей XSLT, содержащуюся в XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| таблица стилей | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Объект XPathNavigator, содержащий таблицу стилей XSLT. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для загрузки любых таблиц стилей, указанных в элементах **xsl:import** и **xsl:include**. Если это **nullptr**, внешние ресурсы не разрешаются. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) method


Загружает таблицу стилей XSLT, содержащуюся в [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий таблицу стилей XSLT. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Загружает таблицу стилей XSLT, содержащуюся в [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий таблицу стилей XSLT. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для загрузки любых таблиц стилей, указанных в элементах **xsl:import** и **xsl:include**. Если это **nullptr**, внешние ресурсы не разрешаются. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const String\&) method


Загружает таблицу стилей XSLT, указанную URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const String\& | URL, указывающий таблицу стилей XSLT для загрузки. |

## См. также

* Class [String](../../../system/string/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Загружает таблицу стилей XSLT, указанную URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const String\& | URL, указывающий таблицу стилей XSLT для загрузки. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) для загрузки таблицы стилей и любых таблиц стилей, указанных в элементах **xsl:import** и **xsl:include**. Если значение равно **nullptr**, используется стандартный [XmlUrlResolver](../../../system.xml/xmlurlresolver/) без учетных данных пользователя для открытия таблицы стилей. Стандартный [XmlUrlResolver](../../../system.xml/xmlurlresolver/) не используется для разрешения внешних ресурсов в таблице стилей, поэтому элементы **xsl:import** и **xsl:include** не разрешаются. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
