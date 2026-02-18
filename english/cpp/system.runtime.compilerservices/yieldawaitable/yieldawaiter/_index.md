---
title: System::Runtime::CompilerServices::YieldAwaitable::YieldAwaiter class
linktitle: YieldAwaiter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::CompilerServices::YieldAwaitable::YieldAwaiter class. The awaiter type for YieldAwaitable in C++.'
type: docs
weight: 200
url: /cpp/system.runtime.compilerservices/yieldawaitable/yieldawaiter/
---
## YieldAwaiter class


The awaiter type for [YieldAwaitable](../).

```cpp
class YieldAwaiter
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsCompleted](./get_iscompleted/)() const | Gets whether the yield operation has completed. |
| [GetResult](./getresult/)() const | Ends the await operation. |
| [OnCompleted](./oncompleted/)(const Action<>\&) | Schedules the continuation action for when the yield operation completes. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [continueOnCapturedContext](./continueoncapturedcontext/) | Specifies whether to continue on the captured synchronization context. |
## See Also

* Class [YieldAwaitable](../)
* Namespace [System::Runtime::CompilerServices](../../)
* Library [Aspose.PDF for C++](../../../)
