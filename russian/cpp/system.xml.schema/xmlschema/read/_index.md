---
title: "Метод System::Xml::Schema::XmlSchema::Read"
linktitle: "Read"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Schema::XmlSchema::Read. Считывает XML Schema из предоставленного потока в C++."
type: docs
weight: 2900
url: /ru/cpp/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) method


Считывает XML [Schema](../../) из предоставленного потока.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const SharedPtr\<IO::Stream\>\& | Предоставленный поток данных. |
| validationEventHandler | ValidationEventHandler | Обработчик события проверки, получающий информацию об ошибках синтаксиса XML [Schema](../../). |

### ReturnValue

Объект [XmlSchema](../), представляющий XML [Schema](../../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [Stream](../../../system.io/stream/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) method


Считывает XML [Schema](../../) из предоставленного [IO::TextReader](../../../system.io/textreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | const SharedPtr\<IO::TextReader\>\& | [IO::TextReader](../../../system.io/textreader/), содержащий XML [Schema](../../) для чтения. |
| validationEventHandler | ValidationEventHandler | Обработчик события проверки, получающий информацию об ошибках синтаксиса XML [Schema](../../). |

### ReturnValue

Объект [XmlSchema](../), представляющий XML [Schema](../../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) method


Считывает XML [Schema](../../) из предоставленного [XmlReader](../../../system.xml/xmlreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/), содержащий XML [Schema](../../) для чтения. |
| validationEventHandler | ValidationEventHandler | Обработчик события проверки, получающий информацию об ошибках синтаксиса XML [Schema](../../). |

### ReturnValue

Объект [XmlSchema](../), представляющий XML [Schema](../../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
