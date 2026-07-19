---
title: "System::TupleFactory::Create method"
linktitle: "Создать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::TupleFactory::Create method. Создаёт новый объект кортежа в C++."
type: docs
weight: 100
url: /ru/cpp/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) method


Создаёт новый объект кортежа.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Tuple](../../tuple/)
* Class [TupleFactory](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) method


Создаёт новый 8‑кортеж. 8‑й элемент хранится внутри [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Tuple](../../tuple/)
* Class [TupleFactory](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
