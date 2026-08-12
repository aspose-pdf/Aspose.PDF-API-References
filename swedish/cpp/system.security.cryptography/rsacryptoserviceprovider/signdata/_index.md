---
title: "System::Security::Cryptography::RSACryptoServiceProvider::SignData method"
linktitle: "SignData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSACryptoServiceProvider::SignData method. Beräknar signaturen för det angivna inmatningsvärdet i C++."
type: docs
weight: 1600
url: /sv/cpp/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) method


Beräknar signaturen för det angivna inmatningsvärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Buffer](../../../system/buffer/) för att läsa indata från. |
| halg | const SharedPtr\<Object\>\& | Hash-algoritm att använda. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) method


Beräknar signaturen för det angivna inmatningsvärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Buffer](../../../system/buffer/) för att läsa indata från. |
| förskjutning | int32_t | Startindex för inmatningsbuffertens del. |
| count | int32_t | Storlek för inmatningsbuffertens del. |
| halg | const SharedPtr\<Object\>\& | Hash-algoritm att använda. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) method


Beräknar signaturen för det angivna inmatningsvärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input_stream | const SharedPtr\<IO::Stream\>\& | Ström för att läsa data som signeras från. |
| halg | const SharedPtr\<Object\>\& | Hash-algoritm att använda. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
