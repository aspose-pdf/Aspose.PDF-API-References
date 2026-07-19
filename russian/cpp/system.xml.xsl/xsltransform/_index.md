---
title: "System::Xml::Xsl::XslTransform класс"
linktitle: "XslTransform"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Xsl::XslTransform класс. Преобразует XML‑данные с помощью таблицы стилей Extensible Stylesheet Language for Transformations (XSLT) в C++."
type: docs
weight: 700
url: /ru/cpp/system.xml.xsl/xsltransform/
---
## XslTransform class


Преобразует XML‑данные с использованием Extensible Stylesheet Language for Transformations (XSLT) таблицы стилей.

```cpp
class XslTransform : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&) | Загружает таблицу стилей XSLT, содержащуюся в [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Загружает таблицу стилей XSLT, содержащуюся в [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) | Загружает таблицу стилей XSLT, содержащуюся в IXPathNavigable. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Загружает таблицу стилей XSLT, содержащуюся в IXPathNavigable. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) | Загружает таблицу стилей XSLT, содержащуюся в XPathNavigator. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Загружает таблицу стилей XSLT, содержащуюся в XPathNavigator. |
| [Load](./load/)(const String\&) | Загружает таблицу стилей XSLT, указанную URL. |
| [Load](./load/)(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Загружает таблицу стилей XSLT, указанную URL. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Устанавливает [XmlResolver](../../system.xml/xmlresolver/), используемый для разрешения внешних ресурсов, когда вызывается метод [XslTransform::Transform](./transform/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) | Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Преобразует XML‑данные в XPathNavigator, используя указанные args, и выводит результат в [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Преобразует XML‑данные в XPathNavigator, используя указанные args, и выводит результат в [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в поток Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в поток Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) | Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в поток Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в поток Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Преобразует XML‑данные во входном файле и выводит результат в выходной файл. |
| [Transform](./transform/)(const String\&, const String\&) | Преобразует XML‑данные во входном файле и выводит результат в выходной файл. |
| [XslTransform](./xsltransform/)() | Инициализирует новый экземпляр класса [XslTransform](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
