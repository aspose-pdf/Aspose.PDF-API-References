---
title: System::StringComparer::Create method
linktitle: Create
second_title: Aspose.PDF for C++ API Reference
description: 'System::StringComparer::Create method. Creates culture-specific comparer in C++.'
type: docs
weight: 100
url: /cpp/system/stringcomparer/create/
---
## StringComparer::Create method


Creates culture-specific comparer.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


| Parameter | Type | Description |
| --- | --- | --- |
| culture | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Culture to create comparer for. |
| ignoreCase | bool | Whether the comparer should ignore case. |

### ReturnValue

Pointer to newly created comparer object.

## See Also

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [StringComparer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
