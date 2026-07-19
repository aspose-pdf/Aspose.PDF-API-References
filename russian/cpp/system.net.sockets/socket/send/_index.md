---
title: "System::Net::Sockets::Socket::Send метод"
linktitle: "Отправка"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket::Send метод. Отправляет указанные данные в сокет в C++."
type: docs
weight: 4600
url: /ru/cpp/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Данные для отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Данные для отправки. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов в указанном массиве, начиная с параметра 'offset'. |
| socketFlags | SocketFlags | Поведение отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Данные для отправки. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов в указанном массиве, начиная с параметра 'offset'. |
| socketFlags | SocketFlags | Поведение отправки. |
| errorCode | SocketError\& | Выходной параметр, в котором будет присвоен код ошибки, если операция отправки завершится с ошибкой. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Данные для отправки. |
| size | int32_t | Количество байтов из указанных данных, которое должно быть отправлено. |
| socketFlags | SocketFlags | Поведение отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Данные для отправки. |
| socketFlags | SocketFlags | Поведение отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Данные для отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Данные для отправки. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов в указанном массиве, начиная с параметра 'offset'. |
| socketFlags | SocketFlags | Поведение отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Данные для отправки. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов в указанном массиве, начиная с параметра 'offset'. |
| socketFlags | SocketFlags | Поведение отправки. |
| errorCode | SocketError\& | Выходной параметр, в котором будет присвоен код ошибки, если операция отправки завершится с ошибкой. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Данные для отправки. |
| size | int32_t | Количество байтов из указанных данных, которое должно быть отправлено. |
| socketFlags | SocketFlags | Поведение отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Данные для отправки. |
| socketFlags | SocketFlags | Поведение отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method


Отправляет указанные данные в сокет.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Данные для отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method


Отправляет указанные данные в сокет.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Данные для отправки. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов в указанном массиве, начиная с параметра 'offset'. |
| socketFlags | SocketFlags | Поведение отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method


Отправляет указанные данные в сокет.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Данные для отправки. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов в указанном массиве, начиная с параметра 'offset'. |
| socketFlags | SocketFlags | Поведение отправки. |
| errorCode | SocketError\& | Выходной параметр, в котором будет присвоен код ошибки, если операция отправки завершится с ошибкой. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method


Отправляет указанные данные в сокет.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Данные для отправки. |
| size | int32_t | Количество байтов из указанных данных, которое должно быть отправлено. |
| socketFlags | SocketFlags | Поведение отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method


Отправляет указанные данные в сокет.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Данные для отправки. |
| socketFlags | SocketFlags | Поведение отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| буферы | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Коллекция массивов байтов, из которых данные должны быть отправлены. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| буферы | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Коллекция массивов байтов, из которых данные должны быть отправлены. |
| socketFlags | SocketFlags | Поведение отправки. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method


Отправляет указанные данные в сокет.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| буферы | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Коллекция массивов байтов, из которых данные должны быть отправлены. |
| socketFlags | SocketFlags | Поведение отправки. |
| errorCode | SocketError\& | Выходной параметр, в котором будет присвоен код ошибки, если операция отправки завершится с ошибкой. |

### ReturnValue

Количество отправленных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
