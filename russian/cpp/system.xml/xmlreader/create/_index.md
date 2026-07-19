---
title: "System::Xml::XmlReader::Create метод"
linktitle: "Создать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::Create метод. Создаёт новый экземпляр XmlReader, используя указанный поток с настройками по умолчанию в C++."
type: docs
weight: 7700
url: /ru/cpp/system.xml/xmlreader/create/
---
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) method


Создаёт новый экземпляр [XmlReader](../), используя указанный поток с настройками по умолчанию.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | Поток, содержащий данные XML. Класс [XmlReader](../) сканирует первые байты потока в поисках маркера порядка байтов или другого признака кодировки. Когда кодировка определена, она используется для продолжения чтения потока, и обработка продолжается, разбирая ввод как поток (Unicode) символов. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) method


Создаёт новый экземпляр [XmlReader](../) с указанным потоком и настройками.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | Поток, содержащий данные XML. Класс [XmlReader](../) сканирует первые байты потока в поисках маркера порядка байтов или другого признака кодировки. Когда кодировка определена, она используется для продолжения чтения потока, и обработка продолжается, разбирая ввод как поток (Unicode) символов. |
| settings | const SharedPtr\<XmlReaderSettings\>\& | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Создаёт новый экземпляр [XmlReader](../), используя указанный поток, настройки и контекстную информацию для разбора.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | Поток, содержащий данные XML. Класс [XmlReader](../) сканирует первые байты потока в поисках маркера порядка байтов или другого признака кодировки. Когда кодировка определена, она используется для продолжения чтения потока, и обработка продолжается, разбирая ввод как поток (Unicode) символов. |
| settings | SharedPtr\<XmlReaderSettings\> | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | Контекстная информация, необходимая для разбора фрагмента XML. Контекст может включать [XmlNameTable](../../xmlnametable/) для использования, кодировку, область имён, текущие области **xml:lang** и **xml:space**, базовый URI и определение типа документа. Это значение может быть **nullptr**. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method


Создаёт новый экземпляр [XmlReader](../), используя указанный поток, базовый URI и настройки.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | Поток, содержащий данные XML. Класс [XmlReader](../) сканирует первые байты потока в поисках маркера порядка байтов или другого признака кодировки. Когда кодировка определена, она используется для продолжения чтения потока, и обработка продолжается, разбирая ввод как поток (Unicode) символов. |
| settings | SharedPtr\<XmlReaderSettings\> | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |
| baseUri | const String\& | Базовый URI для читаемого сущности или документа. Это значение может быть **nullptr**. **[Security](../../../system.security/) Note** Базовый URI используется для разрешения относительного URI XML‑документа. Не используйте базовый URI из ненадёжного источника. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) method


Создаёт новый экземпляр [XmlReader](../), используя указанный текстовый читатель.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | Текстовый читатель, из которого читаются данные XML. Текстовый читатель возвращает поток Unicode‑символов, поэтому кодировка, указанная в объявлении XML, не используется XML‑чтителем для декодирования потока данных. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) method


Создаёт новый экземпляр [XmlReader](../), используя указанный текстовый читатель и настройки.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | Текстовый читатель, из которого читаются данные XML. Текстовый читатель возвращает поток Unicode‑символов, поэтому кодировка, указанная в объявлении XML, не используется XML‑чтителем для декодирования потока данных. |
| settings | const SharedPtr\<XmlReaderSettings\>\& | Настройки для нового [XmlReader](../). Это значение может быть **nullptr**. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Создаёт новый экземпляр [XmlReader](../), используя указанный текстовый читатель, настройки и контекстную информацию для разбора.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | Текстовый читатель, из которого читаются данные XML. Текстовый читатель возвращает поток Unicode‑символов, поэтому кодировка, указанная в объявлении XML, не используется XML‑чтителем для декодирования потока данных. |
| settings | SharedPtr\<XmlReaderSettings\> | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | Контекстная информация, необходимая для разбора фрагмента XML. Контекст может включать [XmlNameTable](../../xmlnametable/) для использования, кодировку, область имён, текущие области **xml:lang** и **xml:space**, базовый URI и определение типа документа. Это значение может быть **nullptr**. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method


Создаёт новый экземпляр [XmlReader](../), используя указанный текстовый читатель, настройки и базовый URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | Текстовый читатель, из которого читаются данные XML. Текстовый читатель возвращает поток Unicode‑символов, поэтому кодировка, указанная в объявлении XML, не используется [XmlReader](../) для декодирования потока данных. |
| settings | SharedPtr\<XmlReaderSettings\> | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |
| baseUri | const String\& | Базовый URI для читаемого сущности или документа. Это значение может быть **nullptr**. **[Security](../../../system.security/) Note** Базовый URI используется для разрешения относительного URI XML‑документа. Не используйте базовый URI из ненадёжного источника. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) method


Создаёт новый экземпляр [XmlReader](../), используя указанный XML‑чтатель и настройки.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| чтитель | const SharedPtr\\<XmlReader\\>\\& | Объект, который вы хотите использовать в качестве базового XML‑чтителя. |
| settings | SharedPtr\<XmlReaderSettings\> | Настройки для нового экземпляра [XmlReader](../). Уровень соответствия объекта [XmlReaderSettings](../../xmlreadersettings/) должен либо совпадать с уровнем соответствия базового читателя, либо быть установлен в [ConformanceLevel::Auto](../../conformancelevel/). |

### ReturnValue

Объект, обёрнутый вокруг указанного объекта [XmlReader](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&) method


Создаёт новый экземпляр [XmlReader](../) с указанным URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const String\& | URI файла, содержащего данные XML. Класс [XmlUrlResolver](../../xmlurlresolver/) используется для преобразования пути в каноническое представление данных. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) method


Создаёт новый экземпляр [XmlReader](../), используя указанный URI и настройки.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const String\& | URI файла, содержащего данные XML. Объект [XmlResolver](../../xmlresolver/) на объекте [XmlReaderSettings](../../xmlreadersettings/) используется для преобразования пути в каноническое представление данных. Если значение XmlReaderSettings::get_XmlResolver равно **nullptr**, используется новый объект [XmlUrlResolver](../../xmlurlresolver/). |
| settings | const SharedPtr\<XmlReaderSettings\>\& | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Создаёт новый экземпляр [XmlReader](../), используя указанный URI, настройки и контекстную информацию для разбора.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const String\& | URI файла, содержащего данные XML. Объект [XmlResolver](../../xmlresolver/) на объекте [XmlReaderSettings](../../xmlreadersettings/) используется для преобразования пути в каноническое представление данных. Если значение XmlReaderSettings::get_XmlResolver равно **nullptr**, используется новый объект [XmlUrlResolver](../../xmlurlresolver/). |
| settings | SharedPtr\<XmlReaderSettings\> | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | Контекстная информация, необходимая для разбора фрагмента XML. Контекст может включать [XmlNameTable](../../xmlnametable/) для использования, кодировку, область имён, текущие области **xml:lang** и **xml:space**, базовый URI и определение типа документа. Это значение может быть **nullptr**. |

### ReturnValue

Объект, используемый для чтения данных XML в потоке.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
