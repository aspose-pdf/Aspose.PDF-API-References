---
title: "System::Threading::Monitor::Enter метод"
linktitle: "Enter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Monitor::Enter метод. Получает эксклюзивную блокировку на указанном объекте в C++."
type: docs
weight: 100
url: /ru/cpp/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) method


Получает эксклюзивную блокировку указанного объекта.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const SharedPtr\<Object\>\& | Объект, на котором необходимо захватить мониторную блокировку. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) method


Получает эксклюзивную блокировку указанного объекта и атомарно устанавливает значение, указывающее, была ли блокировка получена.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
