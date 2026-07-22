---
title: "Aspose::Pdf::Security::VerificationResult‑klass"
linktitle: "VerificationResult"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::VerificationResult‑klass. Representerar resultatet av att verifiera en digital signatur i en PDF‑fil i C++."
type: docs
weight: 1400
url: /sv/cpp/aspose.pdf.security/verificationresult/
---
## VerificationResult class


Representerar resultatet av att verifiera en digital signatur i en PDF-fil.

```cpp
class VerificationResult : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_IsCompromised](./get_iscompromised/)() const | Indikerar om den digitala signaturstrukturen sannolikt är komprometterad. Detta innebär en ändring för att kringgå signaturkontrollen av PDF‑verktyg. Se [Message](../) för mer detaljer. |
| [get_Message](./get_message/)() const | Hämtar meddelandet som är kopplat till verifieringsresultatet. Egenskapens värde ger ytterligare detaljer om verifieringsutfallet, såsom felbeskrivningar eller framgångsmeddelanden. |
| [get_State](./get_state/)() const | Representerar verifieringstillståndet för en digital signatur i en PDF‑fil. Indikerar om signaturen är giltig, ogiltig eller odefinierad. |
| [get_VerificationException](./get_verificationexception/)() const | Hämtar undantaget som är kopplat till verifieringsprocessen om det finns. Denna egenskap ger detaljer om fel eller problem som uppstått under verifieringen av en digital signatur i en PDF‑fil. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
