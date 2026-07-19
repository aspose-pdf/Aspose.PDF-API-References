---
title: "System::Xml::Xsl::XslCompiledTransform::Load method"
linktitle: "Load"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Xsl::XslCompiledTransform::Load method. Компилирует таблицу стилей, содержащуюся в объекте IXPathNavigable в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


Компилирует таблицу стилей, содержащуюся в объекте IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим таблицу стилей. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) method


Компилирует таблицу стилей XSLT, содержащуюся в IXPathNavigable. [XmlResolver](../../../system.xml/xmlresolver/) разрешает любые элементы XSLT **import** или **include**, а настройки XSLT определяют разрешения для таблицы стилей.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим таблицу стилей. |
| settings | SharedPtr\<XsltSettings\> | Настройки [XsltSettings](../../xsltsettings/), применяемые к таблице стилей. Если значение **nullptr**, применяется настройка [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | SharedPtr\<XmlResolver\> | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения любых таблиц стилей, указанных в элементах XSLT **import** и **include**. Если значение **nullptr**, внешние ресурсы не разрешаются. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) method


Компилирует таблицу стилей, содержащуюся в [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | Объект [XmlReader](../../../system.xml/xmlreader/) содержащий таблицу стилей. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method


Компилирует таблицу стилей XSLT, содержащуюся в [XmlReader](../../../system.xml/xmlreader/). [XmlResolver](../../../system.xml/xmlresolver/) разрешает любые элементы XSLT **import** или **include**, а настройки XSLT определяют разрешения для таблицы стилей.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/) с таблицей стилей. |
| settings | const SharedPtr\<XsltSettings\>\& | Настройки [XsltSettings](../../xsltsettings/), применяемые к таблице стилей. Если значение **nullptr**, применяется настройка [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const SharedPtr\<XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения любых таблиц стилей, указанных в элементах XSLT **import** и **include**. Если значение **nullptr**, внешние ресурсы не разрешаются. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const String\&) method


Загружает и компилирует таблицу стилей, расположенную по указанному URI.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheetUri | const String\& | URI таблицы стилей. |

## См. также

* Class [String](../../../system/string/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method


Загружает и компилирует таблицу стилей XSLT, указанную в URI. [XmlResolver](../../../system.xml/xmlresolver/) разрешает любые элементы XSLT **import** или **include**, а настройки XSLT определяют разрешения для таблицы стилей.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheetUri | const String\& | URI таблицы стилей. |
| settings | const SharedPtr\<XsltSettings\>\& | Настройки [XsltSettings](../../xsltsettings/), применяемые к таблице стилей. Если значение **nullptr**, применяется настройка [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const SharedPtr\<XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения URI таблицы стилей и любых таблиц стилей, указанных в элементах XSLT **import** и **include**. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
