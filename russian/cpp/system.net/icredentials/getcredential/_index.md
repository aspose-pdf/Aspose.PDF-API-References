---
title: "System::Net::ICredentials::GetCredential метод"
linktitle: "GetCredential"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::ICredentials::GetCredential метод. Информация RTTI в C++."
type: docs
weight: 100
url: /ru/cpp/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential method


Информация RTTI.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | System::SharedPtr\<Uri\> | URI, для которого клиент предоставляет тип аутентификации. |
| authType | String | Тип аутентификации. |
## Примечания


Возвращает учетные данные для указанного URI и типа аутентификации.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
