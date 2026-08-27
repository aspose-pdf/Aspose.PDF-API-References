---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "Aspose.PDF för .NET API‑referens"
description: "ICustomSecurityHandler-metod. Beräknar EncryptionKey. Vanligtvis beräknas nyckeln baserat på UserKey. Du kan använda värden från EncryptionParams som innehåller de aktuella parametrarna vid anropet. Detta värde skickas som nyckelargument i Encrypt och Decrypt."
type: docs
weight: 60
url: /sv/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

Beräkna EncryptionKey. Vanligtvis beräknas nyckeln baserat på UserKey. Du kan använda värden från EncryptionParams, som innehåller de aktuella parametrarna vid anropet. Detta värde skickas som nyckelargument i [`Encrypt`](../encrypt/) och [`Decrypt`](../decrypt/).

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | String | Lösenordet som angavs av användaren. |

### Returvärde

Arrayen med krypteringsnyckeln.

### Se även

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


