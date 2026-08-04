---
title: "PKCS7"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente l'objet PKCS#7 conforme à la spécification PKCS#7 de la RFC 2315 d'Internet, <br/>            PKCS #7 : Cryptographic Message Syntax, version 1.5.<br/>            Le condensat SHA1 de la plage d'octets du document est encapsulé dans le champ SignedData de PKCS#7."
type: docs
weight: 190
url: /fr/python-net/aspose.pdf.forms/pkcs7/
---

## PKCS7 class

Représente l'objet PKCS#7 conforme à la spécification PKCS#7 de la RFC 2315 d'Internet, <br/>            PKCS #7 : Cryptographic Message Syntax, version 1.5.<br/>            Le condensat SHA1 de la plage d'octets du document est encapsulé dans le champ SignedData de PKCS#7.

Le type PKCS7 expose les membres suivants:
## Constructeurs
| Nom | Description |
| :- | :- |
| PKCS7() | Initialise une nouvelle instance de la classe [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/). |
| PKCS7(pfx, password) | Initialise une nouvelle instance de la classe PKCS7 |
| PKCS7(pfx, password) | Initialise une nouvelle instance de la classe PKCS7 |
## Propriétés
| Nom | Description |
| :- | :- |
| custom_appearance | Obtient/definit l'apparence personnalisée. |
| authority | Le nom de la personne ou de l'autorité signant le document. |
| date | L'heure de la signature. |
| location | Le nom d'hôte du CPU ou l'emplacement physique de la signature. |
| reason | La raison de la signature, telle que (I agreeРІР‚В¦). |
| contact_info | Informations fournies par le signataire pour permettre au destinataire de contacter le signataire <br/>            afin de vérifier la signature, par ex. un numéro de téléphone. |
| byte_range | Un tableau de paires d'entiers (décalage d'octet de départ, longueur en octets) <br/>             qui décrit la plage d'octets exacte pour le calcul du condensat. |
| timestamp_settings | Obtient/definit les paramètres d'horodatage. |
| ocsp_settings | Obtient/definit les paramètres OCSP. |
| use_ltv | Obtient/definit le drapeau de validation LTV. |
| show_properties | Force l'affichage/masquage des propriétés de la signature.<br/>            Si ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini (chaînes à représenter) :<br/>            -------------------------------------------<br/>            Signé numériquement par {certificate subject}<br/>            Date : {signature.Date}<br/>            Raison : {signature.Reason}<br/>            Lieu : {signature.Location}<br/>            -------------------------------------------<br/>            où {X} est un espace réservé pour la valeur X. La signature peut également contenir une image ; dans ce cas, les chaînes listées sont placées sur l'image.<br/>            ShowProperties est vrai par défaut. |
## Méthodes
| Nom | Description |
| :- | :- |
| verify() | Vérifie le document par rapport à cette signature et renvoie true si le document est valide <br/>            sinon false. |

### Voir aussi

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

