---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode ICustomSecurityHandler. Crée un tableau encodé basé sur les mots de passe qui sera écrit dans le champ O du dictionnaire de chiffrement. Ne doit s'appuyer que sur les arguments fournis. Le mot de passe de l'utilisateur peut être calculé à partir de ce champ en utilisant le mot de passe propriétaire. Appelé pendant le chiffrement pour le préparer et remplir le dictionnaire de chiffrement. La valeur sera disponible dans CalculateEncryptionKey pour obtenir la clé à partir de la UserKey. Les mots de passe spécifiés par l'utilisateur lors de l'appel du chiffrement du document seront transmis. Les mots de passe peuvent ne pas être spécifiés ou un seul peut être spécifié."
type: docs
weight: 100
url: /fr/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

Crée un tableau encodé basé sur les mots de passe qui sera écrit dans le champ O du dictionnaire de chiffrement. Ne doit s'appuyer que sur les arguments fournis. Le mot de passe de l'utilisateur peut être calculé à partir de ce champ en utilisant le mot de passe propriétaire. Appelé pendant le chiffrement pour le préparer et remplir le dictionnaire de chiffrement. La valeur sera disponible dans [`CalculateEncryptionKey`](../calculateencryptionkey/) pour obtenir la clé à partir de la UserKey. Les mots de passe spécifiés par l'utilisateur lors de l'appel du chiffrement du document seront transmis. Les mots de passe peuvent ne pas être spécifiés ou un seul peut être spécifié.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Le mot de passe de l'utilisateur. |
| ownerPassword | String | Le mot de passe propriétaire. |

### Valeur de retour

Le tableau de la clé propriétaire.

### Voir aussi

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


