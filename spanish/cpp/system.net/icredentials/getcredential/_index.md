---
title: "System::Net::ICredentials::GetCredential método"
linktitle: "GetCredential"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::ICredentials::GetCredential método. Información RTTI en C++."
type: docs
weight: 100
url: /es/cpp/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential method


Información RTTI.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | System::SharedPtr\<Uri\> | El URI para el cual el cliente proporciona el tipo de autenticación. |
| authType | String | El tipo de autenticación. |
## Observaciones


Devuelve credenciales para la URI especificada y el tipo de autenticación.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
