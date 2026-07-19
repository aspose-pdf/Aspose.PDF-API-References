---
title: "System::Net::Security::AuthenticatedStream класс"
linktitle: "AuthenticatedStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::Security::AuthenticatedStream. Содержит методы передачи учётных данных через поток. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.net.security/authenticatedstream/
---
## AuthenticatedStream class


Содержит методы передачи учётных данных через поток. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_IsAuthenticated](./get_isauthenticated/)() const | Возвращает значение, указывающее, успешно ли пройдена аутентификация. |
| virtual [get_IsEncrypted](./get_isencrypted/)() const | Возвращает значение, указывающее, зашифрованы ли данные, отправленные через этот поток. |
| virtual [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | Возвращает значение, указывающее, аутентифицированы ли сервер и клиент. |
| virtual [get_IsServer](./get_isserver/)() const | Возвращает значение, указывающее, является ли локальная сторона соединения сервером. |
| virtual [get_IsSigned](./get_issigned/)() const | Возвращает значение, указывающее, подписаны ли данные, отправленные через этот поток. |
| [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | Информация RTTI. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Поток без базового хранилища. |
## См. также

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
