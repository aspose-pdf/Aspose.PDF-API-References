---
title: "System::Net::Security::AuthenticatedStream klass"
linktitle: "AuthenticatedStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Security::AuthenticatedStream klass. Innehåller metoderna för att överföra autentiseringsuppgifter över en ström. Objekt av denna klass bör endast allokeras med System::MakeObject() funktion. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.net.security/authenticatedstream/
---
## AuthenticatedStream class


Innehåller metoderna för att överföra autentiseringsuppgifter över en ström. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_IsAuthenticated](./get_isauthenticated/)() const | Returnerar ett värde som indikerar om autentiseringen har lyckats. |
| virtual [get_IsEncrypted](./get_isencrypted/)() const | Returnerar ett värde som indikerar om data som skickas via denna ström är krypterad. |
| virtual [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | Returnerar ett värde som indikerar om en server och en klient är autentiserade. |
| virtual [get_IsServer](./get_isserver/)() const | Returnerar ett värde som indikerar om den lokala sidan av anslutningen är servern. |
| virtual [get_IsSigned](./get_issigned/)() const | Returnerar ett värde som indikerar om data som skickas via denna ström är signerad. |
| [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | RTTI-information. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../../system.io/stream/null/) | En ström utan underliggande lagring. |
## Se även

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
