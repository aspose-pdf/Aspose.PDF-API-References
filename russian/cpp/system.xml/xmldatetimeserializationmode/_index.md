---
title: "System::Xml::XmlDateTimeSerializationMode перечисление"
linktitle: "XmlDateTimeSerializationMode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlDateTimeSerializationMode перечисление. Указывает, как обрабатывать значение времени при преобразовании между строкой и DateTime в C++."
type: docs
weight: 5800
url: /ru/cpp/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum


Указывает, как обрабатывать значение времени при преобразовании между строкой и [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Local | 0 | Обрабатывать как локальное время. Если объект [DateTime](../../system/datetime/) представляет собой всемирное координированное время (UTC), он преобразуется в локальное время. |
| Utc | 1 | Обрабатывать как UTC. Если объект [DateTime](../../system/datetime/) представляет локальное время, он преобразуется в UTC. |
| Unspecified | 2 | Обрабатывать как локальное время, если [DateTime](../../system/datetime/) преобразуется в строку. Если строка преобразуется в [DateTime](../../system/datetime/), преобразуйте в локальное время, если указан часовой пояс. |
| RoundtripKind | 3 | Информация о часовом поясе должна сохраняться при преобразовании. |

## См. также

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
