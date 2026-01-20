---
title: System::Boolean class
linktitle: Boolean
second_title: Aspose.PDF for C++ API Reference
description: 'System::Boolean class. Class that keeps static members of System.Boolean .Net type in C++.'
type: docs
weight: 600
url: /cpp/system/boolean/
---
## Boolean class


Class that keeps static members of [System.Boolean](./) .[Net](../../system.net/) type.

```cpp
class Boolean
```

## Methods

| Method | Description |
| --- | --- |
| static [Parse](./parse/)(const String\&) | Converts the specified string to a value of bool type. |
| static [TryParse](./tryparse/)(const String\&, bool\&) | Converts the specified string to a value of bool type. |
## Fields

| Field | Description |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) representation of 'false' boolean value. |
| static [TrueString](./truestring/) | [String](../string/) representation of 'true' boolean value. |
## Remarks



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Create the boolean variable.
  bool isWeekend = false;

  // Parse the input string and print the result.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
This code example produces the following output:
Is weekend: Yes
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
