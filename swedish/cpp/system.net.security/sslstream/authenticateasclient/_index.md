---
title: "System::Net::Security::SslStream::AuthenticateAsClient metod"
linktitle: "AuthenticateAsClient"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Security::SslStream::AuthenticateAsClient metod. Autentiserar klient-sidan av anslutningen i C++."
type: docs
weight: 200
url: /sv/cpp/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) method


Autentiserar klientdelen av anslutningen.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetHost | String | Namnet på servern som delar den aktuella instansen. |

## Se även

* Class [String](../../../system/string/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) method


Autentiserar klientdelen av anslutningen.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetHost | String | Namnet på servern som delar den aktuella instansen. |
| clientCertificates | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\> | Klientcertifikaten. |
| enabledSslProtocols | System::Security::Authentication::SslProtocols | SSL-protokollen som används för autentisering. |
| checkCertificateRevocation | bool | Ett värde som indikerar om certifikatåterkallningslistan måste kontrolleras under autentisering. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
