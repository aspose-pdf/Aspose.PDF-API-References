---
title: System::Collections::Generic::Dictionary::Enumerator class
linktitle: Enumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::Dictionary::Enumerator class. Enumerator that allows iterating through the dictionary. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.collections.generic/dictionary/enumerator/
---
## Enumerator class


[Enumerator](./) that allows iterating through the dictionary. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public System::Collections::Generic::SimpleEnumerator<map_t, KVPair>
```

## Methods

| Method | Description |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | RTTI information. |
| [Enumerator](./enumerator/)(Ptr) | Creates enumerator. |
## See Also

* Class [SimpleEnumerator](../../simpleenumerator/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
