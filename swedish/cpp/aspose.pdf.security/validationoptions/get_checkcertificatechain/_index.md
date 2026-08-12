---
title: "Aspose::Pdf::Security::ValidationOptions::get_CheckCertificateChain metod"
linktitle: "get_CheckCertificateChain"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ValidationOptions::get_CheckCertificateChain metod. Hämtar ett värde som visar om certifikatkedjan ska kontrolleras under valideringsprocessen i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.security/validationoptions/get_checkcertificatechain/
---
## ValidationOptions::get_CheckCertificateChain method


Hämtar ett värde som indikerar om certifikatkedjan ska kontrolleras under valideringsprocessen.

```cpp
bool Aspose::Pdf::Security::ValidationOptions::get_CheckCertificateChain() const
```

## Anmärkningar


När egenskapen är satt kontrolleras om en kedja av certifikat finns; om den saknas blir verifieringsresultatet [ValidationStatus::Undefined](../../validationstatus/), vilket motsvarar Adobe Acrobat‑beteendet. Om du bara vill kontrollera återkallningsstatusen online, sätt fältet till **false**. Standardvärdet är **false**.
## Se även

* Class [ValidationOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
