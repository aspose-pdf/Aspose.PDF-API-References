---
title: "Aspose::Pdf::Security::ValidationOptions klass"
linktitle: "ValidationOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ValidationOptions klass. Representerar alternativ för validering av en digital signatur i ett PDF‑dokument i C++."
type: docs
weight: 1200
url: /sv/cpp/aspose.pdf.security/validationoptions/
---
## ValidationOptions class


Representerar alternativ för att validera en digital signatur i ett PDF-dokument.

```cpp
class ValidationOptions : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CheckCertificateChain](./get_checkcertificatechain/)() const | Hämtar ett värde som indikerar om certifikatkedjan ska kontrolleras under valideringsprocessen. |
| [get_RequestTimeout](./get_requesttimeout/)() const | Hämtar tidsgränsen, i millisekunder, för nätverksrelaterade operationer under valideringsprocessen. Egenskapen RequestTimeout definierar den maximala tid som systemet ska vänta på ett nätverkssvar när det får åtkomst till online‑resurser, såsom återkallningsstatus eller OCSP‑servrar. |
| [get_ValidationMethod](./get_validationmethod/)() const | Hämtar metoden som används för att validera ett certifikat. |
| [get_ValidationMode](./get_validationmode/)() const | Hämtar valideringsläget för digitala signaturer i ett PDF‑dokument. Egenskapen [ValidationMode](../validationmode/) bestämmer hur strikt valideringsprocessen är. |
| [set_CheckCertificateChain](./set_checkcertificatechain/)(bool) | Ställer in ett värde som indikerar om certifikatkedjan ska kontrolleras under valideringsprocessen. |
| [set_RequestTimeout](./set_requesttimeout/)(int32_t) | Ställer in tidsgränsen, i millisekunder, för nätverksrelaterade operationer under valideringsprocessen. Egenskapen RequestTimeout definierar den maximala tid som systemet ska vänta på ett nätverkssvar när det får åtkomst till online‑resurser, såsom återkallningsstatus eller OCSP‑servrar. |
| [set_ValidationMethod](./set_validationmethod/)(Aspose::Pdf::Security::ValidationMethod) | Ställer in metoden som används för att validera ett certifikat. |
| [set_ValidationMode](./set_validationmode/)(Aspose::Pdf::Security::ValidationMode) | Ställer in valideringsläget för digitala signaturer i ett PDF‑dokument. Egenskapen [ValidationMode](../validationmode/) bestämmer hur strikt valideringsprocessen är. |
| [ValidationOptions](./validationoptions/)() | Skapar en instans av klassen [ValidationOptions](./) klass. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
