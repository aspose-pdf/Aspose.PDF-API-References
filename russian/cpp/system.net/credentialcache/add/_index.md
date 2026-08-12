---
title: "System::Net::CredentialCache::Add метод"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::CredentialCache::Add метод. Добавляет указанные сетевые учетные данные в кэш в C++."
type: docs
weight: 400
url: /ru/cpp/system.net/credentialcache/add/
---
## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) method


Добавляет указанные сетевые учётные данные в кэш.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| host | String | Имя хоста, с которым связаны учетные данные. |
| port | int32_t | Номер порта. |
| authenticationType | String | Схема аутентификации. |
| учетные данные | System::SharedPtr\<NetworkCredential\> | Учетные данные для добавления. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) method


Добавляет указанные сетевые учётные данные в кэш.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uriPrefix | System::SharedPtr\<Uri\> | Префикс URI ресурса, с которым связаны учетные данные. |
| authenticationType | String | Схема аутентификации. |
| учетные данные | System::SharedPtr\<NetworkCredential\> | Учетные данные для добавления. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
