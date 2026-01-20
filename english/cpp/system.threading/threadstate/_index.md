---
title: System::Threading::ThreadState enum
linktitle: ThreadState
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::ThreadState enum. State of the thread in C++.'
type: docs
weight: 2000
url: /cpp/system.threading/threadstate/
---
## ThreadState enum


State of the thread.

```cpp
enum class ThreadState
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Running | 0 | [Thread](../thread/) is running. |
| StopRequested | 1 | [Thread](../thread/) stop is requested. |
| SuspendRequested | 2 | [Thread](../thread/) suspension is requested. |
| Background | 4 | Theread is being executed in background. |
| Unstarted | 8 | [Thread](../thread/) is not started. |
| Stopped | 16 | [Thread](../thread/) is stopped. |
| WaitSleepJoin | 32 | [Thread](../thread/) is bein waited to be joined. |
| Suspended | 64 | [Thread](../thread/) is suspended. |
| AbortRequested | 128 | [Thread](../thread/) abortion is requested. |
| Aborted | 256 | [Thread](../thread/) is aborted. |

## See Also

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
