---
title: System::Net::IPHostEntry class
linktitle: IPHostEntry
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::IPHostEntry class. Represents information about an internet host address. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2600
url: /cpp/system.net/iphostentry/
---
## IPHostEntry class


Represents information about an internet host address. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IPHostEntry : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AddressList](./get_addresslist/)() | Gets the collection of IP addresses of the host. |
| [get_Aliases](./get_aliases/)() | Gets the collection of aliases of the host. |
| [get_HostName](./get_hostname/)() const | RTTI information. |
| [IPHostEntry](./iphostentry/)() | Constructs a new instance. |
| [set_AddressList](./set_addresslist/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>) | Sets a collection of IP addresses of the host. |
| [set_Aliases](./set_aliases/)(System::ArrayPtr\<String\>) | Sets a collection of aliases of the host. |
| [set_HostName](./set_hostname/)(String) | Sets the host name. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
