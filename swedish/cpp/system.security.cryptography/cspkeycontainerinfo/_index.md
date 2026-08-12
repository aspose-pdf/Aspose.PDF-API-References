---
title: "System::Security::Cryptography::CspKeyContainerInfo-klass"
linktitle: "CspKeyContainerInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::CspKeyContainerInfo-klass. Ytterligare information om ett kryptografiskt nyckelpar i C++."
type: docs
weight: 600
url: /sv/cpp/system.security.cryptography/cspkeycontainerinfo/
---
## CspKeyContainerInfo class


Ytterligare information om ett kryptografiskt nyckelpar. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class CspKeyContainerInfo : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CspKeyContainerInfo](./cspkeycontainerinfo/)(const SharedPtr\<CspParameters\>\&) | RTTI-information. |
| [get_Accessible](./get_accessible/)() const | Hämtar en flagga som indikerar om en nyckel i en behållare är åtkomlig. |
| [get_Exportable](./get_exportable/)() const | Hämtar en flagga som indikerar om en nyckel kan exporteras från en behållare. |
| [get_HardwareDevice](./get_hardwaredevice/)() const | Hämtar en flagga som indikerar om en nyckel är en hårdvarunyckel. |
| [get_KeyContainerName](./get_keycontainername/)() const | Hämtar namnet på en nyckelbehållare. |
| [get_KeyNumber](./get_keynumber/)() const | Hämtar ett [KeyNumber](../keynumber/)-objekt. |
| [get_MachineKeyStore](./get_machinekeystore/)() const | Hämtar en flagga som indikerar om en nyckel är laddad från maskinens nyckellager. |
| [get_Protected](./get_protected/)() const | Hämtar en flagga som indikerar om en nyckel är skyddad mot kopiering. |
| [get_ProviderName](./get_providername/)() const | Hämtar leverantörens namn. |
| [get_ProviderType](./get_providertype/)() const | Hämtar leverantörstyp. |
| [get_RandomlyGenerated](./get_randomlygenerated/)() const | Hämtar en flagga som indikerar om en nyckel genererades slumpmässigt. |
| [get_Removable](./get_removable/)() const | Hämtar en flagga som indikerar om en nyckel kan tas bort från en behållare. |
| [get_UniqueKeyContainerName](./get_uniquekeycontainername/)() const | Hämtar ett unikt behållarnamn. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
