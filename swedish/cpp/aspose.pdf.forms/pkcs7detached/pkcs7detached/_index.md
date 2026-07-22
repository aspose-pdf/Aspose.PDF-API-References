---
title: "Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached konstruktor"
linktitle: "PKCS7Detached"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached konstruktor. Initierar en ny instans av klassen PKCS7Detached i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.forms/pkcs7detached/pkcs7detached/
---
## PKCS7Detached::PKCS7Detached() constructor


Initierar en ny instans av klassen [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached()
```

## Se även

* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) constructor


Initierar en ny instans av klassen [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<Aspose::Pdf::TimestampSettings> &timestampSettings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| timestampSettings | const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\& | Tidsstämpelinställningarna för signaturen. |
## Anmärkningar



Tidsstämpelinställningarna används för att skapa en tidsstämpelsignatur utan att behöva tillhandahålla ett certifikat. Du kan ange tidsstämpeln för ett dokument som en separat signatur.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TimestampSettings](../../../aspose.pdf/timestampsettings/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&) constructor


Initierar en ny instans av klassen [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &image)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | const System::SharedPtr\<System::IO::Stream\>\& | Denna bild kommer att definiera signaturens utseende på sidan. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&, DigestHashAlgorithm) constructor


Initierar en ny instans av klassen [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &image, DigestHashAlgorithm digestHashAlgorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | const System::SharedPtr\<System::IO::Stream\>\& | Denna bild kommer att definiera signaturens utseende på sidan. |
| digestHashAlgorithm | DigestHashAlgorithm | Digestalgoritmen för att signera ett dokument. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Initierar en ny instans av klassen [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Ström med certifikatdata organiserad som pfx. |
| password | const System::String\& | Lösenord för att få åtkomst till den privata nyckeln i certifikatet. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, DigestHashAlgorithm) constructor


Initierar en ny instans av klassen [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password, DigestHashAlgorithm digestHashAlgorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Ström med certifikatdata organiserad som pfx. |
| password | const System::String\& | Lösenord för att få åtkomst till den privata nyckeln i certifikatet. |
| digestHashAlgorithm | DigestHashAlgorithm | Digestalgoritmen för att signera ett dokument. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::String\&, const System::String\&) constructor


Initierar en ny instans av klassen [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::String &pfx, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pfx | const System::String\& | Pfx-fil som innehåller certifikat för signering. |
| password | const System::String\& | Lösenord för att få åtkomst till den privata nyckeln i certifikatet. |

## Se även

* Class [String](../../../system/string/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::String\&, const System::String\&, DigestHashAlgorithm) constructor


Initierar en ny instans av klassen [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::String &pfx, const System::String &password, DigestHashAlgorithm digestHashAlgorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pfx | const System::String\& | Pfx-fil som innehåller certifikat för signering. |
| password | const System::String\& | Lösenord för att få åtkomst till den privata nyckeln i certifikatet. |
| digestHashAlgorithm | DigestHashAlgorithm | Digestalgoritmen för att signera ett dokument. |

## Se även

* Class [String](../../../system/string/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(DigestHashAlgorithm) constructor


Initierar en ny instans av klassen [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(DigestHashAlgorithm digestHashAlgorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| digestHashAlgorithm | DigestHashAlgorithm | Digestalgoritmen för att signera ett dokument. |

## Se även

* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
