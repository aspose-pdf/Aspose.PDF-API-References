---
title: "Перечисление System::UriComponents"
linktitle: "UriComponents"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление System::UriComponents. Представляет компоненты URI в C++."
type: docs
weight: 9200
url: /ru/cpp/system/uricomponents/
---
## UriComponents enum


Представляет компоненты URI.

```cpp
enum class UriComponents
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Схема | 1 | Данные Scheme. |
| UserInfo | 2 | Данные UserInfo. |
| Хост | 4 | Данные Host. |
| Port | 8 | Данные Port. |
| SchemeAndServer | n/a | Данные Scheme, Host и Port. |
| Path | 16 | Данные LocalPath. |
| Запрос | 32 | Данные Query. |
| PathAndQuery | n/a | Данные LocalPath и Query. |
| HttpRequestUrl | n/a | Данные Scheme, Host, Port, Query и LocalPath. |
| Fragment | 64 | Данные Fragment. |
| AbsoluteUri | n/a | Данные Scheme, Host, Port, Quer, LocalPath и Fragment. |
| StrongPort | 128 | Данные Port; если данные порта отсутствуют в [Uri](../uri/) и схеме был назначен порт по умолчанию, возвращается порт по умолчанию; если порта по умолчанию нет, возвращается -1. |
| HostAndPort | n/a | Данные Host и Port; если данные порта отсутствуют в [Uri](../uri/) и схеме был назначен порт по умолчанию, возвращается порт по умолчанию. Если порта по умолчанию нет, возвращается -1. |
| StrongAuthority | n/a | Данные UserInfo, Host и Port. Если данные порта отсутствуют в [Uri](../uri/) и схеме был назначен порт по умолчанию, возвращается порт по умолчанию. Если порта по умолчанию нет, возвращается -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Указывает, что разделитель должен быть включён. |
| SerializationInfoString | n/a | Полный контекст [Uri](../uri/), необходимый для сериализаторов [Uri](../uri/). Контекст включает область IPv6. |

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
