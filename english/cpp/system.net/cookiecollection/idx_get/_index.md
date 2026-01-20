---
title: System::Net::CookieCollection::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::CookieCollection::idx_get method. Returns a cookie from the cookie collection at the specified index in C++.'
type: docs
weight: 800
url: /cpp/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) method


Returns a cookie from the cookie collection at the specified index.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The index of a cookie that must be returned. |

### ReturnValue

A cookie at the specified index.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## CookieCollection::idx_get(String) method


Returns a cookie from the cookie collection by specified name.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of a cookie that must be returned. |

### ReturnValue

A cookie from the cookie collection by specified name when it is found, otherwise nullptr.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [String](../../../system/string/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
