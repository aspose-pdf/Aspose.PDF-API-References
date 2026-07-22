---
title: "System::Security namnrymd"
linktitle: "System::Security"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder System::Security namnrymd i C++."
type: docs
weight: 6100
url: /sv/cpp/system.security/
---



## Klasser

| Klass | Beskrivning |
| --- | --- |
| [SecureString](./securestring/) | Secure string, representerar text som bör hållas konfidentiell. Denna klass krypterar INTE den interna datan. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [SecureStringMarshal](./securestringmarshal/) | Samling av metoder för att allokera och kopiera ohanterade minnesblock. |
| [SecurityElement](./securityelement/) | XML-objektmodell för kodning av säkerhetsobjekt. Inte implementerad. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) pekartyp. |
