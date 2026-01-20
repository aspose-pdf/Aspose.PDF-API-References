---
title: System::Net::Security::SslStream::AuthenticateAsClient method
linktitle: AuthenticateAsClient
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Security::SslStream::AuthenticateAsClient method. Authenticates the client-side of the connection in C++.'
type: docs
weight: 200
url: /cpp/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) method


Authenticates the client-side of the connection.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


| Parameter | Type | Description |
| --- | --- | --- |
| targetHost | String | The name of the server that shares the current instance. |

## See Also

* Class [String](../../../system/string/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) method


Authenticates the client-side of the connection.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


| Parameter | Type | Description |
| --- | --- | --- |
| targetHost | String | The name of the server that shares the current instance. |
| clientCertificates | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\> | The client certificates. |
| enabledSslProtocols | System::Security::Authentication::SslProtocols | The SSL protocols that are used for authentication. |
| checkCertificateRevocation | bool | A value that indicates if the certificate revocation list must be checked during authentication. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
