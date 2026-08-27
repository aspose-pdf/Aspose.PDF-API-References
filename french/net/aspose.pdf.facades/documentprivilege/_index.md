---
title: "Classe DocumentPrivilege"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Facades.DocumentPrivilege classe. Représente les privilèges d'accès au fichier Pdf. Voir PdfFileSecurity. Il existe 4 manières d'utiliser cette classe : 1. Utiliser directement le privilège prédéfini. 2. Se baser sur un privilège prédéfini et modifier certaines permissions spécifiques. 3. Se baser sur un privilège prédéfini et modifier une combinaison spécifique de permissions Adobe Professional. 4. Mélanger les méthodes 2 et 3."
type: docs
weight: 4350
url: /fr/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Représente les privilèges d'accès au fichier Pdf. Référez-vous à[`PdfFileSecurity`](../pdffilesecurity/). Il existe 4 façons d'utiliser cette classe : 1. Utiliser le privilège prédéfini directement. 2. Se baser sur un privilège prédéfini et modifier certaines permissions spécifiques. 3. Se baser sur un privilège prédéfini et modifier une combinaison de permissions spécifiques d'Adobe Professional. 4. Mélanger la façon2 et la façon3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Tout autorisé. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Autorise l'assemblage du fichier. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Autorise la copie du fichier. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Autorise l'impression de qualité réduite. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Autorise le remplissage des formulaires dans le fichier. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Tout interdit. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Autorise la modification des annotations du fichier. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Autorise la modification du fichier. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Autorise l'impression du fichier. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Autorise la lecture à l'écran uniquement. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Définit la permission qui autorise l'assemblage ou non. true signifie autorisé et false signifie interdit. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Définit la permission qui autorise la copie ou non. true signifie autorisé et false signifie interdit. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Définit la permission qui autorise l'impression de qualité réduite ou non. true signifie autorisé et false signifie interdit. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Définit la permission qui autorise le remplissage des formulaires ou non. true signifie autorisé et false signifie interdit. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Définit la permission qui autorise la modification des annotations ou non. true signifie autorisé et false signifie interdit. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Définit la permission qui autorise la modification du contenu ou non. true signifie autorisé et false signifie interdit. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Définit la permission qui autorise l'impression ou non. true signifie autorisé et false signifie interdit. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Définit la permission qui autorise les lecteurs d'écran ou non. true signifie autorisé et false signifie interdit. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Obtient et définit le niveau de modification du privilège du document. Identique aux paramètres Changes Allowed d'Adobe Professional. 0 : Aucun. 1 : Insertion, suppression et rotation des pages. 2 : Remplissage des champs de formulaire et signature des champs de signature existants. 3 : Commentaire, remplissage des champs de formulaire et signature des champs de signature existants. 4 : Tout sauf l'extraction des pages. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Obtient et définit le niveau de copie du privilège du document. Identique aux paramètres de permission d'Adobe Professional. 0 : Aucun. 1 : Activer l'accès texte pour les appareils de lecteur d'écran pour les malvoyants. 2 : Activer la copie du texte, des images et d'autres contenus. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Obtient et définit le niveau d'impression du privilège du document. Identique aux paramètres Printing Allowed d'Adobe Professional. 0 : Aucun. 1 : Basse résolution (150 dpi). 2 : Haute résolution. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Compare deux objets `DocumentPrivilege`.  L'objet avec lequel comparer. Un entier signé qui indique les valeurs relatives de cette instance et de la valeur. Inférieur à zéro, cette instance est inférieure à la valeur. Zéro, cette instance est égale à la valeur. Supérieur à zéro, cette instance est supérieure à la valeur. |

## Exemples

```csharp
[C#]	
//Méthode1 : Utiliser le privilège prédéfini directement.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Méthode2 : Se baser sur un privilège prédéfini et modifier certaines permissions spécifiques.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3 : Basé sur un privilège prédéfini et modifie une combinaison de permissions spécifiques d'Adobe Professional.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4 : Combine le way2 et le way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Voir aussi

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


