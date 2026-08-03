---
title: "ICustomSecurityHandler.Initialize"
second_title: "Aspose.PDF för .NET API‑referens"
description: "ICustomSecurityHandler-metod. Anropas för att initiera den aktuella instansen för kryptering. Observera att vid kryptering kommer den att fyllas med data från de överförda egenskaperna ICustomSecurityHandler och vid öppning av document från krypteringsordlistan. Om metoden anropas under ny kryptering kommer UserKey och OwnerKey att vara null."
type: docs
weight: 120
url: /sv/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

Anropas för att initiera den aktuella instansen för kryptering. Observera att vid kryptering kommer den att fyllas med data från de överförda egenskaperna [`ICustomSecurityHandler`](../), och vid öppning av document från krypteringsordlistan. Om metoden anropas under ny kryptering, kommer då [`UserKey`](../../encryptionparameters/userkey/) och [`OwnerKey`](../../encryptionparameters/ownerkey/) att vara null.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parametrar | EncryptionParameters | Krypteringsparametrarna. |

### Se även

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


