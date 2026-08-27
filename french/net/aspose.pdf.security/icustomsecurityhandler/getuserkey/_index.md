---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode ICustomSecurityHandler. Crée un tableau encodé basé sur le mot de passe de l'utilisateur. Cette valeur est généralement utilisée pour vérifier si le mot de passe appartient à l'utilisateur ou au propriétaire et pour obtenir la clé de chiffrement. Appelée pendant le chiffrement pour le préparer et remplir le dictionnaire de chiffrement. Le mot de passe spécifié par l'utilisateur est passé en argument lors de l'appel du chiffrement du document"
type: docs
weight: 110
url: /fr/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

Crée un tableau encodé basé sur le mot de passe de l'utilisateur. Cette valeur est généralement utilisée pour vérifier si le mot de passe appartient à l'utilisateur ou au propriétaire, et pour obtenir la clé de chiffrement. Appelé pendant le chiffrement pour le préparer et remplir le dictionnaire de chiffrement. Le mot de passe spécifié par l'utilisateur est passé en argument lors de l'appel du chiffrement du document.

```csharp
public byte[] GetUserKey(string userPassword)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Le mot de passe de l'utilisateur. |

### Valeur de retour

Le tableau de la clé utilisateur.

### Voir aussi

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


