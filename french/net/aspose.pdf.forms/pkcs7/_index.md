---
title: Class PKCS7
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.PKCS7. Représente l'objet PKCS7 qui conforme à la spécification PKCS7 dans Internet RFC 2315 PKCS 7 Syntaxe de Message Cryptographique Version 1.5. Le hachage SHA1 de la plage d'octets des documents est encapsulé dans le champ SignedData PKCS7.
type: docs
weight: 5180
url: /fr/net/aspose.pdf.forms/pkcs7/
---
## Classe PKCS7

Représente l'objet PKCS#7 qui conforme à la spécification PKCS#7 dans Internet RFC 2315, PKCS #7 : Syntaxe de Message Cryptographique, Version 1.5. Le `SHA1 digest` de la plage d'octets du document est encapsulé dans le champ SignedData PKCS#7.

```csharp
public sealed class PKCS7 : Signature
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PKCS7](pkcs7/#constructor)() | Initialise une nouvelle instance de la classe `PKCS7`. |
| [PKCS7](pkcs7/#constructor_1)(Stream, string) | Initialise une nouvelle instance de la classe `PKCS7`. |
| [PKCS7](pkcs7/#constructor_2)(string, string) | Initialise une nouvelle instance de la classe `PKCS7`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Le nom de la personne ou de l'autorité signant le document. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Obtient et définit une option qui signifie s'il faut éviter d'estimer la longueur d'une signature. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Un tableau de paires d'entiers (décalage d'octet de départ, longueur en octets) qui décrivent la plage d'octets exacte pour le calcul du hachage. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informations fournies par le signataire pour permettre à un destinataire de contacter le signataire pour vérifier la signature, par exemple un numéro de téléphone. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Obtient/définit l'apparence personnalisée. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Le délégué pour signer de manière personnalisée le hachage du document. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Le moment de la signature. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Obtient ou définit la longueur par défaut pour les données de signature en octets. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Le nom d'hôte du CPU ou l'emplacement physique de la signature. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Obtient/définit les paramètres ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | La raison de la signature, telle que (Je suis d'accord, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Force à afficher/cacher les propriétés de la signature. Dans le cas où ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini (chaînes à représenter) : ------------------------------------------- Signé numériquement par {sujet du certificat} Date : {signature.Date} Raison : {signature.Raison} Emplacement : {signature.Location} ------------------------------------------- où {X} est un espace réservé pour la valeur X. De plus, la signature peut avoir une image, dans ce cas, les chaînes énumérées sont placées sur l'image. ShowProperties est vrai par défaut. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Obtient/définit les paramètres de timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Obtient/définit le drapeau de validation ltv. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Récupère des informations sur l'algorithme de signature utilisé dans la signature. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Vérifie le document concernant cette signature et retourne vrai si le document est valide, sinon faux. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Vérifie le document concernant cette signature et retourne vrai si le document est valide, sinon faux. |

### Voir aussi

* classe [Signature](../signature/)
* espace de noms [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)