---
title: "System::Xml::Xsl::XslTransform::Transform метод"
linktitle: "Transform"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Xsl::XslTransform::Transform метод. Преобразует XML-данные в IXPathNavigable, используя указанные args, и выводит результат в XmlReader в C++."
type: docs
weight: 400
url: /ru/cpp/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method


Преобразует XML-данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |

### ReturnValue

Объект [XmlReader](../../../system.xml/xmlreader/), содержащий результаты преобразования.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в поток Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<IO::Stream\>\& | Поток, в который вы хотите вывести данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в поток Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<IO::Stream\>\& | Поток, в который вы хотите вывести данные. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если значение равно **nullptr**, функция **document()** не разрешается. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения метода [XslTransform::Transform](./). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<IO::TextWriter\>\& | Объект TextWriter, в который вы хотите вывести данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<IO::TextWriter\>\& | Объект TextWriter, в который вы хотите вывести данные. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если значение равно **nullptr**, функция **document()** не разрешается. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Преобразует XML-данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если значение равно **nullptr**, функция **document()** не разрешается. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

### ReturnValue

Объект [XmlReader](../../../system.xml/xmlreader/), содержащий результаты преобразования.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<XmlWriter\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Преобразует XML‑данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<XmlWriter\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести данные. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если значение равно **nullptr**, функция **document()** не разрешается. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method


Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | XPathNavigator, содержащий данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |

### ReturnValue

Объект [XmlReader](../../../system.xml/xmlreader/), содержащий результаты преобразования.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в поток Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | XPathNavigator, содержащий данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<IO::Stream\>\& | Поток, в который вы хотите вывести данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в поток Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | XPathNavigator, содержащий данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<IO::Stream\>\& | Поток, в который вы хотите вывести данные. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если значение равно **nullptr**, функция **document()** не разрешается. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | XPathNavigator, содержащий данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<IO::TextWriter\>\& | Объект TextWriter, в который вы хотите вывести данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | XPathNavigator, содержащий данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<IO::TextWriter\>\& | Объект TextWriter, в который вы хотите вывести данные. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если значение равно **nullptr**, функция **document()** не разрешается. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Преобразует XML‑данные в XPathNavigator, используя указанные **args**, и выводит результат в [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | XPathNavigator, содержащий данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если значение равно **nullptr**, функция **document()** не разрешается. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

### ReturnValue

Объект [XmlReader](../../../system.xml/xmlreader/), содержащий результаты преобразования.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Преобразует XML‑данные в XPathNavigator, используя указанные args, и выводит результат в [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | XPathNavigator, содержащий данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<XmlWriter\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Преобразует XML‑данные в XPathNavigator, используя указанные args, и выводит результат в [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | XPathNavigator, содержащий данные для преобразования. |
| args | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы, квалифицированные пространством имен, используемые в качестве входных данных для преобразования. |
| output | const SharedPtr\<XmlWriter\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести данные. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если значение равно **nullptr**, функция **document()** не разрешается. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const String\&, const String\&) method


Преобразует XML‑данные во входном файле и выводит результат в выходной файл.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputfile | const String\& | URL исходного документа, который нужно преобразовать. |
| outputfile | const String\& | URL выходного файла. |

## См. также

* Class [String](../../../system/string/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Преобразует XML‑данные во входном файле и выводит результат в выходной файл.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputfile | const String\& | URL исходного документа, который нужно преобразовать. |
| outputfile | const String\& | URL выходного файла. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если значение равно **nullptr**, функция **document()** не разрешается. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения метода [XslTransform::Transform](./). |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
