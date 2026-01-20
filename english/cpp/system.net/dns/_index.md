---
title: System::Net::Dns class
linktitle: Dns
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Dns class. Provides methods to work with DNS in C++.'
type: docs
weight: 700
url: /cpp/system.net/dns/
---
## Dns class


Provides methods to work with DNS.

```cpp
class Dns : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [BeginGetHostAddresses](./begingethostaddresses/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified string that contains a host name or IP address. |
| static [BeginGetHostByName](./begingethostbyname/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified host name. |
| static [BeginGetHostEntry](./begingethostentry/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified string that contains a host name or IP address. |
| static [BeginGetHostEntry](./begingethostentry/)(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified IP address. |
| static [BeginResolve](./beginresolve/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified host name. |
| [Dns](./dns/)() | The deleted default constructor. |
| static [EndGetHostAddresses](./endgethostaddresses/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes. |
| static [EndGetHostByName](./endgethostbyname/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes. |
| static [EndGetHostEntry](./endgethostentry/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes. |
| static [EndResolve](./endresolve/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes. |
| static [GetHostAddresses](./gethostaddresses/)(String) | Returns a collection of IP addresses of the specified host name or IP address. |
| static [GetHostByAddress](./gethostbyaddress/)(String) | Creates a new IPHostEntry-class instance using the specified string representation of an IP address. |
| static [GetHostByAddress](./gethostbyaddress/)(System::SharedPtr\<IPAddress\>) | Creates a new IPHostEntry-class instance using the specified IP address. |
| static [GetHostByName](./gethostbyname/)(String) | RTTI information. |
| static [GetHostEntry](./gethostentry/)(String) | Creates a new IPHostEntry-class instance using the specified string that contains a host name or IP address. |
| static [GetHostEntry](./gethostentry/)(System::SharedPtr\<IPAddress\>) | Creates a new IPHostEntry-class instance using the specified IP address. |
| static [GetHostName](./gethostname/)() | Returns the host name of the local machine. |
| static [Resolve](./resolve/)(String) | Creates a new IPHostEntry-class instance using the specified host name. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
