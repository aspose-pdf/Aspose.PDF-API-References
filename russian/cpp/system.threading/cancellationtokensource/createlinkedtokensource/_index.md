---
title: "Метод System::Threading::CancellationTokenSource::CreateLinkedTokenSource"
linktitle: "CreateLinkedTokenSource"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::CancellationTokenSource::CreateLinkedTokenSource. Создаёт связанный источник токенов, который отменяется, когда любой из предоставленных токенов отменяется, в C++."
type: docs
weight: 600
url: /ru/cpp/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource method


Создаёт связанный источник токенов, который отменяется, когда любой из предоставленных токенов отменяется.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| token1 | const CancellationToken\& | Первый токен отмены для наблюдения. |
| token2 | const CancellationToken\& | Второй токен отмены для наблюдения. |

### ReturnValue

Новый источник токенов, который отменится, когда любой из входных токенов отменяется.
## Примечания



Возвращённый источник немедленно отменится, если любой из входных токенов уже отменён.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CancellationTokenSource](../)
* Class [CancellationToken](../../cancellationtoken/)
* Class [CancellationTokenSource](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
