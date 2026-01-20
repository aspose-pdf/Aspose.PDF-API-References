---
title: System::Net::Cache::HttpRequestCachePolicy class
linktitle: HttpRequestCachePolicy
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Cache::HttpRequestCachePolicy class. HTTP cache policy that expresses RFC2616 HTTP caching semantic Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.net.cache/httprequestcachepolicy/
---
## HttpRequestCachePolicy class


HTTP cache policy that expresses RFC2616 HTTP caching semantic Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpRequestCachePolicy : public System::Net::Cache::RequestCachePolicy
```

## Methods

| Method | Description |
| --- | --- |
| [get_CacheSyncDate](./get_cachesyncdate/)() const | Gets the time when resources stored in the cache must be revalidated. |
| [get_InternalCacheSyncDateUtc](./get_internalcachesyncdateutc/)() const | Gets the time in the UTC format when resources stored in the cache must be revalidated. For internal use only. |
| [get_Level](./get_level/)() const | RTTI information. |
| [get_MaxAge](./get_maxage/)() const | Gets the max age permitted for a resource. |
| [get_MaxStale](./get_maxstale/)() const | Gets the maximum staleness value that is permitted for a resource. |
| [get_MinFresh](./get_minfresh/)() const | Gets the min age permitted for a resource. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)() | Constructs a new instance. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)(HttpRequestCacheLevel) | Constructs a new instance. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)(HttpCacheAgeControl, TimeSpan) | Constructs a new instance. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)(HttpCacheAgeControl, TimeSpan, TimeSpan) | Constructs a new instance. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)(DateTime) | Constructs a new instance. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) | Constructs a new instance. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [RequestCachePolicy](../requestcachepolicy/)
* Namespace [System::Net::Cache](../)
* Library [Aspose.PDF for C++](../../)
