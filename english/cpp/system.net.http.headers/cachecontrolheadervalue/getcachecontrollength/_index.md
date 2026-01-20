---
title: System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength method
linktitle: GetCacheControlLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength method. Converts a passed string from the specified index to an instance of the CacheControlHeaderValue class in C++.'
type: docs
weight: 3400
url: /cpp/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength method


Converts a passed string from the specified index to an instance of the [CacheControlHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| storeValue | System::SharedPtr\<CacheControlHeaderValue\> | A value that must be added to the parsed object. |
| parsedValue | System::SharedPtr\<CacheControlHeaderValue\>\& | An instance where a parsed object will be assigned. |

### ReturnValue

The length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CacheControlHeaderValue](../)
* Class [CacheControlHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
