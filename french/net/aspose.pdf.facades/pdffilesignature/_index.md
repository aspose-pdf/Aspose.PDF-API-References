---
title: PdfFileSignature
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente une classe pour signer un fichier pdf avec un certificat.
type: docs
weight: 2570
url: /fr/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Représente une classe pour signer un fichier pdf avec un certificat.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfFileSignature](pdffilesignature#constructor)() | Le constructeur de la classe PdfFileSignature. |
| [PdfFileSignature](pdffilesignature#constructor_1)(Document) | Initialise nouveau[`PdfFileSignature`](../pdffilesignature) objet sur la base de la*document* . |

## Propriétés

| Nom | La description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtient la façade du document sur laquelle travaille. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified) { get; } | Obtient l'indicateur déterminant si un document est certifié ou non. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled) { get; } | Obtient l'indicateur LTV activé. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance) { get; set; } | Définit ou obtient une apparence graphique pour la signature. La valeur de la propriété représente le nom du fichier image. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream) { get; set; } | Définit ou obtient une apparence graphique pour la signature. La valeur de la propriété représente le flux d'images. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_1)(Stream) | Lie un flux Pdf pour l'édition. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_2)(string) | Lie un fichier PDF pour l'édition. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify_1)(string, DocMDPSignature) | Certifiez le document avec la signature MDP qui est placée dans le champ de signature déjà présenté. Avant de signer, le champ de signature doit être vide, c'est-à-dire que le champ ne doit pas contenir de dictionnaire de signature. Ainsi, le document pdf a déjà un champ de signature, vous ne devez pas fournir l'endroit pour tamponnez la signature, la page et le rectangle correspondants sont extraits du champ de signature qui se trouve par nom de signature (voir le paramètre sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certifier le document avec la signature MDP. Des données telles que le motif de la signature, le contact et l'emplacement doivent être fournies par les propriétés correspondantes de l'objet Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close)() | Ferme la façade. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature)() | Vérifie si le pdf a une signature numérique ou non. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights)() | Vérifie si le pdf a un droit d'utilisation ou non. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument)(string) | Vérifie si la signature couvre tout le document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Dispose la façade. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate)(string) | Extrait le certificat X.509 unique de la signature sous forme de flux. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage)(string) | Extrait l'image de la signature. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions)() | Renvoie la valeur des autorisations d'accès du document certifié par le type de signature MDP. |
| [GetBlankSignNames](../../aspose.pdf.facades/pdffilesignature/getblanksignnames)() | Obtient les noms de tous les champs de signature vides. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo)(string) | Obtient les coordonnées d'une signature. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime)(string) | Obtient la date et l'heure de la signature. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation)(string) | Obtient l'emplacement d'une signature. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason)(string) | Récupère la raison d'une signature. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision)(string) | Obtient la révision d'une signature. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername)(string) | Obtient le nom de la personne ou de l'organisation qui a signé le document pdf. |
| [GetSignNames](../../aspose.pdf.facades/pdffilesignature/getsignnames)(bool) | Obtient les noms de toutes les signatures non vides. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision)() | Obtient la révision totale. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature)(string) | Supprimer la signature selon le nom de la signature. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature_1)(string, bool) | Supprime la signature en fonction du nom de la signature. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights)() | Supprime l'entrée des droits d'utilisation. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_1)(Stream) | Enregistre le résultat PDF à diffuser. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_2)(string) | Enregistre le résultat PDF dans un fichier. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate)(string, string) | Définir le fichier de certificat et le mot de passe pour la routine de signature. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_4)(string, Signature) | Signez le document avec la signature de type donnée qui est placée dans le champ de signature déjà présenté. Avant de signer, le champ de signature doit être vide, c'est-à-dire que le champ ne doit pas contenir de dictionnaire de signature. Ainsi, le document pdf a déjà un champ de signature, vous ne devez pas fournir le lieu pour tamponner la signature, la page et le rectangle correspondants sont tirés du champ de signature qui se trouve par le nom de la signature (voir le paramètre SigName). Des données telles que le motif de la signature, le contact et l'emplacement doivent être fournies par les propriétés correspondantes de l'objet Signature sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign)(int, bool, Rectangle, Signature) | Signez le document avec le type de signature donné. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_5)(string, string, string, string, Signature) | Signez le document avec la signature de type donnée qui est placée dans le champ de signature déjà présenté. Avant de signer, le champ de signature doit être vide, c'est-à-dire que le champ ne doit pas contenir de dictionnaire de signature. Ainsi, le document pdf a déjà un champ de signature, vous ne devez pas fournir le lieu pour tamponner la signature, la page et le rectangle correspondants sont extraits du champ de signature qui se trouve par nom de signature (voir paramètre SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_1)(int, string, string, string, bool, Rectangle) | Faire une signature sur le document pdf. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Signez le document avec le type de signature donné. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Signez le document avec la signature de type donnée qui est placée dans le champ de signature déjà présenté. Avant de signer le document pdf doit déjà avoir un champ de signature, la page et le rectangle correspondants sont tirés du champ de signature qui se trouve par nom de signature (voir le paramètre SigName) . |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature)(string) | Vérifie la validité d'une signature. |
| [VerifySigned](../../aspose.pdf.facades/pdffilesignature/verifysigned)(string) | Vérifie la validité d'une signature. |

### Voir également

* class [SaveableFacade](../saveablefacade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
