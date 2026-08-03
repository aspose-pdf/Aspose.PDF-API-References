---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Aspose.PDF för .NET API‑referens"
description: "ICustomSecurityHandler-metod. Skapar en kodad array baserad på användarens lösenord. Detta värde används vanligtvis för att kontrollera om lösenordet tillhör användaren eller ägaren och för att hämta krypteringsnyckeln. Anropas under kryptering för att förbereda den och fylla i krypteringsordlistan. Det användarspecificerade lösenordet skickas som ett argument när documentkryptering anropas."
type: docs
weight: 110
url: /sv/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

Skapar en kodad array baserad på användarens lösenord. Detta värde används vanligtvis för att kontrollera om lösenordet tillhör användaren eller ägaren, och för att hämta krypteringsnyckeln. Anropas under kryptering för att förbereda det och fylla i krypteringsordlistan. Det användarspecificerade lösenordet skickas som ett argument när dokumentkryptering anropas.

```csharp
public byte[] GetUserKey(string userPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | String | Användarlösenordet. |

### Returvärde

Arrayen med användarnyckeln.

### Se även

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


