---
title: "System::Net::Sockets::Socket::IOControl метод"
linktitle: "IOControl"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket::IOControl метод. Устанавливает низкоуровневые режимы работы сокета в C++."
type: docs
weight: 4000
url: /ru/cpp/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Устанавливает низкоуровневые режимы работы для сокета.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ioControlCode | int32_t | Код управления операцией, которую необходимо выполнить. |
| optionInValue | System::ArrayPtr\<uint8_t\> | Массив байтов, содержащий входные данные. |
| optionOutValue | System::ArrayPtr\<uint8_t\> | Массив байтов, содержащий выходные данные. |

### ReturnValue

Количество байтов в параметре **optionOutValue**.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Устанавливает низкоуровневые режимы работы для сокета.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ioControlCode | IOControlCode | Код управления операцией, которую необходимо выполнить. |
| optionInValue | System::ArrayPtr\<uint8_t\> | Массив байтов, содержащий входные данные. |
| optionOutValue | System::ArrayPtr\<uint8_t\> | Массив байтов, содержащий выходные данные. |

### ReturnValue

Количество байтов в параметре **optionOutValue**.

## См. также

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
