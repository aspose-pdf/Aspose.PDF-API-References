---
title: "System::Net::Security::SslStream::SslStream constructor"
linktitle: "SslStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Security::SslStream::SslStream constructor. Construye una nueva instancia en C++."
type: docs
weight: 100
url: /es/cpp/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) constructor


Construye una nueva instancia.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | El flujo que se utiliza para enviar y recibir datos. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) constructor


Construye una nueva instancia.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | El flujo que se utiliza para enviar y recibir datos. |
| leaveInnerStreamOpen | bool | Si es verdadero, cerrar la instancia actual no tiene efecto sobre 'InnerStream'. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) constructor


Construye una nueva instancia.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | El flujo que se utiliza para enviar y recibir datos. |
| leaveInnerStreamOpen | bool | Si es verdadero, cerrar la instancia actual no tiene efecto sobre 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | El delegado que se utiliza para validar el certificado proporcionado por la parte remota. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) constructor


Construye una nueva instancia.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | El flujo que se utiliza para enviar y recibir datos. |
| leaveInnerStreamOpen | bool | Si es verdadero, cerrar la instancia actual no tiene efecto sobre 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | El delegado que se utiliza para validar el certificado proporcionado por la parte remota. |
| userCertificateSelectionCallback | LocalCertificateSelectionCallback | El delegado que se utiliza para seleccionar el certificado usado para la autenticación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) constructor


Construye una nueva instancia.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | El flujo que se utiliza para enviar y recibir datos. |
| leaveInnerStreamOpen | bool | Si es verdadero, cerrar la instancia actual no tiene efecto sobre 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | El delegado que se utiliza para validar el certificado proporcionado por la parte remota. |
| userCertificateSelectionCallback | LocalCertificateSelectionCallback | El delegado que se utiliza para seleccionar el certificado usado para la autenticación. |
| encryptionPolicy | EncryptionPolicy | La política de cifrado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
