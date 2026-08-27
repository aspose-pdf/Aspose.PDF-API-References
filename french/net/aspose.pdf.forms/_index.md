---
title: "Aspose.Pdf.Forms"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "L'espace de noms Aspose.Pdf.Forms possède des classes qui décrivent les formulaires standard, statiques, dynamiques et divers types de champs tels que zone de texte, zone de liste, bouton radio, etc."
type: docs
weight: 110
url: /fr/net/aspose.pdf.forms/
---
L’espace de noms **Aspose.Pdf.Forms** possède des classes qui décrivent les formulaires (standard, statiques, dynamiques) et divers types de champs tels que la zone de texte, la zone de liste, le bouton radio, etc.

## Classes

| Classe | Description |
| --- | --- |
| [BarcodeField](./barcodefield/) | La classe représente le champ de code-barres. |
| [ButtonField](./buttonfield/) | La classe représente le champ de bouton poussoir. |
| [CheckboxField](./checkboxfield/) | Classe représentant le champ de case à cocher. |
| [ChoiceField](./choicefield/) | Représente la classe de base pour les champs de choix. |
| [ComboBoxField](./comboboxfield/) | Classe représentant le champ Combobox du formulaire. |
| [DateField](./datefield/) | Champ de date avec affichage du calendrier. |
| [DocMDPSignature](./docmdpsignature/) | Représente la classe du type de signature MDP (détection et prévention de modification) du document. |
| [ExternalSignature](./externalsignature/) | Crée une signature PKCS#7 détachée en utilisant un X509Certificate2. Elle prend en charge les cartes à puce USB, les jetons sans clés privées exportables. |
| [Field](./field/) | Classe de base pour les champs de formulaire acro. |
| [FileSelectBoxField](./fileselectboxfield/) | Champ pour l'élément de boîte de sélection de fichier. |
| [Form](./form/) | Classe représentant l'objet de formulaire. |
| [IconFit](./iconfit/) | Décrit comment l'icône de l'annotation widget doit être affichée à l'intérieur de son rectangle d'annotation. |
| [ListBoxField](./listboxfield/) | La classe représente le champ ListBox. |
| [NumberField](./numberfield/) | Champ texte avec des caractères valides spécifiés. |
| [Option](./option/) | La classe représente une option du champ de choix. |
| [OptionCollection](./optioncollection/) | Classe représentant la collection d'options du champ de choix. |
| [PasswordBoxField](./passwordboxfield/) | Classe décrivant le champ texte pour la saisie du mot de passe. |
| [PKCS1](./pkcs1/) | Représente l'objet de signature conforme à la norme PKCS#1. L'algorithme de chiffrement RSA et la méthode de hachage SHA-1 sont utilisés pour la signature. |
| [PKCS7](./pkcs7/) | Représente l'objet PKCS#7 conforme à la spécification PKCS#7 de la RFC 2315 d'Internet, PKCS #7 : Cryptographic Message Syntax, version 1.5. Le `SHA1 digest` de la plage d'octets du document est encapsulé dans le champ SignedData de PKCS#7. |
| [PKCS7Detached](./pkcs7detached/) | Représente l'objet PKCS#7 conforme à la spécification PKCS#7 de la RFC 2315 d'Internet, PKCS #7 : Cryptographic Message Syntax, version 1.5. Le condensat du message signé original sur la plage d'octets du document est incorporé comme le champ SignedData normal de PKCS#7. Aucune donnée ne doit être encapsulée dans le champ SignedData de PKCS#7. |
| [RadioButtonField](./radiobuttonfield/) | Classe représentant le champ bouton radio. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Classe représentant l'élément du champ RadioButton. |
| [RichTextBoxField](./richtextboxfield/) | Classe décrivant le composant éditeur de texte enrichi. |
| [Signature](./signature/) | Une classe abstraite qui représente l'objet de signature dans le document PDF. Les signatures sont des champs contenant des objets de signature, ces derniers contenant les données utilisées pour vérifier la validité du document. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Une classe abstraite qui représente l'objet d'apparence personnalisée de la signature. |
| [SignatureField](./signaturefield/) | Représente le champ de formulaire de signature. |
| [SignHash](./signhash/) | Délégué pour signer de façon personnalisée le hachage du document. |
| [TextBoxField](./textboxfield/) | Classe représentant le champ de zone de texte. |
| [XFA](./xfa/) | Représente le formulaire XML conformément à l'architecture XML Forms (XFA). |
## Énumération

| Énumération | Description |
| --- | --- |
| [BoxStyle](./boxstyle/) | Représente les styles pour dessiner la coche dans la case à cocher. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Les autorisations d'accès accordées pour ce document. Les valeurs valides sont : 1 - Aucun changement du document n'est autorisé ; toute modification du document invalide la signature. 2 - Les changements autorisés sont le remplissage des formulaires, l'instanciation de modèles de page et la signature ; d'autres modifications invalident la signature. 3 - Les changements autorisés sont les mêmes que pour 2, ainsi que la création, la suppression et la modification d'annotations ; d'autres modifications invalident la signature. |
| [FormType](./formtype/) | Énumération des types possibles de formulaire Acro. |
| [IconCaptionPosition](./iconcaptionposition/) | Décrit la position de l'icône. |
| [ScalingMode](./scalingmode/) | Le type de mise à l'échelle qui doit être utilisé. |
| [ScalingReason](./scalingreason/) | Les circonstances dans lesquelles l'icône doit être mise à l'échelle à l'intérieur du rectangle d'annotation. |
| [SubjectNameElements](./subjectnameelements/) | L'énumération décrit les éléments de la chaîne de sujet de la signature. |
| [Symbology](./symbology/) | Une symbologie (code-barres) définit les détails techniques d'un type particulier de code-barres : la largeur des barres, le jeu de caractères, la méthode d'encodage, les spécifications de la somme de contrôle, etc. |


