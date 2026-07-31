---
title: "ICustomSecurityHandler.Initialize"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "ICustomSecurityHandler-Methode. Wird aufgerufen, um die aktuelle Instanz für die Verschlüsselung zu initialisieren. Hinweis: Beim Verschlüsseln wird sie mit den Daten der übertragenen Eigenschaften ICustomSecurityHandler gefüllt und beim Öffnen des Dokuments aus dem Verschlüsselungswörterbuch. Wenn die Methode während einer neuen Verschlüsselung aufgerufen wird, sind UserKey und OwnerKey null."
type: docs
weight: 120
url: /de/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

Aufgerufen, um die aktuelle Instanz für die Verschlüsselung zu initialisieren. Beachten Sie, dass beim Verschlüsseln die Daten der übertragenen Eigenschaften [`ICustomSecurityHandler`](../) eingefüllt werden und beim Öffnen des Document aus dem Verschlüsselungswörterbuch. Wird die Methode während einer neuen Verschlüsselung aufgerufen, sind [`UserKey`](../../encryptionparameters/userkey/) und [`OwnerKey`](../../encryptionparameters/ownerkey/) null.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Parameter | EncryptionParameters | Die Verschlüsselungsparameter. |

### Siehe auch

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


