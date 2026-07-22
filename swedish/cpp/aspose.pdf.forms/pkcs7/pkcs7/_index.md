---
title: "Aspose::Pdf::Forms::PKCS7::PKCS7 konstruktor"
linktitle: "PKCS7"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::PKCS7::PKCS7 konstruktor. Initierar en ny instans av klassen PKCS7 i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.forms/pkcs7/pkcs7/
---
## PKCS7::PKCS7() constructor


Initierar en ny instans av klassen [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7()
```

## Se även

* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) constructor


Initierar en ny instans av klassen [PKKS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::SharedPtr<Aspose::Pdf::TimestampSettings> &timestampSettings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| timestampSettings | const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\& | Tidsstämpelinställningarna för signaturen. |
## Anmärkningar



Tidsstämpelinställningarna används för att skapa en tidsstämpelsignatur utan att behöva tillhandahålla ett certifikat. Du kan ange tidsstämpeln för ett dokument som en separat signatur.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TimestampSettings](../../../aspose.pdf/timestampsettings/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Initierar en ny instans av klassen [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Ström med certifikatdata organiserad som pfx. |
| password | const System::String\& | Lösenord för att få åtkomst till den privata nyckeln i certifikatet. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::String\&, const System::String\&) constructor


Initierar en ny instans av klassen [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::String &pfx, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pfx | const System::String\& | Pfx-fil som innehåller certifikat för signering. |
| password | const System::String\& | Lösenord för certifikat. |
## Anmärkningar



Lösenord för att få åtkomst till den privata nyckeln i certifikatet.
## Se även

* Class [String](../../../system/string/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
