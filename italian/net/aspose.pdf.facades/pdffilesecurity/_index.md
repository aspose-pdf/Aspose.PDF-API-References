---
title: "Classe PdfFileSecurity"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Facades.PdfFileSecurity. Rappresenta la cifratura o decifratura di un file Pdf con password proprietario o utente modificando le impostazioni di sicurezza e la password"
type: docs
weight: 4670
url: /it/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Rappresenta la cifratura o decifratura di un file Pdf con password proprietario o utente, modificando le impostazioni di sicurezza e la password.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Inizializza l'oggetto PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfFileSecurity` basato sul *document*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facade del documento su cui sta lavorando. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Restituisce l'eccezione generata dall'ultima operazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza il facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Inizializza il facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Inizializza il facade. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Modifica la password utente e la password proprietario tramite la password proprietario, mantenendo le impostazioni di sicurezza originali. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Genera un'eccezione se l'operazione fallisce. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Modifica la password utente e la password tramite la password proprietario, consentendo di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Genera un'eccezione se l'operazione fallisce. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Modifica la password utente e la password tramite la password proprietario, consentendo di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Esistono 6 combinazioni possibili dei valori di KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Genera un'eccezione se l'operazione fallisce. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Chiude la facciata. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Decifra un documento Pdf crittografato tramite la password proprietario. Se il documento non ha una password proprietario, è consentito utilizzare la password utente. Genera un'eccezione se l'operazione fallisce. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Cifra un file Pdf con password utente e password proprietario e imposta i privilegi di accesso del documento. La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la password proprietario in ingresso è null o vuota. Genera un'eccezione se l'operazione fallisce. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Cifra un file Pdf con password utente e password proprietario e imposta i privilegi di accesso del documento. La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la password proprietario in ingresso è null o vuota. Esistono 6 combinazioni possibili dei valori di KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Genera un'eccezione se l'operazione fallisce. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva il documento PDF nello stream specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva il documento PDF nel file specificato. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Imposta la sicurezza del file Pdf con password utente/proprietario vuote. La password proprietario sarà aggiunta con una stringa casuale. Genera un'eccezione se l'operazione fallisce. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Imposta la sicurezza del file Pdf con la password originale. Genera un'eccezione se l'operazione fallisce. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Modifica la password utente e la password proprietario tramite la password proprietario, mantenendo le impostazioni di sicurezza originali. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non genera un'eccezione se l'operazione fallisce. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Modifica la password utente e la password tramite la password proprietario, consentendo di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non genera un'eccezione se l'operazione fallisce. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Modifica la password utente e la password del proprietario, consente di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è null o vuota. Esistono 6 combinazioni possibili di valori KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e verrà sollevata l'eccezione corrispondente se il kit incontra questa combinazione. Non genera un'eccezione se il processo fallisce. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Decripta un documento Pdf crittografato con la password del proprietario. Se il documento non ha una password del proprietario, è consentito usare la password utente. Non genera un'eccezione se il processo fallisce. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Cifra un file Pdf con password utente e password del proprietario e imposta i privilegi del documento per l'accesso. La password utente e la password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la password del proprietario fornita è null o vuota. Non genera un'eccezione se il processo fallisce. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Imposta la sicurezza del file Pdf con la password originale. Non genera un'eccezione se il processo fallisce. |

### Vedi anche

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


