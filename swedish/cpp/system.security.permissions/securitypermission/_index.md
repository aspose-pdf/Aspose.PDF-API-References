---
title: "System::Security::Permissions::SecurityPermission klass"
linktitle: "SecurityPermission"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Permissions::SecurityPermission klass. Klass som beskriver säkerhetsbehörighet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.security.permissions/securitypermission/
---
## SecurityPermission class


Klass som beskriver säkerhetsbehörighet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SecurityPermission : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Flags](./get_flags/)() | RTTI-information. |
| [IsUnrestricted](./isunrestricted/)() | Kontrollerar om behörigheten är obegränsad. |
| [SecurityPermission](./securitypermission/)(PermissionState) | Konstruktor. |
| [SecurityPermission](./securitypermission/)(SecurityPermissionFlag) | Konstruktor. |
| [set_Flags](./set_flags/)(SecurityPermissionFlag) | Ställer in flaggor som är associerade med behörigheten. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Permissions](../)
* Library [Aspose.PDF for C++](../../)
