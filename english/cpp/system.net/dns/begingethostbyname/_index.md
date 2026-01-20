---
title: System::Net::Dns::BeginGetHostByName method
linktitle: BeginGetHostByName
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Dns::BeginGetHostByName method. Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified host name in C++.'
type: docs
weight: 200
url: /cpp/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName method


Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified host name.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hostName | String | A host name. |
| requestCallback | AsyncCallback | A callback to be called when the operation completes. |
| stateObject | System::SharedPtr\<Object\> | User-provided data used to uniquely identify each asynchronous operation. |

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
