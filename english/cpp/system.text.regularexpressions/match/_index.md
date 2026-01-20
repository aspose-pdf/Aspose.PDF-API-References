---
title: System::Text::RegularExpressions::Match class
linktitle: Match
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::Match class. Single match of regexp over string. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.text.regularexpressions/match/
---
## Match class


[Single](../../system/single/) match of regexp over string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Match : public System::Text::RegularExpressions::Group
```

## Methods

| Method | Description |
| --- | --- |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Adds capture into match. |
| [AddGroup](./addgroup/)(const GroupPtr\&) | Adds group into match. |
| static [get_Empty](./get_empty/)() | Empty match accessor. |
| [get_Groups](./get_groups/)() | Gets group list. |
| [Match](./match/)(const UStringPtr\&, int, int) | Constructor. |
| [NextMatch](./nextmatch/)() | Iteration over matches. |
| virtual [Result](./result/)(const String\&) | Formats string by replacing submatch references with their values. |
| [SetMappedIndexes](./setmappedindexes/)(const std::vector\<int\>\&) |  |
## See Also

* Class [Group](../group/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
