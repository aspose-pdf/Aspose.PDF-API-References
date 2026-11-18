---
title: System::CovariantCast method
linktitle: CovariantCast
second_title: Aspose.PDF for C++ API Reference
description: 'System::CovariantCast method. Performs covariant cast from some object to covariant interface which it implements in C++.'
type: docs
weight: 17700
url: /cpp/system/covariantcast/
---
## System::CovariantCast method


Performs covariant cast from some object to covariant interface which it implements.

```cpp
template<class From,class To> auto System::CovariantCast(const From &from)
```


| Parameter | Description |
| --- | --- |
| From | Type of the interface to cast from. |
| To | Type of the interface to cast to. |

| Parameter | Type | Description |
| --- | --- | --- |
| from | const From\& | [Object](../object/) that implements interface of type From to cast from. |

### ReturnValue

Proxy adapter that implements To interface and stores from object inside

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
