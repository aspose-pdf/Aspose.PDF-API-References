---
title: "System::Net::NetworkInformation::IPGlobalProperties klass"
linktitle: "IPGlobalProperties"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::NetworkInformation::IPGlobalProperties klass. Representerar information om nätverksanslutningen för den lokala datorn. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.net.networkinformation/ipglobalproperties/
---
## IPGlobalProperties class


Representerar information om nätverksanslutningen för den lokala datorn. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class IPGlobalProperties : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_DomainName](./get_domainname/)() | Returnerar domänen som den lokala datorn är registrerad i. |
| virtual [get_HostName](./get_hostname/)() | Returnerar värdnamnet för den lokala datorn. |
| static [GetIPGlobalProperties](./getipglobalproperties/)() | RTTI-information. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net::NetworkInformation](../)
* Library [Aspose.PDF for C++](../../)
