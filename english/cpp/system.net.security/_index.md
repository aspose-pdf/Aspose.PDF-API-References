---
title: System::Net::Security namespace
linktitle: System::Net::Security
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Net::Security namespace in C++.'
type: docs
weight: 5400
url: /cpp/system.net.security/
---



## Classes

| Class | Description |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Contains the methods for passing credentials across a stream. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SslStream](./sslstream/) | A stream that uses the SSL protocol to authenticate the server and optionally the client. |
## Enums

| Enum | Description |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest-specific authentication flags. |
| [EncryptionPolicy](./encryptionpolicy/) | Enumerates the encryption policies. |
| [SslPolicyErrors](./sslpolicyerrors/) | Enumerates the policy errors of SSL. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | A user delegate used to select local SSL certificate. |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | A user delegate used to verify remote SSL certificate. |
