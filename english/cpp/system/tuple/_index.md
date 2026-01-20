---
title: System::Tuple class
linktitle: Tuple
second_title: Aspose.PDF for C++ API Reference
description: 'System::Tuple class. Class that represents a tuple data structure. Maximum number of items is 8 in C++.'
type: docs
weight: 6400
url: /cpp/system/tuple/
---
## Tuple class


Class that represents a tuple data structure. Maximum number of items is 8.

```cpp
template<typename ...>class Tuple : public System::Runtime::CompilerServices::ITuple
```


| Parameter | Description |
| --- | --- |
| Args | The tuple elements types. |
## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Determines if the current and the specified objects are identical. |
| [get_Item](./get_item/)() const | Gets the value of the [Tuple](./) object's component. |
| [Tuple](./tuple/)(Args...) | Constructs a tuple object. |
## Remarks



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::MakeObject<System::Tuple<int, int, int>>(32, 16, 128);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
This code example produces the following output:
Item 1: 32
Item 2: 16
Item 3: 128
*/
```

## See Also

* Class [ITuple](../../system.runtime.compilerservices/ituple/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
