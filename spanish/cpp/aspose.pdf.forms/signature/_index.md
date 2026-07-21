---
title: "Aspose::Pdf::Forms::Signature clase"
linktitle: "Signature"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::Signature clase. Una clase abstracta que representa un objeto de firma en el documento pdf. Las firmas son campos con valores de objetos de firma, los cuales contienen datos que se utilizan para verificar la validez del documento en C++."
type: docs
weight: 2400
url: /es/cpp/aspose.pdf.forms/signature/
---
## Signature class


Una clase abstracta que representa un objeto de firma en el documento pdf. [Signatures](../../aspose.pdf.signatures/) son campos con valores de objetos de firma, los cuales contienen datos que se utilizan para verificar la validez del documento.

```cpp
class Signature : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Authority](./get_authority/)() const | El nombre de la persona o autoridad que firma el documento. |
| [get_AvoidEstimatingSignatureLength](./get_avoidestimatingsignaturelength/)() const | Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma. |
| [get_ByteRange](./get_byterange/)() const | Una matriz de pares de enteros (desplazamiento de byte inicial, longitud en bytes) que describen el rango exacto de bytes para el cálculo del digest. |
| [get_ContactInfo](./get_contactinfo/)() const | Información proporcionada por el firmante para permitir que el destinatario contacte al firmante y verifique la firma, p. ej. un número de teléfono. |
| [get_CustomAppearance](./get_customappearance/)() const | Obtiene/establece la apariencia personalizada. |
| [get_CustomSignHash](./get_customsignhash/)() const | El delegado para firmar de forma personalizada el hash del documento. |
| [get_Date](./get_date/)() const | La hora de la firma. |
| [get_DefaultSignatureLength](./get_defaultsignaturelength/)() const | Obtiene la longitud predeterminada de los datos de la firma en bytes. |
| [get_Location](./get_location/)() const | El nombre del host de la CPU o la ubicación física de la firma. |
| [get_OcspSettings](./get_ocspsettings/)() const | Obtiene/establece la configuración OCSP. |
| [get_Reason](./get_reason/)() const | La razón de la firma, como (Estoy de acuerdo, Pip B.). |
| [get_ShowProperties](./get_showproperties/)() const | Forzar mostrar/ocultar las propiedades de la firma. |
| [get_TimestampSettings](./get_timestampsettings/)() const | Obtiene/establece la configuración de marca de tiempo. |
| [get_UseLtv](./get_useltv/)() const | Obtiene/establece la bandera de validación LTV. |
| [GetSignatureAlgorithmInfo](./getsignaturealgorithminfo/)() | Recupera información sobre el algoritmo de firma utilizado en la firma. |
| [set_Authority](./set_authority/)(const System::String\&) | El nombre de la persona o autoridad que firma el documento. |
| [set_AvoidEstimatingSignatureLength](./set_avoidestimatingsignaturelength/)(bool) | Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma. |
| [set_ContactInfo](./set_contactinfo/)(const System::String\&) | Información proporcionada por el firmante para permitir que el destinatario contacte al firmante y verifique la firma, p. ej. un número de teléfono. |
| [set_CustomAppearance](./set_customappearance/)(const System::SharedPtr\<SignatureCustomAppearance\>\&) | Obtiene/establece la apariencia personalizada. |
| [set_CustomSignHash](./set_customsignhash/)(SignHash) | El delegado para firmar de forma personalizada el hash del documento. |
| [set_Date](./set_date/)(System::DateTime) | La hora de la firma. |
| [set_DefaultSignatureLength](./set_defaultsignaturelength/)(int32_t) | Establece la longitud predeterminada de los datos de la firma en bytes. |
| [set_Location](./set_location/)(const System::String\&) | El nombre del host de la CPU o la ubicación física de la firma. |
| [set_OcspSettings](./set_ocspsettings/)(const System::SharedPtr\<Aspose::Pdf::OcspSettings\>\&) | Obtiene/establece la configuración OCSP. |
| [set_Reason](./set_reason/)(const System::String\&) | La razón de la firma, como (Estoy de acuerdo, Pip B.). |
| [set_ShowProperties](./set_showproperties/)(bool) | Forzar mostrar/ocultar las propiedades de la firma. |
| [set_TimestampSettings](./set_timestampsettings/)(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) | Obtiene/establece la configuración de marca de tiempo. |
| [set_UseLtv](./set_useltv/)(bool) | Obtiene/establece la bandera de validación LTV. |
| [Signature](./signature/)() | Inicializa una nueva instancia de la clase [Signature](./). |
| [Signature](./signature/)(const System::String\&, const System::String\&) | Inicializa una nueva instancia de la clase [Signature](./). |
| [Signature](./signature/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Inicializa una nueva instancia de la clase [Signature](./). |
| [TryVerify](./tryverify/)(System::SharedPtr\<Security::VerificationResult\>\&) | Intenta verificar el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. |
| [TryVerify](./tryverify/)(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Intenta verificar el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. |
| [TryVerify](./tryverify/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Intenta verificar el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. La verificación se realiza utilizando el certificado de clave pública externo. |
| [Verify](./verify/)() | Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. |
| [Verify](./verify/)(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. |
| [Verify](./verify/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. La verificación se realiza utilizando el certificado de clave pública externo. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
