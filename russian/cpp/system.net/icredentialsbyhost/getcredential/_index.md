---
title: "System::Net::ICredentialsByHost::GetCredential метод"
linktitle: "GetCredential"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::ICredentialsByHost::GetCredential метод. Информация RTTI в C++."
type: docs
weight: 100
url: /ru/cpp/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential method


Информация RTTI.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| host | String | Хост, аутентифицирующий клиент. |
| port | int32_t | Номер порта хоста. |
| authenticationType | String | Тип аутентификации. |
## Примечания


Возвращает учетные данные для указанного хоста и типа аутентификации.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [String](../../../system/string/)
* Class [ICredentialsByHost](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
