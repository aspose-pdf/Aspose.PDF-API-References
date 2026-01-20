---
title: System::Threading::CancellationTokenSource::CreateLinkedTokenSource method
linktitle: CreateLinkedTokenSource
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::CancellationTokenSource::CreateLinkedTokenSource method. Creates a linked token source that cancels when any of the provided tokens cancel in C++.'
type: docs
weight: 600
url: /cpp/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource method


Creates a linked token source that cancels when any of the provided tokens cancel.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```


| Parameter | Type | Description |
| --- | --- | --- |
| token1 | const CancellationToken\& | First cancellation token to monitor. |
| token2 | const CancellationToken\& | Second cancellation token to monitor. |

### ReturnValue

New token source that will cancel when either input token cancels.
## Remarks



The returned source will immediately cancel if either input token is already canceled. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CancellationTokenSource](../)
* Class [CancellationToken](../../cancellationtoken/)
* Class [CancellationTokenSource](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
