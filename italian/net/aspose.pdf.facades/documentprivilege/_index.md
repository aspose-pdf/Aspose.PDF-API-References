---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.DocumentPrivilege. Rappresenta i privilegi per accedere ai file Pdf. Fare riferimento a PdfFileSecurity. Ci sono 4 modi per utilizzare questa classe: 1. Utilizzando direttamente il privilegio predefinito. 2. Basato su un privilegio predefinito e modificare alcune autorizzazioni specifiche. 3. Basato su un privilegio predefinito e modificare alcune combinazioni di autorizzazioni specifiche di Adobe Professional. 4. Mescola il modo 2 e il modo 3.
type: docs
weight: 4230
url: /it/net/aspose.pdf.facades/documentprivilege/
---
## Classe DocumentPrivilege

Rappresenta i privilegi per accedere ai file Pdf. Fare riferimento a [`PdfFileSecurity`](../pdffilesecurity/). Ci sono 4 modi per utilizzare questa classe: 1. Utilizzando direttamente il privilegio predefinito. 2. Basato su un privilegio predefinito e modificare alcune autorizzazioni specifiche. 3. Basato su un privilegio predefinito e modificare alcune combinazioni di autorizzazioni specifiche di Adobe Professional. 4. Mescola il modo 2 e il modo 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Tutto consentito. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Consente di assemblare il file. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Consente di copiare il file. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Consente la stampa degradata. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Consente di compilare i moduli nel file. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Tutto vietato. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Consente di modificare le annotazioni del file. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Consente di modificare il file. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Consente di stampare il file. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Consente solo la lettura su schermo. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Imposta il permesso che consente l'assemblaggio o meno. true è consentito e false è vietato. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Imposta il permesso che consente la copia o meno. true è consentito e false è vietato. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Imposta il permesso che consente la stampa degradata o meno. true è consentito e false è vietato. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Imposta il permesso che consente di compilare i moduli o meno. true è consentito e false è vietato. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Imposta il permesso che consente di modificare le annotazioni o meno. true è consentito e false è vietato. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Imposta il permesso che consente di modificare i contenuti o meno. true è consentito e false è vietato. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Imposta il permesso che consente di stampare o meno. true è consentito e false è vietato. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Imposta il permesso che consente ai lettori di schermo o meno. true è consentito e false è vietato. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Ottiene e imposta il livello di modifica dei privilegi del documento. Proprio come le impostazioni delle modifiche consentite di Adobe Professional. 0: Nessuno. 1: Inserimento, eliminazione e rotazione delle pagine. 2: Compilazione dei campi del modulo e firma dei campi di firma esistenti. 3: Commento, compilazione dei campi del modulo e firma dei campi di firma esistenti. 4: Qualsiasi tranne l'estrazione delle pagine. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Ottiene e imposta il livello di copia dei privilegi del documento. Proprio come le impostazioni di autorizzazione di Adobe Professional. 0: Nessuno. 1: Abilita l'accesso al testo per i dispositivi di lettura dello schermo per non vedenti. 2: Abilita la copia di testo, immagini e altri contenuti. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Ottiene e imposta il livello di stampa dei privilegi del documento. Proprio come le impostazioni di stampa consentite di Adobe Professional. 0: Nessuno. 1: Bassa risoluzione (150 dpi). 2: Alta risoluzione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Confronta due oggetti `DocumentPrivilege`. L'oggetto da confrontare. Un intero firmato che indica i valori relativi di questa istanza e del valore. Minore di zero questa istanza è minore del valore. Zero questa istanza è uguale al valore. Maggiore di zero questa istanza è maggiore del valore. |

## Esempi

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

### Vedi Anche

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)