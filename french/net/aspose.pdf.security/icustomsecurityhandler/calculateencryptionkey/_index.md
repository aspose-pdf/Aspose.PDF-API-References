---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode ICustomSecurityHandler. Calcule la EncryptionKey. Généralement la clé est calculée à partir de la UserKey. Vous pouvez utiliser les valeurs de EncryptionParams qui contiennent les paramètres actuels au moment de l'appel. Cette valeur est passée comme argument de clé dans Encrypt et Decrypt."
type: docs
weight: 60
url: /fr/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

Calcule la EncryptionKey. Généralement la clé est calculée à partir de la UserKey. Vous pouvez utiliser les valeurs de EncryptionParams, qui contiennent les paramètres actuels au moment de l'appel. Cette valeur est passée comme argument de clé dans [`Encrypt`](../encrypt/) et [`Decrypt`](../decrypt/).

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| password | String | Mot de passe saisi par l'utilisateur. |

### Valeur de retour

Le tableau de la clé de chiffrement.

### Voir aussi

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


