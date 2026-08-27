---
title: "Classe DocumentPrivilege"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Facades.DocumentPrivilege class. Rappresenta i privilegi per l'accesso a file Pdf. Vedi PdfFileSecurity. Esistono 4 modalità di utilizzo di questa classe: 1. Utilizzare direttamente un privilegio predefinito. 2. Basarsi su un privilegio predefinito e modificare alcune autorizzazioni specifiche. 3. Basarsi su un privilegio predefinito e modificare una combinazione specifica di autorizzazioni di Adobe Professional. 4. Mescolare il modo 2 e il modo 3."
type: docs
weight: 4350
url: /it/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Rappresenta i privilegi per l'accesso al file Pdf. Vedi [`PdfFileSecurity`](../pdffilesecurity/). Ci sono 4 modi per utilizzare questa classe: 1. Utilizzare direttamente il privilegio predefinito. 2. Basato su un privilegio predefinito e modificare alcune autorizzazioni specifiche. 3. Basato su un privilegio predefinito e modificare una combinazione specifica di autorizzazioni di Adobe Professional. 4. Mescolare il modo 2 e il modo 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Tutto consentito. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Consente l'assemblaggio del file. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Consente la copia del file. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Consente la stampa a bassa risoluzione. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Consente la compilazione dei moduli nel file. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Tutto vietato. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Consente la modifica delle annotazioni del file. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Consente la modifica del file. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Consente la stampa del file. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Consente la lettura solo su schermo. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Imposta l'autorizzazione che consente l'assemblaggio o meno. true consente e false vieta. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Imposta l'autorizzazione che consente la copia o meno. true consente e false vieta. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Imposta l'autorizzazione che consente la stampa a bassa risoluzione o meno. true consente e false vieta. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Imposta l'autorizzazione che consente la compilazione dei moduli o meno. true consente e false vieta. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Imposta l'autorizzazione che consente la modifica delle annotazioni o meno. true consente e false vieta. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Imposta l'autorizzazione che consente la modifica del contenuto o meno. true consente e false vieta. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Imposta l'autorizzazione che consente la stampa o meno. true consente e false vieta. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Imposta l'autorizzazione che consente i lettori schermo o meno. true consente e false vieta. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Ottiene e imposta il livello di modifica del privilegio del documento. Come le impostazioni Changes Allowed di Adobe Professional. 0: Nessuno. 1: Inserimento, eliminazione e rotazione delle pagine. 2: Compilazione dei campi modulo e firma dei campi firma esistenti. 3: Commenti, compilazione dei campi modulo e firma dei campi firma esistenti. 4: Qualsiasi operazione tranne l'estrazione delle pagine. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Ottiene e imposta il livello di copia del privilegio del documento. Come le impostazioni di autorizzazione di Adobe Professional. 0: Nessuno. 1: Abilita l'accesso al testo per dispositivi di lettura schermo per ipovedenti. 2: Abilita la copia di testo, immagini e altri contenuti. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Ottiene e imposta il livello di stampa del privilegio del documento. Come le impostazioni Printing Allowed di Adobe Professional. 0: Nessuno. 1: Bassa risoluzione (150 dpi). 2: Alta risoluzione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Confronta due oggetti `DocumentPrivilege`.  L'oggetto con cui confrontare. Un intero con segno che indica i valori relativi di questa istanza e del valore. Meno di zero questa istanza è inferiore al valore. Zero questa istanza è uguale al valore. Maggiore di zero questa istanza è superiore al valore. |

## Esempi

```csharp
[C#]	
//Modo 1: Utilizzare direttamente il privilegio predefinito.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Modo 2: Basato su un privilegio predefinito e modificare alcune autorizzazioni specifiche.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Basato su un privilegio predefinito e modifica alcune combinazioni specifiche di permessi di Adobe Professional.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mescola way2 e way3
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

### Vedi anche

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


