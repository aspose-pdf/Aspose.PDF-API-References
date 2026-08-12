---
title: "Метод System::MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()"
linktitle: "operator()"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::MulticastDelegate< ReturnType(ArgumentTypes...)>::operator(). Вызывает все делегаты, находящиеся в текущей коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Оператор блокирует выполнение, пока делегаты не завершат работу в C++."
type: docs
weight: 1500
url: /ru/cpp/system/multicastdelegate_returntype(argumenttypes...)_/operator()/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator() method


Вызывает все делегаты, находящиеся в текущий момент в коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Оператор блокируется, пока делегаты выполняются.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
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
