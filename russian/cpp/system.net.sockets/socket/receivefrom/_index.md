---
title: "System::Net::Sockets::Socket::ReceiveFrom метод"
linktitle: "ReceiveFrom"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket::ReceiveFrom метод. Принимает данные от указанной конечной точки и записывает их в указанный массив байтов в C++."
type: docs
weight: 4400
url: /ru/cpp/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | SocketFlags | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | SocketFlags | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | SocketFlags | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method


Получает данные из указанной конечной точки и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Удалённая конечная точка. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
