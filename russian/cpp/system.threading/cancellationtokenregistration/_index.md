---
title: "System::Threading::CancellationTokenRegistration class"
linktitle: "CancellationTokenRegistration"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::CancellationTokenRegistration class. Представляет регистрацию обратного вызова токена отмены в C++."
type: docs
weight: 300
url: /ru/cpp/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration class


Представляет регистрацию обратного вызова токена отмены.

```cpp
class CancellationTokenRegistration
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() | Уничтожает регистрацию и удаляет обратный вызов из связанного [CancellationTokenSource](../cancellationtokensource/). После вызова этого метода зарегистрированный обратный вызов больше не будет вызываться, когда связанный [CancellationTokenSource](../cancellationtokensource/) будет отменён. |
## Примечания


Этот класс позволяет отменить регистрацию обратного вызова из токена отмены. При уничтожении он удаляет обратный вызов из связанного [CancellationTokenSource](../cancellationtokensource/).
Этот класс не должен создаваться напрямую — он возвращается методами регистрации [CancellationToken](../cancellationtoken/).

## См. также

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
