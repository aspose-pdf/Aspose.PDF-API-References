---
title: System::Collections::BitArray::Enumerator class
linktitle: Enumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::BitArray::Enumerator class. Enumerator type for iteration purposes in C++.'
type: docs
weight: 2900
url: /cpp/system.collections/bitarray/enumerator/
---
## Enumerator class


[Enumerator](./) type for iteration purposes.

```cpp
class Enumerator : public virtual System::Object,
                   public System::Collections::Generic::IEnumerator<bool>
```

## Methods

| Method | Description |
| --- | --- |
| [Enumerator](./enumerator/)(const SharedPtr\<BitArray\>\&) | Creates enumerator. |
| [get_Current](./get_current/)() const override | Gets addressed bit in boolean form. |
| [MoveNext](./movenext/)() override | Moves to the next bit. |
| [Reset](./reset/)() override | Resets enumerator to position before first element. |
## See Also

* Class [Object](../../../system/object/)
* Class [IEnumerator](../../../system.collections.generic/ienumerator/)
* Class [BitArray](../)
* Namespace [System::Collections](../../)
* Library [Aspose.PDF for C++](../../../)
