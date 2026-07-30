---
title: "ICustomSecurityHandler.Initialize"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode ICustomSecurityHandler. Appelée pour initialiser l'instance actuelle pour le chiffrement. Notez que lors du chiffrement, elle sera remplie avec les données des propriétés transférées ICustomSecurityHandler et lors de l'ouverture du document à partir du dictionnaire de chiffrement. Si la méthode est appelée lors d'un nouveau chiffrement, alors UserKey et OwnerKey seront null"
type: docs
weight: 120
url: /fr/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

Appelée pour initialiser l'instance actuelle pour le chiffrement. Notez que lors du chiffrement, elle sera remplie avec les données des propriétés transférées [`ICustomSecurityHandler`](../), et lors de l'ouverture du document à partir du dictionnaire de chiffrement. Si la méthode est appelée lors d'un nouveau chiffrement, alors [`UserKey`](../../encryptionparameters/userkey/) et [`OwnerKey`](../../encryptionparameters/ownerkey/) seront null.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| paramètres | EncryptionParameters | Les paramètres de chiffrement. |

### Voir aussi

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


