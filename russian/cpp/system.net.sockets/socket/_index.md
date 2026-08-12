---
title: "System::Net::Sockets::Socket класс"
linktitle: "Socket"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::Socket класс. Класс Socket реализует интерфейс Berkeley sockets на C++."
type: docs
weight: 400
url: /ru/cpp/system.net.sockets/socket/
---
## Socket class


Класс [Socket](./) реализует интерфейс Berkeley sockets.

```cpp
class Socket : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)() | Создает новый сокет для только что созданного соединения. |
| [BeginConnect](./beginconnect/)(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию подключения. |
| [BeginConnect](./beginconnect/)(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию подключения. |
| [BeginConnect](./beginconnect/)(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию подключения. |
| [BeginConnect](./beginconnect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию подключения. |
| [BeginReceive](./beginreceive/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию записи. |
| [BeginSend](./beginsend/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию отправки. |
| [Bind](./bind/)(System::SharedPtr\<EndPoint\>) | Привязывает сокет к указанной локальной конечной точке. |
| [Close](./close/)() | Закрывает соединение сокета. |
| [Close](./close/)(int) | Закрывает соединение сокета с указанным тайм-аутом, позволяя отправить накопленные данные. |
| [Connect](./connect/)(System::SharedPtr\<EndPoint\>) | Устанавливает соединение с указанной удаленной конечной точкой. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Устанавливает соединение с указанной удаленной конечной точкой. |
| [Connect](./connect/)(String, int32_t) | Устанавливает соединение с указанной удаленной конечной точкой. |
| [Connect](./connect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) | Устанавливает соединение с указанной удаленной конечной точкой. |
| [Dispose](./dispose/)() override | Ничего не делает. |
| [EndConnect](./endconnect/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции подключения. |
| [EndReceive](./endreceive/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции получения. |
| [EndReceive](./endreceive/)(System::SharedPtr\<IAsyncResult\>, SocketError\&) | Ожидает завершения указанной асинхронной операции получения. |
| [EndSend](./endsend/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции отправки. |
| [EndSend](./endsend/)(System::SharedPtr\<IAsyncResult\>, SocketError\&) | Ожидает завершения указанной асинхронной операции отправки. |
| [get_AddressFamily](./get_addressfamily/)() | Возвращает семейство адресов. |
| [get_Available](./get_available/)() | Получает количество байтов, полученных из сети и доступных для чтения. |
| [get_Blocking](./get_blocking/)() | Получает значение, указывающее, находится ли сокет в блокирующем режиме. |
| [get_Connected](./get_connected/)() | Возвращает значение, указывающее, подключен ли сокет к удаленному хосту. |
| [get_DontFragment](./get_dontfragment/)() | Получает значение, указывающее, разрешено ли фрагментирование IP‑датаграмм сокетом. |
| [get_DualMode](./get_dualmode/)() | Получает значение, указывающее, находится ли сокет в двойном режиме. |
| [get_EnableBroadcast](./get_enablebroadcast/)() | Получает значение, указывающее, разрешает ли сокет широковещательные пакеты. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Получает значение, указывающее, может ли только один процесс привязать сокет к порту. |
| [get_IsBound](./get_isbound/)() | Возвращает значение, указывающее, привязан ли сокет к конкретному локальному порту. |
| [get_LingerState](./get_lingerstate/)() | Получает значение, указывающее, будет ли сокет откладывать закрытие в попытке отправить все ожидающие данные. |
| [get_LocalEndPoint](./get_localendpoint/)() | Возвращает локальную конечную точку. |
| [get_MulticastLoopback](./get_multicastloopback/)() | Получает значение, указывающее, принимает ли сокет исходящие мультикаст‑пакеты. |
| [get_NoDelay](./get_nodelay/)() | Получает значение, указывающее, использует ли сокет алгоритм Нейгла. |
| static [get_OSSupportsIPv4](./get_ossupportsipv4/)() | Возвращает значение, указывающее, поддерживают ли операционная система и сетевые адаптеры IPv4. |
| static [get_OSSupportsIPv6](./get_ossupportsipv6/)() | Возвращает значение, указывающее, поддерживают ли операционная система и сетевые адаптеры IPv6. |
| [get_ProtocolType](./get_protocoltype/)() | Возвращает тип протокола. |
| [get_ReceiveBufferSize](./get_receivebuffersize/)() | Получает размер буфера приема. |
| [get_ReceiveTimeout](./get_receivetimeout/)() | Получает период, после которого вызов 'Receive' завершится тайм‑аутом. |
| [get_RemoteEndPoint](./get_remoteendpoint/)() | Возвращает удалённую конечную точку. |
| [get_SendBufferSize](./get_sendbuffersize/)() | Получает размер буфера отправки. |
| [get_SendTimeout](./get_sendtimeout/)() | Получает период, после которого вызов 'Send' завершится тайм‑аутом. |
| [get_SocketType](./get_sockettype/)() | Возвращает тип сокета. |
| static [get_SupportsIPv4](./get_supportsipv4/)() | Информация RTTI. |
| [get_Ttl](./get_ttl/)() | Получает значение TTL. |
| [GetImpl](./getimpl/)() const | Возвращает указатель на реализацию. |
| [GetSocketOption](./getsocketoption/)(SocketOptionLevel, SocketOptionName) | Возвращает значение, соответствующее указанному имени параметра. |
| [GetSocketOption](./getsocketoption/)(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) | Получает значение, соответствующее указанному имени параметра. |
| [GetSocketOption](./getsocketoption/)(SocketOptionLevel, SocketOptionName, int32_t) | Возвращает значение, соответствующее указанному имени параметра. |
| [IOControl](./iocontrol/)(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Устанавливает низкоуровневые режимы работы для сокета. |
| [IOControl](./iocontrol/)(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Устанавливает низкоуровневые режимы работы для сокета. |
| [Listen](./listen/)(int32_t) | Изменяет состояние сокета на 'listen'. |
| [Poll](./poll/)(int32_t, SelectMode) | Возвращает статус сокета на основе указанного режима опроса. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, SocketFlags) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, SocketFlags) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) | Получает данные из сокета и записывает их в указанный массив байтов. |
| [Receive](./receive/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) | Получает данные из сокета и записывает их в указанные массивы байтов. |
| [Receive](./receive/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) | Получает данные из сокета и записывает их в указанные массивы байтов. |
| [Receive](./receive/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) | Получает данные из сокета и записывает их в указанные массивы байтов. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveMessageFrom](./receivemessagefrom/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) | Получает данные из указанной конечной точки и записывает их в указанный массив байтов. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, SocketFlags) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, SocketFlags) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) | Отправляет указанные данные в сокет. |
| [Send](./send/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) | Отправляет указанные данные в сокет. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [SendTo](./sendto/)(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) | Отправляет указанные данные в указанную конечную точку. |
| [set_Blocking](./set_blocking/)(bool) | Устанавливает значение, указывающее, находится ли сокет в блокирующем режиме. |
| [set_ConnectionTimeout](./set_connectiontimeout/)(int32_t) | Устанавливает тайм-аут соединения. |
| [set_DontFragment](./set_dontfragment/)(bool) | Устанавливает значение, указывающее, разрешает ли сокет фрагментацию IP‑датаграмм. |
| [set_DualMode](./set_dualmode/)(bool) | Устанавливает значение, указывающее, находится ли сокет в двойном режиме. |
| [set_EnableBroadcast](./set_enablebroadcast/)(bool) | Устанавливает значение, указывающее, разрешает ли сокет широковещательные пакеты. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Устанавливает значение, указывающее, может ли только один процесс привязать сокет к порту. |
| [set_LingerState](./set_lingerstate/)(System::SharedPtr\<LingerOption\>) | Устанавливает значение, указывающее, будет ли сокет задерживать закрытие в попытке отправить все ожидающие данные. |
| [set_MulticastLoopback](./set_multicastloopback/)(bool) | Устанавливает значение, указывающее, принимает ли сокет исходящие мультикаст‑пакеты. |
| [set_NoDelay](./set_nodelay/)(bool) | Устанавливает значение, указывающее, использует ли сокет алгоритм Нейгла. |
| [set_ReceiveBufferSize](./set_receivebuffersize/)(int32_t) | Устанавливает размер буфера приема. |
| [set_ReceiveTimeout](./set_receivetimeout/)(int32_t) | Устанавливает период, после которого вызов 'Receive' завершится тайм‑аутом. |
| [set_SendBufferSize](./set_sendbuffersize/)(int32_t) | Устанавливает размер буфера отправки. |
| [set_SendTimeout](./set_sendtimeout/)(int32_t) | Устанавливает период, после которого вызов 'Send' завершится тайм‑аутом. |
| [set_Ttl](./set_ttl/)(int16_t) | Устанавливает значение TTL. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, int32_t) | Устанавливает указанную опцию сокета в указанное значение. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) | Устанавливает указанную опцию сокета в указанное значение. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, bool) | Устанавливает указанную опцию сокета в указанное значение. |
| [SetSocketOption](./setsocketoption/)(SocketOptionLevel, SocketOptionName, System::SharedPtr\<Object\>) | Устанавливает указанную опцию сокета в указанное значение. |
| [Shutdown](./shutdown/)(SocketShutdown) | Отключает операции отправки и получения сокета. |
| [Socket](./socket/)(System::Net::Sockets::SocketType, System::Net::Sockets::ProtocolType) | Создаёт новый экземпляр. |
| [Socket](./socket/)(System::Net::Sockets::AddressFamily, System::Net::Sockets::SocketType, System::Net::Sockets::ProtocolType) | Создаёт новый экземпляр. |
| virtual [~Socket](./~socket/)() | Разрушает текущий экземпляр. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [ImplPtr](./implptr/) | Реализация сокета. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
