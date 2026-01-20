---
title: System::ArraySegment class
linktitle: ArraySegment
second_title: Aspose.PDF for C++ API Reference
description: 'System::ArraySegment class. Represents a segment of the one-dimensional array. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 300
url: /cpp/system/arraysegment/
---
## ArraySegment class


Represents a segment of the one-dimensional array. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
template<typename T>class ArraySegment : public System::Object
```


| Parameter | Description |
| --- | --- |
| T | The type of the array segment elements. |
## Methods

| Method | Description |
| --- | --- |
| [ArraySegment](./arraysegment/)(System::ArrayPtr\<T\>) |  |
| [ArraySegment](./arraysegment/)(System::ArrayPtr\<T\>, int32_t, int32_t) |  |
| [ArraySegment](./arraysegment/)() |  |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(ArraySegment\<T\>) |  |
| [get_Array](./get_array/)() |  |
| [get_Count](./get_count/)() |  |
| [get_Offset](./get_offset/)() |  |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../object/gethashcode/) method. Enables hashing of custom objects. |
## Remarks



```cpp
#include <system/array_segment.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<ArraySegment<String>> &segment)
{
  for (auto i = segment->get_Offset(); i < segment->get_Offset() + segment->get_Count(); i++)
  {
    std::cout << segment->get_Array()[i] << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Create and fill the array.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // Create the array segment that contains the entire array.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // Print the array segment items.
  Print(fullArray);

  // Create the array segment.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // Print the array segment items.
  Print(segment);

  return 0;
}
/*
This code example produces the following output:
First Second Third
Second Third
*/
```

## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
