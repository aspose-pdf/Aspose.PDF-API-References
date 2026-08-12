---
title: "System::Net::CredentialCache::GetCredential método"
linktitle: "GetCredential"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::CredentialCache::GetCredential método. Devuelve credenciales para el nombre de host, puerto y tipo de autenticación especificados en C++."
type: docs
weight: 500
url: /es/cpp/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(String, int32_t, String) method


Devuelve credenciales para el nombre de host, puerto y tipo de autenticación especificados.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | String | El nombre de host con el que están asociadas las credenciales. |
| puerto | int32_t | El número de puerto. |
| authenticationType | String | El tipo de autenticación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) method


Devuelve credenciales para el prefijo URI especificado y el tipo de autenticación.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriPrefix | System::SharedPtr\<Uri\> | El prefijo URI. |
| authenticationType | String | Un tipo de autenticación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
