---
title: System::Net::Dns::BeginGetHostEntry method
linktitle: BeginGetHostEntry
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Dns::BeginGetHostEntry method. Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified string that contains a host name or IP address in C++.'
type: docs
weight: 300
url: /cpp/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) method


Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified string that contains a host name or IP address.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | String | The string that contains a hostname or IP address. |
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
## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) method


Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified IP address.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parameter | Type | Description |
| --- | --- | --- |
| address | System::SharedPtr\<IPAddress\> | The IP address. |
| requestCallback | AsyncCallback | A callback to be called when the operation completes. |
| stateObject | System::SharedPtr\<Object\> | User-provided data used to uniquely identify each asynchronous operation. |

### ReturnValue

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [IPAddress](../../ipaddress/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
