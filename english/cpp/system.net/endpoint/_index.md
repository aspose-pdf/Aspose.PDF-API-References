---
title: System::Net::EndPoint class
linktitle: EndPoint
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::EndPoint class. The abstract class contains a network address. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.net/endpoint/
---
## EndPoint class


The abstract class contains a network address. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EndPoint : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Create](./create/)(System::SharedPtr\<SocketAddress\>) | Create a new instance of the [EndPoint](./) class using the specified socket address. |
| virtual [get_AddressFamily](./get_addressfamily/)() | RTTI information. |
| virtual [GetImpl](./getimpl/)() const | Returns a pointer to implementation. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | A pointer to implementation. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
