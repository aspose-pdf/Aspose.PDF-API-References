---
title: System::Buffers::SearchValues class
linktitle: SearchValues
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::SearchValues class. Provides an immutable, read-only set of values optimized for efficient searching. Values are stored in a hash set, so Contains() performs an average O(1) lookup in C++.'
type: docs
weight: 900
url: /cpp/system.buffers/searchvalues/
---
## SearchValues class


Provides an immutable, read-only set of values optimized for efficient searching. Values are stored in a hash set, so [Contains()](./contains/) performs an average O(1) lookup.

```cpp
template<typename T>class SearchValues : public System::Object
```


| Parameter | Description |
| --- | --- |
| T | The type of the values to search for. |
## Methods

| Method | Description |
| --- | --- |
| [Contains](./contains/)(T) const | Determines whether the specified value is contained in the set. |
| static [Create](./create/)(const ReadOnlySpan\<T\>\&) | Creates a [SearchValues](./) instance from the specified set of values. |
| [SearchValues](./searchvalues/)() | Constructs an empty [SearchValues](./) instance. |

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Buffers](../)
* Library [Aspose.PDF for C++](../../)
