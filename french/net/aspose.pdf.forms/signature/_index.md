---
title: "Classe Signature"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Forms.Signature. Une classe abstraite qui représente l'objet signature dans le document PDF. Les signatures sont des champs contenant des objets signature dont les derniers contiennent les données utilisées pour vérifier la validité du document."
type: docs
weight: 5390
url: /fr/net/aspose.pdf.forms/signature/
---
## Signature class

Une classe abstraite qui représente l'objet de signature dans le document PDF. Les signatures sont des champs contenant des objets de signature, ces derniers contenant les données utilisées pour vérifier la validité du document.

```csharp
public abstract class Signature
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Signature](signature/#constructor)() | Initialise une nouvelle instance de la classe `Signature`. |
| [Signature](signature/#constructor_1)(Stream, string) | Initialise une nouvelle instance de la classe `Signature`. |
| [Signature](signature/#constructor_2)(string, string) | Initialise une nouvelle instance de la classe `Signature`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Le nom de la personne ou de l'autorité signant le document. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Obtient et définit une option indiquant s'il faut éviter d'estimer la longueur d'une signature. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Un tableau de paires d'entiers (décalage d'octet de départ, longueur en octets) qui doit décrire la plage d'octets exacte pour le calcul du condensat. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informations fournies par le signataire pour permettre à un destinataire de contacter le signataire afin de vérifier la signature, par ex. un numéro de téléphone. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Obtient/définit l'apparence personnalisée. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Le délégué pour signer de manière personnalisée le hachage du document. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | L'heure de la signature. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Obtient ou définit la longueur par défaut des données de signature en octets. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Le nom d'hôte du CPU ou l'emplacement physique de la signature. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Obtient/définit les paramètres OCSP. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | La raison de la signature, telle que (Je suis d'accord, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Force d'afficher/masquer les propriétés de la signature. Dans le cas où ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini (chaînes à représenter) : ------------------------------------------- Signé numériquement par {certificate subject} Date : {signature.Date} Raison : {signature.Reason} Lieu : {signature.Location} ------------------------------------------- où {X} est un espace réservé pour la valeur X. La signature peut également contenir une image ; dans ce cas, les chaînes listées sont placées sur l'image. ShowProperties est vrai par défaut. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Obtient/définit les paramètres d'horodatage. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Obtient/définit le drapeau de validation LTV. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Récupère les informations sur l'algorithme de signature utilisé dans la signature. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | Vérifie le document par rapport à cette signature et renvoie true si le document est valide, sinon false. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | Vérifie le document par rapport à cette signature et renvoie true si le document est valide, sinon false. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_2)(X509Certificate2, ValidationOptions, out ValidationResult) | Vérifie le document par rapport à cette signature et renvoie true si le document est valide, sinon false. La vérification est effectuée à l'aide du certificat de clé publique externe. |

### Voir aussi

* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


