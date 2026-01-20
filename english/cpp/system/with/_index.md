---
title: System::With method
linktitle: With
second_title: Aspose.PDF for C++ API Reference
description: 'System::With method. Clones reference record and applies initializer functor to it in C++.'
type: docs
weight: 44100
url: /cpp/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) method


Clones reference record and applies initializer functor to it.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


| Parameter | Description |
| --- | --- |
| T | Record type to clone. |
| A | Initialization functor type. |

| Parameter | Type | Description |
| --- | --- | --- |
| record | const SharedPtr\<T\>\& | Shared pointer to the object to clone and initialize. |
| initializer | const A\& | Initialization functor being applied to record clone. |

### ReturnValue

Shared pointer to cloned record.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::With(const T\&, const A\&) method


Copies struct record and applies initializer functor to it.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


| Parameter | Description |
| --- | --- |
| T | Record type to copy. |
| A | Initialization functor type. |

| Parameter | Type | Description |
| --- | --- | --- |
| record | const T\& | Record to copy and initialize. |
| initializer | const A\& | Initialization functor being applied to record copy. |

### ReturnValue

Copied record.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
