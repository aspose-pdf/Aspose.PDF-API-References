---
title: System::Net::Sockets::LingerOption class
linktitle: LingerOption
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::LingerOption class. Specifies whether a socket will remain connected after a call to the Close() or Close() methods. It also specifies the period the socket will remain connected if sending of the data continues. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.net.sockets/lingeroption/
---
## LingerOption class


Specifies whether a socket will remain connected after a call to the Close() or Close() methods. It also specifies the period the socket will remain connected if sending of the data continues. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class LingerOption : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Enabled](./get_enabled/)() | RTTI information. |
| [get_LingerTime](./get_lingertime/)() | Gets a delay timeout in seconds. |
| [LingerOption](./lingeroption/)(bool, int32_t) | Constructs a new instance. |
| [set_Enabled](./set_enabled/)(bool) | Sets a value that indicates if the socket will delay closing in an attempt to send all pending data. |
| [set_LingerTime](./set_lingertime/)(int32_t) | Sets a delay timeout in seconds. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
