---
title: System::Net::Sockets::Socket::IOControl method
linktitle: IOControl
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::Socket::IOControl method. Sets low-level operating modes for the socket in C++.'
type: docs
weight: 4000
url: /cpp/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Sets low-level operating modes for the socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ioControlCode | int32_t | The control code of the operation to perform. |
| optionInValue | System::ArrayPtr\<uint8_t\> | The byte array that contains the input data. |
| optionOutValue | System::ArrayPtr\<uint8_t\> | The byte array that contains the output data. |

### ReturnValue

The number of bytes in the **optionOutValue** parameter.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Sets low-level operating modes for the socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ioControlCode | IOControlCode | The control code of the operation to perform. |
| optionInValue | System::ArrayPtr\<uint8_t\> | The byte array that contains the input data. |
| optionOutValue | System::ArrayPtr\<uint8_t\> | The byte array that contains the output data. |

### ReturnValue

The number of bytes in the **optionOutValue** parameter.

## See Also

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
