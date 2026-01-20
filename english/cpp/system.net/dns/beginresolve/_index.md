---
title: System::Net::Dns::BeginResolve method
linktitle: BeginResolve
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Dns::BeginResolve method. Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified host name in C++.'
type: docs
weight: 400
url: /cpp/system.net/dns/beginresolve/
---
## Dns::BeginResolve method


Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified host name.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hostName | String | A host name that is used to create a new instance of the [IPHostEntry](../../iphostentry/) class. |
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
