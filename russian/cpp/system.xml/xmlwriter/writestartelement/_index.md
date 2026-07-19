---
title: "System::Xml::XmlWriter::WriteStartElement метод"
linktitle: "WriteStartElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlWriter::WriteStartElement метод. При переопределении в производном классе записывает начальный тег с указанным локальным именем в C++."
type: docs
weight: 3200
url: /ru/cpp/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&) method


При переопределении в производном классе записывает стартовый тег с указанным локальным именем.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const String\& | Локальное имя элемента. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteStartElement(const String\&, const String\&) method


При переопределении в производном классе записывает указанный стартовый тег и связывает его с заданным пространством имён.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const String\& | Локальное имя элемента. |
| ns | const String\& | URI пространства имён, которое следует связать с элементом. Если это пространство имён уже находится в области видимости и имеет связанный префикс, запись автоматически также выводит этот префикс. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) method


При переопределении в производном классе записывает указанный стартовый тег и связывает его с заданным пространством имён и префиксом.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | const String\& | Префикс пространства имён элемента. |
| localName | const String\& | Локальное имя элемента. |
| ns | const String\& | URI пространства имён, которое следует связать с элементом. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
