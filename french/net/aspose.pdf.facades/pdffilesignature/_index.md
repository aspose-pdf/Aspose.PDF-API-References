---
title: "Classe PdfFileSignature"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Facades.PdfFileSignature. Représente une classe permettant de signer un fichier pdf avec un certificat"
type: docs
weight: 4680
url: /fr/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Représente une classe pour signer un fichier pdf avec un certificat.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | Le constructeur de la classe PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Initialise un nouvel objet `PdfFileSignature` à partir du *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur laquelle travaille. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Obtient le drapeau déterminant si un document est certifié ou non. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Obtient le drapeau LTV activé. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Définit ou obtient l'apparence graphique de la signature. La valeur de la propriété représente le nom du fichier image. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Définit ou obtient l'apparence graphique de la signature. La valeur de la propriété représente le flux d'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Lie un flux Pdf pour l'édition. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Lie un fichier Pdf pour l'édition. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Certifiez le document avec la signature MDP qui est placée dans le champ de signature déjà présenté. Avant la signature, le champ de signature doit être vide, c’est‑à‑dire qu’il ne doit pas contenir de dictionnaire de signature. Ainsi le document pdf possède déjà un champ de signature, vous ne devez pas fournir l’emplacement pour apposer la signature, la page et le rectangle correspondants sont pris à partir du champ de signature trouvé par le nom de signature (voir le paramètre sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certifiez le document avec la signature MDP. Des données telles que la raison de la signature, le contact et le lieu doivent être fournies via les propriétés correspondantes de l'objet Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Ferme la façade. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Vérifie si le pdf possède une signature numérique ou non. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Vérifie si le pdf possède des droits d'utilisation ou non. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Vérifie si la signature couvre l'ensemble du document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libère la façade. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Extrait le certificat X.509 unique de la signature sous forme de flux. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Extrait l'image de la signature. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Renvoie la valeur des autorisations d'accès du document certifié par le type de signature MDP. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Obtient les noms de tous les champs de signature vides. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Obtient les informations de contact d'une signature. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Obtient la date et l'heure de la signature. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Obtient l'emplacement d'une signature. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Obtient le motif d'une signature. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Obtient la révision d'une signature. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Obtient les noms de toutes les signatures non vides. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Récupère les informations sur tous les algorithmes de signatures présents dans le document PDF. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Obtient le nom de la personne ou de l'organisation qui signe le document PDF. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Obtient la révision totale. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Supprime la signature selon le nom de la signature. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Supprime la signature selon le nom de la signature. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Supprime toutes les signatures. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Supprime l'entrée des droits d'utilisation. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Enregistre le PDF résultant dans le flux. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Enregistre le PDF résultant dans le fichier. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Définit le fichier de certificat et le mot de passe pour la routine de signature. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Signez le document avec le type de signature donné qui est placé dans un champ de signature déjà présent. Avant la signature, le champ de signature doit être vide, c'est‑à‑dire qu'il ne doit pas contenir de dictionnaire de signature. Ainsi le document PDF possède déjà un champ de signature, vous ne devez pas fournir l'emplacement pour apposer la signature, la page correspondante et le rectangle sont récupérés à partir du champ de signature trouvé par le nom de la signature (voir le paramètre SigName). Des données telles que le motif de la signature, le contact et l'emplacement doivent être fournies via les propriétés correspondantes de l'objet Signature sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Signez le document avec le type de signature donné. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Signez le document avec le type de signature donné qui est placé dans un champ de signature déjà présent. Avant la signature, le champ de signature doit être vide, c'est‑à‑dire qu'il ne doit pas contenir de dictionnaire de signature. Ainsi le document PDF possède déjà un champ de signature, vous ne devez pas fournir l'emplacement pour apposer la signature, la page correspondante et le rectangle sont récupérés à partir du champ de signature trouvé par le nom de la signature (voir le paramètre SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Appliquez une signature sur le document PDF. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Signez le document avec le type de signature donné. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Signez le document avec le type de signature donné qui est placé dans un champ de signature déjà présent. Avant la signature, le document PDF doit déjà contenir un champ de signature, la page correspondante et le rectangle sont récupérés à partir du champ de signature trouvé par le nom de la signature (voir le paramètre SigName). |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate)(SignatureName, out Stream) | Extrait le certificat X.509 unique de la signature sous forme de flux. |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate_1)(SignatureName, out X509Certificate2) | Extrait le certificat X.509 unique de la signature. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Vérifie la validité d'une signature. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_2)(SignatureName, X509Certificate2) | Vérifie la validité d'une signature. La vérification est effectuée à l'aide du certificat de clé publique externe. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Vérifie la validité d'une signature. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_3)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | Vérifie la validité d'une signature. La vérification est effectuée à l'aide du certificat de clé publique externe. |

### Voir aussi

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


