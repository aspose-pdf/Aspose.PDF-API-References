---
title: System::Net::NetworkInformation::IPGlobalProperties class
linktitle: IPGlobalProperties
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::NetworkInformation::IPGlobalProperties class. Represents an information about the network connection of the local computer. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.net.networkinformation/ipglobalproperties/
---
## IPGlobalProperties class


Represents an information about the network connection of the local computer. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IPGlobalProperties : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_DomainName](./get_domainname/)() | Returns the domain in which the local computer is registered. |
| virtual [get_HostName](./get_hostname/)() | Returns the host name of the local computer. |
| static [GetIPGlobalProperties](./getipglobalproperties/)() | RTTI information. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net::NetworkInformation](../)
* Library [Aspose.PDF for C++](../../)
