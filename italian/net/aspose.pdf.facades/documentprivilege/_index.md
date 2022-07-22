---
title: DocumentPrivilege
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta i privilegi per laccesso al file Pdf. Fare riferimento aPdfFileSecurity./pdffilesecurity . Esistono 4 modi per utilizzare questa classe 1.Utilizzare direttamente il privilegio predefinito. 2. Basarsi su un privilegio predefinito e modificare alcune autorizzazioni specifiche. 3. Basarsi su un privilegio predefinito e modificare alcune specifiche combinazioni di autorizzazioni Adobe Professional. 4. Mescola il modo2 e il modo3.
type: docs
weight: 2240
url: /it/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Rappresenta i privilegi per l'accesso al file Pdf. Fare riferimento a[`PdfFileSecurity`](../pdffilesecurity) . Esistono 4 modi per utilizzare questa classe: 1.Utilizzare direttamente il privilegio predefinito. 2. Basarsi su un privilegio predefinito e modificare alcune autorizzazioni specifiche. 3. Basarsi su un privilegio predefinito e modificare alcune specifiche combinazioni di autorizzazioni Adobe Professional. 4. Mescola il modo2 e il modo3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall) { get; } | Tutto consentito. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly) { get; } | Consente il file di assemblaggio. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy) { get; } | Consente di copiare il file. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting) { get; } | Consente la stampa degradata. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin) { get; } | Consente la compilazione di moduli in file. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall) { get; } | Tutto proibito. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations) { get; } | Consente di modificare le annotazioni del file. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents) { get; } | Consente di modificare il file. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print) { get; } | Consente la stampa del file. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders) { get; } | Consente di leggere solo sullo schermo. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly) { get; set; } | Imposta l'autorizzazione che consente l'assemblaggio o meno. true è consentito e false è vietato. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy) { get; set; } | Imposta l'autorizzazione che consente la copia o meno. true è consentito e false è vietato. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting) { get; set; } | Imposta l'autorizzazione che consente o meno la stampa degradata. true è consentito e false è vietato. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin) { get; set; } | Imposta l'autorizzazione che consente di compilare o meno i moduli. true è consentito e false è vietato. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations) { get; set; } | Imposta l'autorizzazione che consente di modificare o meno le annotazioni. true è consentito e false è vietato. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents) { get; set; } | Imposta l'autorizzazione che consente di modificare o meno i contenuti. true è consentito e false è vietato. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint) { get; set; } | Imposta l'autorizzazione che consente la stampa o meno. true è consentito e false è vietato. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders) { get; set; } | Imposta l'autorizzazione che consente o meno le utilità per la lettura dello schermo. true è consentito e false è vietato. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel) { set; } | Imposta il livello di modifica del privilegio del documento. Proprio come le impostazioni per le modifiche consentite di Adobe Professional. 0: Nessuno. 1: Inserimento, eliminazione e rotazione di pagine. 2: Compilazione di campi modulo e firma di campi firma esistenti. 3: Creazione di commenti, compilazione di campi modulo e firma di quelli esistenti campi firma. 4: Qualsiasi tranne l'estrazione di pagine. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel) { set; } | Imposta il livello di copia del privilegio del documento. Proprio come le impostazioni di autorizzazione di Adobe Professional. 0: Nessuno. 1: Abilita l'accesso al testo per i dispositivi di lettura dello schermo per non vedenti. 2: Abilita la copia di testo, immagini e altro contenuto. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel) { set; } | Imposta il livello di stampa del privilegio del documento. Proprio come le impostazioni di stampa consentita di Adobe Professional. 0: Nessuno. 1: Bassa risoluzione (150 dpi). 2: Alta risoluzione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto)(object) | Confronta due[`DocumentPrivilege`](../documentprivilege) oggetti.  L'oggetto con cui confrontare. Un numero intero con segno che indica i valori relativi di questa istanza e valore. Minore di zero questa istanza è minore del valore. Zero questa istanza è uguale a valore. Maggiore di zero questa istanza è maggiore di valore. |

### Esempi

```csharp
[C#]	
caso uno:
DocumentPrivilege privilege = DocumentPrivilege.Print;

Il modello di input pdf è un file pdf e l'output è un grande flusso unito.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

caso due:
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

Il modello di input pdf è un file pdf e l'output è un sacco di piccoli file.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'//Way1: utilizzo diretto del privilegio predefinito.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'//Way2: Basato su un privilegio predefinito e modifica alcune autorizzazioni specifiche.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'//Way3: basato su un privilegio predefinito e modifica alcune combinazioni di autorizzazioni Adobe Professional specifiche.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'//Way4: mescola il modo2 e il modo3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Guarda anche

* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
