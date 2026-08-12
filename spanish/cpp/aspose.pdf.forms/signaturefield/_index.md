---
title: "Aspose::Pdf::Forms::SignatureField class"
linktitle: "SignatureField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::SignatureField class. Representa el campo de formulario de firma en C++."
type: docs
weight: 2600
url: /es/cpp/aspose.pdf.forms/signaturefield/
---
## SignatureField class


Representa el campo de formulario de firma.

```cpp
class SignatureField : public Aspose::Pdf::Forms::Field
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ExtractCertificate](./extractcertificate/)() | Extrae el único certificado X.509 en formato DER como un flujo. |
| [ExtractCertificateObject](./extractcertificateobject/)() | Extrae el único objeto de certificado X.509. |
| [ExtractImage](./extractimage/)() | Extrae la imagen de la firma como un flujo codificado en JPEG. |
| [ExtractImage](./extractimage/)(const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Extrae la imagen de la firma como un flujo codificado. |
| [get_Signature](./get_signature/)() | Obtiene el objeto de firma. Este objeto contiene datos de firma relacionados con los estándares criptográficos de clave pública. Las clases [PKCS1](../pkcs1/), [PKCS7](../pkcs7/) y [PKCS7Detached](../pkcs7detached/) representan todos los tipos de objetos de firma compatibles. |
| [Sign](./sign/)(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Firma el documento usando este campo de firma. |
| [Sign](./sign/)(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&) | Firma el documento usando este campo de firma. |
| [SignatureField](./signaturefield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Inicializa una nueva instancia de la clase [SignatureField](./). |
| [SignatureField](./signaturefield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Inicializa una nueva instancia de la clase [SignatureField](./). |
## Ver también

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
