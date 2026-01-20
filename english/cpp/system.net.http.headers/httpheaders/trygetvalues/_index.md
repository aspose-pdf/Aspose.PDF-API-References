---
title: System::Net::Http::Headers::HttpHeaders::TryGetValues method
linktitle: TryGetValues
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::HttpHeaders::TryGetValues method. Tries to get corresponding values by the specified name in C++.'
type: docs
weight: 1900
url: /cpp/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues method


Tries to get corresponding values by the specified name.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The header name. |
| values | System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | An instance where corresponding values will be assigned. |

### ReturnValue

True when the header values are found by the specified name, otherwise false.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [HttpHeaders](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
