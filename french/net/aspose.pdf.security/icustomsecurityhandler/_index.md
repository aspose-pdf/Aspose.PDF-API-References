---
title: "Interface ICustomSecurityHandler"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Interface Aspose.Pdf.Security.ICustomSecurityHandler. L'interface du gestionnaire de sécurité personnalisé"
type: docs
weight: 10150
url: /fr/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

L'interface du gestionnaire de sécurité personnalisé.

```csharp
public interface ICustomSecurityHandler
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | Obtient le nom du filtre. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | Obtient la longueur de la clé. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | Obtient la révision du gestionnaire ou de l'algorithme de chiffrement. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | Obtient le nom du sous-filtre. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | Obtient la version du gestionnaire ou de l'algorithme de chiffrement. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | Calcule la EncryptionKey. Généralement la clé est calculée à partir de la UserKey. Vous pouvez utiliser les valeurs provenant de EncryptionParams, qui contient les paramètres actuels au moment de l'appel. Cette valeur est passée comme argument key dans [`Encrypt`](./encrypt/) et [`Decrypt`](./decrypt/). |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | Décryptez le tableau de données. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | Cryptez le tableau de données. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | Chiffrez le champ des permissions du document. Le résultat sera écrit dans le champ du dictionnaire de chiffrement Perms. Lors de l'ouverture d'un document, la valeur peut être obtenue dans [`EncryptionParameters`](../encryptionparameters/) via le champ Perms. Vous permet de vérifier si les permissions du document ont changé. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | Crée un tableau encodé basé sur les mots de passe qui sera écrit dans le champ O du dictionnaire de chiffrement. Il ne doit s'appuyer que sur les arguments fournis. Le mot de passe utilisateur peut être calculé à partir de ce champ en utilisant le mot de passe propriétaire. Appelé pendant le chiffrement pour le préparer et remplir le dictionnaire de chiffrement. La valeur sera disponible dans [`CalculateEncryptionKey`](./calculateencryptionkey/) pour obtenir la clé à partir de la UserKey. Les mots de passe spécifiés par l'utilisateur lors de l'appel du chiffrement du document seront transmis. Les mots de passe peuvent ne pas être spécifiés ou un seul peut être spécifié. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | Crée un tableau encodé basé sur le mot de passe de l'utilisateur. Cette valeur est généralement utilisée pour vérifier si le mot de passe appartient à l'utilisateur ou au propriétaire, et pour obtenir la clé de chiffrement. Appelé pendant le chiffrement pour le préparer et remplir le dictionnaire de chiffrement. Le mot de passe spécifié par l'utilisateur est passé en argument lors de l'appel du chiffrement du document. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | Appelé pour initialiser l'instance actuelle pour le chiffrement. Notez que lors du chiffrement, elle sera remplie avec les données des propriétés transférées `ICustomSecurityHandler`, et lors de l'ouverture du document depuis le dictionnaire de chiffrement. Si la méthode est appelée lors d'un nouveau chiffrement, alors [`UserKey`](../encryptionparameters/userkey/) et [`OwnerKey`](../encryptionparameters/ownerkey/) seront null. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | Vérifiez si le mot de passe est celui du propriétaire du document. La méthode est appelée après Initialize. L'appel de la méthode est utilisé dans l'API PDF. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | Vérifiez si le mot de passe appartient à l'utilisateur (mot de passe pour ouvrir le Document). La méthode est appelée après Initialize. L'appel de la méthode est utilisé dans l'API PDF. |

### Voir aussi

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


