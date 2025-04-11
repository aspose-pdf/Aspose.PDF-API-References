---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileSignature. Représente une classe pour signer un fichier pdf avec un certificat
type: docs
weight: 4560
url: /fr/net/aspose.pdf.facades/pdffilesignature/
---
## Classe PdfFileSignature

Représente une classe pour signer un fichier pdf avec un certificat.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | Le constructeur de la classe PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Initialise un nouvel objet `PdfFileSignature` sur la base du *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient le document sur lequel la façade travaille. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Obtient le drapeau déterminant si un document est certifié ou non. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Obtient le drapeau LTV activé. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Définit ou obtient une apparence graphique pour la signature. La valeur de la propriété représente le nom du fichier image. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Définit ou obtient une apparence graphique pour la signature. La valeur de la propriété représente le flux d'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Lie un flux Pdf pour l'édition. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Lie un fichier Pdf pour l'édition. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Certifie le document avec la signature MDP qui est placée dans le champ de signature déjà présenté. Avant de signer, le champ de signature doit être vide, c'est-à-dire que le champ ne doit pas contenir de dictionnaire de signature. Ainsi, le document pdf a déjà un champ de signature, vous ne devez pas fournir l'emplacement pour tamponner la signature, la page et le rectangle correspondants sont pris du champ de signature qui est trouvé par le nom de la signature (voir le paramètre sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certifie le document avec la signature MDP. Des données telles que le motif de la signature, le contact et l'emplacement doivent être fournies par les propriétés correspondantes de l'objet Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Ferme la façade. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Vérifie si le pdf a une signature numérique ou non. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Vérifie si le pdf a des droits d'utilisation ou non. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Vérifie si la signature couvre l'ensemble du document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Dispose de la façade. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Extrait le certificat X.509 unique de la signature sous forme de flux. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Extrait l'image de la signature. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Renvoie la valeur des permissions d'accès du document certifié par le type de signature MDP. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Obtient les noms de tous les champs de signature vides. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Obtient les informations de contact d'une signature. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Obtient la date et l'heure de la signature. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Obtient l'emplacement d'une signature. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Obtient le motif d'une signature. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Obtient la révision d'une signature. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Obtient les noms de toutes les signatures non vides. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Récupère des informations sur tous les algorithmes de signature présents dans le document PDF. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Obtient le nom de la personne ou de l'organisation qui signe le document pdf. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Obtient la révision totale. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Supprime la signature selon le nom de la signature. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Supprime la signature selon le nom de la signature. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Supprime toutes les signatures. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Supprime l'entrée des droits d'utilisation. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Enregistre le PDF résultant dans un flux. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Enregistre le PDF résultant dans un fichier. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Définit le fichier de certificat et le mot de passe pour la routine de signature. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Signe le document avec le type de signature donné qui est placé dans le champ de signature déjà présenté. Avant de signer, le champ de signature doit être vide, c'est-à-dire que le champ ne doit pas contenir de dictionnaire de signature. Ainsi, le document pdf a déjà un champ de signature, vous ne devez pas fournir l'emplacement pour tamponner la signature, la page et le rectangle correspondants sont pris du champ de signature qui est trouvé par le nom de la signature (voir le paramètre SigName). Des données telles que le motif de la signature, le contact et l'emplacement doivent être fournies par les propriétés correspondantes de l'objet Signature sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Signe le document avec le type de signature donné. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Signe le document avec le type de signature donné qui est placé dans le champ de signature déjà présenté. Avant de signer, le champ de signature doit être vide, c'est-à-dire que le champ ne doit pas contenir de dictionnaire de signature. Ainsi, le document pdf a déjà un champ de signature, vous ne devez pas fournir l'emplacement pour tamponner la signature, la page et le rectangle correspondants sont pris du champ de signature qui est trouvé par le nom de la signature (voir le paramètre SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Fait une signature sur le document pdf. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Signe le document avec le type de signature donné. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Signe le document avec le type de signature donné qui est placé dans le champ de signature déjà présenté. Avant de signer, le document pdf doit déjà avoir un champ de signature, la page et le rectangle correspondants sont pris du champ de signature qui est trouvé par le nom de la signature (voir le paramètre SigName). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Vérifie la validité d'une signature. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Vérifie la validité d'une signature. |

### Voir aussi

* classe [SaveableFacade](../saveablefacade/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)