---
title: "System::TupleFactory::Create method"
linktitle: "Skapa"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TupleFactory::Create method. Skapar ett nytt tuple-objekt i C++."
type: docs
weight: 100
url: /sv/cpp/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) method


Skapar ett nytt tuple-objekt.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Tuple](../../tuple/)
* Class [TupleFactory](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) method


Skapar en ny 8-tuple. Det åttonde elementet lagras i [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Tuple](../../tuple/)
* Class [TupleFactory](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
