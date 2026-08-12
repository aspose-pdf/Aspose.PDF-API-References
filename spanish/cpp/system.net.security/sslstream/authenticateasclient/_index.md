---
title: "System::Net::Security::SslStream::AuthenticateAsClient método"
linktitle: "AuthenticateAsClient"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Security::SslStream::AuthenticateAsClient método. Autentica el lado cliente de la conexión en C++."
type: docs
weight: 200
url: /es/cpp/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) method


Autentica el lado cliente de la conexión.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetHost | String | El nombre del servidor que comparte la instancia actual. |

## Ver también

* Class [String](../../../system/string/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) method


Autentica el lado cliente de la conexión.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetHost | String | El nombre del servidor que comparte la instancia actual. |
| clientCertificates | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\> | Los certificados del cliente. |
| enabledSslProtocols | System::Security::Authentication::SslProtocols | Los protocolos SSL que se utilizan para la autenticación. |
| checkCertificateRevocation | bool | Un valor que indica si la lista de revocación de certificados debe verificarse durante la autenticación. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
