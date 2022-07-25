---
title: PdfFileSecurity
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta la crittografia o la decrittografia di un file Pdf con password del proprietario o dellutente modifica dellimpostazione di sicurezza e password.
type: docs
weight: 2560
url: /it/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Rappresenta la crittografia o la decrittografia di un file Pdf con password del proprietario o dell'utente, modifica dell'impostazione di sicurezza e password.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity#constructor)() | Inizializza l'oggetto di PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity#constructor_1)(Document) | Inizializza nuovo[`PdfFileSecurity`](../pdffilesecurity) oggetto sulla base del*document* . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception) { get; } | Restituisce l'eccezione generata dall'ultima operazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_1)(Stream) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_2)(string) | Inizializza la facciata. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword)(string, string, string) | Modifica la password utente e la password del proprietario in base alla password del proprietario, mantiene le impostazioni di sicurezza originali. La nuova password utente e la nuova password del proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è nulla o vuota. Genera un'eccezione se il processo non riesce. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Modifica la password utente e la password in base alla password del proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è nulla o vuota. Genera un'eccezione se il processo non riesce. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Modifica la password utente e la password in base alla password del proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è nulla o vuota. Esistono 6 possibili combinazioni di valori KeySize e Algoritmo. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) non sono validi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Genera un'eccezione se il processo non riesce. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close)() | Chiude la facciata. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile)(string) | Decrittografa un documento Pdf crittografato tramite la password del proprietario. Se il documento non ha la password del proprietario, è consentito utilizzare la password dell'utente. Genera un'eccezione se il processo non riesce. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile)(string, string, DocumentPrivilege, KeySize) | Crittografa il file Pdf con userpassword e ownerpassword e imposta i privilegi di accesso del documento. La password utente e la password proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita con una stringa casuale se la password del proprietario immessa è nulla o vuota. Genera un'eccezione se il processo non riesce. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Crittografa il file Pdf con userpassword e ownerpassword e imposta i privilegi di accesso del documento. La password utente e la password proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita con una stringa casuale se la password del proprietario di input è nulla o vuota. Esistono 6 possibili combinazioni di valori KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) non sono validi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Genera un'eccezione se il processo non riesce. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Salva il documento PDF nel flusso specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Salva il documento PDF nel file specificato. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege)(DocumentPrivilege) | Imposta la sicurezza del file Pdf con password utente/proprietario vuote. La password del proprietario verrà aggiunta da una stringa casuale. Genera un'eccezione se il processo non riesce. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege_1)(string, string, DocumentPrivilege) | Imposta la sicurezza del file Pdf con la password originale. Genera un'eccezione se il processo non riesce. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword)(string, string, string) | Modifica la password utente e la password del proprietario in base alla password del proprietario, mantiene le impostazioni di sicurezza originali. La nuova password utente e la nuova password del proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita Non genera un'eccezione se il processo non riesce. con una stringa casuale se la nuova password del proprietario è nulla o vuota. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Modifica la password utente e la password in base alla password del proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è nulla o vuota. Non genera un'eccezione se il processo non riesce. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Modifica la password utente e la password in base alla password del proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è nulla o vuota. Esistono 6 possibili combinazioni di valori KeySize e Algoritmo. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) non sono validi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Non genera un'eccezione se il processo non riesce. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile)(string) | Decrittografa un documento Pdf crittografato tramite la password del proprietario. Se il documento non ha la password del proprietario, è consentito utilizzare la password dell'utente. Non genera un'eccezione se il processo non riesce. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile)(string, string, DocumentPrivilege, KeySize) | Crittografa il file Pdf con userpassword e ownerpassword e imposta i privilegi di accesso del documento. La password utente e la password proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita con una stringa casuale se la password del proprietario di input è nulla o vuota. Non genera un'eccezione se il processo non riesce. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege)(string, string, DocumentPrivilege) | Imposta la sicurezza del file Pdf con la password originale. Non genera un'eccezione se il processo non riesce. |

### Guarda anche

* class [SaveableFacade](../saveablefacade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
