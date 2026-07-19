---
title: "System::Xml::Xsl::XslCompiledTransform класс"
linktitle: "XslCompiledTransform"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Xsl::XslCompiledTransform класс. Преобразует XML‑данные с помощью XSLT‑таблицы стилей в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform class


Преобразует XML‑данные с использованием XSLT‑таблицы стилей.

```cpp
class XslCompiledTransform : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_OutputSettings](./get_outputsettings/)() | Возвращает объект [XmlWriterSettings](../../system.xml/xmlwritersettings/), содержащий информацию вывода, полученную из элемента **xsl:output** таблицы стилей. |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&) | Компилирует таблицу стилей, содержащуюся в [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) | Компилирует XSLT‑таблицу стилей, содержащуюся в [XmlReader](../../system.xml/xmlreader/). [XmlResolver](../../system.xml/xmlresolver/) разрешает любые элементы XSLT **import** или **include**, а настройки XSLT определяют разрешения для таблицы стилей. |
| [Load](./load/)(const String\&) | Загружает и компилирует таблицу стилей, расположенную по указанному URI. |
| [Load](./load/)(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) | Загружает и компилирует XSLT‑таблицу стилей, указанную URI. [XmlResolver](../../system.xml/xmlresolver/) разрешает любые элементы XSLT **import** или **include**, а настройки XSLT определяют разрешения для таблицы стилей. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) | Компилирует таблицу стилей, содержащуюся в объекте IXPathNavigable. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) | Компилирует XSLT‑таблицу стилей, содержащуюся в IXPathNavigable. [XmlResolver](../../system.xml/xmlresolver/) разрешает любые элементы XSLT **import** или **include**, а настройки XSLT определяют разрешения для таблицы стилей. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) | Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в TextWriter. [XsltArgumentList](../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в поток. [XsltArgumentList](../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) | Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../system.xml/xmlreader/), и выводит результаты в [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../system.xml/xmlreader/), и выводит результаты в [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) предоставляет дополнительные аргументы выполнения. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../system.xml/xmlreader/), и выводит результаты в TextWriter. [XsltArgumentList](../xsltargumentlist/) предоставляет дополнительные аргументы выполнения. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../system.xml/xmlreader/), и выводит результаты в поток. [XsltArgumentList](../xsltargumentlist/) предоставляет дополнительные аргументы выполнения. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XmlWriter\>\&) | Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) предоставляет дополнительные аргументы выполнения. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в TextWriter. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в поток. [XsltArgumentList](../xsltargumentlist/) предоставляет дополнительные аргументы выполнения. |
| [Transform](./transform/)(const String\&, const String\&) | Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в файл. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) | Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../system.xml/xmlreader/), и выводит результаты в [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) предоставляет дополнительные аргументы выполнения, а [XmlResolver](../../system.xml/xmlresolver/) разрешает функцию XSLT **document()**. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) | Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) предоставляет дополнительные аргументы выполнения, а [XmlResolver](../../system.xml/xmlresolver/) разрешает функцию XSLT **document()**. |
| [XslCompiledTransform](./xslcompiledtransform/)() | Инициализирует новый экземпляр класса [XslCompiledTransform](./). |
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
