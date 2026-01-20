---
title: System::Net::Http::Headers::CacheControlHeaderValue class
linktitle: CacheControlHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::CacheControlHeaderValue class. Represents a value of the ''Cache-Control'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue class


Represents a value of the 'Cache-Control' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Constructs a new instance. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Extensions](./get_extensions/)() | Returns the collection of the cache-extension tokens. |
| [get_MaxAge](./get_maxage/)() | Gets the maximum age value in seconds that determines a time during which the client will accept a response. |
| [get_MaxStale](./get_maxstale/)() | Gets the value that determines if the client will accept the expired responses. |
| [get_MaxStaleLimit](./get_maxstalelimit/)() | Gets the value in seconds that determines the time during which the client will accept the expired responses. |
| [get_MinFresh](./get_minfresh/)() | Gets the value that determines the freshness lifetime. |
| [get_MustRevalidate](./get_mustrevalidate/)() | Gets the value that determines if the server requires revalidation of a cache entry when the it becomes stale. |
| [get_NoCache](./get_nocache/)() | RTTI information. |
| [get_NoCacheHeaders](./get_nocacheheaders/)() | Gets the collection of fieldnames in the 'no-cache' directive in the 'Cache-Control' header. |
| [get_NoStore](./get_nostore/)() | Gets the value that determines if a cache must not store any part of an HTTP request or response. |
| [get_NoTransform](./get_notransform/)() | Gets the value that determines if a cache or proxy must not change any part of the entity body. |
| [get_OnlyIfCached](./get_onlyifcached/)() | Gets the value that determines if the client must use only cached entries. |
| [get_Private](./get_private/)() | Gets the value that determines if the HTTP response message or its part is intended for a single user and must not be cached by a shared cache. |
| [get_PrivateHeaders](./get_privateheaders/)() | Gets the collection of fieldnames in the 'private' directive in the 'Cache-Control' header. |
| [get_ProxyRevalidate](./get_proxyrevalidate/)() | Gets the value that determines if the server requires revalidation of a cache entry when it becomes stale for the shared user agent caches. |
| [get_Public](./get_public/)() | Gets the value that determines if an HTTP response can be cached by any cache. |
| [get_SharedMaxAge](./get_sharedmaxage/)() | Gets the shared maximum age value in seconds that overrides the 'max-age' directive in the 'Cache-Control'. header or the 'Expires' header for a shared cache. |
| static [GetCacheControlLength](./getcachecontrollength/)(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) | Converts a passed string from the specified index to an instance of the [CacheControlHeaderValue](./) class. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [CacheControlHeaderValue](./) class. |
| [set_MaxAge](./set_maxage/)(Nullable\<TimeSpan\>) | Sets the maximum age value in seconds that determines a time during which the client will accept a response. |
| [set_MaxStale](./set_maxstale/)(bool) | Sets the value that determines if the client will accept the expired responses. |
| [set_MaxStaleLimit](./set_maxstalelimit/)(Nullable\<TimeSpan\>) | Sets the value in seconds that determines the time during which the client will accept the expired responses. |
| [set_MinFresh](./set_minfresh/)(Nullable\<TimeSpan\>) | Sets the value that determines the freshness lifetime. |
| [set_MustRevalidate](./set_mustrevalidate/)(bool) | Sets the value that determines if the server requires revalidation of a cache entry when the it becomes stale. |
| [set_NoCache](./set_nocache/)(bool) | Sets the value that determines if the client will accept a cached response. |
| [set_NoStore](./set_nostore/)(bool) | Sets the value that determines if a cache must not store any part of an HTTP request or response. |
| [set_NoTransform](./set_notransform/)(bool) | Sets the value that determines if a cache or proxy must not change any part of the entity body. |
| [set_OnlyIfCached](./set_onlyifcached/)(bool) | Sets the value that determines if the client must use only cached entries. |
| [set_Private](./set_private/)(bool) | Sets the value that determines if the HTTP response message or its part is intended for a single user and must not be cached by a shared cache. |
| [set_ProxyRevalidate](./set_proxyrevalidate/)(bool) | Sets the value that determines if the server requires revalidation of a cache entry when it becomes stale for the shared user agent caches. |
| [set_Public](./set_public/)(bool) | Sets the value that determines if an HTTP response can be cached by any cache. |
| [set_SharedMaxAge](./set_sharedmaxage/)(Nullable\<TimeSpan\>) | Sets the shared maximum age value in seconds that overrides the 'max-age' directive in the 'Cache-Control'. header or the 'Expires' header for a shared cache. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<CacheControlHeaderValue\>\&) | Tries to convert a passed string to an instance of the [CacheControlHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
