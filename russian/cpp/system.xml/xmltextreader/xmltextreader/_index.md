---
title: "System::Xml::XmlTextReader::XmlTextReader конструктор"
linktitle: "XmlTextReader"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextReader::XmlTextReader конструктор. Инициализирует новый экземпляр класса XmlTextReader с указанным потоком в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным потоком.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | Поток, содержащий XML-данные для чтения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным потоком и [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | Поток, содержащий XML-данные для чтения. |
| nt | const SharedPtr\<XmlNameTable\>\& | Используемый [XmlNameTable](../../xmlnametable/). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным потоком, [XmlNodeType](../../xmlnodetype/) и [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFragment | const SharedPtr\<IO::Stream\>\& | Поток, содержащий XML-фрагмент для разбора. |
| fragType | XmlNodeType | [XmlNodeType](../../xmlnodetype/) XML-фрагмента. Это также определяет, что может содержать фрагмент. |
| context | const SharedPtr\<XmlParserContext\>\& | Контекст [XmlParserContext](../../xmlparsercontext/), в котором будет разбираться **xmlFragment**. Включает используемую [XmlNameTable](../../xmlnametable/), кодировку, область пространства имён, текущий **xml:lang** и область **xml:space**. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | TextReader, содержащий XML‑данные для чтения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным TextReader и [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | TextReader, содержащий XML‑данные для чтения. |
| nt | const SharedPtr\<XmlNameTable\>\& | Используемый [XmlNameTable](../../xmlnametable/). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным файлом.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const String\& | URL файла, содержащего XML‑данные. [XmlTextReader::get_BaseURI](../get_baseuri/) устанавливается в это значение. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным URL и потоком.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const String\& | URL, используемый для разрешения внешних ресурсов. [XmlTextReader::get_BaseURI](../get_baseuri/) устанавливается в это значение. |
| input | const SharedPtr\<IO::Stream\>\& | Поток, содержащий XML-данные для чтения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным URL, потоком и [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const String\& | URL, используемый для разрешения внешних ресурсов. [XmlTextReader::get_BaseURI](../get_baseuri/) устанавливается в это значение. Если **url** равен **nullptr**, **BaseURI** устанавливается в [String::Empty](../../../system/string/empty/). |
| input | const SharedPtr\<IO::Stream\>\& | Поток, содержащий XML-данные для чтения. |
| nt | const SharedPtr\<XmlNameTable\>\& | Используемый [XmlNameTable](../../xmlnametable/). |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным URL и TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const String\& | URL, используемый для разрешения внешних ресурсов. [XmlTextReader::get_BaseURI](../get_baseuri/) устанавливается в это значение. |
| input | const SharedPtr\<IO::TextReader\>\& | TextReader, содержащий XML‑данные для чтения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным URL, TextReader и [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const String\& | URL, используемый для разрешения внешних ресурсов. [XmlTextReader::get_BaseURI](../get_baseuri/) устанавливается в это значение. Если **url** равен **nullptr**, **BaseURI** устанавливается в [String::Empty](../../../system/string/empty/). |
| input | const SharedPtr\<IO::TextReader\>\& | TextReader, содержащий XML‑данные для чтения. |
| nt | const SharedPtr\<XmlNameTable\>\& | Используемый [XmlNameTable](../../xmlnametable/). |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанным файлом и [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const String\& | URL файла, содержащего XML‑данные для чтения. |
| nt | const SharedPtr\<XmlNameTable\>\& | Используемый [XmlNameTable](../../xmlnametable/). |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Инициализирует новый экземпляр класса [XmlTextReader](../) с указанной строкой, [XmlNodeType](../../xmlnodetype/) и [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFragment | const String\& | Строка, содержащая XML‑фрагмент для разбора. |
| fragType | XmlNodeType | [XmlNodeType](../../xmlnodetype/) XML‑фрагмента. Это также определяет, что может содержать строка фрагмента. |
| context | const SharedPtr\<XmlParserContext\>\& | Контекст [XmlParserContext](../../xmlparsercontext/), в котором будет разбираться **xmlFragment**. Включает используемую [XmlNameTable](../../xmlnametable/), кодировку, область пространства имён, текущий **xml:lang** и область **xml:space**. |

## См. также

* Class [String](../../../system/string/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
