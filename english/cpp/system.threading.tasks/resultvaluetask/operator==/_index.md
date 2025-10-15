---
title: System::Threading::Tasks::ResultValueTask::operator== method
linktitle: operator==
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultValueTask::operator== method. Equality operator for ResultValueTask in C++.'
type: docs
weight: 1200
url: /cpp/system.threading.tasks/resultvaluetask/operator==/
---
## ResultValueTask::operator== method


Equality operator for [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| other | const ResultValueTask\& | The other [ResultValueTask](../) to compare with this instance. |

### ReturnValue

bool True if both tasks have the same result value or reference the same underlying task; otherwise, false.
## Remarks



If either instance contains a direct result value, compares the results directly. Otherwise, compares the underlying task pointers. 
## See Also

* Class [ResultValueTask](../)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
