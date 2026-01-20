---
title: System::Net::Security::SslStream::SslStream constructor
linktitle: SslStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Security::SslStream::SslStream constructor. Constructs a new instance in C++.'
type: docs
weight: 100
url: /cpp/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | The stream that is used for sending and receiving data. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | The stream that is used for sending and receiving data. |
| leaveInnerStreamOpen | bool | If true, closing the current instance has no effect on 'InnerStream'. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | The stream that is used for sending and receiving data. |
| leaveInnerStreamOpen | bool | If true, closing the current instance has no effect on 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | The delegate that is used for validating the certificate supplied by the remote party. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | The stream that is used for sending and receiving data. |
| leaveInnerStreamOpen | bool | If true, closing the current instance has no effect on 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | The delegate that is used for validating the certificate supplied by the remote party. |
| userCertificateSelectionCallback | LocalCertificateSelectionCallback | The delegate that is used for selecting the certificate used for authentication. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | The stream that is used for sending and receiving data. |
| leaveInnerStreamOpen | bool | If true, closing the current instance has no effect on 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | The delegate that is used for validating the certificate supplied by the remote party. |
| userCertificateSelectionCallback | LocalCertificateSelectionCallback | The delegate that is used for selecting the certificate used for authentication. |
| encryptionPolicy | EncryptionPolicy | The encryption policy. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
