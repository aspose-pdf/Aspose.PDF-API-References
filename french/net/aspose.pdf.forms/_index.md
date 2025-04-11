---
title: Aspose.Pdf.Forms
second_title: Aspose.PDF for .NET API Reference
description: L'espace de noms Aspose.Pdf.Forms contient des classes qui décrivent des formulaires (standard, statique, dynamique) et divers types de champs comme la zone de texte, la zone de liste, le bouton radio, etc.
type: docs
weight: 110
url: /fr/net/aspose.pdf.forms/
---
Le **namespace Aspose.Pdf.Forms** contient des classes qui décrivent des formulaires (standard, statique, dynamique) et divers types de champs comme la zone de texte, la zone de liste, le bouton radio, etc.

## Classes

| Classe | Description |
| --- | --- |
| [BarcodeField](./barcodefield/) | La classe représente le champ de code-barres. |
| [ButtonField](./buttonfield/) | La classe représente le champ de bouton poussoir. |
| [CheckboxField](./checkboxfield/) | Classe représentant le champ de case à cocher |
| [ChoiceField](./choicefield/) | Représente la classe de base pour les champs de choix. |
| [ComboBoxField](./comboboxfield/) | Classe représentant le champ ComboBox du formulaire. |
| [DateField](./datefield/) | Champ de date avec vue calendrier. |
| [DocMDPSignature](./docmdpsignature/) | Représente la classe de signature de document MDP (détection et prévention de modification). |
| [ExternalSignature](./externalsignature/) | Crée une signature PKCS#7 détachée en utilisant un X509Certificate2. Il prend en charge les cartes intelligentes USB, les jetons sans clés privées exportables. |
| [Field](./field/) | Classe de base pour les champs de formulaire acro. |
| [FileSelectBoxField](./fileselectboxfield/) | Champ pour l'élément de boîte de sélection de fichier. |
| [Form](./form/) | Classe représentant l'objet formulaire. |
| [IconFit](./iconfit/) | Décrit comment l'icône de l'annotation du widget doit être affichée dans son rectangle d'annotation. |
| [ListBoxField](./listboxfield/) | La classe représente le champ ListBox. |
| [NumberField](./numberfield/) | Champ de texte avec des caractères valides spécifiés |
| [Option](./option/) | Classe représentant l'option du champ de choix. |
| [OptionCollection](./optioncollection/) | Classe représentant la collection d'options du champ de choix. |
| [PasswordBoxField](./passwordboxfield/) | Classe décrivant le champ de texte pour entrer le mot de passe. |
| [PKCS1](./pkcs1/) | Représente l'objet de signature concernant la norme PKCS#1. L'algorithme de chiffrement RSA et la méthode de hachage SHA-1 sont utilisés pour la signature. |
| [PKCS7](./pkcs7/) | Représente l'objet PKCS#7 qui est conforme à la spécification PKCS#7 dans le RFC Internet 2315, PKCS #7 : Syntaxe de message cryptographique, Version 1.5. Le `hachage SHA1` de la plage d'octets du document est encapsulé dans le champ SignedData PKCS#7. |
| [PKCS7Detached](./pkcs7detached/) | Représente l'objet PKCS#7 qui est conforme à la spécification PKCS#7 dans le RFC Internet 2315, PKCS #7 : Syntaxe de message cryptographique, Version 1.5. Le hachage du message signé original sur la plage d'octets du document est incorporé comme le champ SignedData PKCS#7 normal. Aucune donnée n'est encapsulée dans le champ SignedData PKCS#7. |
| [RadioButtonField](./radiobuttonfield/) | Classe représentant le champ de bouton radio. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Classe représentant un élément du champ RadioButton. |
| [RichTextBoxField](./richtextboxfield/) | Classe décrivant le composant éditeur de texte enrichi. |
| [Signature](./signature/) | Une classe abstraite qui représente l'objet de signature dans le document pdf. Les signatures sont des champs avec des valeurs d'objets de signature, le dernier contenant des données utilisées pour vérifier la validité du document. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Une classe abstraite qui représente l'objet d'apparence personnalisée de signature. |
| [SignatureField](./signaturefield/) | Représente le champ de formulaire de signature. |
| [SignHash](./signhash/) | Délégué pour signer le hachage du document de manière personnalisée. |
| [TextBoxField](./textboxfield/) | Classe représentant le champ de zone de texte. |
| [XFA](./xfa/) | Représente le formulaire XML concernant l'Architecture des formulaires XML (XFA). |
## Énumération

| Énumération | Description |
| --- | --- |
| [BoxStyle](./boxstyle/) | Représente les styles pour dessiner une coche dans la case à cocher. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Les permissions d'accès accordées pour ce document. Les valeurs valides sont : 1 - Aucun changement au document n'est permis ; tout changement au document invalide la signature. 2 - Les changements permis sont le remplissage de formulaires, l'instanciation de modèles de page et la signature ; d'autres changements invalident la signature. 3 - Les changements permis sont les mêmes que pour 2, ainsi que la création, la suppression et la modification d'annotations ; d'autres changements invalident la signature. |
| [FormType](./formtype/) | Énumération des types possibles de formulaire Acro. |
| [IconCaptionPosition](./iconcaptionposition/) | Décrit la position de l'icône. |
| [ScalingMode](./scalingmode/) | Le type de mise à l'échelle qui doit être utilisé. |
| [ScalingReason](./scalingreason/) | Les circonstances dans lesquelles l'icône doit être mise à l'échelle à l'intérieur du rectangle d'annotation. |
| [SubjectNameElements](./subjectnameelements/) | L'énumération décrit les éléments dans la chaîne de sujet de la signature. |
| [Symbology](./symbology/) | Une symbologie (code-barres) définit les détails techniques d'un type particulier de code-barres : la largeur des barres, l'ensemble de caractères, la méthode de codage, les spécifications de somme de contrôle, etc. |