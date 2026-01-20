---
title: System::Net::CookieCollection::InternalAdd method
linktitle: InternalAdd
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::CookieCollection::InternalAdd method. Adds the specified cookie to the collection in C++.'
type: docs
weight: 1000
url: /cpp/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd method


Adds the specified cookie to the collection.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```


| Parameter | Type | Description |
| --- | --- | --- |
| cookie | System::SharedPtr\<Cookie\> | The cookie to add. |
| isStrict | bool | True when the specified cookie must replace the old one, otherwise false. |

### ReturnValue

0 when the specified cookie replaced the old one, otherwise 1.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
