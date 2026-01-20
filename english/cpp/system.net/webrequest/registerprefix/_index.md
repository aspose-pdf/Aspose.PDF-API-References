---
title: System::Net::WebRequest::RegisterPrefix method
linktitle: RegisterPrefix
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebRequest::RegisterPrefix method. Registers the WebRequest descendant for the specified URI in C++.'
type: docs
weight: 600
url: /cpp/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix method


Registers the [WebRequest](../) descendant for the specified URI.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The URI or the URI prefix. |
| creator | System::SharedPtr\<IWebRequestCreate\> | Creates new instances of the [WebRequest](../) class. |

### ReturnValue

True when the [WebRequest](../) descendant is successfully registered for the specified URI, otherwise false.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWebRequestCreate](../../iwebrequestcreate/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
