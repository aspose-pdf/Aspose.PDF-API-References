---
title: "System::Net::CredentialCache klass"
linktitle: "CredentialCache"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::CredentialCache-klass. Tillhandahåller lagring av autentiseringsuppgifter. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.net/credentialcache/
---
## CredentialCache class


Tillhandahåller lagring av autentiseringsuppgifter. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class CredentialCache : public System::Net::ICredentials,
                        public System::Net::ICredentialsByHost
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) | Lägger till de angivna nätverksuppgifterna i cachen. |
| [Add](./add/)(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) | Lägger till de angivna nätverksuppgifterna i cachen. |
| [CredentialCache](./credentialcache/)() | Skapar en ny instans. |
| static [get_DefaultCredentials](./get_defaultcredentials/)() | RTTI-information. |
| static [get_DefaultNetworkCredentials](./get_defaultnetworkcredentials/)() | Returnerar nätverksuppgifterna för den aktuella användaren eller applikationen. |
| [GetCredential](./getcredential/)(System::SharedPtr\<Uri\>, String) override | Returnerar autentiseringsuppgifter för det angivna URI-prefixet och autentiseringstypen. |
| [GetCredential](./getcredential/)(String, int32_t, String) override | Returnerar autentiseringsuppgifter för det angivna värdnamnet, porten och autentiseringstypen. |
| [Remove](./remove/)(System::SharedPtr\<Uri\>, String) | Tar bort nätverksuppgifter för det angivna URI-prefixet och autentiseringstypen. |
| [Remove](./remove/)(String, int32_t, String) | Tar bort nätverksuppgifter för det angivna värdnamnet, porten och autentiseringstypen. |
## Se även

* Class [ICredentials](../icredentials/)
* Class [ICredentialsByHost](../icredentialsbyhost/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
