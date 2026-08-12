---
title: "метод System::Xml::XmlConvert::ToDateTime"
linktitle: "ToDateTime"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlConvert::ToDateTime. Преобразует String в эквивалент DateTime в C++."
type: docs
weight: 1400
url: /ru/cpp/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) method


Преобразует [String](../../../system/string/) в эквивалент [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строка для преобразования. |

### ReturnValue

Эквивалент [DateTime](../../../system/datetime/) строки.

## См. также

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) method


Преобразует [String](../../../system/string/) в эквивалент [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строка для преобразования. |
| formats | const ArrayPtr\<String\>\& | Массив, содержащий структуры формата, применяемые к преобразованному [DateTime](../../../system/datetime/). Допустимые форматы включают "yyyy-MM-ddTHH:mm:sszzzzzz" и их подмножества. |

### ReturnValue

Эквивалент [DateTime](../../../system/datetime/) строки.

## См. также

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const String\&) method


Преобразует [String](../../../system/string/) в эквивалент [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Строка для преобразования. |
| format | const String\& | Структура формата, применяемая к преобразованному [DateTime](../../../system/datetime/). Допустимые форматы включают "yyyy-MM-ddTHH:mm:sszzzzzz" и их подмножества. Строка проверяется на соответствие этому формату. |

### ReturnValue

Эквивалент [DateTime](../../../system/datetime/) строки.

## См. также

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) method


Преобразует [String](../../../system/string/) в [DateTime](../../../system/datetime/) с использованием указанного [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const String\& | Значение [String](../../../system/string/) для преобразования. |
| dateTimeOption | XmlDateTimeSerializationMode | Одно из значений перечисления, указывающее, следует ли преобразовать дату к локальному времени или сохранить её как всемирное координированное время (UTC), если это дата в формате UTC. |

### ReturnValue

Эквивалент [DateTime](../../../system/datetime/) для [String](../../../system/string/).

## См. также

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
