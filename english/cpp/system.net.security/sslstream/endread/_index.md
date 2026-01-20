---
title: System::Net::Security::SslStream::EndRead method
linktitle: EndRead
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Security::SslStream::EndRead method. Waits until the specified asynchronous read operation completes in C++.'
type: docs
weight: 700
url: /cpp/system.net.security/sslstream/endread/
---
## SslStream::EndRead method


Waits until the specified asynchronous read operation completes.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous read operation |

### ReturnValue

The number of bytes read during the read operation represented by **asyncResult**

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
