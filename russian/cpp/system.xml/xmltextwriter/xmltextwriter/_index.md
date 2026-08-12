---
title: "Конструктор System::Xml::XmlTextWriter::XmlTextWriter"
linktitle: "XmlTextWriter"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::Xml::XmlTextWriter::XmlTextWriter. Создаёт экземпляр класса XmlTextWriter, используя указанный поток и кодировку в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Создаёт экземпляр класса [XmlTextWriter](../), используя указанный поток и кодировку.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| w | const SharedPtr\<IO::Stream\>\& | Поток, в который вы хотите записывать. |
| encoding | const SharedPtr\<Text::Encoding\>\& | Кодировка для генерации. Если кодировка **nullptr**, запись производится в поток в формате UTF-8, и атрибут кодировки опускается в **ProcessingInstruction**. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor


Создаёт экземпляр класса [XmlTextWriter](../), используя указанный TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| w | const SharedPtr\<IO::TextWriter\>\& | TextWriter, в который производится запись. Предполагается, что TextWriter уже настроен на правильную кодировку. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor


Создаёт экземпляр класса [XmlTextWriter](../), используя указанный файл.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const String\& | Имя файла для записи. Если файл существует, он усекается и перезаписывается новым содержимым. |
| encoding | const SharedPtr\<Text::Encoding\>\& | Кодировка для генерации. Если кодировка **nullptr**, файл записывается в формате UTF-8, и атрибут кодировки опускается в **ProcessingInstruction**. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
