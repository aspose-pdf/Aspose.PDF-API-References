---
title: "System::Net::Sockets::Socket::ReceiveMessageFrom метод"
linktitle: "ReceiveMessageFrom"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket::ReceiveMessageFrom метод. Принимает данные от указанной конечной точки и записывает их в указанный массив байтов в C++."
type: docs
weight: 4500
url: /ru/cpp/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags\& | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |
| ipPacketInformation | IPPacketInformation\& | Выходной параметр, в который будет записана информация о пакете. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags\& | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |
| ipPacketInformation | IPPacketInformation\& | Выходной параметр, в который будет записана информация о пакете. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags\& | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |
| ipPacketInformation | IPPacketInformation\& | Выходной параметр, в который будет записана информация о пакете. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
