---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileSecurity. Rappresenta la crittografia o la decrittografia di un file Pdf con password di proprietario o utente cambiando le impostazioni di sicurezza e la password
type: docs
weight: 4550
url: /it/net/aspose.pdf.facades/pdffilesecurity/
---
## Classe PdfFileSecurity

Rappresenta la crittografia o la decrittografia di un file Pdf con password di proprietario o utente, cambiando le impostazioni di sicurezza e la password.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Inizializza l'oggetto PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfFileSecurity` sulla base del *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Restituisce l'eccezione che è stata sollevata dall'ultima operazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Inizializza la facciata. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Cambia la password utente e la password di proprietario mantenendo le impostazioni di sicurezza originali. La nuova password utente e la nuova password di proprietario possono essere null o vuote. La password di proprietario sarà sostituita con una stringa casuale se la nuova password di proprietario è null o vuota. Solleva un'eccezione se il processo fallisce. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Cambia la password utente e la password di proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password di proprietario possono essere null o vuote. La password di proprietario sarà sostituita con una stringa casuale se la nuova password di proprietario è null o vuota. Solleva un'eccezione se il processo fallisce. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Cambia la password utente e la password di proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password di proprietario possono essere null o vuote. La password di proprietario sarà sostituita con una stringa casuale se la nuova password di proprietario è null o vuota. Ci sono 6 possibili combinazioni di valori di KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e verrà sollevata un'eccezione se il kit incontra questa combinazione. Solleva un'eccezione se il processo fallisce. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Chiude la facciata. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Decripta un documento Pdf crittografato con la password di proprietario. Se il documento non ha la password di proprietario, è consentito utilizzare la password utente. Solleva un'eccezione se il processo fallisce. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Cripta il file Pdf con la password utente e la password di proprietario e imposta i privilegi di accesso del documento. La password utente e la password di proprietario possono essere null o vuote. La password di proprietario sarà sostituita con una stringa casuale se la password di proprietario in input è null o vuota. Solleva un'eccezione se il processo fallisce. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Cripta il file Pdf con la password utente e la password di proprietario e imposta i privilegi di accesso del documento. La password utente e la password di proprietario possono essere null o vuote. La password di proprietario sarà sostituita con una stringa casuale se la password di proprietario in input è null o vuota. Ci sono 6 possibili combinazioni di valori di KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e verrà sollevata un'eccezione se il kit incontra questa combinazione. Solleva un'eccezione se il processo fallisce. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva il documento PDF nello stream specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva il documento PDF nel file specificato. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Imposta la sicurezza del file Pdf con password utente/proprietario vuote. La password di proprietario sarà aggiunta con una stringa casuale. Solleva un'eccezione se il processo fallisce. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Imposta la sicurezza del file Pdf con la password originale. Solleva un'eccezione se il processo fallisce. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Cambia la password utente e la password di proprietario mantenendo le impostazioni di sicurezza originali. La nuova password utente e la nuova password di proprietario possono essere null o vuote. La password di proprietario sarà sostituita con una stringa casuale se la nuova password di proprietario è null o vuota. Non solleva un'eccezione se il processo fallisce. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Cambia la password utente e la password di proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password di proprietario possono essere null o vuote. La password di proprietario sarà sostituita con una stringa casuale se la nuova password di proprietario è null o vuota. Non solleva un'eccezione se il processo fallisce. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Cambia la password utente e la password di proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password di proprietario possono essere null o vuote. La password di proprietario sarà sostituita con una stringa casuale se la nuova password di proprietario è null o vuota. Ci sono 6 possibili combinazioni di valori di KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e verrà sollevata un'eccezione se il kit incontra questa combinazione. Non solleva un'eccezione se il processo fallisce. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Decripta un documento Pdf crittografato con la password di proprietario. Se il documento non ha la password di proprietario, è consentito utilizzare la password utente. Non solleva un'eccezione se il processo fallisce. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Cripta il file Pdf con la password utente e la password di proprietario e imposta i privilegi di accesso del documento. La password utente e la password di proprietario possono essere null o vuote. La password di proprietario sarà sostituita con una stringa casuale se la password di proprietario in input è null o vuota. Non solleva un'eccezione se il processo fallisce. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Imposta la sicurezza del file Pdf con la password originale. Non solleva un'eccezione se il processo fallisce. |

### Vedi anche

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)