---
title: "System::Net::Sockets::Socket::SendTo метод"
linktitle: "SendTo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket::SendTo метод. Отправляет указанные данные в указанный конечный пункт в C++."
type: docs
weight: 4700
url: /ru/cpp/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Данные для отправки. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов в указанном массиве, начиная с параметра 'offset'. |
| socketFlags | SocketFlags | Поведение отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Данные для отправки. |
| size | int32_t | Количество байтов в указанном массиве. |
| socketFlags | SocketFlags | Поведение отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Данные для отправки. |
| socketFlags | SocketFlags | Поведение отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Данные для отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Данные для отправки. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов в указанном массиве, начиная с параметра 'offset'. |
| socketFlags | SocketFlags | Поведение отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Данные для отправки. |
| size | int32_t | Количество байтов в указанном массиве. |
| socketFlags | SocketFlags | Поведение отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Данные для отправки. |
| socketFlags | SocketFlags | Поведение отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Данные для отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Данные для отправки. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов в указанном массиве, начиная с параметра 'offset'. |
| socketFlags | SocketFlags | Поведение отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Данные для отправки. |
| size | int32_t | Количество байтов в указанном массиве. |
| socketFlags | SocketFlags | Поведение отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Данные для отправки. |
| socketFlags | SocketFlags | Поведение отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) method


Отправляет указанные данные в указанную конечную точку.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Данные для отправки. |
| remoteEP | System::SharedPtr\<EndPoint\> | Удалённая конечная точка. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
