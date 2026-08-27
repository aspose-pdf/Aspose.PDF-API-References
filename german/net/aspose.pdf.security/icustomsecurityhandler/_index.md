---
title: "Schnittstelle ICustomSecurityHandler"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "Aspose.Pdf.Security.ICustomSecurityHandler Schnittstelle. Die benutzerdefinierte Sicherheits-Handler-Schnittstelle"
type: docs
weight: 10150
url: /de/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

Die benutzerdefinierte Sicherheits-Handler-Schnittstelle.

```csharp
public interface ICustomSecurityHandler
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | Liefert den Filternamen. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | Liefert die Schlüssellänge. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | Liefert die Revision des Handlers oder des Verschlüsselungsalgorithmus. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | Liefert den Subfilter-Namen. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | Liefert die Version des Handlers oder des Verschlüsselungsalgorithmus. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | Berechnet den EncryptionKey. Im Allgemeinen wird der Schlüssel basierend auf dem UserKey berechnet. Sie können Werte aus EncryptionParams verwenden, die die zum Zeitpunkt des Aufrufs aktuellen Parameter enthalten. Dieser Wert wird als Schlüsselargument in [`Encrypt`](./encrypt/) und [`Decrypt`](./decrypt/) übergeben. |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | Entschlüsselt das Datenarray. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | Verschlüsselt das Datenarray. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | Verschlüsselt das Berechtigungsfeld des Dokuments. Das Ergebnis wird in das Perms-Feld des Verschlüsselungswörterbuchs geschrieben. Beim Öffnen eines Dokuments kann der Wert in [`EncryptionParameters`](../encryptionparameters/) über das Perms-Feld abgerufen werden. Ermöglicht es, zu prüfen, ob sich die Dokumentberechtigungen geändert haben. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | Erstellt ein codiertes Array basierend auf Passwörtern, das in das O-Feld des Verschlüsselungswörterbuchs geschrieben wird. Sollte sich ausschließlich auf die übergebenen Argumente stützen. Das Benutzerpasswort kann aus diesem Feld mithilfe des Besitzerpassworts berechnet werden. Wird während der Verschlüsselung aufgerufen, um es vorzubereiten und das Verschlüsselungswörterbuch zu füllen. Der Wert ist in [`CalculateEncryptionKey`](./calculateencryptionkey/) verfügbar, um den Schlüssel aus dem UserKey zu erhalten. Die vom Benutzer beim Aufruf der Dokumentenverschlüsselung angegebenen Passwörter werden übergeben. Passwörter können nicht angegeben werden oder es kann nur eines angegeben werden. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | Erstellt ein codiertes Array basierend auf dem Passwort des Benutzers. Dieser Wert wird typischerweise verwendet, um zu prüfen, ob das Passwort zum Benutzer oder zum Besitzer gehört, und um den Verschlüsselungsschlüssel zu erhalten. Wird während der Verschlüsselung aufgerufen, um es vorzubereiten und das Verschlüsselungs‑Wörterbuch zu füllen. Das vom Benutzer angegebene Passwort wird als Argument beim Aufruf der Dokumentenverschlüsselung übergeben. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | Wird aufgerufen, um die aktuelle Instanz für die Verschlüsselung zu initialisieren. Beachten Sie, dass beim Verschlüsseln die Daten der übertragenen Eigenschaften `ICustomSecurityHandler` eingefügt werden und beim Öffnen des Dokuments aus dem Verschlüsselungswörterbuch. Wenn die Methode während einer neuen Verschlüsselung aufgerufen wird, sind [`UserKey`](../encryptionparameters/userkey/) und [`OwnerKey`](../encryptionparameters/ownerkey/) null. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | Prüft, ob das Passwort das Passwort des Dokumentenbesitzers ist. Die Methode wird nach Initialize aufgerufen. Der Methodenaufruf wird in der PDF‑API verwendet. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | Prüft, ob das Passwort zum Benutzer gehört (Passwort zum Öffnen des Dokuments). Die Methode wird nach Initialize aufgerufen. Der Methodenaufruf wird in der PDF‑API verwendet. |

### Siehe auch

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


