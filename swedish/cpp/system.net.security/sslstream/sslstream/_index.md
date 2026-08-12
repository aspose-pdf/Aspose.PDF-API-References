---
title: "System::Net::Security::SslStream::SslStream konstruktor"
linktitle: "SslStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Security::SslStream::SslStream konstruktor. Skapar en ny instans i C++."
type: docs
weight: 100
url: /sv/cpp/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) constructor


Skapar en ny instans.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | Strömmen som används för att skicka och ta emot data. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) constructor


Skapar en ny instans.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | Strömmen som används för att skicka och ta emot data. |
| leaveInnerStreamOpen | bool | Om true, har stängning av den aktuella instansen ingen effekt på 'InnerStream'. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) constructor


Skapar en ny instans.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | Strömmen som används för att skicka och ta emot data. |
| leaveInnerStreamOpen | bool | Om true, har stängning av den aktuella instansen ingen effekt på 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | Delegaten som används för att validera certifikatet som tillhandahålls av fjärrparten. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) constructor


Skapar en ny instans.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | Strömmen som används för att skicka och ta emot data. |
| leaveInnerStreamOpen | bool | Om true, har stängning av den aktuella instansen ingen effekt på 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | Delegaten som används för att validera certifikatet som tillhandahålls av fjärrparten. |
| userCertificateSelectionCallback | LocalCertificateSelectionCallback | Delegaten som används för att välja certifikatet som används för autentisering. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) constructor


Skapar en ny instans.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | Strömmen som används för att skicka och ta emot data. |
| leaveInnerStreamOpen | bool | Om true, har stängning av den aktuella instansen ingen effekt på 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | Delegaten som används för att validera certifikatet som tillhandahålls av fjärrparten. |
| userCertificateSelectionCallback | LocalCertificateSelectionCallback | Delegaten som används för att välja certifikatet som används för autentisering. |
| encryptionPolicy | EncryptionPolicy | Krypteringspolicyn. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
