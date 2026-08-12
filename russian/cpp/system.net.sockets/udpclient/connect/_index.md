---
title: "Метод System::Net::Sockets::UdpClient::Connect"
linktitle: "Connect"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::Sockets::UdpClient::Connect. Устанавливает соединение с указанным портом на указанном хосте в C++."
type: docs
weight: 300
url: /ru/cpp/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) method


Устанавливает соединение с указанным портом на указанном хосте.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя хоста | String | Имя удалённого DNS‑хоста, к которому вы планируете подключиться. |
| port | int32_t | Локальный номер порта, из которого вы планируете общаться. |

## См. также

* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) method


Устанавливает соединение с хостом по указанному адресу на указанном порту.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| addr | System::SharedPtr\<IPAddress\> | IP‑адрес [IPAddress](../../../system.net/ipaddress/) удалённого хоста, куда отправлять данные. |
| port | int32_t | Локальный номер порта, из которого вы планируете общаться. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) method


Устанавливает соединение с удалённой конечной точкой.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| endPoint | System::SharedPtr\<IPEndPoint\> | Конечная точка, к которой вы привязываете UDP‑соединение. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
