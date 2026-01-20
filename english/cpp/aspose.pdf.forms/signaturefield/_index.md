---
title: Aspose::Pdf::Forms::SignatureField class
linktitle: SignatureField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::SignatureField class. Represents signature form field in C++.'
type: docs
weight: 2600
url: /cpp/aspose.pdf.forms/signaturefield/
---
## SignatureField class


Represents signature form field.

```cpp
class SignatureField : public Aspose::Pdf::Forms::Field
```

## Methods

| Method | Description |
| --- | --- |
| [ExtractCertificate](./extractcertificate/)() | Extracts the single X.509 certificate in DER format as a stream. |
| [ExtractCertificateObject](./extractcertificateobject/)() | Extracts the single X.509 certificate object. |
| [ExtractImage](./extractimage/)() | Extracts signature's image as jpeg encoded stream. |
| [ExtractImage](./extractimage/)(System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>) | Extracts signature's image as encoded stream. |
| [get_Signature](./get_signature/)() | Gets signature object. This object contains signature data regarding public-key cryptographic standards. Classes [PKCS1](../pkcs1/), [PKCS7](../pkcs7/) and [PKCS7Detached](../pkcs7detached/) represent all supported types of signature objects. |
| [Sign](./sign/)(System::SharedPtr\<Aspose::Pdf::Forms::Signature\>, System::SharedPtr\<System::IO::Stream\>, System::String) | Signs the document using this signature field. |
| [Sign](./sign/)(System::SharedPtr\<Aspose::Pdf::Forms::Signature\>) | Sign the document using this signature field. |
| [SignatureField](./signaturefield/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Initializes new instance of the [SignatureField](./) class. |
| [SignatureField](./signaturefield/)(System::SharedPtr\<Document\>, System::SharedPtr\<Rectangle\>) | Initializes new instance of the [SignatureField](./) class. |
## See Also

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
