---
title: "ICustomSecurityHandler.EncryptPermissions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "ICustomSecurityHandler-metod. Krypterar documentets behörighetsfält. Resultatet skrivs till Perms krypteringsordlistafältet. Vid öppning av ett document kan värdet hämtas i EncryptionParameters via Perms-fältet. Gör det möjligt att kontrollera om documentets behörigheter har ändrats."
type: docs
weight: 90
url: /sv/net/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler.EncryptPermissions method

Kryptera documentets behörighetsfält. Resultatet skrivs till Perms krypteringsordlistafältet. Vid öppning av ett document kan värdet hämtas i [`EncryptionParameters`](../../encryptionparameters/) via Perms-fältet. Gör det möjligt att kontrollera om documentets behörigheter har ändrats.

```csharp
public byte[] EncryptPermissions(int permissions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| behörigheter | Int32 | documentets behörigheter i heltalsrepresentation. |

### Returvärde

Den krypterade arrayen.

### Se även

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


