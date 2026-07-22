---
title: "Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain metod"
linktitle: "set_CheckCertificateChain"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain metod. Anger ett värde som visar om certifikatkedjan ska kontrolleras under valideringsprocessen i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.security/validationoptions/set_checkcertificatechain/
---
## ValidationOptions::set_CheckCertificateChain method


Ställer in ett värde som indikerar om certifikatkedjan ska kontrolleras under valideringsprocessen.

```cpp
void Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain(bool value)
```

## Anmärkningar


När egenskapen är satt kontrolleras om en kedja av certifikat finns; om den saknas blir verifieringsresultatet [ValidationStatus::Undefined](../../validationstatus/), vilket motsvarar Adobe Acrobat‑beteendet. Om du bara vill kontrollera återkallningsstatusen online, sätt fältet till **false**. Standardvärdet är **false**.
## Se även

* Class [ValidationOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
