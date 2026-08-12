---
title: "Aspose::Pdf::Facades::PdfFileSignature class"
linktitle: "PdfFileSignature"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Facades::PdfFileSignature. Representa una clase para firmar un archivo pdf con un certificado en C++."
type: docs
weight: 2500
url: /es/cpp/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class


Representa una clase para firmar un archivo pdf con un certificado.

```cpp
class PdfFileSignature : public Aspose::Pdf::Facades::SaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Vincula un archivo [Pdf](../../aspose.pdf/) para editar. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Vincula un flujo [Pdf](../../aspose.pdf/) para editar. |
| [Certify](./certify/)(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::DocMDPSignature\>\&) | Certifica el documento con la firma MDP. Datos como el motivo de la firma, contacto y ubicación deben proporcionarse mediante las propiedades correspondientes del objeto Signature sig. |
| [Certify](./certify/)(const System::String\&, const System::SharedPtr\<Forms::DocMDPSignature\>\&) | Certifica el documento con la firma MDP que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento pdf ya tiene un campo de firma; no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver el parámetro sigName). |
| [Close](./close/)() override | Cierra la fachada. |
| [ContainsSignature](./containssignature/)() | Comprueba si el pdf tiene una firma digital o no. |
| [ContainsUsageRights](./containsusagerights/)() | Comprueba si el pdf tiene derechos de uso o no. |
| [CoversWholeDocument](./coverswholedocument/)(const System::String\&) | Comprueba si la firma cubre todo el documento. |
| [CoversWholeDocument](./coverswholedocument/)(const System::SharedPtr\<SignatureName\>\&) | Comprueba si la firma cubre todo el documento. |
| [ExtractCertificate](./extractcertificate/)(const System::String\&) | Extrae el único certificado X.509 de la firma como un flujo. |
| [ExtractCertificate](./extractcertificate/)(const System::SharedPtr\<SignatureName\>\&) | Extrae el único certificado X.509 de la firma como un flujo. |
| [ExtractImage](./extractimage/)(const System::String\&) | Extrae la imagen de la firma. |
| [ExtractImage](./extractimage/)(const System::SharedPtr\<SignatureName\>\&) | Extrae la imagen de la firma. |
| [get_IsCertified](./get_iscertified/)() | Obtiene la bandera que determina si un documento está certificado o no. |
| [get_IsLtvEnabled](./get_isltvenabled/)() | Obtiene la bandera de LTV habilitada. |
| [get_SignatureAppearance](./get_signatureappearance/)() const | Establece o obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el nombre del archivo de imagen. |
| [get_SignatureAppearanceStream](./get_signatureappearancestream/)() const | Establece o obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el flujo de imagen. |
| [GetAccessPermissions](./getaccesspermissions/)() | Devuelve el valor de permisos de acceso del documento certificado mediante el tipo de firma MDP. |
| [GetBlankSignatureNames](./getblanksignaturenames/)() | Obtiene los nombres de todos los campos de firma vacíos. |
| [GetBlankSignNames](./getblanksignnames/)() | Obtiene los nombres de todos los campos de firma vacíos. |
| [GetContactInfo](./getcontactinfo/)(const System::String\&) | Obtiene la información de contacto de una firma. |
| [GetContactInfo](./getcontactinfo/)(const System::SharedPtr\<SignatureName\>\&) | Obtiene la información de contacto de una firma. |
| [GetDateTime](./getdatetime/)(const System::String\&) | Obtiene la fecha y hora de la firma. |
| [GetDateTime](./getdatetime/)(const System::SharedPtr\<SignatureName\>\&) | Obtiene la fecha y hora de la firma. |
| [GetLocation](./getlocation/)(const System::String\&) | Obtiene la ubicación de una firma. |
| [GetLocation](./getlocation/)(const System::SharedPtr\<SignatureName\>\&) | Obtiene la ubicación de una firma. |
| [GetReason](./getreason/)(const System::String\&) | Obtiene el motivo de una firma. |
| [GetReason](./getreason/)(const System::SharedPtr\<SignatureName\>\&) | Obtiene el motivo de una firma. |
| [GetRevision](./getrevision/)(const System::String\&) | Obtiene la revisión de una firma. |
| [GetRevision](./getrevision/)(const System::SharedPtr\<SignatureName\>\&) | Obtiene la revisión de una firma. |
| [GetSignatureNames](./getsignaturenames/)(bool) | Obtiene los nombres de todas las firmas no vacías. |
| [GetSignaturesInfo](./getsignaturesinfo/)() | Recupera información sobre todos los algoritmos de firmas presentes en el documento PDF. |
| [GetSignerName](./getsignername/)(const System::String\&) | Obtiene el nombre de la persona u organización que firma el documento pdf. |
| [GetSignerName](./getsignername/)(const System::SharedPtr\<SignatureName\>\&) | Obtiene el nombre de la persona u organización que firma el documento pdf. |
| [GetSignNames](./getsignnames/)(bool) | Obtiene los nombres de todas las firmas no vacías. |
| [GetTotalRevision](./gettotalrevision/)() | Obtiene la revisión total. |
| [IsContainSignature](./iscontainsignature/)() | Comprueba si el pdf tiene una firma digital o no. |
| [IsCoversWholeDocument](./iscoverswholedocument/)(const System::String\&) | Comprueba si la firma cubre todo el documento. |
| [PdfFileSignature](./pdffilesignature/)() | El constructor de la clase [PdfFileSignature](./). |
| [PdfFileSignature](./pdffilesignature/)(const System::String\&) | El constructor de la clase [PdfFileSignature](./). |
| [PdfFileSignature](./pdffilesignature/)(const System::String\&, const System::String\&) | El constructor de la clase [PdfFileSignature](./). |
| [PdfFileSignature](./pdffilesignature/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfFileSignature](./) sobre la base del *documento*. |
| [PdfFileSignature](./pdffilesignature/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Inicializa un nuevo objeto [PdfFileSignature](./) sobre la base del *documento*. |
| [RemoveSignature](./removesignature/)(const System::String\&) | Elimina la firma según el nombre de la firma. |
| [RemoveSignature](./removesignature/)(const System::SharedPtr\<SignatureName\>\&) | Elimina la firma según el nombre de la firma. |
| [RemoveSignature](./removesignature/)(const System::String\&, bool) | Elimina la firma según el nombre de la firma. |
| [RemoveSignature](./removesignature/)(const System::SharedPtr\<SignatureName\>\&, bool) | Elimina la firma según el nombre de la firma. |
| [RemoveSignatures](./removesignatures/)() | Elimina todas las firmas. |
| [RemoveUsageRights](./removeusagerights/)() | Elimina la entrada de derechos de uso. |
| [Save](./save/)(System::String) override | Guarda el PDF resultante en un archivo. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Guarda el PDF resultante en un flujo. |
| [Save](./save/)() | Guarda el archivo PDF firmado. El nombre del archivo de salida debe proporcionarse antes mediante el constructor correspondiente de [PdfFileSignature](./). |
| [set_SignatureAppearance](./set_signatureappearance/)(const System::String\&) | Establece o obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el nombre del archivo de imagen. |
| [set_SignatureAppearanceStream](./set_signatureappearancestream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece o obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el flujo de imagen. |
| [SetCertificate](./setcertificate/)(const System::String\&, const System::String\&) | Establece el archivo de certificado y la contraseña para la rutina de firma. |
| [Sign](./sign/)(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle) | Crea una firma en el documento PDF. |
| [Sign](./sign/)(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) | Firma el documento con la firma del tipo especificado. |
| [Sign](./sign/)(int32_t, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) | Firma el documento con la firma del tipo especificado. |
| [Sign](./sign/)(const System::String\&, const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) | Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento PDF ya tiene un campo de firma; no debe proporcionar la ubicación para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). |
| [Sign](./sign/)(int32_t, const System::String\&, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) | Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. Antes de firmar, el documento PDF debe ya contener un campo de firma; la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). |
| [Sign](./sign/)(const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) | Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento PDF ya tiene un campo de firma; no debe proporcionar la ubicación para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). Datos como el motivo de la firma, el contacto y la ubicación deben proporcionarse mediante las propiedades correspondientes del objeto Signature sig. |
| [TryExtractCertificate](./tryextractcertificate/)(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) | Extrae el certificado X.509 único de la firma. |
| [TryExtractCertificate](./tryextractcertificate/)(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::IO::Stream\>\&) | Extrae el único certificado X.509 de la firma como un flujo. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Intenta verificar la validez de una firma. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Intenta verificar la validez de una firma. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Intenta verificar la validez de una firma. La verificación se realiza utilizando el certificado de clave pública externo. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Intenta verificar la validez de una firma. La verificación se realiza utilizando el certificado de clave pública externo. |
| [VerifySignature](./verifysignature/)(const System::String\&) | Comprueba la validez de una firma. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&) | Comprueba la validez de una firma. |
| [VerifySignature](./verifysignature/)(const System::String\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Comprueba la validez de una firma. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Comprueba la validez de una firma. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Comprueba la validez de una firma. La verificación se realiza utilizando el certificado de clave pública externo. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) | Comprueba la validez de una firma. La verificación se realiza utilizando el certificado de clave pública externo. |
| [VerifySigned](./verifysigned/)(const System::String\&) | Comprueba la validez de una firma. El método está obsoleto y será eliminado en la versión 25.1. Utilice el método VerifySignature en su lugar. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
