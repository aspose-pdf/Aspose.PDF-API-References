---
title: "System::Net::Sockets::Socket::GetSocketOption метод"
linktitle: "GetSocketOption"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket::GetSocketOption метод. Возвращает значение, соответствующее указанному имени параметра в C++."
type: docs
weight: 3900
url: /ru/cpp/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) method


Возвращает значение, соответствующее указанному имени параметра.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | Уровень параметра сокета. |
| optionName | SocketOptionName | Имя параметра. |

### ReturnValue

Значение, соответствующее указанному имени параметра.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) method


Возвращает значение, соответствующее указанному имени параметра.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | Уровень параметра сокета. |
| optionName | SocketOptionName | Имя параметра. |
| optionLength | int32_t | Длина параметра. |

### ReturnValue

Значение, соответствующее указанному имени параметра.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) method


Получает значение, соответствующее указанному имени параметра.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | Уровень параметра сокета. |
| optionName | SocketOptionName | Имя параметра. |
| optionValue | System::ArrayPtr\<uint8_t\> | Выходной параметр, в который будет присвоено соответствующее значение. |

## См. также

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
