---
title: "System::Net::ICredentials::GetCredential metod"
linktitle: "GetCredential"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::ICredentials::GetCredential metod. RTTI‑information i C++."
type: docs
weight: 100
url: /sv/cpp/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential method


RTTI-information.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | System::SharedPtr\<Uri\> | URI:n för vilken autentiseringstypen tillhandahålls av en klient. |
| authType | String | Autentiseringstypen. |
## Anmärkningar


Returnerar autentiseringsuppgifter för den angivna URI:n och autentiseringstypen.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
