---
title: System::Predicate typedef
linktitle: Predicate
second_title: Aspose.PDF for C++ API Reference
description: 'System::Predicate typedef. Represents a pointer to a predicate - an invokable entity that accepts a single argument and returns a bool value in C++.'
type: docs
weight: 12600
url: /cpp/system/predicate/
---
## Predicate typedef


Represents a pointer to a predicate - an invokable entity that accepts a single argument and returns a bool value.

```cpp
using System::Predicate =  MulticastDelegate<bool(T)>
```

## Remarks



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Fill the array.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Create the predicate that returns an array element that is greater than 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Find the first element of the array using the created predicate and print it.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
This code example produces the following output:
5
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
