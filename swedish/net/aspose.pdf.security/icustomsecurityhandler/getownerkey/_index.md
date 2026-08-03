---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Aspose.PDF för .NET API‑referens"
description: "ICustomSecurityHandler‑metod. Skapar en kodad array baserat på lösenord som kommer att skrivas till O‑fältet i krypteringsdictionaryn. Bör endast förlita sig på de argument som skickas. Användarlösenordet kan beräknas från detta fält med ägarlösenordet. Anropas under kryptering för att förbereda den och fylla i krypteringsdictionaryn. Värdet kommer att vara tillgängligt i CalculateEncryptionKey för att hämta nyckeln från UserKey. Lösenorden som specificerats av användaren när document kryptering anropas kommer att vidarebefordras. Lösenord kan vara ospecificerade eller endast ett kan vara specificerat"
type: docs
weight: 100
url: /sv/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

Skapar en kodad array baserat på lösenord som kommer att skrivas till O‑fältet i krypteringsdictionaryn. Bör endast förlita sig på de argument som skickas. Användarlösenordet kan beräknas från detta fält med ägarlösenordet. Anropas under kryptering för att förbereda den och fylla i krypteringsdictionaryn. Värdet kommer att vara tillgängligt i [`CalculateEncryptionKey`](../calculateencryptionkey/) för att hämta nyckeln från UserKey. Lösenorden som specificerats av användaren när document kryptering anropas kommer att vidarebefordras. Lösenord kan vara ospecificerade eller endast ett kan vara specificerat.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | String | Användarlösenordet. |
| ownerPassword | String | Ägarlösenordet. |

### Returvärde

Arrayen med ägarnyckeln.

### Se även

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


