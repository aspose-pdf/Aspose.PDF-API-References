---
title: "System::Net::NetworkCredential class"
linktitle: "NetworkCredential"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::NetworkCredential-klass. Tillhandahåller autentiseringsuppgifter för lösenordsbaserade autentiseringsscheman. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2900
url: /sv/cpp/system.net/networkcredential/
---
## NetworkCredential class


Tillhandahåller autentiseringsuppgifter för lösenordsbaserade autentiseringsscheman. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class NetworkCredential : public System::Net::ICredentials,
                          public System::Net::ICredentialsByHost,
                          public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Domain](./get_domain/)() | Hämtar domänen som verifierar autentiseringsuppgifterna. |
| [get_Password](./get_password/)() | Hämtar lösenordet. |
| [get_UserName](./get_username/)() | RTTI-information. |
| [GetCredential](./getcredential/)(System::SharedPtr\<Uri\>, String) override | Returnerar autentiseringsuppgifter för den angivna URI:n och autentiseringstypen. |
| [GetCredential](./getcredential/)(String, int32_t, String) override | Returnerar autentiseringsuppgifter för det angivna värdnamnet, porten och autentiseringstypen. |
| [NetworkCredential](./networkcredential/)() | Skapar en ny instans. |
| [NetworkCredential](./networkcredential/)(String, String) | Skapar en ny instans. |
| [NetworkCredential](./networkcredential/)(String, String, String) | Skapar en ny instans. |
| [set_Domain](./set_domain/)(String) | Ställer in domänen som verifierar autentiseringsuppgifterna. |
| [set_Password](./set_password/)(String) | Ställer in lösenordet. |
| [set_UserName](./set_username/)(String) | Ställer in användarnamnet. |
## Se även

* Class [ICredentials](../icredentials/)
* Class [ICredentialsByHost](../icredentialsbyhost/)
* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
