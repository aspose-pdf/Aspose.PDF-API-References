---
title: "System::Threading::Semaphore::Semaphore конструктор"
linktitle: "Semaphore"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Semaphore::Semaphore конструктор. Информация RTTI в C++."
type: docs
weight: 100
url: /ru/cpp/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) constructor


Информация RTTI.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| initialCount | int | Начальное количество активных записей. |
| maximumCount | int | Максимальное количество разрешённых записей. |
## Примечания


Создаёт безымянный семафор.
## См. также

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Semaphore::Semaphore(int, int, const String\&) constructor


Создаёт именованный семафор.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| initialCount | int | Начальное количество активных записей. |
| maximumCount | int | Максимальное количество разрешённых записей. |
| name | const String\& | [Semaphore](../) имя. |

## См. также

* Class [String](../../../system/string/)
* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Semaphore::Semaphore(int, int, const String\&, bool\&) constructor


Создаёт именованный семафор.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| initialCount | int | Начальное количество активных записей. |
| maximumCount | int | Максимальное количество разрешённых записей. |
| name | const String\& | [Semaphore](../) имя. |
| createdNew | bool\& | Ссылка на переменную, которая устанавливается в true, если семафор был создан, и в false, если был использован существующий с тем же именем. |

## См. также

* Class [String](../../../system/string/)
* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
