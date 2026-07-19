---
title: "System::Xml::XmlWriter::Create метод"
linktitle: "Создать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlWriter::Create метод. Создаёт новый экземпляр XmlWriter, используя указанный поток в C++."
type: docs
weight: 3700
url: /ru/cpp/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) method


Создаёт новый экземпляр [XmlWriter](../) с использованием указанного потока.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| output | const SharedPtr\<IO::Stream\>\& | Поток, в который вы хотите записывать. [XmlWriter](../) записывает текстовый синтаксис XML 1.0 и добавляет его в указанный поток. |

### ReturnValue

Объект [XmlWriter](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) method


Создаёт новый экземпляр [XmlWriter](../), используя поток и объект [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| output | const SharedPtr\<IO::Stream\>\& | Поток, в который вы хотите записывать. [XmlWriter](../) записывает текстовый синтаксис XML 1.0 и добавляет его в указанный поток. |
| settings | SharedPtr\<XmlWriterSettings\> | Объект [XmlWriterSettings](../../xmlwritersettings/), используемый для настройки нового экземпляра [XmlWriter](../). Если он равен **nullptr**, используется [XmlWriterSettings](../../xmlwritersettings/) с настройками по умолчанию. Если [XmlWriter](../) используется с методом XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), следует использовать значение XslCompiledTransform::get_OutputSettings для получения объекта [XmlWriterSettings](../../xmlwritersettings/) с корректными настройками. Это гарантирует, что созданный объект [XmlWriter](../) имеет правильные параметры вывода. |

### ReturnValue

Объект [XmlWriter](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) method


Создаёт новый экземпляр [XmlWriter](../), используя указанный TextWriter.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| output | const SharedPtr\<IO::TextWriter\>\& | TextWriter, в который вы хотите записывать. [XmlWriter](../) записывает текстовый синтаксис XML 1.0 и добавляет его в указанный TextWriter. |

### ReturnValue

Объект [XmlWriter](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) method


Создаёт новый экземпляр [XmlWriter](../), используя TextWriter и объекты [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| output | const SharedPtr\<IO::TextWriter\>\& | TextWriter, в который вы хотите записывать. [XmlWriter](../) записывает текстовый синтаксис XML 1.0 и добавляет его в указанный TextWriter. |
| settings | SharedPtr\<XmlWriterSettings\> | Объект [XmlWriterSettings](../../xmlwritersettings/), используемый для настройки нового экземпляра [XmlWriter](../). Если он равен **nullptr**, используется [XmlWriterSettings](../../xmlwritersettings/) с настройками по умолчанию. Если [XmlWriter](../) используется с методом XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), следует использовать значение XslCompiledTransform::get_OutputSettings для получения объекта [XmlWriterSettings](../../xmlwritersettings/) с корректными настройками. Это гарантирует, что созданный объект [XmlWriter](../) имеет правильные параметры вывода. |

### ReturnValue

Объект [XmlWriter](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) method


Создаёт новый экземпляр [XmlWriter](../), используя указанный [Text::StringBuilder](../../../system.text/stringbuilder/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| output | const SharedPtr\<Text::StringBuilder\>\& | Объект [Text::StringBuilder](../../../system.text/stringbuilder/), в который следует записывать. Содержимое, записанное [XmlWriter](../), добавляется к [Text::StringBuilder](../../../system.text/stringbuilder/). |

### ReturnValue

Объект [XmlWriter](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) method


Создаёт новый экземпляр [XmlWriter](../), используя [Text::StringBuilder](../../../system.text/stringbuilder/) и объекты [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| output | const SharedPtr\<Text::StringBuilder\>\& | Объект [Text::StringBuilder](../../../system.text/stringbuilder/), в который следует записывать. Содержимое, записанное [XmlWriter](../), добавляется к [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | SharedPtr\<XmlWriterSettings\> | Объект [XmlWriterSettings](../../xmlwritersettings/), используемый для настройки нового экземпляра [XmlWriter](../). Если он равен **nullptr**, используется [XmlWriterSettings](../../xmlwritersettings/) с настройками по умолчанию. Если [XmlWriter](../) используется с методом XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), следует использовать значение XslCompiledTransform::get_OutputSettings для получения объекта [XmlWriterSettings](../../xmlwritersettings/) с корректными настройками. Это гарантирует, что созданный объект [XmlWriter](../) имеет правильные параметры вывода. |

### ReturnValue

Объект [XmlWriter](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) method


Создаёт новый экземпляр [XmlWriter](../), используя указанный объект [XmlWriter](../).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| output | const SharedPtr\<XmlWriter\>\& | Объект [XmlWriter](../), который вы хотите использовать в качестве базового записывающего устройства. |

### ReturnValue

Объект [XmlWriter](../), обёрнутый вокруг указанного объекта [XmlWriter](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) method


Создаёт новый экземпляр [XmlWriter](../), используя указанные объекты [XmlWriter](../) и [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| output | const SharedPtr\<XmlWriter\>\& | Объект [XmlWriter](../), который вы хотите использовать в качестве базового записывающего устройства. |
| settings | SharedPtr\<XmlWriterSettings\> | Объект [XmlWriterSettings](../../xmlwritersettings/), используемый для настройки нового экземпляра [XmlWriter](../). Если он равен **nullptr**, используется [XmlWriterSettings](../../xmlwritersettings/) с настройками по умолчанию. Если [XmlWriter](../) используется с методом XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), следует использовать значение XslCompiledTransform::get_OutputSettings для получения объекта [XmlWriterSettings](../../xmlwritersettings/) с корректными настройками. Это гарантирует, что созданный объект [XmlWriter](../) имеет правильные параметры вывода. |

### ReturnValue

Объект [XmlWriter](../), обёрнутый вокруг указанного объекта [XmlWriter](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const String\&) method


Создаёт новый экземпляр [XmlWriter](../), используя указанное имя файла.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | const String\& | Файл, в который вы хотите записывать. [XmlWriter](../) создаёт файл по указанному пути и записывает в него текстовый синтаксис XML 1.0. Параметр **outputFileName** должен быть путём в файловой системе. |

### ReturnValue

Объект [XmlWriter](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) method


Создает новый экземпляр [XmlWriter](../), используя имя файла и объект [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | const String\& | Файл, в который вы хотите записывать. [XmlWriter](../) создаёт файл по указанному пути и записывает в него текстовый синтаксис XML 1.0. Параметр **outputFileName** должен быть путём в файловой системе. |
| settings | SharedPtr\<XmlWriterSettings\> | Объект [XmlWriterSettings](../../xmlwritersettings/), используемый для настройки нового экземпляра [XmlWriter](../). Если он равен **nullptr**, используется [XmlWriterSettings](../../xmlwritersettings/) с настройками по умолчанию. Если [XmlWriter](../) используется с методом XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), следует использовать значение XslCompiledTransform::get_OutputSettings для получения объекта [XmlWriterSettings](../../xmlwritersettings/) с корректными настройками. Это гарантирует, что созданный объект [XmlWriter](../) имеет правильные параметры вывода. |

### ReturnValue

Объект [XmlWriter](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
