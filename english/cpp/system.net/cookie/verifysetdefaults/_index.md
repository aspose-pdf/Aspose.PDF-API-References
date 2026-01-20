---
title: System::Net::Cookie::VerifySetDefaults method
linktitle: VerifySetDefaults
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Cookie::VerifySetDefaults method. Verifies and sets the default attribute''s values in C++.'
type: docs
weight: 4200
url: /cpp/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults method


Verifies and sets the default attribute's values.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```


| Parameter | Type | Description |
| --- | --- | --- |
| variant | CookieVariant | The cookie's specification. |
| uri | System::SharedPtr\<Uri\> | The Uri-class instance that is used to initialize the internal fields. |
| isLocalDomain | bool | A value that indicates if the cookie is pushed into the the local domain. |
| localDomain | String | A local domain name. |
| setDefault | bool | A value that indicates if the cookie's attributes must be initialized using their default values. |
| shouldThrow | bool | A value that indicates if an exception should be thrown when the specified values are invalid. |

### ReturnValue

True when all values are valid, otherwise false.

## See Also

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
