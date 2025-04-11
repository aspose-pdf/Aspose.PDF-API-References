---
title: Class ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.ExternalSignature. Crée une signature PKCS7 détachée en utilisant un X509Certificate2. Elle prend en charge les jetons de cartes intelligentes USB sans clés privées exportables.
type: docs
weight: 5040
url: /fr/net/aspose.pdf.forms/externalsignature/
---
## Classe ExternalSignature

Crée une signature PKCS#7 détachée en utilisant un X509Certificate2. Elle prend en charge les cartes intelligentes USB, les jetons sans clés privées exportables.

```csharp
public class ExternalSignature : Signature
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | Crée une signature PKCS#7 `(détachée)` en utilisant un X509Certificate2. Elle prend en charge les cartes intelligentes USB, les jetons sans clés privées exportables. |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | Crée une signature PKCS#7 en utilisant un X509Certificate2 sous forme de chaîne base64. |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | Crée une signature PKCS#7 `(détachée)` en utilisant un X509Certificate2 sous forme de chaîne base64. |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | Crée une signature PKCS#7 détachée en utilisant un X509Certificate2. Elle prend en charge les cartes intelligentes USB, les jetons sans clés privées exportables. |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | Crée une signature PKCS#7 `(détachée)` en utilisant un X509Certificate2. Elle prend en charge les cartes intelligentes USB, les jetons sans clés privées exportables. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Le nom de la personne ou de l'autorité signant le document. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Obtient et définit une option qui indique s'il faut éviter d'estimer la longueur d'une signature. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Un tableau de paires d'entiers (décalage d'octet de départ, longueur en octets) qui décrit la plage d'octets exacte pour le calcul du hachage. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informations fournies par le signataire pour permettre à un destinataire de contacter le signataire pour vérifier la signature, par exemple un numéro de téléphone. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Obtient/définit l'apparence personnalisée. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Le délégué pour signer le hachage du document de manière personnalisée. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Le moment de la signature. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Obtient ou définit la longueur par défaut pour les données de signature en octets. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Le nom d'hôte du CPU ou l'emplacement physique de la signature. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Obtient/définit les paramètres OCSP. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | La raison de la signature, telle que (J'accepte, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Force à afficher/cacher les propriétés de la signature. Si ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini (chaînes à représenter) : ------------------------------------------- Signé numériquement par {sujet du certificat} Date : {signature.Date} Raison : {signature.Raison} Emplacement : {signature.Location} ------------------------------------------- où {X} est un espace réservé pour la valeur X. De plus, la signature peut avoir une image, dans ce cas, les chaînes énumérées sont placées sur l'image. ShowProperties est vrai par défaut. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Obtient/définit les paramètres de timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Obtient/définit le drapeau de validation LTV. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Récupère des informations sur l'algorithme de signature utilisé dans la signature. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Vérifie le document concernant cette signature et retourne vrai si le document est valide, sinon faux. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Vérifie le document concernant cette signature et retourne vrai si le document est valide, sinon faux. |

## Champs

| Nom | Description |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | Le certificat avec la clé privée. |

### Voir aussi

* classe [Signature](../signature/)
* espace de noms [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)