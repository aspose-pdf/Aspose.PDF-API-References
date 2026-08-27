---
title: "ICustomSecurityHandler.EncryptPermissions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode ICustomSecurityHandler. Crypte le champ des autorisations du document. Le résultat sera écrit dans le champ du dictionnaire de chiffrement Perms. Lors de l'ouverture d'un document, la valeur peut être obtenue dans EncryptionParameters via le champ Perms. Permet de vérifier si les autorisations du document ont changé"
type: docs
weight: 90
url: /fr/net/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler.EncryptPermissions method

Crypte le champ des autorisations du document. Le résultat sera écrit dans le champ du dictionnaire de chiffrement Perms. Lors de l'ouverture d'un document, la valeur peut être obtenue dans [`EncryptionParameters`](../../encryptionparameters/) via le champ Perms. Permet de vérifier si les autorisations du document ont changé.

```csharp
public byte[] EncryptPermissions(int permissions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| autorisations | Int32 | Les autorisations du document sous forme entière. |

### Valeur de retour

Le tableau chiffré.

### Voir aussi

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


