---
title: "Aspose::Pdf::Forms::Signature-klass"
linktitle: "Signature"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::Signature-klass. En abstrakt klass som representerar signaturobjekt i pdf-dokumentet. Signaturer är fält med värden av signaturobjekt, de sista innehåller data som används för att verifiera dokumentets giltighet i C++."
type: docs
weight: 2400
url: /sv/cpp/aspose.pdf.forms/signature/
---
## Signature class


En abstrakt klass som representerar signaturobjekt i pdf-dokumentet. [Signatures](../../aspose.pdf.signatures/) är fält med värden av signaturobjekt, de sista innehåller data som används för att verifiera dokumentets giltighet.

```cpp
class Signature : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Authority](./get_authority/)() const | Namnet på personen eller myndigheten som signerar dokumentet. |
| [get_AvoidEstimatingSignatureLength](./get_avoidestimatingsignaturelength/)() const | Hämtar och anger ett alternativ som betyder om man ska undvika att uppskatta längden på en signatur. |
| [get_ByteRange](./get_byterange/)() const | En array av par av heltal (startbyteoffset, längd i byte) som ska beskriva det exakta byteintervallet för digestberäkningen. |
| [get_ContactInfo](./get_contactinfo/)() const | Information som tillhandahålls av signatären för att möjliggöra att mottagaren kan kontakta signatären för att verifiera signaturen, t.ex. ett telefonnummer. |
| [get_CustomAppearance](./get_customappearance/)() const | Hämtar/anger det anpassade utseendet. |
| [get_CustomSignHash](./get_customsignhash/)() const | Delegaten för att anpassat signera dokumentets hash. |
| [get_Date](./get_date/)() const | Tidpunkten för signering. |
| [get_DefaultSignatureLength](./get_defaultsignaturelength/)() const | Hämtar standardlängden för signaturdata i byte. |
| [get_Location](./get_location/)() const | CPU-värdnamnet eller den fysiska platsen för signeringen. |
| [get_OcspSettings](./get_ocspsettings/)() const | Hämtar/anger OCSP-inställningar. |
| [get_Reason](./get_reason/)() const | Anledningen till signeringen, såsom (Jag godkänner, Pip B.). |
| [get_ShowProperties](./get_showproperties/)() const | Tvinga att visa/dölja signaturegenskaper. |
| [get_TimestampSettings](./get_timestampsettings/)() const | Hämtar/anger tidsstämpelinställningar. |
| [get_UseLtv](./get_useltv/)() const | Hämtar/anger LTV-valideringsflagga. |
| [GetSignatureAlgorithmInfo](./getsignaturealgorithminfo/)() | Hämtar information om signaturalgoritmen som används i signaturen. |
| [set_Authority](./set_authority/)(const System::String\&) | Namnet på personen eller myndigheten som signerar dokumentet. |
| [set_AvoidEstimatingSignatureLength](./set_avoidestimatingsignaturelength/)(bool) | Hämtar och anger ett alternativ som betyder om man ska undvika att uppskatta längden på en signatur. |
| [set_ContactInfo](./set_contactinfo/)(const System::String\&) | Information som tillhandahålls av signatären för att möjliggöra att mottagaren kan kontakta signatären för att verifiera signaturen, t.ex. ett telefonnummer. |
| [set_CustomAppearance](./set_customappearance/)(const System::SharedPtr\<SignatureCustomAppearance\>\&) | Hämtar/anger det anpassade utseendet. |
| [set_CustomSignHash](./set_customsignhash/)(SignHash) | Delegaten för att anpassat signera dokumentets hash. |
| [set_Date](./set_date/)(System::DateTime) | Tidpunkten för signering. |
| [set_DefaultSignatureLength](./set_defaultsignaturelength/)(int32_t) | Anger standardlängden för signaturdata i byte. |
| [set_Location](./set_location/)(const System::String\&) | CPU-värdnamnet eller den fysiska platsen för signeringen. |
| [set_OcspSettings](./set_ocspsettings/)(const System::SharedPtr\<Aspose::Pdf::OcspSettings\>\&) | Hämtar/anger OCSP-inställningar. |
| [set_Reason](./set_reason/)(const System::String\&) | Anledningen till signeringen, såsom (Jag godkänner, Pip B.). |
| [set_ShowProperties](./set_showproperties/)(bool) | Tvinga att visa/dölja signaturegenskaper. |
| [set_TimestampSettings](./set_timestampsettings/)(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) | Hämtar/anger tidsstämpelinställningar. |
| [set_UseLtv](./set_useltv/)(bool) | Hämtar/anger LTV-valideringsflagga. |
| [Signature](./signature/)() | Initierar en ny instans av klassen [Signature](./). |
| [Signature](./signature/)(const System::String\&, const System::String\&) | Initierar en ny instans av klassen [Signature](./). |
| [Signature](./signature/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Initierar en ny instans av klassen [Signature](./). |
| [TryVerify](./tryverify/)(System::SharedPtr\<Security::VerificationResult\>\&) | Försök att verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |
| [TryVerify](./tryverify/)(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Försök att verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |
| [TryVerify](./tryverify/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Försök att verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. Verifieringen utförs med hjälp av det externa offentliga nyckelcertifikatet. |
| [Verify](./verify/)() | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |
| [Verify](./verify/)(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |
| [Verify](./verify/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. Verifieringen utförs med hjälp av det externa offentliga nyckelcertifikatet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
