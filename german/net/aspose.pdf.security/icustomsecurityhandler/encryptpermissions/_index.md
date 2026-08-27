---
title: "ICustomSecurityHandler.EncryptPermissions"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "ICustomSecurityHandler-Methode. Verschlüsselt das Berechtigungsfeld des Document. Das Ergebnis wird in das Perms‑Feld des Verschlüsselungswörterbuchs geschrieben. Beim Öffnen eines Document kann der Wert in EncryptionParameters über das Perms‑Feld abgerufen werden. Ermöglicht die Überprüfung, ob sich die Document‑Berechtigungen geändert haben."
type: docs
weight: 90
url: /de/net/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler.EncryptPermissions method

Verschlüsselt das Berechtigungsfeld des Document. Das Ergebnis wird in das Perms‑Verschlüsselungswörterbuchfeld geschrieben. Beim Öffnen eines Document kann der Wert über das Perms‑Feld in [`EncryptionParameters`](../../encryptionparameters/) abgerufen werden. Ermöglicht die Überprüfung, ob sich die Document‑Berechtigungen geändert haben.

```csharp
public byte[] EncryptPermissions(int permissions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Berechtigungen | Int32 | Die Document‑Berechtigungen in ganzzahliger Darstellung. |

### Rückgabewert

Das verschlüsselte Array.

### Siehe auch

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


