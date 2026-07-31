---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "ICustomSecurityHandler-Methode. Erstellt ein codiertes Array basierend auf dem Benutzerpasswort. Dieser Wert wird typischerweise verwendet, um zu prüfen, ob das Passwort zum Benutzer oder Eigentümer gehört und um den Verschlüsselungsschlüssel zu erhalten. Wird während der Verschlüsselung aufgerufen, um sie vorzubereiten und das Verschlüsselungswörterbuch zu füllen. Das benutzerdefinierte Passwort wird als Argument übergeben, wenn die Document-Verschlüsselung aufgerufen wird."
type: docs
weight: 110
url: /de/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

Erstellt ein codiertes Array basierend auf dem Passwort des Benutzers. Dieser Wert wird typischerweise verwendet, um zu prüfen, ob das Passwort zum Benutzer oder zum Besitzer gehört, und um den Verschlüsselungsschlüssel zu erhalten. Wird während der Verschlüsselung aufgerufen, um es vorzubereiten und das Verschlüsselungs‑Wörterbuch zu füllen. Das vom Benutzer angegebene Passwort wird als Argument beim Aufruf der Dokumentenverschlüsselung übergeben.

```csharp
public byte[] GetUserKey(string userPassword)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Das Benutzerpasswort. |

### Rückgabewert

Das Array des Benutzerschlüssels.

### Siehe auch

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


