---
title: "System::Net::Sockets::Socket::Poll метод"
linktitle: "Poll"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket::Poll метод. Возвращает состояние сокета в зависимости от указанного режима опроса в C++."
type: docs
weight: 4200
url: /ru/cpp/system.net.sockets/socket/poll/
---
## Socket::Poll method


Возвращает статус сокета на основе указанного режима опроса.

```cpp
bool System::Net::Sockets::Socket::Poll(int32_t microSeconds, SelectMode mode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| микросекунды | int32_t | Количество времени в миллисекундах, которое следует ждать ответа. |
| режим | SelectMode | Режим опроса. |

### ReturnValue

Состояние сокета в зависимости от указанного режима опроса.

## См. также

* Enum [SelectMode](../../selectmode/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
