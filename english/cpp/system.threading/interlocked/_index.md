---
title: System::Threading::Interlocked class
linktitle: Interlocked
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Interlocked class. Provides API for thread-safe operations. This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 600
url: /cpp/system.threading/interlocked/
---
## Interlocked class


Provides API for thread-safe operations. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Interlocked
```

## Methods

| Method | Description |
| --- | --- |
| static [Add](./add/)(int32_t\&, int32_t) | Increases value atomically. |
| static [Add](./add/)(int64_t\&, int64_t) | Increases value atomically. |
| static [CompareExchange](./compareexchange/)(T\&, T, T) | Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected. |
| static [CompareExchange](./compareexchange/)(T\&, T, T) | Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected. Not implemented. |
| static [CompareExchange](./compareexchange/)(int32_t\&, int32_t, int32_t, bool\&) | Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected. |
| static [Decrement](./decrement/)(int32_t\&) | Decrements value atomically. |
| static [Decrement](./decrement/)(int64_t\&) | Decrements value atomically. |
| static [Exchange](./exchange/)(T\&, T) | Exchanges value on variable: stores new value and returns the value variable had immediately before storing. |
| static [Exchange](./exchange/)(T\&, T) | Exchanges value on variable: stores new value and returns the value variable had immediately before storing. Not implemented. |
| static [ExchangeAdd](./exchangeadd/)(int32_t\&, int32_t) | Increases value atomically via exchange-add procedure. |
| static [ExchangeAdd](./exchangeadd/)(int64_t\&, int64_t) | Increases value atomically via exchange-add procedure. |
| static [Increment](./increment/)(int32_t\&) | Increments value atomically. |
| static [Increment](./increment/)(int64_t\&) | Increments value atomically. |
| static [Read](./read/)(int64_t\&) | Returns a 64-bit value, loaded as an atomic operation. |
## See Also

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
