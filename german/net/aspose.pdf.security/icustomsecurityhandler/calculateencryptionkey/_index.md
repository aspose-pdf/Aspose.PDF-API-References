---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "ICustomSecurityHandler-Methode. Berechnet den EncryptionKey. Im Allgemeinen wird der Schlüssel basierend auf dem UserKey berechnet. Sie können Werte aus EncryptionParams verwenden, die die aktuellen Parameter zum Zeitpunkt des Aufrufs enthalten. Dieser Wert wird als Schlüsselargument in Encrypt und Decrypt übergeben."
type: docs
weight: 60
url: /de/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

Berechnet den EncryptionKey. Im Allgemeinen wird der Schlüssel basierend auf dem UserKey berechnet. Sie können Werte aus EncryptionParams verwenden, die die aktuellen Parameter zum Zeitpunkt des Aufrufs enthalten. Dieser Wert wird als Schlüsselargument in [`Encrypt`](../encrypt/) und [`Decrypt`](../decrypt/) übergeben.

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | String | Vom Benutzer eingegebenes Passwort. |

### Rückgabewert

Das Array des Verschlüsselungsschlüssels.

### Siehe auch

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


