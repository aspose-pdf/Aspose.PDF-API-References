---
title: "System::Xml::XmlValidatingReader::XmlValidatingReader конструктор"
linktitle: "XmlValidatingReader"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlValidatingReader::XmlValidatingReader конструктор. Инициализирует новый экземпляр класса XmlValidatingReader с указанными значениями в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Инициализирует новый экземпляр класса [XmlValidatingReader](../) с указанными значениями.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFragment | const SharedPtr\<IO::Stream\>\& | Поток, содержащий XML-фрагмент для разбора. |
| fragType | XmlNodeType | Тип [XmlNodeType](../../xmlnodetype/) XML‑фрагмента. Это определяет, что может содержать фрагмент (см. таблицу ниже). |
| context | const SharedPtr\<XmlParserContext\>\& | Контекст [XmlParserContext](../../xmlparsercontext/), в котором будет разбираться XML‑фрагмент. Он включает используемую [XmlNameTable](../../xmlnametable/), кодировку, область пространства имён, текущий **xml:lang** и область **xml:space**. |
## Примечания



В следующей таблице перечислены допустимые значения **fragType** и то, как читатель разбирает каждый из разных типов узлов. |||
|-|-|
| XmlNodeType | Фрагмент может содержать |
| Элемент | Любое допустимое содержимое элемента (например, произвольное сочетание элементов, комментариев, инструкций обработки, CDATA, текста и ссылок на сущности). |
| Атрибут | Значение атрибута (часть внутри кавычек). |
| Document | Содержимое полного XML‑документа; это накладывает правила уровня документа. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor


Инициализирует новый экземпляр класса [XmlValidatingReader](../), который проверяет содержимое, возвращаемое указанным [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | const SharedPtr\<XmlReader\>\& | Экземпляр [XmlReader](../../xmlreader/) для чтения во время проверки. Текущая реализация поддерживает только [XmlTextReader](../../xmltextreader/). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Инициализирует новый экземпляр класса [XmlValidatingReader](../) с указанными значениями.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFragment | const String\& | Строка, содержащая XML‑фрагмент для разбора. |
| fragType | XmlNodeType | Тип [XmlNodeType](../../xmlnodetype/) XML‑фрагмента. Это также определяет, что может содержать строка фрагмента (см. таблицу ниже). |
| context | const SharedPtr\<XmlParserContext\>\& | Контекст [XmlParserContext](../../xmlparsercontext/), в котором будет разбираться XML‑фрагмент. Он включает используемую [NameTable](../../nametable/), кодировку, область пространства имён, текущий **xml:lang** и область **xml:space**. |
## Примечания



В следующей таблице перечислены допустимые значения **fragType** и то, как читатель разбирает каждый из разных типов узлов. |||
|-|-|
| XmlNodeType | Фрагмент может содержать |
| Элемент | Любое допустимое содержимое элемента (например, произвольное сочетание элементов, комментариев, инструкций обработки, CDATA, текста и ссылок на сущности). |
| Атрибут | Значение атрибута (часть внутри кавычек). |
| Document | Содержимое полного XML‑документа; это накладывает правила уровня документа. |

## См. также

* Class [String](../../../system/string/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
