---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.DocumentPrivilege. Représente les privilèges pour accéder au fichier Pdf. Référez-vous à PdfFileSecurity. Il existe 4 façons d'utiliser cette classe  1. En utilisant directement un privilège prédéfini. 2. Basé sur un privilège prédéfini et en changeant certaines permissions spécifiques. 3. Basé sur un privilège prédéfini et en changeant certaines combinaisons de permissions Adobe Professional spécifiques. 4. Mélange les méthodes 2 et 3.
type: docs
weight: 4230
url: /fr/net/aspose.pdf.facades/documentprivilege/
---
## Classe DocumentPrivilege

Représente les privilèges pour accéder au fichier Pdf. Référez-vous à [`PdfFileSecurity`](../pdffilesecurity/). Il existe 4 façons d'utiliser cette classe : 1. En utilisant directement un privilège prédéfini. 2. Basé sur un privilège prédéfini et en changeant certaines permissions spécifiques. 3. Basé sur un privilège prédéfini et en changeant certaines combinaisons de permissions Adobe Professional spécifiques. 4. Mélange les méthodes 2 et 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Tout est autorisé. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Permet d'assembler le fichier. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Permet de copier le fichier. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Permet l'impression dégradée. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Permet de remplir des formulaires dans le fichier. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Tout est interdit. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Permet de modifier les annotations du fichier. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Permet de modifier le fichier. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Permet d'imprimer le fichier. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Permet de lire uniquement sur écran. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Définit la permission qui permet l'assemblage ou non. true est autorisé et false est interdit. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Définit la permission qui permet la copie ou non. true est autorisé et false est interdit. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Définit la permission qui permet l'impression dégradée ou non. true est autorisé et false est interdit. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Définit la permission qui permet de remplir des formulaires ou non. true est autorisé et false est interdit. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Définit la permission qui permet de modifier les annotations ou non. true est autorisé et false est interdit. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Définit la permission qui permet de modifier le contenu ou non. true est autorisé et false est interdit. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Définit la permission qui permet d'imprimer ou non. true est autorisé et false est interdit. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Définit la permission qui permet aux lecteurs d'écran ou non. true est autorisé et false est interdit. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Obtient et définit le niveau de changement des privilèges du document. Tout comme les paramètres de modifications autorisées d'Adobe Professional. 0 : Aucun. 1 : Insertion, suppression et rotation de pages. 2 : Remplissage des champs de formulaire et signature des champs de signature existants. 3 : Commentaires, remplissage des champs de formulaire et signature des champs de signature existants. 4 : Tout sauf l'extraction de pages. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Obtient et définit le niveau de copie des privilèges du document. Tout comme les paramètres de permission d'Adobe Professional. 0 : Aucun. 1 : Activer l'accès au texte pour les dispositifs de lecture d'écran pour les malvoyants. 2 : Activer la copie de texte, d'images et d'autres contenus. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Obtient et définit le niveau d'impression des privilèges du document. Tout comme les paramètres d'impression autorisée d'Adobe Professional. 0 : Aucun. 1 : Basse résolution (150 dpi). 2 : Haute résolution. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Compare deux objets `DocumentPrivilege`. L'objet à comparer. Un entier signé qui indique les valeurs relatives de cette instance et de la valeur. Moins que zéro cette instance est inférieure à la valeur. Zéro cette instance est égale à la valeur. Plus que zéro cette instance est supérieure à la valeur. |

## Exemples

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
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