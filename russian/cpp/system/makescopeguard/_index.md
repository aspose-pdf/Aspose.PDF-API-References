---
title: "Метод System::MakeScopeGuard"
linktitle: "MakeScopeGuard"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::MakeScopeGuard. Фабричная функция, создающая экземпляры класса ScopedGuard в C++."
type: docs
weight: 25500
url: /ru/cpp/system/makescopeguard/
---
## System::MakeScopeGuard method


Фабричная функция, создающая экземпляры класса ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


| Параметр | Описание |
| --- | --- |
| Эта | тип объект-функции, который будет вызван сконструированным объектом ScopedGuard |

| Параметр | Тип | Описание |
| --- | --- | --- |
| f | F | Объект-функция, передаваемый в конструктор класса ScopedGuard. |

### ReturnValue

Новый экземпляр класса ScopedGuard

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
