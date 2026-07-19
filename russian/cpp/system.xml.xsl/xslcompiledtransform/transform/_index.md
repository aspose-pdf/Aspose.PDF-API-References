---
title: "System::Xml::Xsl::XslCompiledTransform::Transform метод"
linktitle: "Transform"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Xsl::XslCompiledTransform::Transform метод. Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в XmlWriter в C++."
type: docs
weight: 400
url: /ru/cpp/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method


Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| results | const SharedPtr\<XmlWriter\>\& | Объект [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите выводить. Если таблица стилей содержит элемент **xsl:output**, следует создать [XmlWriter](../../../system.xml/xmlwriter/) с помощью объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого значением [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные параметры вывода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в поток. [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы с пространством имён, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| результаты | const SharedPtr\<IO::Stream\>\& | Поток, в который вы хотите вывести данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в TextWriter. [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы с пространством имён, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| результаты | const SharedPtr\<IO::TextWriter\>\& | Объект TextWriter, в который вы хотите вывести данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим данные для преобразования. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы с пространством имён, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | Объект [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите выводить. Если таблица стилей содержит элемент **xsl:output**, следует создать [XmlWriter](../../../system.xml/xmlwriter/) с помощью объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого значением [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные параметры вывода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method


Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения, а [XmlResolver](../../../system.xml/xmlresolver/) разрешает функцию XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Документ для преобразования, указанный объектом IXPathNavigable. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Список аргументов как [XsltArgumentList](../../xsltargumentlist/). |
| results | const SharedPtr\<XmlWriter\>\& | Объект [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите выводить. Если таблица стилей содержит элемент **xsl:output**, следует создать [XmlWriter](../../../system.xml/xmlwriter/) с использованием объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого значением [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные параметры вывода. |
| documentResolver | const SharedPtr\<XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если он **nullptr**, функция **document()** не разрешается. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method


Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../../system.xml/xmlreader/), и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/) содержащий входной документ. |
| results | const SharedPtr\<XmlWriter\>\& | Объект [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите выводить. Если таблица стилей содержит элемент **xsl:output**, следует создать [XmlWriter](../../../system.xml/xmlwriter/) с помощью объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого значением [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные параметры вывода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../../system.xml/xmlreader/), и выводит результаты в поток. [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий входной документ. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы с пространством имён, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| результаты | const SharedPtr\<IO::Stream\>\& | Поток, в который вы хотите вывести данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../../system.xml/xmlreader/), и выводит результаты в TextWriter. [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий входной документ. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы с пространством имён, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| результаты | const SharedPtr\<IO::TextWriter\>\& | Объект TextWriter, в который вы хотите вывести данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../../system.xml/xmlreader/), и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы во время выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий входной документ. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы с пространством имён, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | Объект [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите выводить. Если таблица стилей содержит элемент **xsl:output**, следует создать [XmlWriter](../../../system.xml/xmlwriter/) с помощью объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого значением [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные параметры вывода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method


Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../../system.xml/xmlreader/), и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы во время выполнения, а [XmlResolver](../../../system.xml/xmlresolver/) разрешает функцию XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий входной документ. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы с пространством имён, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | Объект [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите выводить. Если таблица стилей содержит элемент **xsl:output**, следует создать [XmlWriter](../../../system.xml/xmlwriter/) с помощью объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого значением [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные параметры вывода. |
| documentResolver | const SharedPtr\<XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения функции XSLT **document()**. Если он **nullptr**, функция **document()** не разрешается. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method


Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const String\& | URI входного документа. |
| results | const SharedPtr\<XmlWriter\>\& | Объект [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите выводить. Если таблица стилей содержит элемент **xsl:output**, следует создать [XmlWriter](../../../system.xml/xmlwriter/) с помощью объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого значением [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные параметры вывода. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в поток. [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы во время выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const String\& | URI входного документа. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы с пространством имён, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| результаты | const SharedPtr\<IO::Stream\>\& | Поток, в который вы хотите вывести данные. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const String\& | URI входного документа. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы с пространством имён, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| результаты | const SharedPtr\<IO::TextWriter\>\& | Объект TextWriter, в который вы хотите вывести данные. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы во время выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const String\& | URI входного документа. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Объект [XsltArgumentList](../../xsltargumentlist/), содержащий аргументы с пространством имён, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | Объект [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите выводить. Если таблица стилей содержит элемент **xsl:output**, следует создать [XmlWriter](../../../system.xml/xmlwriter/) с помощью объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого значением [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные параметры вывода. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const String\&) method


Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в файл.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const String\& | URI входного документа. |
| resultsFile | const String\& | URI выходного файла. |

## См. также

* Class [String](../../../system/string/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
