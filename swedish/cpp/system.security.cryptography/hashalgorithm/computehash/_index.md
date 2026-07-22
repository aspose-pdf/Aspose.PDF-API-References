---
title: "System::Security::Cryptography::HashAlgorithm::ComputeHash metod"
linktitle: "ComputeHash"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::HashAlgorithm::ComputeHash metod. Hashar bufferten i C++."
type: docs
weight: 200
url: /sv/cpp/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) method


Hashar buffert.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Källbuffert. |

### ReturnValue

Beräknat hashvärde.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) method


Hashar buffertsegment.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Källbuffert. |
| förskjutning | int | Offset i källbufferten. |
| count | int | Antal byte att använda från källbufferten. |

### ReturnValue

Beräknat hashvärde.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) method


Läser ström tills slutet och beräknar hash för den lästa datan.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | SharedPtr\<IO::Stream\> const\& | Ström för att läsa data från. |

### ReturnValue

Beräknat hashvärde för hela strömdata.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
