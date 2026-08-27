---
title: "Aspose.Pdf.Security"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "L'espace de noms Aspose.Pdf.Security contient des classes utilisées pour le chiffrement et la signature numérique."
type: docs
weight: 210
url: /fr/net/aspose.pdf.security/
---
L’espace de noms **Aspose.Pdf.Security** contient des classes utilisées pour le chiffrement et la signature numérique.

## Classes

| Classe | Description |
| --- | --- |
| [CertificateEncryptionOptions](./certificateencryptionoptions/) | Représente une classe pour les options de chiffrement d'un document PDF en utilisant une méthode de chiffrement basée sur un certificat. Utilisée pour ouvrir des documents PDF chiffrés. |
| [DsaAlgorithmInfo](./dsaalgorithminfo/) | Représente une classe contenant les informations sur l'algorithme de signature DSA. |
| [EcdsaAlgorithmInfo](./ecdsaalgorithminfo/) | Représente une classe contenant les informations sur l'algorithme de signature ECDSA. |
| [EncryptionParameters](./encryptionparameters/) | Représente une classe de paramètres de chiffrement. |
| [KeyedSignatureAlgorithmInfo](./keyedsignaturealgorithminfo/) | Représente une classe contenant les informations sur un algorithme de signature à clé. |
| [RsaAlgorithmInfo](./rsaalgorithminfo/) | Représente une classe contenant les informations sur l'algorithme de signature RSA. |
| [SignatureAlgorithmInfo](./signaturealgorithminfo/) | Représente une classe contenant les informations sur un algorithme de signature, y compris son type, la norme cryptographique et l'algorithme de hachage de digest. |
| [SignatureLengthMismatchException](./signaturelengthmismatchexception/) | Représente les erreurs qui surviennent lors de la signature PDF. Se produit si [`SignHash`](../aspose.pdf.forms/signhash/) est utilisé pour signer un document et que la longueur réelle de la signature est supérieure à celle spécifiée dans l'option [`DefaultSignatureLength`](../aspose.pdf.forms/signature/defaultsignaturelength/). |
| [TimestampAlgorithmInfo](./timestampalgorithminfo/) | Représente une classe contenant les informations sur l'algorithme de signature de timestamp. |
| [UnknownSignatureAlgorithmInfo](./unknownsignaturealgorithminfo/) | Représente une classe contenant les informations sur un algorithme de signature inconnu. |
| [ValidationOptions](./validationoptions/) | Représente les options de validation d'une signature numérique dans un document PDF. |
| [ValidationResult](./validationresult/) | Représente le résultat d'un processus de validation pour un certificat. |
## Interfaces

| Interface | Description |
| --- | --- |
| [ICustomSecurityHandler](./icustomsecurityhandler/) | L'interface du gestionnaire de sécurité personnalisé. |
## Énumération

| Énumération | Description |
| --- | --- |
| [CryptographicStandard](./cryptographicstandard/) | Représente les normes cryptographiques disponibles pour sécuriser les documents PDF. |
| [SignatureAlgorithmType](./signaturealgorithmtype/) | Énumère les types d'algorithmes de signature utilisés pour les signatures numériques. |
| [ValidationMethod](./validationmethod/) | Représente une énumération définissant la méthode utilisée pour la validation des certificats. |
| [ValidationMode](./validationmode/) | Spécifie le mode de validation pour les processus de validation de signature PDF. |
| [ValidationStatus](./validationstatus/) | Représente l'état de validation d'une validation de certificat. |


