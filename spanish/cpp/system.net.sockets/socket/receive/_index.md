---
title: "System::Net::Sockets::Socket::Receive método"
linktitle: "Recibir"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::Socket::Receive método. Recibe datos del socket y los escribe en el arreglo de bytes especificado en C++."
type: docs
weight: 4300
url: /es/cpp/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| errorCode | SocketError\& | El parámetro de salida donde se asignará el código de error cuando falle la operación de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| size | int32_t | El número de bytes a recibir. |
| socketFlags | SocketFlags | El comportamiento de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| socketFlags | SocketFlags | El comportamiento de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| errorCode | SocketError\& | El parámetro de salida donde se asignará el código de error cuando falle la operación de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| size | int32_t | El número de bytes a recibir. |
| socketFlags | SocketFlags | El comportamiento de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| socketFlags | SocketFlags | El comportamiento de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| errorCode | SocketError\& | El parámetro de salida donde se asignará el código de error cuando falle la operación de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| size | int32_t | El número de bytes a recibir. |
| socketFlags | SocketFlags | El comportamiento de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method


Recibe datos del socket y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| socketFlags | SocketFlags | El comportamiento de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method


Recibe datos del socket y los escribe en las matrices de bytes especificadas.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búferes | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Los arreglos de bytes donde se asignarán los datos recibidos. |

### ReturnValue

El número de bytes que se reciben.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method


Recibe datos del socket y los escribe en las matrices de bytes especificadas.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búferes | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Los arreglos de bytes donde se asignarán los datos recibidos. |
| socketFlags | SocketFlags | El comportamiento de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method


Recibe datos del socket y los escribe en las matrices de bytes especificadas.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búferes | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Los arreglos de bytes donde se asignarán los datos recibidos. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| errorCode | SocketError\& | El parámetro de salida donde se asignará el código de error cuando falle la operación de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
