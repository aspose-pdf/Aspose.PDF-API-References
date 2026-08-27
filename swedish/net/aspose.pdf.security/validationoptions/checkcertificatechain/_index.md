---
title: "ValidationOptions.CheckCertificateChain"
second_title: "Aspose.PDF för .NET API‑referens"
description: "ValidationOptions egenskap. Hämtar eller anger ett värde som indikerar om certifikatkedjan ska kontrolleras under valideringsprocessen."
type: docs
weight: 20
url: /sv/net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

Hämtar eller anger ett värde som indikerar om certifikatkedjan ska kontrolleras under valideringsprocessen.

```csharp
public bool CheckCertificateChain { get; set; }
```

## Anmärkningar

När egenskapen är inställd kontrolleras om en kedja av certifikat finns; om den saknas blir verifieringsresultatet Undefined, vilket motsvarar beteendet i Adobe Acrobat. Om du bara vill kontrollera revokeringsstatusen online, sätt fältet till `false`. Standardvärdet är `false`.

### Se även

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


