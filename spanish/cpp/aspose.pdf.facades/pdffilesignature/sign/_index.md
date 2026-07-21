---
title: "Aspose::Pdf::Facades::PdfFileSignature::Sign método"
linktitle: "Firmar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::Sign método. Firma el documento con la firma de tipo dado que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento PDF ya tiene un campo de firma; no debe proporcionar la ubicación para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). Datos como el motivo de la firma, el contacto y la ubicación deben ser proporcionados por las propiedades correspondientes del objeto Signature sig en C++."
type: docs
weight: 3600
url: /es/cpp/aspose.pdf.facades/pdffilesignature/sign/
---
## PdfFileSignature::Sign(const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) method


Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento PDF ya tiene un campo de firma; no debe proporcionar la ubicación para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). Datos como el motivo de la firma, el contacto y la ubicación deben proporcionarse mediante las propiedades correspondientes del objeto Signature sig.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(const System::String &SigName, const System::SharedPtr<Forms::Signature> &sig)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| SigName | const System::String\& | El nombre del campo de firma. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | El tipo de la firma, puede ser PKCS1 (objeto Pkcs1Signature), PKCS7 y PKCS7 detached (objeto Pkcs7Signature) |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(const System::String\&, const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) method


Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento PDF ya tiene un campo de firma; no debe proporcionar la ubicación para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(const System::String &SigName, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, const System::SharedPtr<Forms::Signature> &sig)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| SigName | const System::String\& | El nombre del campo de firma. |
| SigReason | const System::String\& | La razón de la firma. |
| SigContact | const System::String\& | El contacto de la firma. |
| SigLocation | const System::String\& | La ubicación de la firma. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | El tipo de la firma, puede ser PKCS1, PKCS7 y PKCS7Detached. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) method


Firma el documento con la firma del tipo especificado.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::Signature> &sig)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int32_t | El número de página en el que se realiza la firma. |
| visible | bool | La visibilidad de la firma. |
| annotRect | System::Drawing::Rectangle | El rectángulo de la firma. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | El tipo de la firma, puede ser PKCS1, PKCS7 y PKCS7Detached. Datos como el motivo de la firma, el contacto y la ubicación deben estar ya presentes en este objeto (ver propiedades correspondientes). |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, const System::String\&, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) method


Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. Antes de firmar, el documento PDF debe ya contener un campo de firma; la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, const System::String &SigName, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::Signature> &sig)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int32_t | El número de página en el que se realiza la firma. |
| SigName | const System::String\& | El nombre del campo de firma. |
| SigReason | const System::String\& | La razón de la firma. |
| SigContact | const System::String\& | El contacto de la firma. |
| SigLocation | const System::String\& | La ubicación de la firma. |
| visible | bool | La visibilidad de la firma. |
| annotRect | System::Drawing::Rectangle | El rectángulo de la firma. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | El tipo de la firma, puede ser PKCS1, PKCS7 y PKCS7Detached. |

## Ver también

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle) method


Crea una firma en el documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int32_t | El número de página en el que se realiza la firma. |
| SigReason | const System::String\& | La razón de la firma. |
| SigContact | const System::String\& | El contacto de la firma. |
| SigLocation | const System::String\& | La ubicación de la firma. |
| visible | bool | La visibilidad de la firma. |
| annotRect | System::Drawing::Rectangle | El rectángulo de la firma. |

## Ver también

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) method


Firma el documento con la firma del tipo especificado.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::Signature> &sig)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int32_t | El número de página en el que se realiza la firma. |
| SigReason | const System::String\& | La razón de la firma. |
| SigContact | const System::String\& | El contacto de la firma. |
| SigLocation | const System::String\& | La ubicación de la firma. |
| visible | bool | La visibilidad de la firma. |
| annotRect | System::Drawing::Rectangle | El rectángulo de la firma. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | El tipo de la firma, puede ser PKCS1, PKCS7 y PKCS7Detached. |

## Ver también

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
