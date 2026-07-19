---
title: "System::Net::Sockets::TcpListener класс"
linktitle: "TcpListener"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::TcpListener класс. Представляет слушатель для TCP сетевых сервисов. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.net.sockets/tcplistener/
---
## TcpListener class


Представляет слушатель для TCP сетевых сервисов. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class TcpListener : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [AcceptSocket](./acceptsocket/)() | Принимает ожидающий запрос на соединение и возвращает сокет, используемый для отправки и получения данных. |
| [AcceptTcpClient](./accepttcpclient/)() | Принимает ожидающий запрос на соединение и возвращает экземпляр класса TcpClient, используемый для отправки и получения данных. |
| [AllowNatTraversal](./allownattraversal/)(bool) | Включает или отключает обход NAT. |
| [BeginAcceptSocket](./beginacceptsocket/)(AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию принятия соединения. |
| [BeginAcceptTcpClient](./beginaccepttcpclient/)(AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию принятия соединения. |
| static [Create](./create/)(int32_t) | Создаёт новый экземпляр, используя указанный номер порта. |
| [EndAcceptSocket](./endacceptsocket/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции принятия. |
| [EndAcceptTcpClient](./endaccepttcpclient/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции принятия. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Получает значение, указывающее, позволяет ли текущий экземпляр только одному клиенту использовать порт. |
| [get_LocalEndpoint](./get_localendpoint/)() | Возвращает базовую конечную точку. |
| [get_Server](./get_server/)() | Информация RTTI. |
| [Pending](./pending/)() | Возвращает значение, указывающее, есть ли ожидающие запросы на соединение. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Устанавливает значение, указывающее, разрешает ли текущий экземпляр только одному клиенту использовать порт. |
| [Start](./start/)() | Начинает прослушивание входящих соединений. |
| [Start](./start/)(int32_t) | Начинает прослушивание входящих соединений. |
| [Stop](./stop/)() | Прекращает прослушивание входящих соединений. |
| [TcpListener](./tcplistener/)(System::SharedPtr\<IPEndPoint\>) | Создаёт новый экземпляр. |
| [TcpListener](./tcplistener/)(System::SharedPtr\<IPAddress\>, int32_t) | Создаёт новый экземпляр. |
| [TcpListener](./tcplistener/)(int32_t) | Создаёт новый экземпляр. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
