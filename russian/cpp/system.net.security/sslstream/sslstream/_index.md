---
title: "Конструктор System::Net::Security::SslStream::SslStream"
linktitle: "SslStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::Net::Security::SslStream::SslStream. Создаёт новый экземпляр в C++."
type: docs
weight: 100
url: /ru/cpp/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) constructor


Создаёт новый экземпляр.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | Поток, который используется для отправки и получения данных. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) constructor


Создаёт новый экземпляр.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | Поток, который используется для отправки и получения данных. |
| leaveInnerStreamOpen | bool | Если true, закрытие текущего экземпляра не влияет на 'InnerStream'. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) constructor


Создаёт новый экземпляр.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | Поток, который используется для отправки и получения данных. |
| leaveInnerStreamOpen | bool | Если true, закрытие текущего экземпляра не влияет на 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | Делегат, используемый для проверки сертификата, предоставленного удалённой стороной. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) constructor


Создаёт новый экземпляр.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | Поток, который используется для отправки и получения данных. |
| leaveInnerStreamOpen | bool | Если true, закрытие текущего экземпляра не влияет на 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | Делегат, используемый для проверки сертификата, предоставленного удалённой стороной. |
| userCertificateSelectionCallback | LocalCertificateSelectionCallback | Делегат, используемый для выбора сертификата, используемого для аутентификации. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) constructor


Создаёт новый экземпляр.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| innerStream | System::SharedPtr\<IO::Stream\> | Поток, который используется для отправки и получения данных. |
| leaveInnerStreamOpen | bool | Если true, закрытие текущего экземпляра не влияет на 'InnerStream'. |
| userCertificateValidationCallback | RemoteCertificateValidationCallback | Делегат, используемый для проверки сертификата, предоставленного удалённой стороной. |
| userCertificateSelectionCallback | LocalCertificateSelectionCallback | Делегат, используемый для выбора сертификата, используемого для аутентификации. |
| encryptionPolicy | EncryptionPolicy | Политика шифрования. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
