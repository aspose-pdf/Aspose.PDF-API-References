---
title: "Aspose::Pdf::Forms::SignatureField class"
linktitle: "SignatureField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::SignatureField class. Representerar signaturformulärfält i C++."
type: docs
weight: 2600
url: /sv/cpp/aspose.pdf.forms/signaturefield/
---
## SignatureField class


Representerar signaturformulärfält.

```cpp
class SignatureField : public Aspose::Pdf::Forms::Field
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ExtractCertificate](./extractcertificate/)() | Extraherar det enda X.509-certifikatet i DER-format som en ström. |
| [ExtractCertificateObject](./extractcertificateobject/)() | Extraherar det enda X.509-certifikatobjektet. |
| [ExtractImage](./extractimage/)() | Extraherar signaturens bild som JPEG-kodad ström. |
| [ExtractImage](./extractimage/)(const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Extraherar signaturens bild som kodad ström. |
| [get_Signature](./get_signature/)() | Hämtar signaturobjekt. Detta objekt innehåller signaturdata relaterad till offentliga nyckelkryptografiska standarder. Klasserna [PKCS1](../pkcs1/), [PKCS7](../pkcs7/) och [PKCS7Detached](../pkcs7detached/) representerar alla stödda typer av signaturobjekt. |
| [Sign](./sign/)(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Signerar dokumentet med detta signaturfält. |
| [Sign](./sign/)(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&) | Signera dokumentet med detta signaturfält. |
| [SignatureField](./signaturefield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Initierar en ny instans av klassen [SignatureField](./). |
| [SignatureField](./signaturefield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Initierar en ny instans av klassen [SignatureField](./). |
## Se även

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
