---
title: System::Net::Dns::BeginGetHostAddresses method
linktitle: BeginGetHostAddresses
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Dns::BeginGetHostAddresses method. Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified string that contains a host name or IP address in C++.'
type: docs
weight: 100
url: /cpp/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses method


Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified string that contains a host name or IP address.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | String | A string that contains a hostname or IP address. |
| requestCallback | AsyncCallback | A callback to be called when the operation completes. |
| state | System::SharedPtr\<Object\> | User-provided data used to uniquely identify each asynchronous operation. |

### ReturnValue

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
