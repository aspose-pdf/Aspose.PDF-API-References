---
title: "ICustomSecurityHandler.Encrypt"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "ICustomSecurityHandler-Methode. Verschlüsselt das Datenarray."
type: docs
weight: 80
url: /de/net/aspose.pdf.security/icustomsecurityhandler/encrypt/
---
## ICustomSecurityHandler.Encrypt method

Verschlüsselt das Datenarray.

```csharp
public byte[] Encrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | Byte[] | Zu verschlüsselnde Daten. |
| objectNumber | Int32 | Nummer des Objekts, das die verschlüsselten Daten enthält. |
| generation | Int32 | Generation des Objekts. |
| key | Byte[] | Schlüssel, der durch die Methode CalculateEncryptionKey erhalten wird. |

### Rückgabewert

Die verschlüsselten Daten.

### Siehe auch

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


