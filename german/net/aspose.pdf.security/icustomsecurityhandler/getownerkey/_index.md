---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "ICustomSecurityHandler-Methode. Erstellt ein codiertes Array basierend auf Passwörtern, das in das O-Feld des Verschlüsselungswörterbuchs geschrieben wird. Sollte sich nur auf die übergebenen Argumente verlassen. Das Benutzerpasswort kann aus diesem Feld mithilfe des Besitzerpassworts berechnet werden. Wird während der Verschlüsselung aufgerufen, um sie vorzubereiten und das Verschlüsselungswörterbuch zu füllen. Der Wert ist in CalculateEncryptionKey verfügbar, um den Schlüssel aus dem UserKey zu erhalten. Die vom Benutzer beim Aufrufen der Dokumentverschlüsselung angegebenen Passwörter werden übergeben. Passwörter müssen nicht angegeben werden oder es kann nur eines angegeben werden."
type: docs
weight: 100
url: /de/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

Erstellt ein codiertes Array basierend auf Passwörtern, das in das O-Feld des Verschlüsselungswörterbuchs geschrieben wird. Sollte sich nur auf die übergebenen Argumente verlassen. Das Benutzerpasswort kann aus diesem Feld mithilfe des Besitzerpassworts berechnet werden. Wird während der Verschlüsselung aufgerufen, um sie vorzubereiten und das Verschlüsselungswörterbuch zu füllen. Der Wert ist in [`CalculateEncryptionKey`](../calculateencryptionkey/) verfügbar, um den Schlüssel aus dem UserKey zu erhalten. Die vom Benutzer beim Aufrufen der Dokumentverschlüsselung angegebenen Passwörter werden übergeben. Passwörter müssen nicht angegeben werden oder es kann nur eines angegeben werden.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Das Benutzerpasswort. |
| ownerPassword | String | Das Besitzerpasswort. |

### Rückgabewert

Das Array des owner key.

### Siehe auch

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


