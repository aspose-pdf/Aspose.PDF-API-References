---
title: System::Net::IWebProxy::IsBypassed method
linktitle: IsBypassed
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::IWebProxy::IsBypassed method. Returns a value that indicates if the proxy must not be used for the specified host in C++.'
type: docs
weight: 300
url: /cpp/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed method


Returns a value that indicates if the proxy must not be used for the specified host.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| host | System::SharedPtr\<Uri\> | The host URI to check. |

### ReturnValue

True when the proxy server must not be used, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [IWebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
