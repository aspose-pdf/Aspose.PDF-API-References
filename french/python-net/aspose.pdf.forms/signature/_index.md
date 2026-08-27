---
title: "Signature"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe abstraite qui représente l'objet signature dans le document PDF. <br/>            Les signatures sont des champs contenant des valeurs d'objets signature, ces derniers contenant les données utilisées pour<br/>            vérifier la validité du document."
type: docs
weight: 250
url: /fr/python-net/aspose.pdf.forms/signature/
---

## Signature class

Classe abstraite qui représente l'objet signature dans le document PDF. <br/>            Les signatures sont des champs contenant des valeurs d'objets signature, ces derniers contenant les données utilisées pour<br/>            vérifier la validité du document.

Le type Signature expose les membres suivants :
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

