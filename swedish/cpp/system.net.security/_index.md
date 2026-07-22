---
title: "System::Net::Security‑namnutrymme"
linktitle: "System::Net::Security"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder System::Net::Security‑namnutrymmet i C++."
type: docs
weight: 5400
url: /sv/cpp/system.net.security/
---



## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Innehåller metoderna för att skicka autentiseringsuppgifter över en ström. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [SslStream](./sslstream/) | En ström som använder SSL‑protokollet för att autentisera servern och valfritt även klienten. |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest‑specifika autentiseringsflaggor. |
| [EncryptionPolicy](./encryptionpolicy/) | Enumererar krypteringspolicyerna. |
| [SslPolicyErrors](./sslpolicyerrors/) | Enumererar policyfel för SSL. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | En användardelegat som används för att välja lokalt SSL‑certifikat. |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | En användardelegat som används för att verifiera fjärr‑SSL‑certifikat. |
