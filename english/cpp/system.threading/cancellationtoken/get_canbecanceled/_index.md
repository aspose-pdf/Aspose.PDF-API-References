---
title: System::Threading::CancellationToken::get_CanBeCanceled method
linktitle: get_CanBeCanceled
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::CancellationToken::get_CanBeCanceled method. Gets whether this token is capable of being in the canceled state in C++.'
type: docs
weight: 200
url: /cpp/system.threading/cancellationtoken/get_canbecanceled/
---
## CancellationToken::get_CanBeCanceled method


Gets whether this token is capable of being in the canceled state.

```cpp
bool System::Threading::CancellationToken::get_CanBeCanceled() const
```


### ReturnValue

true if this token is capable of being in the canceled state; otherwise, false.
## Remarks



Tokens created from [CancellationTokenSource](../../cancellationtokensource/) will return true, while the None token will always return false. 

## See Also

* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
