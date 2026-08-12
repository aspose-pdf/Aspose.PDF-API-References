---
title: "System::Net::Sockets::Socket::Receive метод"
linktitle: "Получить"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket::Receive метод. Принимает данные из сокета и записывает их в указанный массив байтов в C++."
type: docs
weight: 4300
url: /ru/cpp/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |
| errorCode | SocketError\& | Выходной параметр, в который будет записан код ошибки, если операция получения завершится неудачей. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| size | int32_t | Количество байтов для получения. |
| socketFlags | SocketFlags | Поведение получения. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::ArrayPtr\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | SocketFlags | Поведение получения. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |

### ReturnValue

Количество полученных байтов.

## См. также

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |
| errorCode | SocketError\& | Выходной параметр, в который будет записан код ошибки, если операция получения завершится неудачей. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| size | int32_t | Количество байтов для получения. |
| socketFlags | SocketFlags | Поведение получения. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<uint8_t\> | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | SocketFlags | Поведение получения. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Массив байтов, в который будут записаны полученные данные. |

### ReturnValue

Количество полученных байтов.

## См. также

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество байтов для получения, которое будет записано в указанный массив байтов, начиная с индекса 'offset'. |
| socketFlags | SocketFlags | Поведение получения. |
| errorCode | SocketError\& | Выходной параметр, в который будет записан код ошибки, если операция получения завершится неудачей. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| size | int32_t | Количество байтов для получения. |
| socketFlags | SocketFlags | Поведение получения. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method


Получает данные из сокета и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | System::Details::StackArray\<uint8_t, N\>\& | Массив байтов, в который будут записаны полученные данные. |
| socketFlags | SocketFlags | Поведение получения. |

### ReturnValue

Количество полученных байтов.

## См. также

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method


Получает данные из сокета и записывает их в указанные массивы байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| буферы | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Массивы байтов, в которые будут записаны полученные данные. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method


Получает данные из сокета и записывает их в указанные массивы байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| буферы | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Массивы байтов, в которые будут записаны полученные данные. |
| socketFlags | SocketFlags | Поведение получения. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method


Получает данные из сокета и записывает их в указанные массивы байтов.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| буферы | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Массивы байтов, в которые будут записаны полученные данные. |
| socketFlags | SocketFlags | Поведение получения. |
| errorCode | SocketError\& | Выходной параметр, в который будет записан код ошибки, если операция получения завершится неудачей. |

### ReturnValue

Количество полученных байтов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
