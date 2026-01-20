---
title: System::Collections::BitArray class
linktitle: BitArray
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::BitArray class. Array of bits which can be addressed by index. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.collections/bitarray/
---
## BitArray class


[Array](../../system/array/) of bits which can be addressed by index. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BitArray : public virtual System::Object,
                 public System::Collections::Generic::ICollection<bool>
```

## Nested classes

* Class [Enumerator](./enumerator/)
* Class [Reference](./reference/)
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const bool\&) override | Adds value to the end of container. |
| [And](./and/)(const BitArrayPtr\&) | Calculates bitwise 'and' between two BitSets. |
| [BitArray](./bitarray/)(const bitset\&) | Copy constructor. |
| [BitArray](./bitarray/)(const BitArray\&) | Copy constructor. |
| [BitArray](./bitarray/)(const BitArrayPtr\&) | Copy constructor. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<bool\>\&) | Copy constructor. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<uint8_t\>\&) | Copy constructor. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<int\>\&) | Copy constructor. |
| [BitArray](./bitarray/)(int, bool) | Fill constructor. |
| [Clear](./clear/)() override | Deletes all elements. |
| [Contains](./contains/)(const bool\&) const override | Checks whether specific value is present in container. Not implemented. |
| [CopyTo](./copyto/)(System::ArrayPtr\<bool\>, int) override | Copies data to existing array elements. |
| [data](./data/)() | Underlying data structure access. |
| [data](./data/)() const | Underlying data structure access. |
| [Get](./get/)(int) const | Gets [BitArray](./) element. |
| [get_Count](./get_count/)() const override | Gets container size. |
| [get_Length](./get_length/)() const | Gets container size. |
| [GetEnumerator](./getenumerator/)() override | Creates enumerator object. |
| [idx_get](./idx_get/)(int) const | Getter function. |
| [idx_set](./idx_set/)(int, bool) | Setter function. |
| [Not](./not/)() | Negates BitSet. |
| [operator!=](./operator!=/)(const BitArray\&) const | Bitwise comparison operator. |
| [operator==](./operator==/)(const BitArray\&) const | Bitwise comparison operator. |
| [operator[]](./operator[]/)(int) | Accessor function. |
| [Or](./or/)(const BitArrayPtr\&) | Calculates bitwise 'or' between two BitSets. |
| [Remove](./remove/)(const bool\&) override | Returns first occurance of specified value. Not implemented. |
| [Set](./set/)(int, bool) | Sets [BitArray](./) element. |
| [SetAll](./setall/)(bool) | Sets all elements to specific value. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Formal implementation of weak template arguments mechanism; inapplicable to this class. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
| [Xor](./xor/)(const BitArrayPtr\&) | Calculates bitwise 'xor' between two BitSets. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [bitset](./bitset/) | RTTI information. |
## Remarks



```cpp
#include <system/collections/bitarray.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void Print(const System::SmartPtr<System::Collections::Generic::IEnumerable<bool>> &bitArray)
{
  for (const auto item: bitArray)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Constructs a new instance of the BitArray class.
  auto bitArray = MakeObject<System::Collections::BitArray>(3);

  // Print values.
  Print(bitArray);

  return 0;
}
/*
This code example produces the following output:
0 0 0
*/
```

## See Also

* Class [Object](../../system/object/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
