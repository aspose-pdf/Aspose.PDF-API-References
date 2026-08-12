---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke метод"
linktitle: "invoke"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke метод. Вызывает все делегаты, находящиеся в текущей коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Метод блокирует выполнение, пока делегаты исполняются в C++."
type: docs
weight: 1200
url: /ru/cpp/system/multicastdelegate_returntype(argumenttypes...)_/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke method


Вызывает все делегаты, находящиеся в текущий момент в коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Метод блокируется, пока делегаты выполняются.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| args | ArgumentTypes... | Аргументы, передаваемые вызываемым делегатам |

### ReturnValue

Возвращаемое значение последнего вызванного делегата

## См. также

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
