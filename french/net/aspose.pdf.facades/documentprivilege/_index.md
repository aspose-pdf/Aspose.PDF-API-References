---
title: DocumentPrivilege
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente les privilèges daccès au fichier Pdf. Faire référence àPdfFileSecurity./pdffilesecurity . Il existe 4 façons dutiliser cette classe  1.Utilisation directe dun privilège prédéfini. 2.Basé sur un privilège prédéfini et modification de certaines autorisations spécifiques. 3.Basé sur un privilège prédéfini et modification dune combinaison dautorisations Adobe Professional spécifique. 4. Mélange la voie2 et la voie3.
type: docs
weight: 2240
url: /fr/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Représente les privilèges d'accès au fichier Pdf. Faire référence à[`PdfFileSecurity`](../pdffilesecurity) . Il existe 4 façons d'utiliser cette classe : 1.Utilisation directe d'un privilège prédéfini. 2.Basé sur un privilège prédéfini et modification de certaines autorisations spécifiques. 3.Basé sur un privilège prédéfini et modification d'une combinaison d'autorisations Adobe Professional spécifique. 4. Mélange la voie2 et la voie3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Propriétés

| Nom | La description |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall) { get; } | Tout autorisé. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly) { get; } | Permet d'assembler le fichier. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy) { get; } | Permet de copier le fichier. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting) { get; } | Permet l'impression dégradée. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin) { get; } | Permet de remplir des formulaires dans le fichier. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall) { get; } | Tout interdit. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations) { get; } | Permet de modifier les annotations du fichier. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents) { get; } | Permet de modifier le fichier. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print) { get; } | Permet d'imprimer le fichier. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders) { get; } | Permet de lire à l'écran uniquement. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly) { get; set; } | Définit l'autorisation qui autorise ou non l'assemblage. true est autorisé et false est interdit. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy) { get; set; } | Définit l'autorisation qui autorise ou non la copie. true est autorisé et false est interdit. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting) { get; set; } | Définit la permission qui autorise ou non l'impression dégradée. true est autorisé et false est interdit. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin) { get; set; } | Définit la permission qui permet de remplir ou non les formulaires. true est autorisé et false est interdit. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations) { get; set; } | Définit la permission qui autorise ou non la modification des annotations. true est autorisé et false est interdit. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents) { get; set; } | Définit la permission qui permet de modifier le contenu ou non. true est autorisé et false est interdit. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint) { get; set; } | Définit l'autorisation qui autorise ou non l'impression. true est autorisé et false est interdit. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders) { get; set; } | Définit l'autorisation qui autorise ou non les lecteurs d'écran. true est autorisé et false est interdit. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel) { set; } | Définit le niveau de modification du privilège du document. Tout comme les paramètres d'Adobe Professional Modifications autorisées. 0 : Aucun. 1 : Insérer, supprimer et faire pivoter des pages. 2 : Remplir les champs de formulaire et signer les champs de signature existants. 3 : Commenter, remplir les champs de formulaire et signer les champs de signature. 4 : tous sauf pages d'extraction. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel) { set; } | Définit le niveau de privilège de copie du document. Tout comme les paramètres d'autorisation d'Adobe Professional. 0 : Aucun. 1 : Activez l'accès au texte pour les appareils de lecture d'écran pour les malvoyants. 2 : Activez la copie de texte, d'images et d'autres contenus. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel) { set; } | Définit le niveau d'impression du privilège du document. Tout comme les paramètres d'impression autorisée d'Adobe Professional. 0 : Aucun. 1 : basse résolution (150 dpi). 2 : haute résolution. |

## Méthodes

| Nom | La description |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto)(object) | Compare deux[`DocumentPrivilege`](../documentprivilege) objets.  L'objet à comparer. Un entier signé qui indique les valeurs relatives de cette instance et de cette valeur. Inférieur à zéro, cette instance est inférieure à la valeur. Zéro cette instance est égale à valeur. Supérieure à zéro, cette instance est supérieure à la valeur. |

### Exemples

```csharp
[C#]	
//Way1 : Utilisation directe des privilèges prédéfinis.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2 : Basé sur un privilège prédéfini et modifier certaines autorisations spécifiques.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3 : Basé sur un privilège prédéfini et modifier certaines combinaisons d'autorisations Adobe Professional spécifiques.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4 : Mélange le chemin2 et le chemin3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1 : Utilisation directe des privilèges prédéfinis.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2 : Basé sur un privilège prédéfini et modifier certaines autorisations spécifiques.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3 : Basé sur un privilège prédéfini et modifier certaines combinaisons d'autorisations Adobe Professional spécifiques.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4 : mélange les voies 2 et 3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Voir également

* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
