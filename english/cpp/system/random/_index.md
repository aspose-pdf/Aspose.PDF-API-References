---
title: System::Random class
linktitle: Random
second_title: Aspose.PDF for C++ API Reference
description: 'System::Random class. Represents a pseudo-random number generator. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 5200
url: /cpp/system/random/
---
## Random class


Represents a pseudo-random number generator. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Random : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [IsNull](./isnull/)() const | Always returns false. |
| virtual [Next](./next/)() | Returns a nonnegative random number less then int32 max value. |
| virtual [Next](./next/)(int32_t) | Returns a nonnegative random number less than the specified maximum. |
| virtual [Next](./next/)(int32_t, int32_t) | Returns a random number within the specified range. |
| virtual [NextBytes](./nextbytes/)(const ArrayPtr\<uint8_t\>\&) | Fills the elements of the specified array of bytes with random numbers. |
| virtual [NextDouble](./nextdouble/)() | Returns a random number between 0.0 and 1.0. |
| [Random](./random/)() | Initializes a new instance, using a time-dependent default seed value. |
| [Random](./random/)(int32_t) | Initializes a new instance of the [System.Random](./) class, using the specified seed value. |
## Remarks



```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // Get a random month number and print it.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // Fill the array with random numbers.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // Print the array.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
This code example produces the following output:
Month: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
