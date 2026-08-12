---
title: "System::Net::Sockets::SocketFlags enum"
linktitle: "SocketFlags"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::SocketFlags enum. Предоставляет постоянные значения для сообщений сокета в C++."
type: docs
weight: 1400
url: /ru/cpp/system.net.sockets/socketflags/
---
## SocketFlags enum


Предоставляет константные значения для сообщений сокета.

```cpp
enum class SocketFlags
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Для этого вызова не используются флаги. |
| OutOfBand | 1 | Обрабатываются данные вне канала. |
| Peek | 2 | Просмотр входящего сообщения. |
| DontRoute | 4 | Отправить сообщение без использования таблиц маршрутизации. |
| Truncated | 256 | Сообщение слишком велико, чтобы поместиться в указанный буфер. Оно было усечено. |
| ControlDataTruncated | 512 | Контрольные данные превышают 64 КБ и не помещаются во внутренний буфер. Они были усечены. |
| Broadcast | 1024 | Трансляционный пакет. |
| Мультикаст | 2048 | Мультикастовый пакет. |
| Частичный | 32768 | Сообщение, отправленное или полученное частично. |

## См. также

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
