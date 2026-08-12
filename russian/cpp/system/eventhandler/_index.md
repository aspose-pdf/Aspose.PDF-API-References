---
title: "System::EventHandler typedef"
linktitle: "EventHandler"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::EventHandler typedef. Представляет метод, который реагирует на событие и обрабатывает его. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 11800
url: /ru/cpp/system/eventhandler/
---
## EventHandler typedef


Представляет метод, который реагирует на событие и обрабатывает его. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
using System::EventHandler =  MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
